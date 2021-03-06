+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "BackendSrvRequest"
keywords = ["grafana","documentation","sdk","@grafana/runtime"]
type = "docs"
disable_edit_link = true
+++

## BackendSrvRequest type

### BackendSrvRequest type

Used to initiate a remote call via the [BackendSrv]({{< relref "../runtime/backendsrv.md" >}})

<b>Signature</b>

```typescript
export declare type BackendSrvRequest = {
    url: string;
    retry?: number;
    headers?: Record<string, any>;
    method?: string;
    showSuccessAlert?: boolean;
    showErrorAlert?: boolean;
    requestId?: string;
    hideFromInspector?: boolean;
    data?: any;
    params?: Record<string, any>;
    responseType?: 'json' | 'text' | 'arraybuffer' | 'blob';
    credentials?: RequestCredentials;
    withCredentials?: boolean;
};
```
<b>Import</b>

```typescript
import { BackendSrvRequest } from '@grafana/runtime';
```
