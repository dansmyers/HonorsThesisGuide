# Computer Science Honors Thesis Guide

## Overview

This is a guide for preparing an Honors thesis in computer science at Rollins College. It provides some guidelines on the thesis process, timelines, and specifications for formatting and writing your thesis document.

This guide is **opinionated**. The "rules" it contains are only our thoughts on what seems to work well. They aren't official Rollins policies or universal requirements of all thesis projects in computer science. Some of the guidelines are arbitrary, but they are presented in the spirit of giving you as much information and structure as possible.

## Process

### Working

The First and Greatest Rule of Productivity: **do not binge**. You will make better progress if you work on your research in **brief, regular sessions**, rather than trying to block out one huge chunk of time per week (probably right before a meeting).

There are several reasons for this:

- It's easier to schedule and honor a small 30-60 minute block of time than to dedicate all day to one project.

- Regular sessions keep your mind engaged on the project. Taking a long break from research requires you to spend the first part of your session just remembering where you left off last time. Keeping a journal, discussed below, will also help organize your work and keep you on task.

- Brief sessions are mentally easier and less intimidating. You avoid the anxiety and perceived lack of progress that comes from scheduling six hours to work on your thesis, but only really working for two.

- Finally, brief, regular sessions will actually let you accumulate more total time on the project than binging once a week.

### Scheduling

Block out a window of at least 30 minutes (45 or 60 minutes is better) on each day, Monday through Friday. This is your **scheduled research time** and you **will not schedule anything else** during this block. Treat it like a class.

We'll have a scheduled meeting once per week. Working in regular sessions will ensure that you're prepared for our meetings so we can use them effectively to review what you've worked on and determine the next steps for the upcoming week.

### Getting Unstuck

If you get stuck on something, work to get yourself unstuck as soon as possible. Don't spend an entire week or more blocked and unable to make progress because of a technical issue, or because of something you don't understand and can't answer on your own in a reasonable timeframe.

In general, if you spend an entire daily research session stuck on one issue, let your advisor know so you can debug it together.

### Research Journal

You will keep a journal of your research activity each time you sit down to work on your project. Some researchers like paper journals or lab books. I use a plain text file that I type in while I work.

The journal is your log of what happened during each session. It records your progress for each day: what you did, what problems you encountered and solved, any interesting things you observed. It's also the place for you to reflect on your own research process and explore issues such as what's going well, what isn't, and how you can improve your own research process.

The journal is not a formal document. You don't have to turn it in, although I may end up seeing it at points.

### A Daily Research Session

*This section is influenced by Robert Boice's* Nihil Nimus *. This is the approach I use in my own research sessions.*

As your scheduled research time begins, sit yourself in a place where you can be productive and focus. This is different for every person, but doing your research in the same time and place each day will help you get into a productive frame of mind.

Close your eyes, pause, and breath calmly and deeply for about 30 seconds. Don't dwell on conscious thoughts. If any emerge, just let them go and return your focus to your breathing. This brief meditation centers you and creates a separation between your activities before the research session and the work of the session itself.

You're now ready to begin.

Open your journal and make a heading for today. Spend a few minutes free writing about the project: what you did last time, what you need to do today, what open questions exist, even what you're enjoying about the project and want to study in more detail. Keep it free and don't edit yourself. This exercise helps you reengage with the state of the project.

Now dive in and work on your tasks for today. As you tackle each task, make a note of what you are doing. If you try something and it doesn't work, make a note of that, then note what you're trying next. As you obtain results, you'll also log those in the journal.

Take a break if you need to, but resist the temptation to visit social media or Internet sites that aren't directly relevant to your project. You can sustain your focus for 40 minutes and the constant reflective journaling will help keep you engaged.

When you reach the end of your time, or a natural stopping place, pause for a moment before concluding. Free write for a few more lines about what you did today and what you think you need to do next.

Finally, **write down one to four tasks**, in order of priority, for the next session. This is your to-do list. When you come back next time, you'll tackle these tasks, with the highest priority one coming first. If a task seems too large, break it into subtasks, then prioritize those.

