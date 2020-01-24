# Blue South 2020

## Visualization 1: Population Movement
*Goal:* Demonstrate visually that Southern states are the fastest growing in the country

*Source:* [County-to-County Migration Flows: 2013-2017 ACS](https://www.census.gov/data/tables/2017/demo/geographic-mobility/county-to-county-migration-2013-2017.html)

*Challenge:* This is high volume data and must demonstrate directionality, both of which can be difficult to visualize. The following visualisations represent a multitude of attempts

---

### Bar Graph: State Net Migration
![](state_migration/state_to_state_bar.png)

### Bar Graph: Top County Movements
![](state_migration/southern_county_to_county_bar.png)

---

### Choropleth: Net Migration
![](state_migration/states_net_migration.png)

---

### Network Analysis 
State to state migration, representing the "inflow" amounts from state to state, rather than net migration. The network was filtered to include only inflows that were >= 10,000 and states that have 2 or more inflows of that size

#### Version 1: Unweighted:
![](state_migration/state_network_2deg_10000inflow.png)

#### Version 2: Weighted:
![](state_migration/state_network_2deg_10000inflow_weighted.png)

---

### State to State Migration Map
![](state_migration/state_to_state_migration2.png)

### County to County Migration Map

This is a very large data set. To make it more intelligible visually, I made several adjustments: only included positive migration into Southern states, omitted movement between counties within the South

Even so, the resulting map had 32,466 connections. I then made two filtered maps - one with the top 10% of county migrations (~3,300) and one with the top 1% (~330). You can see all three versions below

#### Option 1: all migration to southern counties
![](state_migration/southern_county_to_county_migration.png)

#### Option 2: top 10% of migration to southern counties
![](state_migration/southern_county_to_county_migration_top10.png)

#### Option 3: top 1% of migration to southern counties
![](state_migration/southern_county_to_county_migration_top1.png)

---

### Chord Diagram

TBD
