### DRAFT

This document in in draft form and is actively being worked on. If you wish to
contribute please feel free to fork and submit a pull request. For help with
using git and github check out this awesome tutorial.

[jlord/git-it-electron](https://github.com/jlord/git-it-electron)

This document is written in markdown. Markdown is extremely helpful for
displaying documentation related to your projects. For help with markdown, try
this webapp. It includes a helpful cheat sheet.

[stackedit.io](https://stackedit.io/app)

Alternatively, you can download and install [writage](http://www.writage.com/).
It allows you to edit markdown files in Word.

<img src="https://hcpss.me/images/hcpss-logo.svg" alt="HCPSS Logo" width="50%" />

Source Control Guidelines
=========================

Programming is hard. The simplest mistake can cause catastrophic failure. As
developers, engineers, and programmers, we are expected to work independently
with little oversight or audit to solve problems through software while
maintaining the integrity, confidentiality and availability of millions of data
for thousands of users.

We need source control to do our jobs. We must know why software is the way it
is and how we can change it to make it better. And when we have questions, we
need access to resources where we might find answers.

We have many tools at our disposal that are designed to help us. But without
clear guidance and a shared understanding of how to use these tools, we will
spend a lot of time lost in fruitless searches or writing documentation that may
never be read. These guidelines exist to establish and communicate a clear
understanding of how we implement source control.

### HCPSS Manifesto

-   Developers should be free to express ideas, solve problems, and generate
    code with minimal administrative overhead

-   Code should be organized and accessible

-   Documentation should be precise and pithy, not redundant or wordy

-   Tell us where your secrets are, not what your secrets are

-   Use change management

### Dos and Don’ts

-   **Private Repositories** – By default all newly created Git Repositories are
    private. Keep these settings unless you have an explicit need to expose the
    repository

-   **Repository Names** – When possible choose names that clearly indicate what
    the repository is for. You may also want to add a readme.md file to add more
    description about the project

-   **Commit Related Changes** – It’s a good idea to make related changes in a
    single commit. If you are working on two different bugs then it makes sense
    that you should have two different commits for each bug. This makes it
    easier for team members to understand and roll the changes back if they need
    to.

-   **Commit Often** – Committing often allows you to share your changes with
    others more frequently. It also helps others to be able to integrate tour
    changes in their code to avoid merge conflicts.

-   **Don’t Commit unfinished work** – Only commit pieces of code that work. Do
    not commit code that will not compile. Always test your code before
    committing.

-   **Write Good Commit Messages** - Make sure that the Summary clearly captures
    what the commit is all about. If you would like to like to link the commit
    to an existing JIRA, then be sure to reference the JIRA number in the
    description field.

-   **Backup Your Local Repositories** – Source Control is not meant to be used
    as a backup system. There is a chance that you may have lots of committed
    changes that you may have not yet pushed to GitHub. I would recommend that
    local repositories be backed up to the Z:/drive (home directory)

-   **Use Branching Whenever Possible** – Branching is a powerful feature that
    is easy to use. It allows you to have multiple lines of development at once.
    Avoid working on the master as best as you can.
