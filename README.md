<!-- This file was automatically generated by the `build-harness`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->
[![README Header][readme_header_img]][readme_header_link]

[![Cloud Posse][logo]](https://cpco.io/homepage)

# Build with @cloudposse/build-harness

 [![Build Status](https://travis-ci.org/cloudposse/build-harness.svg?branch=master)](https://travis-ci.org/cloudposse/build-harness) [![Latest Release](https://img.shields.io/github/release/cloudposse/build-harness.svg)](https://github.com/cloudposse/build-harness/releases/latest) [![Slack Community](https://slack.cloudposse.com/badge.svg)](https://slack.cloudposse.com)


This `build-harness` is a collection of Makefiles to facilitate building Golang projects, Dockerfiles, Helm charts, and more.
It's designed to work with CI/CD systems such as Travis CI, CircleCI and Jenkins.


---

This project is part of our comprehensive ["SweetOps"](https://cpco.io/sweetops) approach towards DevOps. 
[<img align="right" title="Share via Email" src="https://docs.cloudposse.com/images/ionicons/ios-email-outline-2.0.1-16x16-999999.svg"/>][share_email]
[<img align="right" title="Share on Google+" src="https://docs.cloudposse.com/images/ionicons/social-googleplus-outline-2.0.1-16x16-999999.svg" />][share_googleplus]
[<img align="right" title="Share on Facebook" src="https://docs.cloudposse.com/images/ionicons/social-facebook-outline-2.0.1-16x16-999999.svg" />][share_facebook]
[<img align="right" title="Share on Reddit" src="https://docs.cloudposse.com/images/ionicons/social-reddit-outline-2.0.1-16x16-999999.svg" />][share_reddit]
[<img align="right" title="Share on LinkedIn" src="https://docs.cloudposse.com/images/ionicons/social-linkedin-outline-2.0.1-16x16-999999.svg" />][share_linkedin]
[<img align="right" title="Share on Twitter" src="https://docs.cloudposse.com/images/ionicons/social-twitter-outline-2.0.1-16x16-999999.svg" />][share_twitter]






It's 100% Open Source and licensed under the [MIT](LICENSE).









## Screenshots


![demo](https://cdn.rawgit.com/cloudposse/build-harness/master/docs/demo.svg)
*Example of using the `build-harness` to build a docker image*


## Introduction

This is an introduction.

## Usage



At the top of your `Makefile` add, the following...

```make
-include $(shell curl -sSL -o .build-harness "https://git.io/build-harness"; echo .build-harness)
```

This will download a `Makefile` called `.build-harness` and include it at run-time. We recommend adding the `.build-harness` file to your `.gitignore`.

This automatically exposes many new targets that you can leverage throughout your build & CI/CD process.

Run `make help` for a list of available targets.

**NOTE:** the `/` is interchangable with the `:` in target names

## Quick Start

Here's how to get started...


## Examples

Here are some real world examples:
- [`github-authorized-keys`](https://github.com/cloudposse/github-authorized-keys/) - A Golang project that leverages `docker/%`, `go/%`, `travis/%` targets
- [`charts`](https://github.com/cloudposse/charts/) - A collection of Helm Charts that leverages `docker/%` and `helm/%` targets
- [`bastion`](https://github.com/cloudposse/bastion/) - A docker image that leverages `docker/%` and `bash/lint` targets
- [`terraform-null-label`](https://github.com/cloudposse/terraform-null-label/) - A terraform module that leverages `terraform/%` targets






## References

For additional context, refer to some of these links. 

- [Wikipedia - Test Harness](https://en.wikipedia.org/wiki/Test_harness) - The `build-harness` is similar in concept to a "Test Harness"


## Help

**Got a question?**

File a GitHub [issue](https://github.com/GeekHomeInside/build-harness-readme-example/issues), send us an [email][email] or join our [Slack Community][slack].

[![README Commercial Support][readme_commercial_support_img]][readme_commercial_support_link]

## Commercial Support

Work directly with our team of DevOps experts via email, slack, and video conferencing. 

We provide [*commercial support*][commercial_support] for all of our [Open Source][github] projects. As a *Dedicated Support* customer, you have access to our team of subject matter experts at a fraction of the cost of a full-time engineer. 

[![E-Mail](https://img.shields.io/badge/email-hello@cloudposse.com-blue.svg)][email]

- **Questions.** We'll use a Shared Slack channel between your team and ours.
- **Troubleshooting.** We'll help you triage why things aren't working.
- **Code Reviews.** We'll review your Pull Requests and provide constructive feedback.
- **Bug Fixes.** We'll rapidly work to fix any bugs in our projects.
- **Build New Terraform Modules.** We'll [develop original modules][module_development] to provision infrastructure.
- **Cloud Architecture.** We'll assist with your cloud strategy and design.
- **Implementation.** We'll provide hands-on support to implement our reference architectures. 




## Slack Community

Join our [Open Source Community][slack] on Slack. It's **FREE** for everyone! Our "SweetOps" community is where you get to talk with others who share a similar vision for how to rollout and manage infrastructure. This is the best place to talk shop, ask questions, solicit feedback, and work together as a community to build totally *sweet* infrastructure.

## Newsletter

Signup for [our newsletter][newsletter] that covers everything on our technology radar.  Receive updates on what we're up to on GitHub as well as awesome new projects we discover. 

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/GeekHomeInside/build-harness-readme-example/issues) to report any bugs or file feature requests.

### Developing

If you are interested in being a contributor and want to get involved in developing this project or [help out](https://cpco.io/help-out) with our other projects, we would love to hear from you! Shoot us an [email][email].

In general, PRs are welcome. We follow the typical "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull Request** so that we can review your changes

**NOTE:** Be sure to merge the latest changes from "upstream" before making a pull request!



## Copyrights

Copyright © 2019-2019 [GeekHomeInside](https://portfolio.geekhomeinside.com/)








## License 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Source: <https://opensource.org/licenses/MIT>






## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## About

This project is maintained and funded by [Cloud Posse, LLC][website]. Like it? Please let us know by [leaving a testimonial][testimonial]!

[![Cloud Posse][logo]][website]

We're a [DevOps Professional Services][hire] company based in Los Angeles, CA. We ❤️  [Open Source Software][we_love_open_source].

We offer [paid support][commercial_support] on all of our projects.  

Check out [our other projects][github], [follow us on twitter][twitter], [apply for a job][jobs], or [hire us][hire] to help with your cloud strategy and implementation.



### Contributors

|  [![Adrien DEVIENNE][guiadco_avatar]][guiadco_homepage]<br/>[Adrien DEVIENNE][guiadco_homepage] |
|---|

  [guiadco_homepage]: https://github.com/guiadco
  [guiadco_avatar]: https://img.cloudposse.com/150x150/https://github.com/guiadco.png



[![README Footer][readme_footer_img]][readme_footer_link]
[![Beacon][beacon]][website]

  [logo]: https://cloudposse.com/logo-300x69.svg
  [docs]: https://cpco.io/docs
  [website]: https://cpco.io/homepage
  [github]: https://cpco.io/github
  [jobs]: https://cpco.io/jobs
  [hire]: https://cpco.io/hire
  [slack]: https://cpco.io/slack
  [linkedin]: https://cpco.io/linkedin
  [twitter]: https://cpco.io/twitter
  [testimonial]: https://cpco.io/leave-testimonial
  [newsletter]: https://cpco.io/newsletter
  [email]: https://cpco.io/email
  [commercial_support]: https://cpco.io/commercial-support
  [we_love_open_source]: https://cpco.io/we-love-open-source
  [module_development]: https://cpco.io/module-development
  [terraform_modules]: https://cpco.io/terraform-modules
  [readme_header_img]: https://cloudposse.com/readme/header/img?repo=GeekHomeInside/build-harness-readme-example
  [readme_header_link]: https://cloudposse.com/readme/header/link?repo=GeekHomeInside/build-harness-readme-example
  [readme_footer_img]: https://cloudposse.com/readme/footer/img?repo=GeekHomeInside/build-harness-readme-example
  [readme_footer_link]: https://cloudposse.com/readme/footer/link?repo=GeekHomeInside/build-harness-readme-example
  [readme_commercial_support_img]: https://cloudposse.com/readme/commercial-support/img?repo=GeekHomeInside/build-harness-readme-example
  [readme_commercial_support_link]: https://cloudposse.com/readme/commercial-support/link?repo=GeekHomeInside/build-harness-readme-example
  [share_twitter]: https://twitter.com/intent/tweet/?text=Build+with+@cloudposse/build-harness&url=https://github.com/GeekHomeInside/build-harness-readme-example
  [share_linkedin]: https://www.linkedin.com/shareArticle?mini=true&title=Build+with+@cloudposse/build-harness&url=https://github.com/GeekHomeInside/build-harness-readme-example
  [share_reddit]: https://reddit.com/submit/?url=https://github.com/GeekHomeInside/build-harness-readme-example
  [share_facebook]: https://facebook.com/sharer/sharer.php?u=https://github.com/GeekHomeInside/build-harness-readme-example
  [share_googleplus]: https://plus.google.com/share?url=https://github.com/GeekHomeInside/build-harness-readme-example
  [share_email]: mailto:?subject=Build+with+@cloudposse/build-harness&body=https://github.com/GeekHomeInside/build-harness-readme-example
  [beacon]: https://ga-beacon.cloudposse.com/UA-76589703-4/GeekHomeInside/build-harness-readme-example?pixel&cs=github&cm=readme&an=build-harness-readme-example
