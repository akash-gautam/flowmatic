## Overview

The Kubeflow Addon for KKP (Flowmatic) allows automated installation of [Kubeflow Machine Learning Toolkit for Kubernetes][20]
in [Kubermatic Kubernetes Platform][21], with Kubeflow authentication integrated with KKP.

The repository consists of the [Kubeflow Addon for KKP](addon) and [manifests](manifests) used to customize
upstream Kubeflow manifests for KKP needs.

## Installation

Please see [the documentation][22] for the Kubeflow Addon installation instructions.

_The code and sample YAML files in the master branch of the Flowmatic repository are under active development and are not guaranteed to be stable. Use them at your own risk!_

## More information

[The documentation][22] provides a list of prerequisites, installation instructions and a list of limitations and known issues.

Please use the version selector at the top of the site to ensure you are using the appropriate documentation for your version of Kubermatic.

## Troubleshooting

If you encounter issues [file an issue][1] or talk to us on the [#kubermatic channel][12] on the [Kubermatic Slack][15].

## Contributing

Thanks for taking the time to join our community and start contributing!

Feedback and discussion are available on [the mailing list][11].

### Before you start

* Please familiarize yourself with the [Code of Conduct][4] before contributing.
* See [CONTRIBUTING.md][2] for instructions on the developer certificate of origin that we require.
* Read how [we're using ZenHub][13] for project and roadmap planning

### Pull requests

* We welcome pull requests. Feel free to dig through the [issues][1] and jump in.

## Changelog

See [the list of releases][3] to find out about feature changes.

[1]: https://github.com/kubermatic/flowmatic/issues
[2]: https://github.com/kubermatic/flowmatic/blob/master/CONTRIBUTING.md
[3]: https://github.com/kubermatic/flowmatic/releases
[4]: https://github.com/kubermatic/flowmatic/blob/master/CODE_OF_CONDUCT.md

[11]: https://groups.google.com/forum/#!forum/kubermatic-dev
[12]: https://kubermatic.slack.com/messages/kubermatic
[13]: https://github.com/kubermatic/flowmatic/blob/master/Zenhub.md
[15]: http://slack.kubermatic.io/

[20]: https://www.kubeflow.org/
[21]: https://github.com/kubermatic/kubermatic
[22]: https://docs.kubermatic.com/kubermatic/master/advanced/addons/kubeflow/
