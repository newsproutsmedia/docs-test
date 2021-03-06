+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "FieldConfigEditorConfig"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## FieldConfigEditorConfig interface

<b>Signature</b>

```typescript
export interface FieldConfigEditorConfig<TOptions, TSettings = any, TValue = any> extends OptionEditorConfig<TOptions, TSettings, TValue> 
```
<b>Import</b>

```typescript
import { FieldConfigEditorConfig } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [hideFromDefaults](#hidefromdefaults-property) | <code>boolean</code> | Indicates that option shoukd not be available in the Field config tab |
|  [hideFromOverrides](#hidefromoverrides-property) | <code>boolean</code> | Indicates that option should not be available for the overrides |
|  [shouldApply](#shouldapply-property) | <code>(field: Field) =&gt; boolean</code> | Function that allows specifying whether or not this field config should apply to a given field. |

### hideFromDefaults property

Indicates that option shoukd not be available in the Field config tab

<b>Signature</b>

```typescript
hideFromDefaults?: boolean;
```

### hideFromOverrides property

Indicates that option should not be available for the overrides

<b>Signature</b>

```typescript
hideFromOverrides?: boolean;
```

### shouldApply property

Function that allows specifying whether or not this field config should apply to a given field.

<b>Signature</b>

```typescript
shouldApply?: (field: Field) => boolean;
```
