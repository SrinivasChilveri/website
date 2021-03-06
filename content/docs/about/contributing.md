+++
title = "Contributing to KubeGene"
weight = 10
toc = true
aliases = ["/docs/about/"]
[menu.main]
  parent = "What is KubeGene?"
  weight = 4
+++

The following sections outline the process all changes to the KubeGene
repositories go through.

- [Working groups](#working-groups)
- [Design documents](#design-documents)
- [Contributing a feature](#contributing-a-feature)
- [Setting up to contribute to KubeGene](#setting-up-to-contribute-to-kubegene)
- [Pull requests](#pull-requests)
- [Issues](#issues)

## Working groups

The KubeGene community is organized into a set of working groups.
Any contribution to KubeGene should be started by first engaging with the appropriate working group.

## Design documents

Any substantial design deserves a design document. Design documents are written with Google Docs and
should be shared with the community by adding the doc to our [Team Drive](TBD)
and sending a note to the appropriate working group to let people know the doc is there. To get write access
to the drive, you'll need to be a [member](ROLES.md#member) of the KubeGene organization.

Anybody can access the team drive for reading and commenting. To get access simply join the
[kubegene-team-drive-access@](TBD) group.
Once you've done that, head to Team Drive and
behold all the docs.

## Contributing a feature

In order to contribute a feature to KubeGene you'll need to go through the following steps:

- Discuss your idea with the appropriate working groups on the working
group's mailing list.

- Once there is general agreement that the feature is useful, create a GitHub issue to track the discussion. The issue should include information
about the requirements and use cases that it is trying to address. Include a discussion of the proposed design and technical details of the
implementation in the issue.

- If the feature is substantial enough:

  - Working group leads will ask for a design document as outlined in the previous section.
  Create the design document and add a link to it in the GitHub issue. Don't forget to send a note to the
  working group to let everyone know your document is ready for review.

  - Depending of the breath of the design and how contentious it is, the working group leads may decide
  the feature needs to be discussed in one or more working group meetings before being approved.

  - Once the major technical issues are resolved and agreed upon, post a note to the working group's mailing
  list with the design decision and the general execution plan.

- Submit PRs to [kubegene/kubegene](https://github.com/kubegene/kubegene) with your code changes.

- Submit PRs to [kubegene/docs](https://github.com/kubegene/docs) with
documentation for your feature, including usage examples when possible.

> Note that we prefer bite-sized PRs instead of giant monster PRs. It's therefore preferable if you
can introduce large features in smaller reviewable changes that build on top of one another.

If you would like to skip the process of submitting an issue and
instead would prefer to just submit a pull request with your desired
code changes then that's fine. But keep in mind that there is no guarantee
of it being accepted and so it is usually best to get agreement on the
idea/design before time is spent coding it. However, sometimes seeing the
exact code change can help focus discussions, so the choice is up to you.

## Setting up to contribute to KubeGene

Check out this [README](https://github.com/kubegene/kubegene/blob/master/README.md) to learn about
the KubeGene source base and setting up your development environment.

## Pull requests

If you're working on an existing issue, simply respond to the issue and express
interest in working on it. This helps other people know that the issue is
active, and hopefully prevents duplicated efforts.

To submit a proposed change:

- Fork the affected repository.

- Create a new branch for your changes.

- Develop the code/fix.

- Add new test cases. In the case of a bug fix, the tests should fail
  without your code changes. For new features try to cover as many
  variants as reasonably possible.

- Modify the documentation as necessary.

- Verify the entire CI process (building and testing) works.

While there may be exceptions, the general rule is that all PRs should
be 100% complete - meaning they should include all test cases and documentation
changes related to the change.


## Issues

[GitHub issues](https://github.com/kubegene/kubegene/issues) can be used to report bugs or submit feature requests.

When reporting a bug please include the following key pieces of information:

- The version of the project you were using (e.g. version number,
  or git commit)

- Operating system you are using.

- The exact, minimal, steps needed to reproduce the issue.
  Submitting a 5 line script will get a much faster response from the team
  than one that's hundreds of lines long.
