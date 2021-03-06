+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "GraphNGProps"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
disable_edit_link = true
+++

## GraphNGProps interface

<b>Signature</b>

```typescript
export interface GraphNGProps extends Themeable2 
```
<b>Import</b>

```typescript
import { GraphNGProps } from '@grafana/ui';
```
<b>Properties</b>

|  Property | Type | Description |
|  --- | --- | --- |
|  [children](#children-property) | <code>(builder: UPlotConfigBuilder, alignedFrame: DataFrame) =&gt; React.ReactNode</code> |  |
|  [fields](#fields-property) | <code>XYFieldMatchers</code> |  |
|  [frames](#frames-property) | <code>DataFrame[]</code> |  |
|  [height](#height-property) | <code>number</code> |  |
|  [legend](#legend-property) | <code>VizLegendOptions</code> |  |
|  [onLegendClick](#onlegendclick-property) | <code>(event: GraphNGLegendEvent) =&gt; void</code> |  |
|  [preparePlotFrame](#prepareplotframe-property) | <code>(frames: DataFrame[], dimFields: XYFieldMatchers) =&gt; DataFrame</code> |  |
|  [prepConfig](#prepconfig-property) | <code>(alignedFrame: DataFrame, allFrames: DataFrame[], getTimeRange: () =&gt; TimeRange) =&gt; UPlotConfigBuilder</code> |  |
|  [propsToDiff](#propstodiff-property) | <code>Array&lt;string &#124; PropDiffFn&gt;</code> |  |
|  [renderLegend](#renderlegend-property) | <code>(config: UPlotConfigBuilder) =&gt; React.ReactElement &#124; null</code> |  |
|  [structureRev](#structurerev-property) | <code>number</code> |  |
|  [timeRange](#timerange-property) | <code>TimeRange</code> |  |
|  [timeZone](#timezone-property) | <code>TimeZone</code> |  |
|  [width](#width-property) | <code>number</code> |  |

### children property

<b>Signature</b>

```typescript
children?: (builder: UPlotConfigBuilder, alignedFrame: DataFrame) => React.ReactNode;
```

### fields property

<b>Signature</b>

```typescript
fields?: XYFieldMatchers;
```

### frames property

<b>Signature</b>

```typescript
frames: DataFrame[];
```

### height property

<b>Signature</b>

```typescript
height: number;
```

### legend property

<b>Signature</b>

```typescript
legend: VizLegendOptions;
```

### onLegendClick property

<b>Signature</b>

```typescript
onLegendClick?: (event: GraphNGLegendEvent) => void;
```

### preparePlotFrame property

<b>Signature</b>

```typescript
preparePlotFrame?: (frames: DataFrame[], dimFields: XYFieldMatchers) => DataFrame;
```

### prepConfig property

<b>Signature</b>

```typescript
prepConfig: (alignedFrame: DataFrame, allFrames: DataFrame[], getTimeRange: () => TimeRange) => UPlotConfigBuilder;
```

### propsToDiff property

<b>Signature</b>

```typescript
propsToDiff?: Array<string | PropDiffFn>;
```

### renderLegend property

<b>Signature</b>

```typescript
renderLegend: (config: UPlotConfigBuilder) => React.ReactElement | null;
```

### structureRev property

<b>Signature</b>

```typescript
structureRev?: number;
```

### timeRange property

<b>Signature</b>

```typescript
timeRange: TimeRange;
```

### timeZone property

<b>Signature</b>

```typescript
timeZone: TimeZone;
```

### width property

<b>Signature</b>

```typescript
width: number;
```
