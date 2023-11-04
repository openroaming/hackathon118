
# Use Case #1 Tracking Between Devices
## Example Observation Record

| IDP Subscription | (Some IDP Name) |
|:----|:---|
| User consented sharing | [(yes) or (no)] |
| NAS Vendor | (Some Vendor Name) |
| Event-Time  | 2023.11.04T10:30 |
| | |
| Device | (Some Device Type) |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |
| | |
| Device | (Some Device Type) |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |

# Use Case #2 Tracking Between Access Networks
## Example Observation Record

| IDP Subscription | (Some IDP Name) |
|:----|:---|
| User consented sharing | [(yes) or (no)] |
| Device | (Some Device Type) |
| Event-Time  | 2023.11.04T10:30 |
| | |
| NAS Vendor | (Some Vendor Name) |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |
| | |
| NAS Vendor | (Some Vendor Name) |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |

# Use Case #3 Temporal Tracking
## Example Observation Record

| IDP Subscription | (Some IDP Name) |
|:----|:---|
| User consented sharing | [(yes) or (no)] |
| Device | (Some Device Type) |
| NAS Vendor | (Some Vendor Name) |
| | |
| Event-Time  | 2023.11.04T10:30 |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |
| | |
| Event-Time  | 2023.11.05T10:30 |
| **RADIUS**  | **Access-Request** |
| User-Name | (recorded user-name) |
| Calling-Station-Id | (recorded mac address) |
| **RADIUS**  | **Access-Accept** |
| User-Name | (recorded user-name) |
| Class | (recorded Class attribute(s)) |
| Chargeable-User-Identity | (recorded Chargeable-User-Identity) |
