---
altLangPrefix: index
authorName: Natural Resources Canada
authorUrl:
contentTitle:
  fr: OpenDRR - Réduction des risques de catastrophe ouverte
  en: OpenDRR - Open Disaster Risk Reduction
dateModified: 2021-02-18
description:
  en: Available datasets
  fr: Ensembles de données disponibles
noContentTitle: true
pageclass: wb-prettify all-pre
subject:
  en: [OpenDRR (Open Disaster Risk Reduction) Platform]
  fr: [OpenDRR (plate-forme ouverte pour la réduction des risques de catastrophes)]
title: OpenDRR
---

# {{ page.contentTitle.en }}

Welcome!

The OpenDRR platform is middleware between hazard or risk modeling environments like the [OpenQuake](https://www.globalquakemodel.org/openquake) engine and end users who need to understand and evaluate risk to make economic and policy decisions.

The end-user interface is available at [www.RiskProfiler.ca](https://www.riskprofiler.ca/) and operates as a web application using standard web browsers in desktop, tablet or hand-held device environments.

Full documentation of the RiskProfiler product is available through that website. For documentation of this OpenDRR platform, see the links below.

## Downloads

* [OpenDRR Data Downloads](https://opendrr.github.io/downloads/en/){:target="_blank"} at <https://opendrr.github.io/downloads/en/>{:target="_blank"}

## Documentation

### Research Paper

* [A Federated OpenDRR Platform to Support Disaster Resilience Planning in Canada: High Level Requirements](https://opendrr.github.io/documentation/docs/opendrr-platform.html){:target="_blank"}

## Video Introduction

<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/-M3NHo-aW_g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

Visit the [Understanding Risk (UR) BC 2020 Online Symposium](https://www.urbc.ca/){:target="_blank"} for more great sessions.  Here are some of them among many:

* 2020-11-03: [Test Driving a Rapid Disaster Modelling Methodology for British Columbia Earthquakes](https://www.urbc.ca/disastermodellingmethodologyforbc){:target="_blank"}
* 2020-11-17: [Mainstreaming Seismic Resilience: Transforming Earthquake Risk Information into Plans for Resilient Communities](https://www.urbc.ca/mainstreamingseismicresilience){:target="_blank"}
* 2020-11-24: [Terra-Cognita: How can we Accelerate Disaster Resilience Planning with OpenData?](https://www.urbc.ca/terra-cognita){:target="_blank"}

## For Developers

* [Parent GitHub repository for the OpenDRR Platform](https://github.com/OpenDRR/opendrr-platform){:target="_blank"} at <https://github.com/OpenDRR/opendrr-platform>{:target="_blank"}


{% if false %}

{{page.description.en}}

<ul>
  {% for page in site.pages %}
  {% if page.path contains 'en/data' %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.contentTitle.en }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>

{% endif %}
