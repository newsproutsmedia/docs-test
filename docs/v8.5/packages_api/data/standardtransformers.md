+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "standardTransformers"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
disable_edit_link = true
+++

## standardTransformers variable

### standardTransformers variable

<b>Signature</b>

```typescript
standardTransformers: {
    noopTransformer: import("..").DataTransformerInfo<import("./transformers/noop").NoopTransformerOptions>;
    filterFieldsTransformer: import("..").DataTransformerInfo<import("./transformers/filter").FilterOptions>;
    filterFieldsByNameTransformer: import("..").DataTransformerInfo<import("./transformers/filterByName").FilterFieldsByNameTransformerOptions>;
    filterFramesTransformer: import("..").DataTransformerInfo<import("./transformers/filter").FilterOptions>;
    filterFramesByRefIdTransformer: import("..").DataTransformerInfo<import("./transformers/filterByRefId").FilterFramesByRefIdTransformerOptions>;
    filterByValueTransformer: import("..").DataTransformerInfo<import("./transformers/filterByValue").FilterByValueTransformerOptions>;
    orderFieldsTransformer: import("..").DataTransformerInfo<import("./transformers/order").OrderFieldsTransformerOptions>;
    organizeFieldsTransformer: import("..").DataTransformerInfo<import("./transformers/organize").OrganizeFieldsTransformerOptions>;
    reduceTransformer: import("..").DataTransformerInfo<import("./transformers/reduce").ReduceTransformerOptions>;
    concatenateTransformer: import("..").DataTransformerInfo<import("./transformers/concat").ConcatenateTransformerOptions>;
    calculateFieldTransformer: import("..").DataTransformerInfo<import("./transformers/calculateField").CalculateFieldTransformerOptions>;
    seriesToColumnsTransformer: import("..").SynchronousDataTransformerInfo<import("./transformers/seriesToColumns").SeriesToColumnsOptions>;
    seriesToRowsTransformer: import("..").DataTransformerInfo<import("./transformers/seriesToRows").SeriesToRowsTransformerOptions>;
    renameFieldsTransformer: import("..").DataTransformerInfo<import("./transformers/rename").RenameFieldsTransformerOptions>;
    labelsToFieldsTransformer: import("..").SynchronousDataTransformerInfo<import("./transformers/labelsToFields").LabelsToFieldsOptions>;
    ensureColumnsTransformer: import("..").SynchronousDataTransformerInfo<any>;
    groupByTransformer: import("..").DataTransformerInfo<import("./transformers/groupBy").GroupByTransformerOptions>;
    sortByTransformer: import("..").DataTransformerInfo<import("./transformers/sortBy").SortByTransformerOptions>;
    mergeTransformer: import("..").DataTransformerInfo<import("./transformers/merge").MergeTransformerOptions>;
    renameByRegexTransformer: import("..").DataTransformerInfo<import("./transformers/renameByRegex").RenameByRegexTransformerOptions>;
    histogramTransformer: import("..").SynchronousDataTransformerInfo<import("./transformers/histogram").HistogramTransformerOptions>;
    convertFieldTypeTransformer: import("..").SynchronousDataTransformerInfo<import("./transformers/convertFieldType").ConvertFieldTypeTransformerOptions>;
    groupingToMatrixTransformer: import("..").DataTransformerInfo<import("./transformers/groupingToMatrix").GroupingToMatrixTransformerOptions>;
}
```
<b>Import</b>

```typescript
import { standardTransformers } from '@grafana/data';
```