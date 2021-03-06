+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "localTimeFormat"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## localTimeFormat() function

### localTimeFormat() function

localTimeFormat helps to generate date formats for momentjs based on browser's locale

<b>Signature</b>

```typescript
export declare function localTimeFormat(options: Intl.DateTimeFormatOptions, locale?: string | string[] | null, fallback?: string): string;
```
<b>Import</b>

```typescript
import { localTimeFormat } from '@grafana/data';
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | <code>Intl.DateTimeFormatOptions</code> | DateTimeFormatOptions to format date |
|  locale | <code>string &#124; string[] &#124; null</code> | browser locale, or default |
|  fallback | <code>string</code> | default format if Intl API is not present |

<b>Returns:</b>

`string`

