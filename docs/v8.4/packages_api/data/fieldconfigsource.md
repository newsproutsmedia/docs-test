+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "FieldConfigSource"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## FieldConfigSource interface

<b>Signature</b>

```typescript
export interface FieldConfigSource<TOptions = any> 
```
<b>Import</b>

```typescript
import { FieldConfigSource } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [defaults](#defaults-property) | <code>FieldConfig&lt;TOptions&gt;</code> |  |
|  [overrides](#overrides-property) | <code>ConfigOverrideRule[]</code> |  |

### defaults property

<b>Signature</b>

```typescript
defaults: FieldConfig<TOptions>;
```

### overrides property

<b>Signature</b>

```typescript
overrides: ConfigOverrideRule[];
```