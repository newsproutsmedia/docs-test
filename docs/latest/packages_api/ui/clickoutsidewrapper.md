+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "ClickOutsideWrapper"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
disable_edit_link = true
+++

## ClickOutsideWrapper class

<b>Signature</b>

```typescript
export declare class ClickOutsideWrapper extends PureComponent<Props, State> 
```
<b>Import</b>

```typescript
import { ClickOutsideWrapper } from '@grafana/ui';
```
<b>Properties</b>

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [defaultProps](#defaultprops-property) | <code>static</code> | <code>{</code><br/><code>        includeButtonPress: boolean;</code><br/><code>        parent: (Window &amp; typeof globalThis) &#124; null;</code><br/><code>        useCapture: boolean;</code><br/><code>    }</code> |  |
|  [myRef](#myref-property) |  | <code>React.RefObject&lt;HTMLDivElement&gt;</code> |  |
|  [onOutsideClick](#onoutsideclick-property) |  | <code>(event: any) =&gt; void</code> |  |
|  [state](#state-property) |  | <code>{</code><br/><code>        hasEventListener: boolean;</code><br/><code>    }</code> |  |

<b>Methods</b>

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [componentDidMount()](#componentdidmount-method) |  |  |
|  [componentWillUnmount()](#componentwillunmount-method) |  |  |
|  [render()](#render-method) |  |  |

### defaultProps property

<b>Signature</b>

```typescript
static defaultProps: {
        includeButtonPress: boolean;
        parent: (Window & typeof globalThis) | null;
        useCapture: boolean;
    };
```

### myRef property

<b>Signature</b>

```typescript
myRef: React.RefObject<HTMLDivElement>;
```

### onOutsideClick property

<b>Signature</b>

```typescript
onOutsideClick: (event: any) => void;
```

### state property

<b>Signature</b>

```typescript
state: {
        hasEventListener: boolean;
    };
```

### componentDidMount method

<b>Signature</b>

```typescript
componentDidMount(): void;
```
<b>Returns:</b>

`void`

### componentWillUnmount method

<b>Signature</b>

```typescript
componentWillUnmount(): void;
```
<b>Returns:</b>

`void`

### render method

<b>Signature</b>

```typescript
render(): JSX.Element;
```
<b>Returns:</b>

`JSX.Element`

