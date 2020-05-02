---
altLangPrefix: index
authorName: Natural Resources Canada
authorUrl:
contentTitle: dsra_sim6p8_cr2022_rlz_1_b0_casualties_agg_view
dateModified: 2020-05-02
description:
  en: "Get quick, easy access to all Government of Canada services and information."
  fr: "Accédez rapidement et facilement à tous les services et renseignements du gouvernement du Canada."
noContentTitle: true
pageclass: wb-prettify all-pre
subject:
  en: [GV Government and Politics, Government services]
  fr: [GV Gouvernement et vie politique, Services gouvernementaux]
title: Test page - Canada.ca
# Leaflet
leaflet: true
latlng: [49.24, -123.11]
zoom: 10
layer: "/assets/data/dsra_sim6p8_cr2022_rlz_1_b0_casualties_agg_view.geojson"
# mlatlng: [49.24, -123.11] # marker lat/lon
---
# {{ page.contentTitle }}

{% include leaflet.html %}

Preview of {{ page.contentTitle }} dataset.

## Downloads

[GeoJSON]({{page.layer}})
