+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "@grafana/runtime"
keywords = ["grafana","documentation","sdk","@grafana/runtime"]
type = "docs"
disable_edit_link = true
+++

## @grafana/runtime package

A library containing services, configurations etc. used to interact with the Grafana engine.

## Classes

|  Class | Description |
|  --- | --- |
|  [DataSourceWithBackend](./datasourcewithbackend/) | Extend this class to implement a data source plugin that is depending on the Grafana backend API. |
|  [GrafanaBootConfig](./grafanabootconfig/) |  |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [EchoEventType](./echoeventtype/) | Supported echo event types that can be sent via the [EchoSrv]({{< relref "../runtime/echosrv.md" >}})<!-- -->. |
|  [HealthStatus](./healthstatus/) | Describes the current health status of a data source plugin. |
|  [MetaAnalyticsEventName](./metaanalyticseventname/) | The meta analytics events that can be added to the echo service. |

## Functions

|  Function | Description |
|  --- | --- |
|  [frameToMetricFindValue(frame)](./frametometricfindvalue/) | <b><i>(BETA)</i></b> Return the first string or non-time field as the value |
|  [getAngularLoader()](./getangularloader/) | Used to retrieve the [AngularLoader]({{< relref "../runtime/angularloader.md" >}}) that enables the use of Angular components within a React component.<!-- -->Please see the [AngularComponent]({{< relref "../runtime/angularcomponent.md" >}}) for a proper example. |
|  [getDataSourceSrv()](./getdatasourcesrv/) | Used to retrieve the [DataSourceSrv]({{< relref "../runtime/datasourcesrv.md" >}}) that is the entry point for communicating with a datasource that is added as a plugin (both external and internal). |
|  [getEchoSrv()](./getechosrv/) | Used to retrieve the [EchoSrv]({{< relref "../runtime/echosrv.md" >}}) that can be used to report events to registered echo backends. |
|  [getLocationSrv()](./getlocationsrv/) | Used to retrieve the [LocationSrv]({{< relref "../runtime/locationsrv.md" >}}) that can be used to automatically navigate the user to a new place in Grafana. |
|  [loadPluginCss(options)](./loadplugincss/) | Use this to load css for a Grafana plugin by specifying a [PluginCssOptions]({{< relref "../runtime/plugincssoptions.md" >}}) containing styling for the dark and the light theme. |
|  [logDebug(message, contexts)](./logdebug/) | Log a message at DEBUG level. Depending on configuration might be forwarded to backend and logged to stdout or sent to Sentry |
|  [logError(err, contexts)](./logerror/) | Log an error. Depending on configuration might be forwarded to backend and logged to stdout or sent to Sentry |
|  [logInfo(message, contexts)](./loginfo/) | Log a message at INFO level. Depending on configuration might be forwarded to backend and logged to stdout or sent to Sentry |
|  [logWarning(message, contexts)](./logwarning/) | Log a message at WARNING level. Depending on configuration might be forwarded to backend and logged to stdout or sent to Sentry |
|  [toDataQueryError(err)](./todataqueryerror/) | Convert an object into a DataQueryError -- if this is an HTTP response, it will put the correct values in the error field |
|  [toDataQueryResponse(res, queries)](./todataqueryresponse/) | Parse the results from /api/ds/query into a DataQueryResponse |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AngularComponent](./angularcomponent/) | Used to enable rendering of Angular components within a React component without losing proper typings. |
|  [AngularLoader](./angularloader/) | Used to load an Angular component from the context of a React component. Please see the [AngularComponent]({{< relref "../runtime/angularcomponent.md" >}}) for a proper example. |
|  [AzureSettings](./azuresettings/) |  |
|  [BackendSrv](./backendsrv/) | Used to communicate via http(s) to a remote backend such as the Grafana backend, a datasource etc. The BackendSrv is using the [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) under the hood to handle all the communication.<!-- -->The request function can be used to perform a remote call by specifying a [BackendSrvRequest]({{< relref "../runtime/backendsrvrequest.md" >}})<!-- -->. To make the BackendSrv a bit easier to use we have added a couple of shorthand functions that will use default values executing the request. |
|  [DashboardInfo](./dashboardinfo/) | Describes the basic dashboard information that can be passed as the meta analytics payload. |
|  [DashboardViewEventPayload](./dashboardvieweventpayload/) | Describes the payload of a dashboard view event. |
|  [DataRequestEventPayload](./datarequesteventpayload/) | Describes the payload of a data request event. |
|  [DataRequestInfo](./datarequestinfo/) | Describes the data request information passed as the meta analytics payload. |
|  [DataSourceSrv](./datasourcesrv/) | This is the entry point for communicating with a datasource that is added as a plugin (both external and internal). Via this service you will get access to the [DataSourceApi]({{< relref "../data/datasourceapi.md" >}}) that have a rich API for communicating with the datasource. |
|  [EchoBackend](./echobackend/) | Describes echo backends that can be registered to receive of events. |
|  [EchoEvent](./echoevent/) | Describes an echo event. |
|  [EchoMeta](./echometa/) | Describes the meta information that are sent together with each event. |
|  [EchoSrv](./echosrv/) | Used to send events to all the registered backends. This should be accessed via the [getEchoSrv()]({{< relref "../runtime/getechosrv.md" >}}) function. Will, by default, flush events to the backends every 10s or when the flush function is triggered. |
|  [FetchError](./fetcherror/) | Error type for fetch function in [BackendSrv]({{< relref "../runtime/backendsrv.md" >}}) |
|  [FetchErrorDataProps](./fetcherrordataprops/) | Error type for fetch function in [BackendSrv]({{< relref "../runtime/backendsrv.md" >}}) |
|  [FetchResponse](./fetchresponse/) | Response for fetch function in [BackendSrv]({{< relref "../runtime/backendsrv.md" >}}) |
|  [GetDataSourceListFilters](./getdatasourcelistfilters/) |  |
|  [HealthCheckResult](./healthcheckresult/) | Describes the payload returned when checking the health of a data source plugin. |
|  [InteractionEchoEventPayload](./interactionechoeventpayload/) | Describes the payload of a user interaction event. |
|  [LocationSrv](./locationsrv/) | If you need to automatically navigate the user to a new place in the application this should be done via the LocationSrv and it will make sure to update the application state accordingly. |
|  [LocationUpdate](./locationupdate/) |  |
|  [MetaAnalyticsEvent](./metaanalyticsevent/) | Describes meta analytics event with predefined  type. |
|  [PageviewEchoEventPayload](./pageviewechoeventpayload/) | Describes the payload of a pageview event. |
|  [PluginCssOptions](./plugincssoptions/) | Option to specify a plugin css that should be applied for the dark and the light theme. |
|  [SizeMeta](./sizemeta/) | Describes a size with width/height |
|  [TemplateSrv](./templatesrv/) | Via the TemplateSrv consumers get access to all the available template variables that can be used within the current active dashboard.<!-- -->For a more in-depth description visit: https://grafana.com/docs/grafana/v8.1/reference/templating |

