+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "DropzoneFile"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
disable_edit_link = true
+++

## DropzoneFile interface

<b>Signature</b>

```typescript
export interface DropzoneFile 
```
<b>Import</b>

```typescript
import { DropzoneFile } from '@grafana/ui';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [abortUpload](#abortupload-property) | <code>() =&gt; void</code> |  |
|  [error](#error-property) | <code>DOMException &#124; null</code> |  |
|  [file](#file-property) | <code>File</code> |  |
|  [id](#id-property) | <code>string</code> |  |
|  [progress](#progress-property) | <code>number</code> |  |
|  [retryUpload](#retryupload-property) | <code>() =&gt; void</code> |  |

### abortUpload property

<b>Signature</b>

```typescript
abortUpload?: () => void;
```

### error property

<b>Signature</b>

```typescript
error: DOMException | null;
```

### file property

<b>Signature</b>

```typescript
file: File;
```

### id property

<b>Signature</b>

```typescript
id: string;
```

### progress property

<b>Signature</b>

```typescript
progress?: number;
```

### retryUpload property

<b>Signature</b>

```typescript
retryUpload?: () => void;
```