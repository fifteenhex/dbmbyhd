# dbmbyhd
Don't Blame Me if it Burns Your House Down - RT9525GQW LiPo charger breakout

![omnomnom](/outputs/dbmbyhd.png)


## WHY?!

The RT9525GQW has active power path management that means the load is switched to your
input source instead of the load being powered from the battery while the charger
is trying to charge it. Woot!

## PCBs/Components

- PCB is shared on OSHPark; https://oshpark.com/shared_projects/hrCHnlJL
- The RT9525QGW is available from various suppliers on AliExpress for about $1, On taobao they are about $.50
- Get a cheap 0603 resistor/cap kit for the passives. Buy a stick of 10uF 0805 caps from ebay or whatever.

## Bugs

### Rev 0

- Missing via between gnd fill on the top and bottom layers. Means the iseta resistor and timer cap 
  aren't connected to ground
