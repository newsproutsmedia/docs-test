+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "PluginMeta"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## PluginMeta interface

<b>Signature</b>

```typescript
export interface PluginMeta<T extends KeyValue = {}> 
```
<b>Import</b>

```typescript
import { PluginMeta } from '@grafana/data';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [baseUrl](#baseurl-property) | <code>string</code> |  |
|  [defaultNavUrl](#defaultnavurl-property) | <code>string</code> |  |
|  [dependencies](#dependencies-property) | <code>PluginDependencies</code> |  |
|  [enabled](#enabled-property) | <code>boolean</code> |  |
|  [enterprise](#enterprise-property) | <code>boolean</code> |  |
|  [hasUpdate](#hasupdate-property) | <code>boolean</code> |  |
|  [id](#id-property) | <code>string</code> |  |
|  [includes](#includes-property) | <code>PluginInclude[]</code> |  |
|  [info](#info-property) | <code>PluginMetaInfo</code> |  |
|  [jsonData](#jsondata-property) | <code>T</code> |  |
|  [latestVersion](#latestversion-property) | <code>string</code> |  |
|  [live](#live-property) | <code>boolean</code> |  |
|  [module](#module-property) | <code>string</code> |  |
|  [name](#name-property) | <code>string</code> |  |
|  [pinned](#pinned-property) | <code>boolean</code> |  |
|  [secureJsonData](#securejsondata-property) | <code>KeyValue</code> |  |
|  [signature](#signature-property) | <code>PluginSignatureStatus</code> |  |
|  [signatureOrg](#signatureorg-property) | <code>string</code> |  |
|  [signatureType](#signaturetype-property) | <code>PluginSignatureType</code> |  |
|  [state](#state-property) | <code>PluginState</code> |  |
|  [type](#type-property) | <code>PluginType</code> |  |

### baseUrl property

<b>Signature</b>

```typescript
baseUrl: string;
```

### defaultNavUrl property

<b>Signature</b>

```typescript
defaultNavUrl?: string;
```

### dependencies property

<b>Signature</b>

```typescript
dependencies?: PluginDependencies;
```

### enabled property

<b>Signature</b>

```typescript
enabled?: boolean;
```

### enterprise property

<b>Signature</b>

```typescript
enterprise?: boolean;
```

### hasUpdate property

<b>Signature</b>

```typescript
hasUpdate?: boolean;
```

### id property

<b>Signature</b>

```typescript
id: string;
```

### includes property

<b>Signature</b>

```typescript
includes?: PluginInclude[];
```

### info property

<b>Signature</b>

```typescript
info: PluginMetaInfo;
```

### jsonData property

<b>Signature</b>

```typescript
jsonData?: T;
```

### latestVersion property

<b>Signature</b>

```typescript
latestVersion?: string;
```

### live property

<b>Signature</b>

```typescript
live?: boolean;
```

### module property

<b>Signature</b>

```typescript
module: string;
```

### name property

<b>Signature</b>

```typescript
name: string;
```

### pinned property

<b>Signature</b>

```typescript
pinned?: boolean;
```

### secureJsonData property

<b>Signature</b>

```typescript
secureJsonData?: KeyValue;
```

### signature property

<b>Signature</b>

```typescript
signature?: PluginSignatureStatus;
```

### signatureOrg property

<b>Signature</b>

```typescript
signatureOrg?: string;
```

### signatureType property

<b>Signature</b>

```typescript
signatureType?: PluginSignatureType;
```

### state property

<b>Signature</b>

```typescript
state?: PluginState;
```

### type property

<b>Signature</b>

```typescript
type: PluginType;
```
