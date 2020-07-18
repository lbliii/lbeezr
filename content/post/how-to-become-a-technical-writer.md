---
authors:
 - Lawrence Lane
date: 2019-04-22
title: How to Become a Technical Writer Pt. 1
hero: "/images/how-to-become-a-technical-writer/how-to-part-1.png"
weight:
description: Learn how to become a technical writer for startup companies and become familiar with industry-leading content tools.
---

This is a guide on how to become a technical writer (TW) in the software industry. Anyone can do it. By following this guide, I believe you could be ready to interview for a TW position within 6 months --- less, if you put in the time.

 Okay, Let's get started.

# Common Misconceptions

I'm going to get these out of the way first to help you better evaluate whether being a TW makes sense for you.

> Technical writer --- Does that mean you code?

No. It certainly helps to know how to code, but you do not need it to begin a career. Some technical writers may be expected to write code in a hybrid role, but that's likely outlined in the job description.

> Writing all day sounds boring. I couldn't do that.

Perhaps. But before you write off (haha) becoming a technical writer, consider this: it's a well-paid job that's relatively low stress compared to being a developer or digital marketing specialist. There's also some great perks available in the right industry, such as: unlimited vacation, paid healthcare, stocks, and location independence.

> I don't have the right degree; I'd have to go back to school.

You do not need any particular degree to obtain the skills needed or to build a writing portfolio. In fact, the beauty of working in the tech industry is that many IT & engineering professionals are self-taught (and proudly so). It is one of the most open-minded industries when it comes to bootstrapped careers. Your hiring manager will care more about **demonstrable skills** and **experience** than your degree.

Take me for example. I have a BFA in Creative Writing, with a minor in English. My technical skills came from playing World of Warcraft and editing skins for online writing communities (translation: limited HTML/CSS knowledge).

---
# Part One: Knowledge Building

Your goal as a technical writer is to become a user advocate. You accomplish this in several ways:

- Make product documentation searchable
- Create objective-oriented content
- Anticipate when <cite>UX[^1]</cite> falls short of intuition
- Advocate for usability and clarity during the product's build phase

Everything discussed beyond this point supports our main objective in one of those ways.

# 1.  How to Write for Technical Products

The advice in this section goes for user guides, admin guides, in-product copy, and API documentation. If you aren't sure what any of those things are yet, don't worry. We'll have another article solely on different content pieces and how to deliver them.

## Be concise

Never say more than you have to.

### Bad

 ```html
 Dashboards will start populating data a few minutes after setting up an integration.
 ```

### Good

```html
Dashboards populate data a few minutes after integration setup.
```

Too much information can derail the user from their objective _and_ make your content hard to digest. But sometimes there's optional steps a user must be aware of. Here's what to do with those:

- **Brief Optional Steps**: Include them in the series
- **Complex Optional Steps**: Move to a dedicated sub-section

> Why?

Two reasons: to promote linear, objective-driven thought **and** to create whitespace. Whitespace is essential for a user to comfortably scan and read content without getting fatigued or feeling overwhelmed. You do not want a user to open your document only to hit a wall. It needs several welcoming entry points.

#### Example of adding too much information

```html
1. Log in to ABC Console.
2. Navigate to Settings.
3. Enable XYZ Feature.
  - if you're using AWS, you must first enable LMN feature in your AWS Admin console.
    - optionally, enable cost analytics
    - note: Enabling this feature may affect your AWS Bill.  
  - if you're using Microsoft Azure, you must first enable HIJ feature in your Azure console.
    - optionally, enable cost analytics
3. Optionally, set up notifications for this feature.
4. Save.
```

The above steps are overloaded with optional actions, notes, and try to tackle setup instructions for two different platforms. Some of the lines are also redundant. This list would serve users better by being split into two lists: one for AWS setup and one for Microsoft Azure setup.


## Use active voice

Make your user take action.

### Bad

```html
The table is saved after pressing the Save button.
```

### Good

```html
Save.
```

This is demonstrative, brief, clear. It's also often the name of a button in the <cite>UI[^8]</cite> and signals to the reader to look for a **save** button.

## Style consistently

- Use bulleted lists for non sequential items
- Use numbered lists for steps in a series
- Make your list items parallel
- Standardize your header sizes for (h1/h2/h3/h4) and stick to them
- Be aware of casing consistency for each header style
- Put code in `code style`
- Put input variables in `code style`
- Use chevrons (`>`) for multi-action navigations
- Bold buttons --- select **attributes** > **tag** > input `green`
- Match spelling and casing when referring to UI elements.


## Choose versatile language

What kind of device is your audience accessing this software from? A desktop computer, a tablet, a laptop, a phone? Well, on 50% of those devices, a user can't _click_ because there is no _mouse_.

Save yourself (and your team) the headache of having to revise your whole library as your business scales. Be more glocal, inclusive, or future focused from the start.

**Don't Use:** _press_, _turn on_, or _click_

**Use:**  _select_, _enable_, or _choose_

Apply this mindset to identify verbs and descriptors that only work for one user experience and not all.

# 2. How & when to use screenshots


Many writers feel as though they must add a screenshot to every step of their documentation. I argue that isn't so. In fact, having too many screenshots  can inflate instructions that would otherwise convey the meaning immediately.

