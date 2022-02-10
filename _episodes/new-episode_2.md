---
title: Version control
teaching: 10
exercises: 20
duration: 0
summary: ""
questions: null
objectives: null
keypoints: null
is-break: false
ukrn_wb_rules: []
day: 1
order: 400000
missingDependencies:
  - /fig/play-changes.svg
  - /fig/versions.svg
  - /fig/merge.svg
dependencies: []
originalRepository: hturner/open-code-foundations

---
Version control systems start with a base version of the document and
then record changes you make each step of the way. You can
think of it as a recording of your progress: you can rewind to start at the base
document and play back each change you made, eventually arriving at your
more recent version.

![Changes Are Saved Sequentially]({% include installedFile.lqd path='/fig/play-changes.svg' %})

Once you think of changes as separate from the document itself, you
can then think about "playing back" different sets of changes on the base document, ultimately
resulting in different versions of that document. For example, two users can make independent
sets of changes on the same document. 

![Different Versions Can be Saved]({% include installedFile.lqd path='/fig/versions.svg' %})

Unless multiple users make changes to the same section of the document - a conflict - you can 
incorporate two sets of changes into the same base document.

![Multiple Versions Can be Merged]({% include installedFile.lqd path='/fig/merge.svg' %})

A version control system is a tool that keeps track of these changes for us,
effectively creating different versions of our files. It allows us to decide
which changes will be made to the next version (each record of these changes is
called a [commit](), and keeps useful metadata
about them. The complete history of commits for a particular project and their
metadata make up a [repository]().
Repositories can be kept in sync across different computers, facilitating
collaboration among different people.

> ## The Long History of Version Control Systems
>
> Automated version control systems are nothing new.
> Tools like [RCS](https://en.wikipedia.org/wiki/Revision_Control_System), [CVS](https://en.wikipedia.org/wiki/Concurrent_Versions_System), or [Subversion](https://en.wikipedia.org/wiki/Apache_Subversion) have been around since the early 1980s and are used by 
> many large companies.
> However, many of these are now considered legacy systems (i.e., outdated) due to various 
> limitations in their capabilities.
> More modern systems, such as Git and [Mercurial](https://swcarpentry.github.io/hg-novice/),
> are *distributed*, meaning that they do not need a centralized server to host the repository.
> These modern systems also include powerful merging tools that make it possible for 
> multiple authors to work on
> the same files concurrently.
{: .callout}

> ## Paper Writing
>
> *   Imagine you drafted an excellent paragraph for a paper you are writing, but later ruin 
>     it. How would you retrieve the *excellent* version of your conclusion? Is it even possible?
>
> *   Imagine you have 5 co-authors. How would you manage the changes and comments 
>     they make to your paper?  If you use LibreOffice Writer or Microsoft Word, what happens if 
>     you accept changes made using the `Track Changes` option? Do you have a 
>     history of those changes?
>
> > ## Solution
> >
> > *   Recovering the excellent version is only possible if you created a copy
> >     of the old version of the paper. The danger of losing good versions
> >     often leads to the problematic workflow illustrated in the PhD Comics
> >     cartoon at the top of this page.
> >     
> > *   Collaborative writing with traditional word processors is cumbersome.
> >     Either every collaborator has to work on a document sequentially
> >     (slowing down the process of writing), or you have to send out a
> >     version to all collaborators and manually merge their comments into
> >     your document. The 'track changes' or 'record changes' option can
> >     highlight changes for you and simplifies merging, but as soon as you
> >     accept changes you will lose their history. You will then no longer
> >     know who suggested that change, why it was suggested, or when it was
> >     merged into the rest of the document. Even online word processors like
> >     Google Docs or Microsoft Office Online do not fully resolve these
> >     problems.
> {: .solution}
{: .challenge}
