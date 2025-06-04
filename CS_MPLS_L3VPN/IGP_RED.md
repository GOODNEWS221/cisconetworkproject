Route Redistribution (EIGRP ↔ OSPF) - when both are used
router ospf 1
 redistribute eigrp 100 subnets

router eigrp 100
 redistribute ospf 1 metric 10000 100 255 1 1500
