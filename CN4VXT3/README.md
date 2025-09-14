# Hardware 
- PowerEdge R650 in Rack 22
  
## CPU
- 2 x Xeon Silver 4310 CPU @ 2.10 GHz 

## DRAM
- Slots available: 32
- Slots used: 8
- Installed: 256GB
- Type: Multi-bit ECC

## Storage
PERC H745 Front (Embedded)
2 * 1.8GB SSD in **RAID0**

## Network
- Embedded: Broadcom NetXtreme Gigabit Ethernet
- Slot 1: Intel(R) Ethernet 1G 4P I350-t OCP
- Slot 2: QLogic 25GE 2P QL41262HxCU-DE Adapter
- 

| NIC      | MAC               | to Switch       | Switch IPv4    | Port          | VLAN ID |
| -------- | ----------------- |-----------------|----------------|---------------|---------| 
| gb01     | B4:45:06:E8:56:95 |                 | 172.27.10.131  | Gi1/31        |    6    |
| gb02     | B4:45:06:E8:56:96 |                 |                |               |         |
| 1gb01    | B4:83:51:04:18:FC |                 |                |               |         |
| 1gb02    | B4:83:51:04:18:FD |                 |                |               |         |
| 1gb03    | B4:83:51:04:18:FE |                 |                |               |         |
| 1gb04    | B4:83:51:04:18:FF |                 |                |               |         |
| 25gb01   | F4:C7:AA:4C:9D:40 |                 |                |               |         |
| 25gb02   | F4:C7:AA:4C:9D:41 |                 |                |               |         |

## Actions
- Add a BOSS card
- Use 25GB's cards
- Get 2nd GB card working
