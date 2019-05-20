---
author: "Lawrence Lane"
date: 2019-04-22
linktitle: How to Become a Technical Writer Pt. 1
next:  
prev:
title: How to Become a Technical Writer Pt. 1
image: "/images/how-to-become-a-technical-writer/become-technical-writer-pt1.png"
weight:
description: Learn how to become a technical writer for startup companies and become familiar with industry-leading content tools.
---

This is a guide on how to become a technical writer (TW) in the software industry. Anyone can do it. By following this guide, I believe you could be ready to interview for a TW position within 6 months --- less, if you put in the time.

 Okay, Let's get started.

{{< instagram Bp3g99VnjKK hidecaption >}}

 ---
## Common Misconceptions

I'm going to get these out of the way first to help you better evaluate whether being a TW makes sense for you.

### Technical writer --- Does that mean you code?

No. It certainly helps to know how to code, but you do not need it to begin a career. Some technical writers may be expected to write code in a hybrid role, but that's likely outlined in the job description.

### Writing all day sounds boring. I couldn't do that.

Perhaps. But before you write off (haha) becoming a technical writer, consider this: it's a well-paid job that's relatively low stress compared to being a developer or digital marketing specialist. There's also some great perks available in the right industry, such as: unlimited vacation, paid healthcare, stocks, and location independence.

### I don't have the right degree; I'd have to go back to school.

You do not need any particular degree to obtain the skills needed or to build a writing portfolio. In fact, the beauty of working in the tech industry is that many IT & engineering professionals are self-taught (and proudly so). It is one of the most open-minded industries when it comes to bootstrapped careers. Your hiring manager will care more about **demonstrable skills** and **experience** than your degree.

>Take me for example. I have a BFA in Creative Writing, with a minor in English. My technical skills came from playing World of Warcraft and editing skins for online writing communities (translation: limited HTML/CSS knowledge).

---
## Part One: Knowledge Building

{{< instagram BpxeJXDn2nD hidecaption >}}

### 1. How to write technical documentation

Your goal is to be the user's advocate. You accomplish this in 4 ways:

- Make documentation searchable
- Create objective-oriented content
- Anticipate when UX falls short of intuition
- Minimize reader exhaustion

Everything discussed beyond this point supports our main objective in one of those ways.

> <i class="fas fa-info-circle"></i> **UX**: User experience; the flow of actions, communications, and feelings a user goes through in a product.

#### Be concise

Never say more than you have to.

**Bad:**

> Dashboards will start populating data a few minutes after setting up an integration.

**Good:**

>Dashboards populate data a few minutes after integration setup.

Too much information can derail the user from their objective _and_ make your content hard to digest. But sometimes there's optional steps a user must be aware of. Here's what to do with those:

- **Brief Optional Steps**: Include them in the series
- **Complex Optional Steps**: Move to a dedicated sub-section

Why?

Two reasons: to promote linear, objective-driven thought **and** to create whitespace. Whitespace is essential for a user to comfortably scan and read content without getting fatigued or feeling overwhelmed. You do not want a user to open your document only to hit a wall. It needs several welcoming entry points.


#### Use active voice

Make your user take action.

**Bad**

> The table is saved after pressing <i class="fas fa-save"></i>.

**Good**

> Select <i class="fas fa-save"></i> to save.

The _good_ example here is stripped quite bare, but remember that you can rely on context to create brevity. The above line is likely the final step in a list of actions related to a savable object---in this case, a table.

{{< instagram BtJFQuinE_2 hidecaption >}}

#### Style consistently

