+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "GetFieldDisplayValuesOptions"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## GetFieldDisplayValuesOptions interface

<b>Signature</b>

```typescript
export interface GetFieldDisplayValuesOptions 
```
<b>Import</b>

```typescript
import { GetFieldDisplayValuesOptions } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [data](#data-property) | <code>DataFrame[]</code> |  |
|  [fieldConfig](#fieldconfig-property) | <code>FieldConfigSource</code> |  |
|  [reduceOptions](#reduceoptions-property) | <code>ReduceDataOptions</code> |  |
|  [replaceVariables](#replacevariables-property) | <code>InterpolateFunction</code> |  |
|  [sparkline](#sparkline-property) | <code>boolean</code> |  |
|  [theme](#theme-property) | <code>GrafanaTheme2</code> |  |
|  [timeZone](#timezone-property) | <code>TimeZone</code> |  |

### data property

<b>Signature</b>

```typescript
data?: DataFrame[];
```

### fieldConfig property

<b>Signature</b>

```typescript
fieldConfig: FieldConfigSource;
```

### reduceOptions property

<b>Signature</b>

```typescript
reduceOptions: ReduceDataOptions;
```

### replaceVariables property

<b>Signature</b>

```typescript
replaceVariables: InterpolateFunction;
```

### sparkline property

<b>Signature</b>

```typescript
sparkline?: boolean;
```

### theme property

<b>Signature</b>

```typescript
theme: GrafanaTheme2;
```

### timeZone property

<b>Signature</b>

```typescript
timeZone?: TimeZone;
```
