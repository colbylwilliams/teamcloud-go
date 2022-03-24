# TeamCloud Client SDKs

This file contains the configuration for generating client SDKs for the TeamCloud API.

> see <https://aka.ms/autorest>

## Getting Started

To generate the client SDKs for the TeamCloud API, simply install AutoRest via `npm` (`[sudo] npm install -g autorest`) and then run:

```shell
cd path/to/openapi
autorest --v3 go.md
```

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest GitHub page.

## Configuration

The remainder of this file is configuration details used by AutoRest.

### Inputs

``` yaml
use: '@autorest/go@https://github.com/Azure/autorest.go/releases/download/v4.0.0-preview.37/autorest-go-4.0.0-preview.37.tgz'
input-file: openapi.yaml
output-folder: './../teamcloud'
module: teamcloud
module-version: '0.5.2'
credential-scopes: openid
license-header: MICROSOFT_MIT_NO_VERSION
clear-output-folder: true
```
