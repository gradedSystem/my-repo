---
title: Regions and continents with the most medals at the Paris 2024 Olympic Games
description: Countries in Western Europe, East Asia, and North America were the best performers
---

<PlotlyLineChart
  data={{
    url: 'continent_golds.csv'
  }}
  title="Gold medals by continent"
  xAxis="Continent"
  yAxis="Gold Medals"
/>
<FlatUiTable data={{ url: "continent_golds.csv" }}/>