## Basic Requirements

### Approximate Timeline

| Deliverable | Date |
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

### References and Citations

You should plan to accumulate at least **12 references** during the literature review phase of your project.

Your literature review should focus on **peer-reviewed scholarly articles published in research journals or computer science conference proceedings**.

General-interest media articles, opinion pieces, blog posts, etc., even those published in reputable news outlets such as the *New York Times*, are not appropriate citation material, unless the media itself is the focus of your study.

Because the CS field is built around dialogue between academics and industry practitioners, there are cases where important work has appeared outside of the traditional peer-reviewed publishing process. Satoshi Nakamoto's original 2008 Bitcoin paper is a good example. It was first published pseudonymously on the Internet, and other cryptocurrency developers (who are mostly not traditional academics) have adopted the practice of releasing their work in public white papers.
Software engineering and web programming are other areas where influential writing has happened outside of scholarly journals and conferences.

Cite your references using APA-style (Name, Date) pairs in parentheses.

> The original Bitcoin protocol was developed by a person or group using the pseudonym "Satoshi Nakamoto" and publicly described in a white paper released on the Internet (Nakamoto, 2008).

Many CS papers use numbered references in brackets, e.g. [1, 2], but this style requires an automatic citation manager such as BibTeX. The (Name, Date) style allows you to modify your reference list without renumbering.

List all your references in a section at the end of your document, after the Conclusion. Format each list entry according to APA guidelines and alphabetize them by the authors' last names.

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

Simon Peyton-Jones suggests the following structure for engineering-oriented papers, where the locus of the research is building and validating a system, application, or tool:

- Introduction
- Literature Review
- Problem Description
- Solution Description
- Details and Experimental Results
- Conclusion

In these kinds of papers, the Problem Description section may incorporate some quantitative experiment to prove that the problem exists. The rest of the paper describes the engineering solution, its design, and its implementation, then performs experiments to show that it really solves the original problem.

Note that the section names can be changed to something more descriptive if it's appropriate.

### Placement of the Literature Review

In theses and dissertations, it's traditional to place the Literature Review right after the Introduction, before the presentation of your new research. In many CS papers, however, the review often comes *after* the main body of the paper, before the conclusion. This placement allows the authors to present their original ideas first, then place them in the context of the broader literature.

## Tips for Writing Individual Sections

### Abstract

Your document should include an Abstract before the Introduction, giving a one-paragraph summary of the entire paper. Write it last.

### Writing the Introduction

*This section is influenced by Karen Kelsky's grant writing template.*

The Introduction section establishes the main idea for the entire paper. A reader should finish the introduction knowing

- what problem or question your thesis addresses,

- that this problem or question matters,

- how you approach the problem or question, and

- what else your thesis contains

The most important rule for introductions: **actually tell the reader what your thesis is about**. This is not a Hitchcock movie! You don't get extra credit for keeping the reader in suspense or making them guess what's going to happen next.

The key to structuring your introduction is to include **reader orientation paragraphs** that clearly state what you are doing, why you are doing it, and why it matters.

I recommend the following structure for your introduction.

1. Begin by stating a broad issue of general interest. For example, here's the first line of Satoshi's 2008 Bitcoin paper:

    > Commerce on the Internet has come to rely almost exclusively on financial institutions serving as trusted third parties to process electronic payments.
  
    The paper doesn't begin by diving right in to the technical details of Bitcoin. Rather, it opens by calling attention to the Internet's dependence on large financial institutions.
    
    If necessary, include one or two more sentences to provide more context on the problem and elaborate on its significance. Your overall goal is to arouse the reader's interest by connecting the topic of your study to a significant problem.

2. Provide a brief reference to the literature (with one or more citations) showing that other researchers have recognized this problem and addressed aspects of it. This may include a relevant quote from one of your sources.

