# nephio-upf-nad

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-upf-nad`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-upf-nad`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-upf-nad
kpt live apply nephio-upf-nad --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
