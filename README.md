# SQL_Query23

Write a solution to report the number of users that used each bus.
Return the result table ordered by bus_id in ascending order.
Bus_id contains unique values.
Each row of this table contains information about the arrival time of a bus at the LeetCode station and its capacity 
(the number of empty seats it has).
No two buses will arrive at the same time and all bus capacities will be positive integers.
passenger_id contains unique values.
Each row of this table contains information about the arrival time of a passenger at the LeetCode station.
Buses and passengers arrive at the LeetCode station. If a bus arrives at the station at a time tbus and a passenger 
arrived at a time tpassenger where tpassenger <= tbus and the passenger did not catch any bus, the passenger will use that bus. 
In addition, each bus has a capacity. If at the moment the bus arrives at the station there are more passengers waiting than its 
capacity capacity, only capacity passengers will use the bus.
