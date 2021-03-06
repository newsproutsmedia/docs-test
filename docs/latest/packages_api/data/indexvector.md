+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "IndexVector"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## IndexVector class

IndexVector is a simple vector implementation that returns the index value for each element in the vector. It is functionally equivolant a vector backed by an array with values: `[0,1,2,...,length-1]`

<b>Signature</b>

```typescript
export declare class IndexVector extends FunctionalVector<number> 
```
<b>Import</b>

```typescript
import { IndexVector } from '@grafana/data';
```
<b>Constructors</b>

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [constructor(len)](#constructor-len) |  | Constructs a new instance of the <code>IndexVector</code> class |

<b>Properties</b>

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [length](#length-property) |  | <code>number</code> |  |

<b>Methods</b>

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [get(index)](#get-method) |  |  |
|  [newField(len)](#newfield-method) | <code>static</code> | Returns a field representing the range \[0 ... length-1\] |

### constructor(len)

Constructs a new instance of the `IndexVector` class

<b>Signature</b>

```typescript
constructor(len: number);
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  len | <code>number</code> |  |

### length property

<b>Signature</b>

```typescript
get length(): number;
```

### get method

<b>Signature</b>

```typescript
get(index: number): number;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  index | <code>number</code> |  |

<b>Returns:</b>

`number`

### newField method

Returns a field representing the range \[0 ... length-1\]

<b>Signature</b>

```typescript
static newField(len: number): Field<number>;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  len | <code>number</code> |  |

<b>Returns:</b>

`Field<number>`

