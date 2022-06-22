+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "ValueLinkConfig"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## ValueLinkConfig interface


<b>Signature</b>

```typescript
export interface ValueLinkConfig 
```
<b>Import</b>

```typescript
import { ValueLinkConfig } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [calculatedValue](#calculatedvalue-property) | <code>DisplayValue</code> | Result of field reduction |
|  [valueRowIndex](#valuerowindex-property) | <code>number</code> | Index of the value row within Field. Should be provided only when value is not a result of a reduction |

### calculatedValue property

Result of field reduction

<b>Signature</b>

```typescript
calculatedValue?: DisplayValue;
```

### valueRowIndex property

Index of the value row within Field. Should be provided only when value is not a result of a reduction

<b>Signature</b>

```typescript
valueRowIndex?: number;
```