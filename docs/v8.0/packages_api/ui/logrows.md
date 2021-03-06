+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "LogRows"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
disable_edit_link = true
+++

## LogRows variable

### LogRows variable

<b>Signature</b>

```typescript
LogRows: React.FunctionComponent<{
    timeZone: TimeZone;
    getRowContext?: ((row: LogRowModel, options?: RowContextOptions | undefined) => Promise<any>) | undefined;
    logsSortOrder?: LogsSortOrder | null | undefined;
    highlighterExpressions?: string[] | undefined;
    wrapLogMessage: boolean;
    showContextToggle?: ((row?: LogRowModel | undefined) => boolean) | undefined;
    onClickFilterLabel?: ((key: string, value: string) => void) | undefined;
    onClickFilterOutLabel?: ((key: string, value: string) => void) | undefined;
    showDetectedFields?: string[] | undefined;
    onClickShowDetectedField?: ((key: string) => void) | undefined;
    onClickHideDetectedField?: ((key: string) => void) | undefined;
    getFieldLinks?: ((field: Field, rowIndex: number) => Array<LinkModel<Field>>) | undefined;
    showLabels: boolean;
    showTime: boolean;
    enableLogDetails: boolean;
    forceEscape?: boolean | undefined;
    logRows?: LogRowModel[] | undefined;
    deduplicatedRows?: LogRowModel[] | undefined;
    dedupStrategy: LogsDedupStrategy;
    previewLimit?: number | undefined;
}>
```
<b>Import</b>

```typescript
import { LogRows } from '@grafana/ui';
```
