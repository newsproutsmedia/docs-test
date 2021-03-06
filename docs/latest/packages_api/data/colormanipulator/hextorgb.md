+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "hexToRgb"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## colorManipulator.hexToRgb() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

### colorManipulator.hexToRgb() function

Converts a color from CSS hex format to CSS rgb format.

<b>Signature</b>

```typescript
export declare function hexToRgb(color: string): string;
```
<b>Import</b>

```typescript
import { colorManipulator } from '@grafana/data';
const { hexToRgb } = colorManipulator;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  color | <code>string</code> | Hex color, i.e. \#nnn or \#nnnnnn |

<b>Returns:</b>

`string`

A CSS rgb color string

