+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "GrafanaThemeCommons"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## GrafanaThemeCommons interface

<b>Signature</b>

```typescript
export interface GrafanaThemeCommons 
```
<b>Import</b>

```typescript
import { GrafanaThemeCommons } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [border](#border-property) | <code>{</code><br/><code>        radius: {</code><br/><code>            sm: string;</code><br/><code>            md: string;</code><br/><code>            lg: string;</code><br/><code>        };</code><br/><code>        width: {</code><br/><code>            sm: string;</code><br/><code>        };</code><br/><code>    }</code> |  |
|  [breakpoints](#breakpoints-property) | <code>{</code><br/><code>        xs: string;</code><br/><code>        sm: string;</code><br/><code>        md: string;</code><br/><code>        lg: string;</code><br/><code>        xl: string;</code><br/><code>        xxl: string;</code><br/><code>    }</code> |  |
|  [height](#height-property) | <code>{</code><br/><code>        sm: number;</code><br/><code>        md: number;</code><br/><code>        lg: number;</code><br/><code>    }</code> |  |
|  [name](#name-property) | <code>string</code> |  |
|  [panelHeaderHeight](#panelheaderheight-property) | <code>number</code> |  |
|  [panelPadding](#panelpadding-property) | <code>number</code> |  |
|  [spacing](#spacing-property) | <code>{</code><br/><code>        base: number;</code><br/><code>        insetSquishMd: string;</code><br/><code>        d: string;</code><br/><code>        xxs: string;</code><br/><code>        xs: string;</code><br/><code>        sm: string;</code><br/><code>        md: string;</code><br/><code>        lg: string;</code><br/><code>        xl: string;</code><br/><code>        gutter: string;</code><br/><code>        formSpacingBase: number;</code><br/><code>        formMargin: string;</code><br/><code>        formFieldsetMargin: string;</code><br/><code>        formInputHeight: number;</code><br/><code>        formButtonHeight: number;</code><br/><code>        formInputPaddingHorizontal: string;</code><br/><code>        formInputAffixPaddingHorizontal: string;</code><br/><code>        formInputMargin: string;</code><br/><code>        formLabelPadding: string;</code><br/><code>        formLabelMargin: string;</code><br/><code>        formValidationMessagePadding: string;</code><br/><code>        formValidationMessageMargin: string;</code><br/><code>        inlineFormMargin: string;</code><br/><code>    }</code> |  |
|  [typography](#typography-property) | <code>{</code><br/><code>        fontFamily: {</code><br/><code>            sansSerif: string;</code><br/><code>            monospace: string;</code><br/><code>        };</code><br/><code>        size: {</code><br/><code>            base: string;</code><br/><code>            xs: string;</code><br/><code>            sm: string;</code><br/><code>            md: string;</code><br/><code>            lg: string;</code><br/><code>        };</code><br/><code>        weight: {</code><br/><code>            light: number;</code><br/><code>            regular: number;</code><br/><code>            semibold: number;</code><br/><code>            bold: number;</code><br/><code>        };</code><br/><code>        lineHeight: {</code><br/><code>            xs: number;</code><br/><code>            sm: number;</code><br/><code>            md: number;</code><br/><code>            lg: number;</code><br/><code>        };</code><br/><code>        heading: {</code><br/><code>            h1: string;</code><br/><code>            h2: string;</code><br/><code>            h3: string;</code><br/><code>            h4: string;</code><br/><code>            h5: string;</code><br/><code>            h6: string;</code><br/><code>        };</code><br/><code>        link: {</code><br/><code>            decoration: string;</code><br/><code>            hoverDecoration: string;</code><br/><code>        };</code><br/><code>    }</code> |  |
|  [zIndex](#zindex-property) | <code>{</code><br/><code>        dropdown: number;</code><br/><code>        navbarFixed: number;</code><br/><code>        sidemenu: number;</code><br/><code>        tooltip: number;</code><br/><code>        modalBackdrop: number;</code><br/><code>        modal: number;</code><br/><code>        portal: number;</code><br/><code>        typeahead: number;</code><br/><code>    }</code> |  |

### border property

<b>Signature</b>

```typescript
border: {
        radius: {
            sm: string;
            md: string;
            lg: string;
        };
        width: {
            sm: string;
        };
    };
```

### breakpoints property

<b>Signature</b>

```typescript
breakpoints: {
        xs: string;
        sm: string;
        md: string;
        lg: string;
        xl: string;
        xxl: string;
    };
```

### height property

<b>Signature</b>

```typescript
height: {
        sm: number;
        md: number;
        lg: number;
    };
```

### name property

<b>Signature</b>

```typescript
name: string;
```

### panelHeaderHeight property

<b>Signature</b>

```typescript
panelHeaderHeight: number;
```

### panelPadding property

<b>Signature</b>

```typescript
panelPadding: number;
```

### spacing property

<b>Signature</b>

```typescript
spacing: {
        base: number;
        insetSquishMd: string;
        d: string;
        xxs: string;
        xs: string;
        sm: string;
        md: string;
        lg: string;
        xl: string;
        gutter: string;
        formSpacingBase: number;
        formMargin: string;
        formFieldsetMargin: string;
        formInputHeight: number;
        formButtonHeight: number;
        formInputPaddingHorizontal: string;
        formInputAffixPaddingHorizontal: string;
        formInputMargin: string;
        formLabelPadding: string;
        formLabelMargin: string;
        formValidationMessagePadding: string;
        formValidationMessageMargin: string;
        inlineFormMargin: string;
    };
```

### typography property

<b>Signature</b>

```typescript
typography: {
        fontFamily: {
            sansSerif: string;
            monospace: string;
        };
        size: {
            base: string;
            xs: string;
            sm: string;
            md: string;
            lg: string;
        };
        weight: {
            light: number;
            regular: number;
            semibold: number;
            bold: number;
        };
        lineHeight: {
            xs: number;
            sm: number;
            md: number;
            lg: number;
        };
        heading: {
            h1: string;
            h2: string;
            h3: string;
            h4: string;
            h5: string;
            h6: string;
        };
        link: {
            decoration: string;
            hoverDecoration: string;
        };
    };
```

### zIndex property

<b>Signature</b>

```typescript
zIndex: {
        dropdown: number;
        navbarFixed: number;
        sidemenu: number;
        tooltip: number;
        modalBackdrop: number;
        modal: number;
        portal: number;
        typeahead: number;
    };
```