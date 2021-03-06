+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "hslToRgb"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## colorManipulator.hslToRgb() function

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.
> 

### colorManipulator.hslToRgb() function

Converts a color from hsl format to rgb format.

<b>Signature</b>

```typescript
export declare function hslToRgb(color: string | DecomposeColor): string;
```
<b>Import</b>

```typescript
import { colorManipulator } from '@grafana/data';
const { hslToRgb } = colorManipulator;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  color | <code>string &#124; DecomposeColor</code> | HSL color values |

<b>Returns:</b>

`string`

rgb color values

