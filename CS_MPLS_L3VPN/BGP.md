BGP VPNv4 Configuration
router bgp 65000
 address-family vpnv4
  neighbor 2.2.2.2 activate
  neighbor 2.2.2.2 send-community both
