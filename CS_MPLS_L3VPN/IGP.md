IGP config
(OSPF)
router ospf 1
 router-id 1.1.1.1
 network 10.0.0.0 0.0.0.3 area 0

(EIGRP)
router eigrp 100
 router-id 1.1.1.1
 network 192.168.1.0

