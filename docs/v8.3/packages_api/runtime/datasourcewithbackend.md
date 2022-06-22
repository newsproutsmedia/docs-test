+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "DataSourceWithBackend"
keywords = ["grafana","documentation","sdk","@grafana/runtime"]
type = "docs"
disable_edit_link = true
+++

## DataSourceWithBackend class

Extend this class to implement a data source plugin that is depending on the Grafana backend API.

<b>Signature</b>

```typescript
declare class DataSourceWithBackend<TQuery extends DataQuery = DataQuery, TOptions extends DataSourceJsonData = DataSourceJsonData> extends DataSourceApi<TQuery, TOptions> 
```
<b>Import</b>

```typescript
import { DataSourceWithBackend } from '@grafana/runtime';
```
<b>Constructors</b>

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [constructor(instanceSettings)](#constructor-instancesettings) |  | Constructs a new instance of the <code>DataSourceWithBackend</code> class |

<b>Properties</b>

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [streamOptionsProvider](#streamoptionsprovider-property) |  | <code>StreamOptionsProvider&lt;TQuery&gt;</code> | Optionally override the streaming behavior |

<b>Methods</b>

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [applyTemplateVariables(query, scopedVars)](#applytemplatevariables-method) |  | Override to apply template variables. The result is usually also <code>TQuery</code>, but sometimes this can be used to modify the query structure before sending to the backend.<!-- -->NOTE: if you do modify the structure or use template variables, alerting queries may not work as expected |
|  [callHealthCheck()](#callhealthcheck-method) |  | Run the datasource healthcheck |
|  [getResource(path, params)](#getresource-method) |  | Make a GET request to the datasource resource path |
|  [interpolateVariablesInQueries(queries, scopedVars)](#interpolatevariablesinqueries-method) |  | Apply template variables for explore |
|  [postResource(path, body)](#postresource-method) |  | Send a POST request to the datasource resource path |
|  [query(request)](#query-method) |  | Ideally final -- any other implementation may not work as expected |
|  [testDatasource()](#testdatasource-method) |  | Checks the plugin health see public/app/features/datasources/state/actions.ts for what needs to be returned here |

### constructor(instanceSettings)

Constructs a new instance of the `DataSourceWithBackend` class

<b>Signature</b>

```typescript
constructor(instanceSettings: DataSourceInstanceSettings<TOptions>);
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  instanceSettings | <code>DataSourceInstanceSettings&lt;TOptions&gt;</code> |  |

### streamOptionsProvider property

Optionally override the streaming behavior

<b>Signature</b>

```typescript
streamOptionsProvider: StreamOptionsProvider<TQuery>;
```

### applyTemplateVariables method

Override to apply template variables. The result is usually also `TQuery`<!-- -->, but sometimes this can be used to modify the query structure before sending to the backend.

NOTE: if you do modify the structure or use template variables, alerting queries may not work as expected

<b>Signature</b>

```typescript
/** @virtual */
applyTemplateVariables(query: TQuery, scopedVars: ScopedVars): Record<string, any>;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  query | <code>TQuery</code> |  |
|  scopedVars | <code>ScopedVars</code> |  |

<b>Returns:</b>

`Record<string, any>`

### callHealthCheck method

Run the datasource healthcheck

<b>Signature</b>

```typescript
callHealthCheck(): Promise<HealthCheckResult>;
```
<b>Returns:</b>

`Promise<HealthCheckResult>`

### getResource method

Make a GET request to the datasource resource path

<b>Signature</b>

```typescript
getResource(path: string, params?: any): Promise<any>;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  path | <code>string</code> |  |
|  params | <code>any</code> |  |

<b>Returns:</b>

`Promise<any>`

### interpolateVariablesInQueries method

Apply template variables for explore

<b>Signature</b>

```typescript
interpolateVariablesInQueries(queries: TQuery[], scopedVars: ScopedVars | {}): TQuery[];
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  queries | <code>TQuery[]</code> |  |
|  scopedVars | <code>ScopedVars &#124; {}</code> |  |

<b>Returns:</b>

`TQuery[]`

### postResource method

Send a POST request to the datasource resource path

<b>Signature</b>

```typescript
postResource(path: string, body?: any): Promise<any>;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  path | <code>string</code> |  |
|  body | <code>any</code> |  |

<b>Returns:</b>

`Promise<any>`

### query method

Ideally final -- any other implementation may not work as expected

<b>Signature</b>

```typescript
query(request: DataQueryRequest<TQuery>): Observable<DataQueryResponse>;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | <code>DataQueryRequest&lt;TQuery&gt;</code> |  |

<b>Returns:</b>

`Observable<DataQueryResponse>`

### testDatasource method

Checks the plugin health see public/app/features/datasources/state/actions.ts for what needs to be returned here

<b>Signature</b>

```typescript
testDatasource(): Promise<any>;
```
<b>Returns:</b>

`Promise<any>`
