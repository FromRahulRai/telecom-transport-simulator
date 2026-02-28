Access Layer – Towers

Tower 1

- VLAN 10 (4G): 10.1.10.0/24

- VLAN 20 (5G): 10.1.20.0/24

Tower 2

- VLAN 10 (4G): 10.2.10.0/24

- VLAN 20 (5G): 10.2.20.0/24

Tower 3

- VLAN 10 (4G): 10.3.10.0/24

- VLAN 20 (5G): 10.3.20.0/24

Distribution / Aggregation to Core Link

172.16.0.0/30

- AGG-R1 → 172.16.0.1

- CORE-R1 → 172.16.0.2

Core to Server Network

10.100.0.0/24

CORE-R1 → 10.100.0.1

- Media Server → 10.100.0.10

