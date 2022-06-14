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

