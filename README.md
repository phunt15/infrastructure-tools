[![Build Status](https://9e6a-2601-142-8200-25e0-f4a7-84ce-8c36-1d92.ngrok.io/api/badges/PHunt14/infrastructure-tools/status.svg)](https://9e6a-2601-142-8200-25e0-f4a7-84ce-8c36-1d92.ngrok.io/PHunt14/infrastructure-tools)
# infrastructure-tools
Common tools that our infrastructure management scripts like to use, lovingly packaged in a Docker container for your convenience.

## What's in the box?
General purpose tools:

- AWS CLI
- jq
- Root CA certifications
- Git

Community tools for our Helmfile-centric workflow:
- Helm
- Helmfile
- `helm-diff` plugin for Helm

Somewhat bespoke tools for our Helmfile-centric workflow:

- [cfn-create-or-update](https://www.npmjs.com/package/cfn-create-or-update)
- [branch-officer](https://www.npmjs.com/package/@fountainhead/branch-officer)
- [helmfile-cleanup](https://www.npmjs.com/package/@fountainhead/helmfile-cleanup)

Since there are no compatible binary distributions of these tools, their sources are pulled in and compiled:

- git-crypt
