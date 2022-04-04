Spaning-tree & rapid-pvst ///
Switch(config)#spanning-tree mode rapid-pvst 
stp > spanning-tree bpduguard enable
spanning-tree portfast 

Switch(config-if-range)#sw port-security mac-address sticky 

switchport trunk native vlan 44 
encapsulation dot1q (vlannumarası)

    switchport trunk yaptıktan sonra bunu gir
dtp kapatma > switchport nonegoitate

service password-encryption (girilen şifreleri kriptolama)

Switch(config)#spanning-tree vlan 1 priority 4096
