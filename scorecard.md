# Project Maturity Scorecard

Top Hat's open source projects are scored from 1-4, where levels 3 and 4 are considered ready for production use.

Below, you'll find what features and level of support you can find at each level.

### 1 - New Project
Projects at this level are under heavy development and should _not be used in production_. However, once a project hits level one, expect the following baseline requirements to be met:

|Item|Description|
|-------|-----------|
|Disabled Wiki|All Top Hat OSS projects use plain markdown files for documentation.|
|Proper credit to Carol Skelly|Thanks to Carol for donating the github.com/tophat org!|
|Contributor list|A big thank you to all our contributors!|
|Public Repo|Repo should be fully open for community use/contributions.|
|Uses GitHub Issues|Issue tracking for all projects should be done in GitHub|
|Uses Github Projects|Project roadmap will be publicly available in GitHub Projects|
|Uses Top Hat code style|All projects must conform to the applicable style guide for their language|
|Uses correct license|We've standardized on the Apache-2 license for all our OSS projects|
|Only allow squash merging|All repos should be configured to only allow squash merges for PRs|
|No secrets in commits|Any secrets/configuration data should be stored outside the repo|
|Issue templates|All Top Hat projects use a standard issue template to help handle feature requests, bug reports, and PRs|
|Code of conduct|All Top Hat projects should link to our standard code of conduct.|
|Branch protection|The master branch of all projects should have protections enabled to ensure that no unverified code is released|

### 2 - First Release
Projects at this level will have their core feature set defined and finished, as well as basic
infrastructure such as CI, a test suite, and a dedicated owner internally. Some documentation may be incomplete, and automatic releases may not yet be in place. We recommend not using projects at
this level in production but they should be stable enough for non-critical systems. 

|Item|Description|
|----|-----------|
| Built on CircleCI |All Top Hat OSS projects use CircleCI for running tests and releasing |
|Detailed README|Projects at this level should have detailed READMEs, but may be missing some other documentation.|
|No Top Hat specific logic|Level 2 projects should have any Top Hat specific logic or code removed, to ensure they're suitable for others to use.|
|Has a test runner|Projects marked level 2 should have a test suite integrated with CI for all PRs|
|Has a Top Hat owner|Each product in First Release will have a dedicated owner to ensure that external PRs and issues are triaged appropriately.|
|Publicly available artifacts|Any releases of this project will have publicly downloadable artifacts, but they may not be generated automatically and may not be published in standard package managers.|

### 3 - Stable
Stable projects are ones that are used internally at Top Hat in production and have mature
infrastructure around releasing, testing, and versioning. Additionally, expect projects labelled 
as "stable" to include fairly complete documentation with code examples and some level of
community support. 

|Item|Description|
|----|-----------|
|Semantic versioning|Projects marked stable will use semantic versioning to ensure backwards compatability with new releases.|
|Code examples|Stable projects should have code examples available for common usecases to make it easy to get started with usage.|
|Releases in package managers|Stable projects will have releases made available in standard package managers (PyPI, npm, etc).|
|Automatic publishing|Stable projects should have matured to the point of having automatic publishing through CircleCI.|
|Multiple Top Hat maintainers|Stable projects will have an internal advocacy group to triage feature request, bug reports, and questions. Additionally, they will maintain a public roadmap for the project.|
|Website and branding|Level 3 projects will have a feature website as well as branding to help encourage usage and contributions.|

### 4 - Critical
Critical projects are used not only in production at Top Hat but at other companies. These will
have the highest levels of support and documentation, as well as a long term roadmap.

|Item|Description|
|----|-----------|
|Stack Overflow Tag|Critical projects will have a Stack Overflow tag created and monitored by Top Hat for any questions.|
|Long term roadmap|Critical projects will have a long term feature roadmap and planned releases.|