3. The next sentence is key. Karen Kelsky calls it **The Kicker**. The Kicker sentence identifies the gap in the existing research that your thesis addresses. **The Kicker sentence must be on the first page of your document**.

    Here is a sentence that functions as a Kicker in Satoshi's paper. It begins the second paragraph on the first page:

    > What is needed is an electronic payment system based on cryptographic proof instead of trust,
allowing any two willing parties to transact directly with each other without the need for a trusted
third party.

    Think of the Kicker as the main topic sentence for your entire thesis document. The drive to address this issue will ultimately motivate everything in the rest of the paper. 
    
    The rest of the paragraph following the Kicker elaborates on why this gap is a problem that must be addressed, in the context of the major issue you identified at the beginning of the paper.
    
4. The rest of the introduction elaborates on the approach you take in the rest of the paper. What are the essential details of your study? What data sources did you use? What analysis techniques or theoretical frameworks do you draw upon?

5. The end of the Introduction is a **statement of your contributions**, summarizing the key results and accomplishments of your work. 

    Be explicit! It's okay to say, "The key result of this paper is..." or, "This paper makes the following contributions..." Don't force your reader to guess whether your thesis accomplished anything.

Taken together, this structure does several things:

- It connects your thesis to an issue of recognized importance.

- It establishes that other researchers care about this issue and that you're aware of the scholarly conversation around it.

- It identifies a meaningful gap in the current work, which provides the rationale for your study.

- It gives readers a brief, but engaging overview of your approach, so that they are ready to read on and learn more.

- Finally, it expicitly tells the reader what contributions you are making and why they are important.

Here is the complete second paragraph of the (Nakamoto, 2008) paper introduction. It tells you, in four sentences, the main gap that the paper addresses, the need for addressing this gap, and the two main contributions of the paper. I have emphasized the key phrases.
    
> *What is needed is* an electronic payment system based on cryptographic proof instead of trust,
allowing any two willing parties to transact directly with each other without the need for a trusted
third party. Transactions that are computationally impractical to reverse *would protect* sellers
from fraud, and routine escrow mechanisms could easily be implemented to protect buyers. *In
this paper, we propose a solution* to the double-spending problem using a peer-to-peer distributed
timestamp server to generate computational proof of the chronological order of transactions. *The
system is secure* as long as honest nodes collectively control more CPU power than any
cooperating group of attacker nodes.

### Writing the Literature Review

A good literature review will

- equip you with background knowledge you need for your thesis,

- provide the body of references you'll use in your work, and

- demonstrate to your reviewers that you have done sufficient background research and have an understanding of your topic area.

Three common problems plague the thesis literature review:

1. Doing the minimum and ending up with a literature review that's too sparse and cursory to show any understanding of the area.

2. The opposite: taking forever with the lit review and refusing to move on the actual thesis. This is a favorite procrastination technique of insecure grad students.

3. A review that summarizes a more-or-less random set of tangentially related papers, with no regard for their relationships or relative importance. This is what you get if you base your research on the top links returned by Google Scholar.

A good literature review is more than a summary of several articles. Rather, it should be a concise overview of the **most important work and key background information** related to your topic. The focus of your review should be on **identifying and summarizing relevant and influential articles**.

As you study a paper, write a one paragraph summary of it that answers the following questions:

- What is the main idea or overaching goal of the paper? If you had to summarize it in one sentence, what would you say? If you can't do this, you probably don't yet have a good grip on the key idea of the paper.

- How is the paper connected to the broader literature? What earlier work does it build upon? What later work, if any, did it inspire?

- What are the technical methods of the paper? If it's experimental, what are the data sets and analysis techniques? If it's an engineering paper, what is the tool or system? One way to answer these questions is to write a one sentence summary of each major section of the paper.

- Are there limitations or weaknesses of the paper, whether acknowledged or unacknowledged?

For example, here's my summary of the (Nakamoto, 2008) Bitcoin paper:

