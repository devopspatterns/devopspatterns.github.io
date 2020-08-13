---
title: "Micro vs Mono Repo"
date: 2020-08-10T09:07:42-04:00
---
> "One codebase tracked in revision control, many deploys"
>
> --12 Factor App

1. Following the principal of a single repository for each application forces teams to analyze the integration points of their application and identify potential monoliths that can be split off into microservices.
1. Single team can work on smaller repositories without as much merging and conflict management
1. Releases can be better managed and maintained in smaller repos that deploy specific applications or components vs monoliths