- Use bulleted lists for non sequential items
- Use numbered lists for steps in a series
- Make your list items parallel
- Standardize your header sizes for (h1/h2/h3/h4) and stick to them
- Be aware of casing consistency for each header style
- Put code in `code style`
- Put input variables in `code style`
- Use `>` for multi-action navigations
- Bold buttons --- select **attributes** > **tag** > input `green`
  - Button casing should match what is in product (even if it's wrong :'()


#### Choose versatile language

Where is your audience using this software? On a desktop, a tablet, a laptop, a phone? Well, on 50% of those devices, a user can't _click_ because there is no _mouse_.

Save yourself (and your team) the headache of having to revise your whole library as your business scales. Be more glocal, inclusive, or future focused from the start.

**Don't Use:** _press_, _turn on_, or _click_

**Use:**  _select_, _enable_, or _choose_

Apply this mindset to identify verbs and descriptors that only work for one user experience and not all.

### 2. How & when to use screenshots


Many writers feel as though they must add a screenshot to every step of their documentation. I argue that isn't so. In fact, having too many screenshots  can inflate instructions that would otherwise convey the meaning immediately.

For example, is there only one button named **submit** on the modal? Is it well placed and intuitive to standard form submissions?  If so, you probably don't need that screenshot.

#### Use screenshots when

- There is a new procedure that is unique or unfamiliar to the user
- There is a complex idea present that is difficult to convey otherwise

Screenshots are also a pain to maintain as your content ages. Features are updated all the time. UI styles change. Whole navigation panes are moved from top to left.

#### How to take a screenshot

- Standardize width; I tend to use full-width screenshots so no measuring or resizing is needed. It's distracting for a user to see varying image sizes when scrolling through a page.
- Minimize multi-navigation overlay. Although sometimes unavoidable, doing this when possible maximizes the enduring relevance of your screenshot. Don't create more work for yourself later.

><i class="fas fa-info-circle"></i> **Navigation Pane**: a menu that slides out or overlays above all over items on the screen.

><i class="fas fa-info-circle"></i> **Modal**: a pop-up window within a product that needs user input to be submitted.

{{< instagram BpxiYJfHZ3C hidecaption >}}

### 3. Know commonly used tools

There are a _ton_ of tools out there. Every business uses a different combination. You do not need to know them all. Start with those mentioned here first and then branch out to tools you see mentioned in job descriptions.

#### GUI writing tools

- Confluence
- WordPress
- GitBook
- ZenDesk Guide
- Madcap Flare
- Salesforce Knowledge

I **do not recommend** WordPress, ZenDesk Guide, or Salesforce Knowledge. In my opinion, these tools were never intended to meet the needs of long-form help documentation. They often mix HTML styling with content drafting which is **a huge pain in the ass**. Revising content (such as link anchors and images) often breaks the styling of your lists and headers, meaning you have to sit there for _quite some time_ to fix what should work automatically.

These solutions also bring about the _PlUgIn ApOcAlYpSe_. Plugins are a terrible solution.

Why?

They're 3rd party supported, eventually stop being updated, and cause conflicts with your platform. It's inevitable. That being said, you should know how to use them.

#### Combo solutions

- Static Site Generators (like Hugo) **+**
- Text and Code Source Editors (like Atom) **+**
- GitHub

This is the solution I've moved my company to. It requires more technical knowledge to get started, but gaining those skills makes you a more valuable technical writer. Also, drafting becomes super easy and consistent thanks to [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

#### Industry tools
- Slack
- Github
- JIRA
- Confluence
- Atom

You'll see how these tools apply in the next section.

### 4. Understand your peers & the workflow

Technical writers are not developers. They should, however, understand developers. We work together toward the same goal. Here's the high-level:

Code is written on something called a branch in a text-and-source-code editor (like Atom). That branch is pushed from the developer's local computer to a cloud repository (like GitHub) where it is peer reviewed and then merged into the production branch.

Your work as a writer comes from the additions and changes made to these repositories. For things that should be documented that cannot be seen in the product itself (in UAT), you can search the GitHub repository for relevant changes. That search should start in the team's ticketing software (like JIRA).

><i class="fas fa-info-circle"></i> **Repository**: a library of code; one application can rely on several repositories to create one product.

><i class="fas fa-info-circle"></i> **UAT**: User Acceptance Testing; the stage to catch bugs and errors before pushing new features or changes to production.

##### Example ticket

```
Ticket ID: ACME-11234
Epic Name: 2019 X Report UI Overhaul
Ticket Name: Add Report Preview to X Report Modal
Description: As a user, I would like to be able to preview the report settings I've changed in the modal before I apply them. Attached is a mock of how the graph should look.
```
You are tasked with updating the documentation for X Report. It's likely this change requires some screenshot updates (the modal has a new feature: report preview). This needs a release note and potentially some small announcement.

{{< instagram Bp6BBktHH1c hidecaption >}}
