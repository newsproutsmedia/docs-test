+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "getFlotPairsConstant"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## getFlotPairsConstant() function

### getFlotPairsConstant() function

Returns a constant series based on the first value from the provide series.

<b>Signature</b>

```typescript
export declare function getFlotPairsConstant(seriesData: GraphSeriesValue[][], range: TimeRange): GraphSeriesValue[][];
```
<b>Import</b>

```typescript
import { getFlotPairsConstant } from '@grafana/data';
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  seriesData | <code>GraphSeriesValue[][]</code> | Series |
|  range | <code>TimeRange</code> | Start and end time for the constant series |

<b>Returns:</b>

`GraphSeriesValue[][]`
