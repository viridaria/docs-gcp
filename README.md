# Rackspace Fanatical Support for GCP Product Guide

This repository contains the source files that generate the Rackspace Fanatical
Support for GCP Product Guide:

* <https://developer.rackspace.com/docs/fanatical-support-gcp/>

When you commit changes to the master branch of this repository, the
[Strider CI/CD build job](https://build.developer.rackspace.com/rackerlabs/docs-gcp/)
builds the documentation. Successful builds are deployed to production.

[![Netlify Status](https://api.netlify.com/api/v1/badges/b8c923a6-ad57-45a3-8fcc-6bf8c2cfdd10/deploy-status)](https://app.netlify.com/sites/docs-gcp/deploys)

## Local Setup

`npm i -g netlify-cli`
`netlify init`
`netlify build`
`netlify dev`
`netlify deploy`

### Support and feedback

We welcome feedback, comments, and bug reports. Follow the [contributor guidelines](CONTRIBUTING.md)
to propose a source file change, or [submit a GitHub issue](https://github.com/rackerlabs/docs-cloud-servers/issues/new)
to request an update or to provide feedback.

You can also contact the [Rackspace documentation team](mailto:devdoc@rackspace.com) directly for general
issues or questions about the content.
