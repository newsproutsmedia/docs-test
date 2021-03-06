+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "locationUtil"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## locationUtil variable

### locationUtil variable

<b>Signature</b>

```typescript
locationUtil: {
    initialize: (dependencies: LocationUtilDependencies) => void;
    stripBaseFromUrl: (url: string) => string;
    assureBaseUrl: (url: string) => string;
    updateSearchParams: (init: string, partial: string) => string;
    getTimeRangeUrlParams: () => string | null;
    getVariablesUrlParams: (scopedVars?: ScopedVars | undefined) => string | null;
    processUrl: (url: string) => string;
}
```
<b>Import</b>

```typescript
import { locationUtil } from '@grafana/data';
```
