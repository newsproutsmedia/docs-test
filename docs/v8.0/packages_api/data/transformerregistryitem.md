+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "TransformerRegistryItem"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## TransformerRegistryItem interface

<b>Signature</b>

```typescript
export interface TransformerRegistryItem<TOptions> extends RegistryItem 
```
<b>Import</b>

```typescript
import { TransformerRegistryItem } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [editor](#editor-property) | <code>React.ComponentType&lt;TransformerUIProps&lt;TOptions&gt;&gt;</code> | React component used as UI for the transformer |
|  [transformation](#transformation-property) | <code>DataTransformerInfo&lt;TOptions&gt;</code> | Object describing transformer configuration |

### editor property

React component used as UI for the transformer

<b>Signature</b>

```typescript
editor: React.ComponentType<TransformerUIProps<TOptions>>;
```

### transformation property

Object describing transformer configuration

<b>Signature</b>

```typescript
transformation: DataTransformerInfo<TOptions>;
```