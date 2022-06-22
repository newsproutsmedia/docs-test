+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "LogsModel"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## LogsModel interface

<b>Signature</b>

```typescript
export interface LogsModel 
```
<b>Import</b>

```typescript
import { LogsModel } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [hasUniqueLabels](#hasuniquelabels-property) | <code>boolean</code> |  |
|  [meta](#meta-property) | <code>LogsMetaItem[]</code> |  |
|  [queries](#queries-property) | <code>DataQuery[]</code> |  |
|  [rows](#rows-property) | <code>LogRowModel[]</code> |  |
|  [series](#series-property) | <code>DataFrame[]</code> |  |
|  [visibleRange](#visiblerange-property) | <code>AbsoluteTimeRange</code> |  |

### hasUniqueLabels property

<b>Signature</b>

```typescript
hasUniqueLabels: boolean;
```

### meta property

<b>Signature</b>

```typescript
meta?: LogsMetaItem[];
```

### queries property

<b>Signature</b>

```typescript
queries?: DataQuery[];
```

### rows property

<b>Signature</b>

```typescript
rows: LogRowModel[];
```

### series property

<b>Signature</b>

```typescript
series?: DataFrame[];
```

### visibleRange property

<b>Signature</b>

```typescript
visibleRange?: AbsoluteTimeRange;
```