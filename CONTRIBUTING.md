# Contributing to ModernFW
ModernFW is an open source project licensed under the [BSD+Patent license](https://opensource.org/licenses/BSDplusPatent).

## Coding Style
We follow the [TianoCore coding style](https://github.com/tianocore/tianocore.github.io/wiki/Code-Style-C).

## Certificate of Origin
In order to get a clear contribution chain of trust we use the [signed-off-by language](https://01.org/community/signed-process) used by the Linux kernel project.

## Patch format
Besides the signed-off-by footer, we expect each patch to comply with the following format:
```
<component>: Change summary

More detailed explanation of your changes: Why and how.
Wrap it to 72 characters.
See http://chris.beams.io/posts/git-commit/
for some more good pieces of advice.

Signed-off-by: <contributor@foo.com>
```

## Pull requests
ModernFW uses the “fork-and-pull” development model. Follow these steps if you want to merge your changes to ModernFW:
1. Fork the ModernFW project into your github organization.
2. Within your fork, create a branch for your contribution.
3. Create a pull request against the master branch of the ModernFW repository.
4. Add reviewers to your pull request and then work with your reviewers to address any comments and obtain approvals from a minimum of two maintainers. To update your pull request amend existing commits whenever applicable and then push the new changes to your pull request branch.
5. Once the pull request is approved, one of the maintainers will merge it.

## Issue tracking
If you have a problem, please let us know. We recommend using [github issues](https://github.com/intel/ModernFW/issues/new) for formally reporting and documenting them.
To quickly and informally bring something up to us, you can also reach out on [email](mailto:modernfw@lists.01.org).

## Closing issues
You can either close issues manually by adding the fixing commit SHA1 to the issue comments or by adding the `Fixes` keyword to your commit message. Then, after the corresponding PR is merged, Github will automatically close that issue when parsing the [commit message](https://help.github.com/articles/closing-issues-via-commit-messages/).