## Variables

|  Variable | Description |
|  --- | --- |
|  [config](./config/) | Use this to access the [GrafanaBootConfig]({{< relref "../runtime/grafanabootconfig.md" >}}) for the current running Grafana instance. |
|  [getBackendSrv](./getbackendsrv/) | Used to retrieve the [BackendSrv]({{< relref "../runtime/backendsrv.md" >}}) that can be used to communicate via http(s) to a remote backend such as the Grafana backend, a datasource etc. |
|  [getLegacyAngularInjector](./getlegacyangularinjector/) | <b><i>(BETA)</i></b> WARNING: this function provides a temporary way for plugins to access anything in the angular injector. While the migration from angular to react continues, there are a few options that do not yet have good alternatives. Note that use of this function will be removed in the future. |
|  [getTemplateSrv](./gettemplatesrv/) | Used to retrieve the [TemplateSrv]({{< relref "../runtime/templatesrv.md" >}}) that can be used to fetch available template variables. |
|  [isInteractionEvent](./isinteractionevent/) | Interaction event typeguard. |
|  [isPageviewEvent](./ispageviewevent/) | Pageview event typeguard. |
|  [registerEchoBackend](./registerechobackend/) | Used to register echo backends that will receive Grafana echo events during application runtime. |
|  [reportInteraction](./reportinteraction/) | Helper function to report interaction events to the [EchoSrv]({{< relref "../runtime/echosrv.md" >}})<!-- -->. |
|  [reportMetaAnalytics](./reportmetaanalytics/) | Helper function to report meta analytics to the [EchoSrv]({{< relref "../runtime/echosrv.md" >}})<!-- -->. |
|  [reportPageview](./reportpageview/) | Helper function to report pageview events to the [EchoSrv]({{< relref "../runtime/echosrv.md" >}})<!-- -->. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [BackendSrvRequest](./backendsrvrequest/) | Used to initiate a remote call via the [BackendSrv]({{< relref "../runtime/backendsrv.md" >}}) |
|  [HealthCheckResultDetails](./healthcheckresultdetails/) | Describes the details in the payload returned when checking the health of a data source plugin.<!-- -->If the 'message' key exists, this will be displayed in the error message in DataSourceSettingsPage If the 'verboseMessage' key exists, this will be displayed in the expandable details in the error message in DataSourceSettingsPage |
|  [InteractionEchoEvent](./interactionechoevent/) | Describes interaction event with predefined  type. |
|  [MetaAnalyticsEventPayload](./metaanalyticseventpayload/) | Describes the meta analytics payload passed with the [MetaAnalyticsEvent]({{< relref "../runtime/metaanalyticsevent.md" >}}) |
|  [PageviewEchoEvent](./pageviewechoevent/) | Describes pageview event with predefined  type. |
|  [StreamOptionsProvider](./streamoptionsprovider/) | This allows data sources to customize the streaming connection query |

