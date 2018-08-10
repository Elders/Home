# Contributing

This document describes contribution guidelines that should be followed for any contribution to the Elders organization.

## Worfklow

> The workflow that should be used in order to contribute is the standard [GitHub Flow](https://guides.github.com/introduction/flow/) where the working/dev branch is the `release-x.x.x` branch.

## Coding Style

We intend to bring all our projects into full conformance with the style guidelines described in [Coding Style](https://github.com/dotnet/corefx/blob/master/Documentation/coding-guidelines/coding-style.md). This style is a standard to contributing to .NET projects.

- **DO** give priority to the current style of the project or file you're changing even if it diverges from the general guidelines.
- **DO NOT** submit PRs with code which does not comply to the general coding-guidelines.

## Git Commits

- **DO** commit with small and descriptive messages.
- **DO NOT** commit multiple files in one commit, unless they are logically related.

## API Changes

- **DO** include documentation of what an API endpoint serves for.
- **DO** update old/non-existing documentation upon working on an API endpoint.
- **DO NOT** submit PRs for APis which do not match the responses from the rest of the APIs.
- **DO NOT** submit PRs for APIs without including documentation of any sort.
- **DO NOT** submit PRs without including integration tests for the changed components.

## Pull Requests

- **DO** submit all code changes via pull requests (PRs) rather than through a direct commit. PRs will be reviewed and potentially merged by the repository maintainers after a peer review that includes at least one maintainer.
- **DO** give PRs short-but-descriptive names (e.g. "Improve code coverage for System.Console by 10%", not "Fix #1234")
- **DO** tag any users that should know about and/or review the change.
- **DO** ensure each commit successfully builds. The entire PR must pass all tests in the Continuous Integration (CI) system before it'll be merged.
- **DO** address PR feedback in an additional commit(s) rather than amending the existing commits, and only rebase/squash them when necessary. This makes it easier for reviewers to track changes.
- **DO NOT** submit PRs without including unit tests for the changed components.
- **DO NOT** submit "work in progress" PRs. A PR should only be submitted when it is considered ready for review and subsequent merging by the contributor.

## Feature requests

You can request a new feature by submitting an issue to an Elders' GitHub repository. Before requesting a feature read the contribution guidelines for the specific project.

## Semantic Versioning 2.0.1

> Basing on the [Semantic Versioning](https://semver.org/) we strive to improve the workflow and removal of stale and old packages/dependencies for our projects. Thus we strive to keep the process of keeping up-to-date our dependencies by including them in our workflow and implicit Releases of Major and Minor Versions.

BETA:
> Upon creating a pull request which releases a **MINOR** version, all packages should be updated to their latest minor version.
> Upon creating a pull request which releases a **MAJOR** version, all packages should be updated to their latest Major version.

Example:
> Let's say that the current version of a product is 2.0.0 and has a dependency to package X with version 1.2.0. Upon finishing all work on release-2.1.0 branch, in order to submit a PR and it being accepted, in the case that X has a latest version of 2.0.0, nothing should be done. However, If X has released a minor between 1.2.0 and 2.0.0, such as 1.3.0, the package should be updated to the greatest minor version. After releasing 2.1.0, package X should be 1.3.0.
>
> Let's use the aforementioned example and say that we need to Release a major version such as 3.0.0. A requirement to move on to a new Major version is to have all dependencies updated to their latest Major Versions. If X(which was 1.3.0 after the new release branch) has a new major version of 2.0.0, the dependency should be updated before releasing the products major version. After releasing 3.0.0, package X should be 2.0.0.

## Contributor License Agreement

By contributing your code to Elders you grant Elders a non-exclusive, irrevocable, worldwide, royalty-free, sublicenseable, transferable license under all of Your relevant intellectual property rights (including copyright, patent, and any other rights), to use, copy, prepare derivative works of, distribute and publicly perform and display the Contributions on any licensing terms, including without limitation: (a) open source licenses like the MIT license; and (b) binary, proprietary, or commercial licenses. Except for the licenses granted herein, You reserve all right, title, and interest in and to the Contribution.

You confirm that you are able to grant us these rights. You represent that You are legally entitled to grant the above license. If Your employer has rights to intellectual property that You create, You represent that You have received permission to make the Contributions on behalf of that employer, or that Your employer has waived such rights for the Contributions.

You represent that the Contributions are Your original works of authorship, and to Your knowledge, no other person claims, or has the right to claim, any right in any invention or patent related to the Contributions. You also represent that You are not legally obligated, whether by entering into an agreement or otherwise, in any way that conflicts with the terms of this license.

Elders acknowledges that, except as explicitly described in this Agreement, any Contribution which you provide is on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, WITHOUT LIMITATION, ANY WARRANTIES OR CONDITIONS OF TITLE, NON-INFRINGEMENT, MERCHANTABILITY, OR FITNESS FOR A PARTICULAR PURPOSE.