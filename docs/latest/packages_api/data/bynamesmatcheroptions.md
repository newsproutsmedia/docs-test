+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "ByNamesMatcherOptions"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## ByNamesMatcherOptions interface

Options to instruct the by names matcher to either match all fields in given list or all except the fields in the list.

<b>Signature</b>

```typescript
export interface ByNamesMatcherOptions 
```
<b>Import</b>

```typescript
import { ByNamesMatcherOptions } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [mode](#mode-property) | <code>ByNamesMatcherMode</code> |  |
|  [names](#names-property) | <code>string[]</code> |  |
|  [prefix](#prefix-property) | <code>string</code> |  |
|  [readOnly](#readonly-property) | <code>boolean</code> |  |

### mode property

<b>Signature</b>

```typescript
mode?: ByNamesMatcherMode;
```

### names property

<b>Signature</b>

```typescript
names?: string[];
```

### prefix property

<b>Signature</b>

```typescript
prefix?: string;
```

### readOnly property

<b>Signature</b>

```typescript
readOnly?: boolean;
```
