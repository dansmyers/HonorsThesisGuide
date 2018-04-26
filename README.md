# Honors Thesis Guide

## Overview

This is a guide for preparing an Honors thesis in computer science at Rollins College. It provides some guidelines on the thesis process, timelines, and specifications for formatting and writing your thesis document.

This guide is **opinionated**. The "rules" it contains are only our thoughts on what seems to work well; they aren't official Rollins policies or universal requirements of all thesis projects in computer science. Some of the guidelines are arbitrary, but they are presented in the spirit of giving you as much information and structure as possible.

## Process

### Working

The First and Greatest Rule of Productivity: **do not binge**. You will make better progress if you work on your research in **brief, regular sessions**, rather than trying to block out one huge chunk of time per week (probably right before a meeting).

There are several reasons for this:

- It's easier to schedule and honor a small 30-60 minute block of time than to dedicate all day to one project.

- Regular sessions keep your mind engaged on the project. Taking a long break from research requires you to spend the first part of your session just remembering where you left off last time. Keeping a journal, discussed below, will also help organize your work and keep you on task.

- Brief sessions are mentally easier and less intimidating. You avoid the anxiety and perceived lack of progress that comes from scheduling six hours to work on your thesis, but only really working for two.

- Finally, brief, regular sessions will actually let you accumulate more total time on the project than binging once a week.

### Scheduling

I recommend blocking out a window of at least 30 minutes (45 or 60 minutes is better) on each day, Monday through Friday. This is your **scheduled research time** and you **will not schedule anything else** during this block. Treat it like a class.

We'll have a scheduled meeting once per week. Working in regular sessions will ensure that you're prepared for our meetings so we can use them effectively to review what you've worked on and determine the next steps for the upcoming week.

### Getting Unstuck

If you get stuck on something, work to get yourself unstuck as soon as possible. Don't spend an entire week or more blocked and unable to make progress because of a technical issue, or because of something you don't understand and can't answer on your own in a reasonable timeframe.

In general, if you spend an entire daily research session stuck on one issue, let me know so we can debug it together.

### Research Journal

You will keep a journal of your research activity each time you sit down to work on your project. Some researchers like paper journals or lab books. I use a plain text file that I type in while I work.

The journal is your log of what happened during each session. It records your progress for each day: what you did, what problems you encountered and solved, any interesting things you observed. It's also the place for you to reflect on your own research process and explore issues such as what's going well, what isn't, and how you can improve your own research process.

The journal is not a formal document. You don't have to turn it in, although I may end up seeing it at points.

### A Daily Research Session

*This section is influenced by Robert Boice's *Nihil Nimus*. This is the approach I use in my own research sessions.*

As your scheduled research time begins, sit yourself in a place where you can be productive and focus. This is different for every person, but doing your research in the same time and place each day will help you get into a productive frame of mind.

Close your eyes, pause, and breath calmly and deeply for about 30 seconds. Don't dwell on conscious thoughts. If any emerge, just let them go and return your focus to your breathing. This brief meditation centers you and creates a separation between your activities before the research session and the work of the session itself.

You're now ready to begin.

Open your journal and make a heading for today. Spend a few minutes free writing about the project: what you did last time, what you need to do today, what open questions exist, even what you're enjoying about the project and want to study in more detail. Keep it free and don't edit yourself. This exercise helps you reengage with the state of the project.

Now dive in and work on your tasks for today. As you tackle each task, make a note of what you are doing. If you try something and it doesn't work, make a note of that, then note what you're trying next. As you obtain results, you'll also log those in the journal.

Take a break if you need to, but resist the temptation to visit social media or Internet sites that aren't directly relevant to your project. You can sustain your focus for 40 minutes and the constant reflective journaling will help keep you engaged.

When you reach the end of your time, or a natural stopping place, pause for a moment before concluding. Free write for a few more lines about what you did today and what you think you need to do next.

Finally, **write down one to four tasks**, in order of priority, for the next session. This is your to-do list. When you come back next time, you'll tackle these tasks, with the highest priority one coming first. If a task seems too large, break it into subtasks, then prioritize those.

## Basic Requirements

### Rough Timeline

| Deliverable   |  Date |
|----------|------:|
| Draft of literature review and reference list | October 15 |
| Mid-course presentation to committee | December 1 |
| Draft of introduction and methods sections | End of fall semester |
| Draft of results section | March 15 |
| Schedule defense | First week of April |
| Draft of complete document with all sections, references, and figures | Two weeks prior to defense |
| Final document delivered to committee | One week prior to defense |
| Submission of final document with committee's revisions | End of spring semester |


### Length

