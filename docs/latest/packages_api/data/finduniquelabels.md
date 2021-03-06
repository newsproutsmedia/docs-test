+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "findUniqueLabels"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## findUniqueLabels() function

### findUniqueLabels() function

Returns a map of labels that are in `labels`<!-- -->, but not in `commonLabels`<!-- -->.

<b>Signature</b>

```typescript
export declare function findUniqueLabels(labels: Labels | undefined, commonLabels: Labels): Labels;
```
<b>Import</b>

```typescript
import { findUniqueLabels } from '@grafana/data';
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  labels | <code>Labels &#124; undefined</code> |  |
|  commonLabels | <code>Labels</code> |  |

<b>Returns:</b>

`Labels`

