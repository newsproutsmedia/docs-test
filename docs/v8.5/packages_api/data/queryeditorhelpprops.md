+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "QueryEditorHelpProps"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## QueryEditorHelpProps interface

<b>Signature</b>

```typescript
export interface QueryEditorHelpProps<TQuery extends DataQuery = DataQuery> 
```
<b>Import</b>

```typescript
import { QueryEditorHelpProps } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [datasource](#datasource-property) | <code>DataSourceApi&lt;TQuery&gt;</code> |  |
|  [exploreId](#exploreid-property) | <code>any</code> |  |
|  [onClickExample](#onclickexample-property) | <code>(query: TQuery) =&gt; void</code> |  |
|  [query](#query-property) | <code>TQuery</code> |  |

### datasource property

<b>Signature</b>

```typescript
datasource: DataSourceApi<TQuery>;
```

### exploreId property

<b>Signature</b>

```typescript
exploreId?: any;
```

### onClickExample property

<b>Signature</b>

```typescript
onClickExample: (query: TQuery) => void;
```

### query property

<b>Signature</b>

```typescript
query: TQuery;
```