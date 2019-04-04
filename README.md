Power plant
================

## Iteration 1 ##

- Electricity is produced by power plants. For example, a power plant can produce an average of 1 gigawatts or 1000 megawatts or 1,000,000,000 watts.
- Electricity is consumed by individual buildings. For example, an average of 4 kW/h.

- Individual buildings have a monthly electricity report, and this report is based on the amount of consumed electricity of that building during one month.

- Electricity distribution can be categorized by different groups such: areas, cities, streets or individual buildings.

- Each group consume is equal to the sumatory of the individual building consume in each group.

    - Example: An area with 3000 buildings should have an average consume of 4kwh * 3000 = 12MW/h

- Power plants have a monthly balance with the cost of the total generated/consumed electricity.


## Iteration 2
- Electric network can fail, then some individual buildings, streets, cities, and/or areas can run out of electricity during a period of time.

- In this case, electricity is not consumed, so during this period of time, should not appear any consume in the monthly report. But should appear on power plants balance as lost.

## Iteration 3

- When electric network fail, power plants should get notified with an alert.

- Areas, cities, streets have a maximum of consume of kWh. This value cannot be exceeded, in case of reach the maximum, power plants should be alerted.

- When a individual buildings electricity consume changes more than 20%  compared with the last previous 3 months, power plants should get notified with a message:
    - A Warning notification in falling consumption
    - An Alert notification in case of overconsume


## Iteration 4

 - Individual buildings, can generate electricity for example using solar panel, (average 1 kwh), this affect the building's electrical consume, and this should be reflected on the monthly report.

- In case of network fail, this buildings should consume only its own electricity.
