# IceCreamParlor

## Description

Two friends like to pool their money and go to the ice cream parlour. They always choose two distinct flavors and they spend all of their money.

Given a list of prices for the flavours of ice cream, select the two that will cost all of the money they have.

Example. _m = 6 cost = [1, 3, 4, 5, 6]_
The two flavours that cost and meet the criteria. Using -based indexing, they are at indices _1_ and _4_.

## Returns

- int[2]: the indices of the prices of the two flavours they buy, sorted ascending

## Input

- The first line contains an integer, _t_, the number of trips to the ice cream parlour. The next _t_ sets of lines each describes a visit.

Each trip is described as follows:

- The integer _m_, the amount of money they have pooled.
- The integer _n_, the number of flavors offered at the time.
- _n_ space-separated integers denoting the cost of each flavor: _cost[cost[1], cost[2], ..., cost[n]]_.

Note: The index within the cost array represents the flavor of the ice cream purchased. 