> This paper describes Bitcoin, a peer-to-peer system that uses cryptographic protocols to allow irreversible cash-like transactions
over the Internet without the need for trusted third parties such as banks. This is the original article that provided the first public description of the Bitcoin protocol. In the Bitcoin system, a transaction is a cryptographically-signed message authorizing the transfer of digital currency from one party to another. To ensure that a payer cannot spend the same coin more than once, there must be a global, timestamped record of transactions that tracks when and where each coin was spent. In the Bitcoin system, a distributed network of nodes maintains a public ledger of all transactions. New transactions are  only accepted after being validated against the ledger. The introduction of new data into the ledger requires solving a computationally difficult "proof-of-work" problem (inspired by Adam Back's Hashcash system) that cryptographically ties new transactions to old transactions in a way that makes it infeasible for adversaries to modify the ledger. The paper presents a statistical argument that the system will remain secure from attack as long as a majority of its total computational power is in honest hands. The system described in the paper supports only irreversible, trustless, cash-like transactions.

As you read papers, collect your summaries, along with the citation information for each paper, in a document (or better yet, a citation management system like Zotero).

To write the Literature Review section,

1. Group your papers into two to four natural categories. Each category becomes a numbered subsection in your document.

2. Write an introductory paragraph to each subsection that introduces the area of research and its major themes.

3. Arrange the papers in each category chronologically. Carefully investigate any large, decade-plus gaps in your coverage. For example, if your survey of neural networks included only papers from the 1960's and modern post-2010 papers, **that would be a problem**.

4. Using your summaries as a starting point, **write one paragraph for each paper**, with an emphasis on describing the evolution of each stream of research and the key ideas that developed over time. You **don't** have to include all of the technical detail you captured in your original summaries.

Here's an edited part of the lit review taken from my own dissertation. The numbers in parentheses are references. Notice that the motivation, data sources, and key results of each paper are summarized and that the later paper is connected back to the first study. Here, the first paragraph doubles as an introduction to the entire subsection, because it lays out some major questions that have been revisted again and again by file system researchers.

> An important early study of file system behavior was carried out by Ousterhout et al. at UC-Berkeley in 1985 (64). The Berkeley study
was motivated by questions that have remained relevant to file system design and development in the present day: identifying common file access patterns (and, by extension, the protocols that best serve those access patterns), and investigating the management and performance benefits of in-memory disk block caching. The Berkeley team approached these questions by analyzing a set of traces collected from the UNIX 4.2 BSD file system (51).
>
> The Berkeley study empirically confirmed several commonly held beliefs concerning UNIX file access. First, users access files in a sporadic, but bursty fashion: most users averaged only a few hundred bytes of data transfer per second over the lifetime of the trace, but peak per-user transfer rates could be as high as 100 KB per second. Second, most files are small, but large files account for the majority of bytes transferred. Third, most file accesses are sequential, and files tend to be sequentially read or written in their entirety. Fourth, most files are open for a short time and new files are likely to be temporary and have short lifetimes.
>    
> Baker et al. revisited many of the results of the original 1985 BSD study in (9), where they worked with a set of logical file system traces taken from the Sprite network operating system (63). Their results show that the key insights of the BSD study remained valid in 1991, despite the shift from time-shared minicomputers to more powerful personalized workstations...
    

### Writing the Methods and Results

Your Methods and Results are the **most imporant sections of your paper**. They are the truly original part of your work. You want your readers to **understand** these sections so they will appreciate the quality of your research.

The contents of these sections depend on the details of your study, but the following guidelines will help you.

#### Outline Your Sections

The Methods section will typically have a subsection describing your data collection and another describing your analysis techniques.

To outline the Methods, write down what you did to collect and analyze your data as a series of numbered steps. Take each step and expand it into a series of numbered substeps. Repeat this process until you have a complete description of your methods that anyone in the field could follow to repeat your work. 

Structure the Results section as a series of numbered subsections, each presenting one of your main conclusions.

- First, write down your key conclusions, in order of most-supported to least-supported, then write down one sentence summaries of the supporting evidence for each conclusion.

    Note that some results may have several pieces of supporting evidence, some may only have one. The strength of a conclusion isn't determined by the *quantity* of evidence that you present. Trying to overwhelm a reader with low-quality data can backfire on you.

- Expand each of your summary sentences into a full paragraph, describing the measurement, graph, table, etc. that supports your conclusion.
    
Throughout these sections, **continue to tell the reader what's important**. Call out your main results and key pieces of evidence. Don't bury important information in the middle of paragraphs.

#### Explain the Details

Most student drafts **are light on details**. Readers **want to know what you did**. Always err on the side of describing things in thorough, even exhaustive, detail. Do not attempt to summarize a complex method or argument in a single sentence.

You may need to transform data, make calculations, or derive new measurements from raw values. **Carefully explain these steps**, why they are necessary, and how you implemented them. Readers need to have confidence that the numbers you've calculated accurately measure what you claim they measure. This is particularly important if you later show derived measurements in a graph or table. **Don't be afraid to illustrate your methods with small examples**.

Data from humans is tricky. If you've worked with surveys, journals, or interviews, you should carefully document the data collection process (when, where, by whom, under what conditions). Include relevant excerpts from the instruments in the body of the document and the full instruments in an Appendix.

**Do not make unsupported assertions**. Everything you claim as a result must be backed up by either supporting data from your study or a citation.

***Everything***.

Don't **tell** the reader something without **showing** the data that allowed you to draw that conclusion.

**Avoid generalizing claims** beyond the data at hand. Be careful of using words like *shows*, *demonstrates*, or (shudder) *proves* without careful qualification.
    
Also, remember that words like *significant*, *rate*, and *trend* have **specific technical definitions**.

#### Graphs and Tables

Create the simplest possible graphs and tables, and avoid figures that are overly complex, filled with irrelevant data, or too small to read.

When you introduce a graph or table, tell the reader how to interpret it. What are the axes and units? What does the shape of a line represent? What direction on the graph corresponds to improvement? Don't just put a figure in your document and expect your reader to understand why it's important.
    
Label graph axes and **always include units**. Multi-line plots should have a legend.

Make sure your table columns and rows have descriptive titles. In your text, explain which values in the table illustrate the point you want to make.
    
Some additional tips:

- Use color sparingly, if at all. Some people are colorblind, and differences in line style are often easier to distinguish than solid lines of different colors.
    
- More than two or three lines per graph is hard to interpret.
    
- Huge tables full of numbers are also hard to interpret. Carefully evaluate any table with more than 10-15 entries. Show only the set of values needed to illustrate your point.
    
- Use line plots for **continuous data** or discrete sets with many points that effectively appear continuous. Use bar graphs or scatter plots for discrete measurements.
    
- Vertical graph axes should always start at 0. **Do not set the axis range to the data range**: this is a common trick to make minor differences appear important. Readers will be skeptical of any graph that does not start at 0.
    
- Include a table of notation in mathematical papers, listing symbols, their meaning, and units where appropriate.

#### Acknowledge Your Limitations
    
All studies have imperfections. Don't try to hide yours, or pretend they don't exist.

Acknowledge issues that exist with your data or limitations of your methods, then explain why they do not undermine your overall research project. Readers generally appreciate this attention to detail; they get angry if they think you're trying to hide something.

**Write defensively**. Anticipate your readers' objections and address them.
 
For example, if you're doing a qualitative study with a small *N*, you know that generalizing your conclusions is going to be impossible. You could acknowledge that you can't claim statistical significance with a small sample, but you can still collect other valuable insights into the attitudes and experiences of your participants, which can inform further research.
    
### Grammar, Sentences, and Other Writing Tips

I recommend the following guides from Hamilton College:

- [Seven Deadly Sins of Writing](https://www.hamilton.edu/academics/centers/writing/seven-sins-of-writing)

- [Writing a Good History Paper](https://www.hamilton.edu/academics/centers/writing/writing-resources/writing-a-good-history-paper)  (obviously focused on history, but the important points are relevant for all writers)

- [APA Quick Guide](https://www.hamilton.edu/academics/centers/writing/writing-resources/apa-quick-guide)


    
