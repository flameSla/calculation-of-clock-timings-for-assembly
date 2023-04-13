# Сalculation of "clock" timings for assembly machines
## A "clock" - what is it?

1. The assembly machine works faster than the melting furnace

This leads to the fact that the inserter takes 1 plate instead of 12 ->  need to do extra swings -> bad for UPS

2. **clock** UPS optimization technique

We specifically slow down the work of the inserter, now the inserter always takes 12 items

cons - logic circuits are needed

3.  **back pressure** UPS optimization technique

we accelerate the work of the melting furnace, as a result, we have overproduction - there are always 100 plates in the furnace

now the inserter always takes 12 items

cons  - you need more furnaces, beacons, modules, etc.

but there will be a benefit for UPS

## Плавильные печи
