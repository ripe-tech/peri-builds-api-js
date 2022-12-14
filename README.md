# PERI Builds API Client for JavaScript

The JavaScript based API client for PERI Builds.

## Example

```javascript
import { API as BuildsApi } from "peri-builds";
await BuildsApi.load();
const api = new BuildsApi();
const info = await api.getInfo();
```

## Configuration

| Name                     | Type  | Default                                  | Description                                                 |
| ------------------------ | ----- | ---------------------------------------- | ----------------------------------------------------------- |
| **PERI_BUILDS_BASE_URL** | `str` | `https://peri-builds-sbx.platforme.com/` | The base URL to the PERI Builds server instance to be used. |

## License

PERI Builds API for Javascript is currently licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/).

## Build Automation

[![Build Status](https://app.travis-ci.com/ripe-tech/peri-builds-api-js.svg?branch=master)](https://travis-ci.com/github/ripe-tech/peri-builds-api-js)
[![Build Status GitHub](https://github.com/ripe-tech/peri-builds-api-js/workflows/Main%20Workflow/badge.svg)](https://github.com/ripe-tech/peri-builds-api-js/actions)
[![npm Status](https://img.shields.io/npm/v/peri-builds-api.svg)](https://www.npmjs.com/package/peri-builds-api)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://www.apache.org/licenses/)