A reasonable goal for a thesis is enough material for a single computer science research article. A normal CS conference paper would be about 12-15 pages in a tight two-column LaTeX format, which corresponds to **20 to 30 pages** in a typical MS-Word document.

That said, length is ultimately a function of the project. You'll write as much as you need to write to describe your problem, process, and results.

### Formatting

Most students type their theses in Microsoft Word. If you are going to grad school and want to learn LaTeX, we can talk about it.

Use normal margins and 12-point Times New Roman or a similar professional-looking font. Set the line spacing to 1.5.

Sections and subsections should be numbered, with 1 for the Introduction, 2 for the first body section, 2.1 for the first body subsection, and so forth. You can use numbered sub-subsections if necessary, but those are often better handled with un-numbered paragraph headings.

References should be cited using APA-style (Name, Date) pairs in parenthesis.

> The original Bitcoin protocol was developed by a person or group using the pseudonym "Satoshi Nakamoto" and publicly described in (Nakamoto, 2008).

Many CS papers use numbered references in brackets, like [1, 2], but this style is hard to use without an automatic citation manager such as BibTEX.

Include a title page with the project title, your name, etc.

## Document Sections and Structure

### Experimental Theses

Many theses have the following sections:

- Introduction
- Literature Review
- Methods
- Results
- Discussion
- Conclusion

This structure is standard for papers that are broadly experimental, where the locus of the research is collecting and analyzing some type of data.

- The Introduction orients the reader to the problem and your proposed approach and it provides a high-level overiew of the contributions of your document.

- The Methods section summarizes the details of your experiment, such as the data collection, processing, and analysis steps. 

- The Results section presents quantitative and qualitative data (as appropriate for your study) that answer the experimental questions driving the paper.

- The Discussion section elaborates on the significance of the results, acknowledges limitations, and places them in broader context. it may also suggest directions for future work or elaboration.

### Engineering Theses

Simon Peyton-Jones suggests the following structure, which is useful for papers that are more engineering-oriented, where the locus of the research is building and validating a system, application, or tool:

- Introduction
- Literature Review
- Problem Description
- Solution Description
- Details and Experimental Results
- Conclusion

In these kinds of papers, the Problem Description section may incorporate some quantitative experiment to prove that the problem exists. The rest of the paper describes the engineering solution, its design, and its implementation, then performs experiments to show that it really solves the original problem.

Note that the section names can be changed to something more descriptive if it's appropriate.

## Tips for Writing Individual Sections

### Abstract

The abstract is a one-paragraph summary of the entire paper. Write this last.

### Writing the Introduction

*This section is influenced by Karen Kelsky's grant-writing template.*

The Introduction section establishes the main idea for the entire paper. A reader should finish the introduction knowing

- what problem or question your thesis addresses,

- that this problem or question matters,

- how you approach the problem or question, and

- what else your thesis contains

The most important rule for introductions: **actually tell the reader what your thesis is about**. This is not a Hitchcock movie! You don't get extra credit for keeping the reader in suspense or making them guess what's going to happen next.

The key to structuring your introduction is to include **reader orientation paragraphs** that clearly state what you are doing, why you are doing it, and why it matters.

I recommend the following structure for your introduction.

1. Begin by stating a big, obvious problem of general interest. One that your grandmother would recognize as a problem. This immediately lifts your thesis out of narrow technical concerns and into the realm of real-world change. The problem you pick, of course, must be plausibly connected to the technical topic of your thesis.

2. Provide a brief reference to the literature (with one or more citations) showing that other researchers have addressed aspects of this problem. This may be a relevant quote from one of your sources. Together, these items make up your first paragraph.

3. The next sentence is key. Karen Kelsky calls it **The Kicker**. The Kicker sentence always begins with **"However,..."**, and then continues to identify the gap in the existing research that your thesis addresses. The rest of your second paragraph elaborates on why this gap is a problem that merits attention.

4. The rest of the introduction elaborates on the approach you take in the rest of the paper. What are the essential details of your study? What data sources did you use? What broad analysis techniques or theoretical frameworks?

5. The end of the Introduction is a **bulleted list of contributions**, summarizing the key points and accomplishments of your work. This also serves as a overview of the document structure. This section can be didactic. It's okay to tell the reader something as explicit as "This paper makes the following contributions..." or "The key result of this paper is..."

Taken together, this structure does several things:

- It connects your thesis to an issue of recognized importance.

- It establishes that other researchers see this issue as important and that you're aware of the scholarly conversation around it.

- It identifies a meaningful gap in the current work, which provides the rationale for your study.

- It gives readers a brief, but engaging overview of your approach, so that they are ready to read on and learn more.

- Finally, it expicitly tells the reader what contributions you are making and why they are important.


### Writing the Literature Review


### Writing the Methods and Results


## General Writing Tips
