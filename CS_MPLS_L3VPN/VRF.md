VRF config
ip vrf CUSTOMER1
 rd 100:1
 route-target export 100:1
 route-target import 100:1

Configure interfaces with VRF binding
interface GigabitEthernet0/0
 ip vrf forwarding CUSTOMER1
 ip address 192.168.1.1 255.255.255.0
