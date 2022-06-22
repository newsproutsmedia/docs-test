+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "logInfo"
keywords = ["grafana","documentation","sdk","@grafana/runtime"]
type = "docs"
disable_edit_link = true
+++

## logInfo() function

### logInfo() function

Log a message at INFO level. Depending on configuration might be forwarded to backend and logged to stdout or sent to Sentry

<b>Signature</b>

```typescript
export declare function logInfo(message: string, contexts?: Contexts): void;
```
<b>Import</b>

```typescript
import { logInfo } from '@grafana/runtime';
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  message | <code>string</code> |  |
|  contexts | <code>Contexts</code> |  |

<b>Returns:</b>

`void`
