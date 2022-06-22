---
_build:
  list: false
aliases:
  - /docs/grafana/v8.5/release-notes/release-notes-8-0-4/
title: Release notes for Grafana 8.0.4
---

<!-- Auto generated by update changelog github action -->

# Release notes for Grafana 8.0.4

### Features and enhancements

- **Live:** Rely on app url for origin check. [#35983](https://github.com/grafana/grafana/pull/35983), [@FZambia](https://github.com/FZambia)
- **PieChart:** Sort legend descending, update placeholder to show default …. [#36062](https://github.com/grafana/grafana/pull/36062), [@ashharrison90](https://github.com/ashharrison90)
- **TimeSeries panel:** Do not reinitialize plot when thresholds mode change. [#35952](https://github.com/grafana/grafana/pull/35952), [@dprokop](https://github.com/dprokop)

### Bug fixes

- **Elasticsearch:** Allow case sensitive custom options in date_histogram interval. [#36168](https://github.com/grafana/grafana/pull/36168), [@Elfo404](https://github.com/Elfo404)
- **Elasticsearch:** Restore previous field naming strategy when using variables. [#35624](https://github.com/grafana/grafana/pull/35624), [@Elfo404](https://github.com/Elfo404)
- **Explore:** Fix import of queries between SQL data sources. [#36210](https://github.com/grafana/grafana/pull/36210), [@ivanahuckova](https://github.com/ivanahuckova)
- **InfluxDB:** InfluxQL query editor: fix retention policy handling. [#36022](https://github.com/grafana/grafana/pull/36022), [@gabor](https://github.com/gabor)
- **Loki:** Send correct time range in template variable queries. [#36268](https://github.com/grafana/grafana/pull/36268), [@ivanahuckova](https://github.com/ivanahuckova)
- **TimeSeries:** Preserve RegExp series overrides when migrating from old graph panel. [#36134](https://github.com/grafana/grafana/pull/36134), [@ashharrison90](https://github.com/ashharrison90)