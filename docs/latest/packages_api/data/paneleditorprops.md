+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "PanelEditorProps"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## PanelEditorProps interface

<b>Signature</b>

```typescript
export interface PanelEditorProps<T = any> 
```
<b>Import</b>

```typescript
import { PanelEditorProps } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [data](#data-property) | <code>PanelData</code> | Result set of panel queries |
|  [onOptionsChange](#onoptionschange-property) | <code>(options: T, callback?: () =&gt; void) =&gt; void</code> | Panel options change handler |
|  [options](#options-property) | <code>T</code> | Panel options |

### data property

Result set of panel queries

<b>Signature</b>

```typescript
data?: PanelData;
```

### onOptionsChange property

Panel options change handler

<b>Signature</b>

```typescript
onOptionsChange: (options: T, callback?: () => void) => void;
```

### options property

Panel options

<b>Signature</b>

```typescript
options: T;
```
