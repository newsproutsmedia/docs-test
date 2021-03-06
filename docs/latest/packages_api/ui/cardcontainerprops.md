+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "CardContainerProps"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
disable_edit_link = true
+++

## CardContainerProps interface


<b>Signature</b>

```typescript
export interface CardContainerProps extends HTMLAttributes<HTMLOrSVGElement>, CardInnerProps 
```
<b>Import</b>

```typescript
import { CardContainerProps } from '@grafana/ui';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [className](#classname-property) | <code>string</code> | Custom container styles |
|  [disableEvents](#disableevents-property) | <code>boolean</code> | Disable pointer events for the Card, e.g. click events |
|  [disableHover](#disablehover-property) | <code>boolean</code> | No style change on hover |
|  [isSelected](#isselected-property) | <code>boolean</code> | Makes the card selectable, set to "true" to apply selected styles |

### className property

Custom container styles

<b>Signature</b>

```typescript
className?: string;
```

### disableEvents property

Disable pointer events for the Card, e.g. click events

<b>Signature</b>

```typescript
disableEvents?: boolean;
```

### disableHover property

No style change on hover

<b>Signature</b>

```typescript
disableHover?: boolean;
```

### isSelected property

Makes the card selectable, set to "true" to apply selected styles

<b>Signature</b>

```typescript
isSelected?: boolean;
```
