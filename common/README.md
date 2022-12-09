# common

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] common`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree common`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init common
kpt live apply common --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
