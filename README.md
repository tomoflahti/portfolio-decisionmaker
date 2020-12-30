# Development Portfolio Decision Tool
Building AI course project - initial skeleton setup for Python DataViz tools

## Summary
An AI-powered portfolio decision making tool - that takes input from historical data and WSJF (weighted shortest job first) analysis and provides an API response or a heatmap on given architectural areas.

## Background
Portfolio Analysis typically takes input from either an educated guess, experiences from previous solutions or other heuristical methods. This solution aims to map necessary data and provide an easy solution for Enterprise Architectural decisions.

## How it works?
Two components:
* portfolio-api: Flask application that provides on-demand decision input.
* DataViz application: Provides a WSJF score plotted on a heatmap

## Portfolio API inputs
Provide data to analysis API in a given schema:
* identifier (string, unique)
* user-business value (integer)
* time criticality (integer)
* risk reduction / opportunity enablement (integer)
* job duration (integer)

## DataViz inputs
Take data from predefined sets of variables, CMDBs and historical analysis of workflow states per domain/area/application per workitem size.

* Parse data from Atlassian JIRA via API or a flat file

## DataViz Outputs
* DataViz: WSJF score plotted on a heatmap
