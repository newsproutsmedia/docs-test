+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "DataFrameType"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## DataFrameType enum

### DataFrameType enum

See also: https://github.com/grafana/grafana-plugin-sdk-go/blob/main/data/frame\_type.go

<b>Signature</b>

```typescript
export declare enum DataFrameType 
```
<b>Import</b>

```typescript
import { DataFrameType } from '@grafana/data';
```

## Enumeration Members

|  Member | Value | Description |
|  --- | --- | --- |
|  DirectoryListing | <code>&quot;directory-listing&quot;</code> | Directory listing |
|  HeatmapCells | <code>&quot;heatmap-cells&quot;</code> | Explicit fields for: xMin, yMin, count, ...<!-- -->All values in the grid exist and have regular spacing<!-- -->If the y value is actually ordinal, use <code>meta.custom</code> to specify the bucket lookup values |
|  HeatmapRows | <code>&quot;heatmap-rows&quot;</code> | First field is X, the rest are ordinal values used as rows in the heatmap |
|  TimeSeriesLong | <code>&quot;timeseries-long&quot;</code> |  |
|  TimeSeriesMany | <code>&quot;timeseries-many&quot;</code> |  |
|  TimeSeriesWide | <code>&quot;timeseries-wide&quot;</code> |  |