For example, is there only one button named **submit** on the <cite>modal[^3]</cite>? Is it well placed and intuitive to standard form submissions?  If so, you probably don't need that screenshot.

## Use screenshots when

- There is a new procedure that is unique or unfamiliar to the user
- There is a complex idea present that is difficult to convey otherwise

Screenshots are also a pain to maintain as your content ages. Features are updated all the time. UI styles change. Whole <cite>navigation panes[^2]</cite> are moved from top to left.

## Take the right screenshot

Make sure your screenshots are consistent and convey the information they need to.

- **Standardize width**: I tend to use full-width screenshots so no measuring or resizing is needed. It's distracting for a user to see varying image sizes when scrolling through a page.
- **Minimize multi-navigation overlay**: Although sometimes unavoidable, doing this when possible maximizes the enduring relevance of your screenshot. Don't create more work for yourself later.

# 3. How to approach writing tools

There are a _lot_ of tools out there. Every business uses a different combination. You do not need to know them all. Start with those mentioned here first and then branch out to tools you see mentioned in job descriptions.

## GUI writing tools

- Confluence
- WordPress
- GitBook
- ZenDesk Guide
- Madcap Flare
- Salesforce Knowledge

I **do not recommend** WordPress, ZenDesk Guide, or Salesforce Knowledge. In my opinion, these tools were never intended to meet the needs of long-form help documentation. They often mix HTML styling with content drafting which is **a huge pain in the ass**. Revising content (such as link anchors and images) often breaks the styling of your lists and headers, meaning you have to sit there for _quite some time_ to fix what should work automatically.

These solutions also bring about the _PlUgIn ApOcAlYpSe_. Plugins are terrible.

> Why?

They're 3rd party supported, eventually stop being updated, and cause conflicts with your platform. It's inevitable. That being said, you should know how to use them.

## Combo solutions

- Static Site Generators (like Hugo) **+**
- Text and Code Source Editors (like Atom) **+**
- GitHub

This is the solution I've moved my clients towards. This setup is more stable, less costly, authored in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), and highly customizable. It requires more technical knowledge to get started, but gaining those skills makes you a more valuable technical writer.

## Industry tools
- Slack
- Github
- JIRA
- Confluence
- Atom

You'll see how these tools apply in the next section.

# 4. How to understand your peers & the workflow

Technical writers are not developers. They should, however, understand developers. We work together toward the same goal. Here's the high-level:

Code is written on something called a branch in a text-and-source-code editor (like Atom). That branch is pushed from the developer's local computer to a cloud <cite>repository[^4]</cite> (like GitHub) where it is peer reviewed and then merged into the production branch.

Your work as a writer comes from the additions and changes made to these repositories. For things that should be documented that cannot be seen in the product itself (in <cite>UAT[^5]</cite>), you can search the GitHub repository for relevant changes. That search should start in the team's ticketing software (like JIRA).


## Example ticket

```html
Ticket ID: ACME-11234
Epic Name: 2019 X Report UI Overhaul
Ticket Name: Add Report Preview to X Report Modal
Description: As a user, I would like to be able to preview the report settings I've changed in the modal before I apply them. Attached is a mock of how the graph should look.
```

This story (and the entire epic) indicates that there will be some work for you to do. It's likely this change requires some screenshot updates (the modal has a new feature: report preview).

Before we start writing about the new report preview feature, we need to be sure we know all of the details that impact a user.

## Find Writing Resources

The ticket itself is just one resource. Ideally, all demos, screenshots, UI-mocks, etc are attached to either the <cite>epic[^9]</cite>-level or <cite>story[^10]</cite> level tickets involved---but usually you'll have to track these down separately. Here's how to do that:

1. Talk to the Product Owner about the feature. They lead this initiative and should be able to tell you a lot about it, or point you to the developer who created it.
2. Talk to the Quality Assurance Engineer (QA) for this team. They had to test the feature, and likely know all of the setup steps. Sometimes you'll also be able to use the environment they operate in to explore the upcoming feature.
3. Talk to the UX designer. It's very lightly that there is a Figma or Sketch mock that showcases what this feature will look like and how it's intended to function.
4. Check internal knowledge repositories. Some organizations draft technical specs and project overviews that may not be attached to tickets, but offer a rough draft of everything you need to get your documents started.


# Summary of Pt. 1

In this article you have _quickly_ run through information on how to:

- Write considerate documentation
- Take effective screenshots
- Research writing tools
- Anticipate & research writing tasks

---

[^1]: **UX**: User experience; the flow of actions, communications, and feelings a user goes through in a product.
[^2]: **Navigation Pane**: a menu that slides out or overlays above all over items on the screen.
[^3]: **Modal**: a pop-up window within a product that needs user input to be submitted.
[^4]: **Repository**: a library of code; one application can rely on several repositories to create one product.
[^5]: **UAT**: User Acceptance Testing; the stage to catch bugs and errors before pushing new features or changes to production.
[^8]: **UI**: User Interface; the visual components a person may interact with on a device (buttons, text, graphics).
[^9]: **Epic**: A project that spans more than 2 weeks that has multiple tasks (stories) that must be completed.
[^10]: **Story**: A unit of work (a task) that should be completable within 2 weeks. Many stories make up one epic.
