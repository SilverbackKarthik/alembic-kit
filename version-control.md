# Version Control <!-- omit in toc -->

#### Table of Contents
- [Introduction](#introduction)
- [General Information](#general-information)
- [Branch Naming Convention](#branch-naming-convention)
- [Rules for Commit Messages](#rules-for-commit-messages)
- [Important Notes](#important-notes)
- [Learning about Git](#learning-about-git)

*Note: Links in italics are important.*

---

## Introduction

Silverback uses GitHub as it's primary version control system. GitHub is also used for Project Management, Wiki and Task Lists.

Other version control systems(basically old project archives):
- GitLab (*[Login Here][1]*)
- KingKong - Mercurial (*refer: [Here][2]*)
- KingKong - SVN (*refer: [Here][3]*)

[1]: https://about.gitlab.com/
[2]: https://sites.google.com/site/silverbackknowledgebase/server-docs/mercurial-unity/setting-up-mercurial-for-unity
[3]: https://sites.google.com/site/silverbackknowledgebase/server-docs/svn-unity/svn-for-unity

---

## General Information

**Project repositories should follow the Atlassian Git-flow branching model.**
([Detailed here: GitFlow Workflow][6])

- New features should be implemented in a branch of their own and merged back into the develop branch through a pull request. **Never merge your own feature unless the change is very small or very low risk.**
- **Commit early and commit often**. This not only makes it easier to understand the timeline, but can be invaluable when debugging as you can step through commits and see at which point the issue in question occurs.
- Remove compiler warnings before your feature branch is merged back into the develop branch.
- Using Rebase is generally good as it facilitates a clean, and readable timeline but be aware of the implications that rewriting history can have on the rest of your team.
- Do not use Rebase on a branch that has already been pushed to a remote repository.
- Branch names should follow the convention `feature/<NameOfFeature>`, `hotfix/<NameOfFix>`, etc.

---
<div style="page-break-after: always;"></div> <!-- omit in toc -->

## Branch Naming Convention

*Branch naming convention may vary from project to project, but in general use the following.*

	Use standard Git-Flow branch prefixes, like `feature`, `hotfix`, and `release`. 

Examples include:
- `feature/SomeNewFeature`
- `hotfix/Issue#43`

Use **PascalCase** for the body of the branch name:
- *Correct:* `feature/SomeNewFeature`
- *Incorrect:* `feature/somefeature`
- *Incorrect:* `feature/some_feature`

Individual projects may use specific prefixes agreed on by the team. Examples include:
- `prototype/SomeDangerousPrototype`
- `concept/TotallyCoolSetPiece`

---

## Rules for Commit Messages

A good series of guidelines can be found here: *[Commit Message Guidelines][7]*.

In summary:
- Separate subject from body with a blank line
- Limit the subject line to 50 characters
- Capitalize the subject line
- Do not end the subject line with a period
- Use the imperative mood in the subject line
- Wrap the body at `72` characters
- Use the body to explain what and why vs how

---

## Important Notes

`.gitignore`  - A good starting point for Unity project repository `.gitignore` files.

*Refer: https://drive.google.com/open?id=1flcPu_CwOR5IdOyc0X7I7AoCJA5yQ06Y*

`.gitattributes` - A good starting point for Unity project repositories that will use Git LFS.

*Refer: https://drive.google.com/open?id=1K-kvnzdtpw4vDhOwKkifBOgQZXXEXn8n*

---
<div style="page-break-after: always;"></div> <!-- omit in toc -->

## Learning about Git

- *[Git Basics][4]*
- [Pro Git Book][5]
- *[Git Workflow][6]*
- *[Git Commit Message Guidelines][7]*
- [How to write a Git commit message][8]
- *[How to Git with Unity][9]*
- [Unity SmartMerge][10]
- *[Git LFS][11]*

[4]: https://git-scm.com/book/en/v1/Getting-Started-Git-Basics
[5]: https://git-scm.com/book/en/v2
[6]: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow
[7]: https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53
[8]: https://chris.beams.io/posts/git-commit/
[9]: https://thoughtbot.com/blog/how-to-git-with-unity
[10]: https://docs.unity3d.com/Manual/SmartMerge.html
[11]: https://git-lfs.github.com/

---