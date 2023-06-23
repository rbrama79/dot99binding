Modbus devices
================

The following simulated devices are available via Modbus, and via XMPP (1451.99 concentrator interface), 
for the interop demo. The first 4 columns contain Modbus connection information. The three last columns, 
represents XMPP and 1451.99 connection information, using the concentrator avility to bridge procotols
(in this case XMPP <-> Modbus). In XMPP and 1451.99 you can also address parent nodes directly. In Modbus,
this representation is symbolic, as you only address registers directly.

| Host             | Port | Device | Register | Description                    | JID                         | Node ID                     | Source ID          |
|:-----------------|-----:|-------:|---------:|:-------------------------------|:----------------------------|:----------------------------|--------------------|
| `lab.tagroot.io` |  502 |     10 |          | Outdoor temperature sensor 1.  | `lab.tagroot.io@tagroot.io` | `Outdoor__1`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     10 |        0 | Outdoor temperature 1.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 1`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     11 |          | Outdoor temperature sensor 2.  | `lab.tagroot.io@tagroot.io` | `Outdoor__2`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     11 |        0 | Outdoor temperature 2.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 2`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     12 |          | Outdoor temperature sensor 3.  | `lab.tagroot.io@tagroot.io` | `Outdoor__3`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     12 |        0 | Outdoor temperature 3.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 3`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     13 |          | Outdoor temperature sensor 4.  | `lab.tagroot.io@tagroot.io` | `Outdoor__4`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     13 |        0 | Outdoor temperature 4.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 4`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     14 |          | Outdoor temperature sensor 5.  | `lab.tagroot.io@tagroot.io` | `Outdoor__5`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     14 |        0 | Outdoor temperature 5.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 5`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     15 |          | Outdoor temperature sensor 6.  | `lab.tagroot.io@tagroot.io` | `Outdoor__6`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     15 |        0 | Outdoor temperature 6.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 6`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     16 |          | Outdoor temperature sensor 7.  | `lab.tagroot.io@tagroot.io` | `Outdoor__7`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     16 |        0 | Outdoor temperature 7.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 7`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     17 |          | Outdoor temperature sensor 8.  | `lab.tagroot.io@tagroot.io` | `Outdoor__8`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     17 |        0 | Outdoor temperature 8.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 8`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     18 |          | Outdoor temperature sensor 9.  | `lab.tagroot.io@tagroot.io` | `Outdoor__9`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     18 |        0 | Outdoor temperature 9.         | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 9`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     19 |          | Outdoor temperature sensor 10. | `lab.tagroot.io@tagroot.io` | `Outdoor_10`                | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     19 |        0 | Outdoor temperature 10.        | `lab.tagroot.io@tagroot.io` | `Outdoor Temperature 10`    | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     20 |          | Indoor temperature sensor 1.   | `lab.tagroot.io@tagroot.io` | `Indoor__1`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     20 |        0 | Indoor temperature 1.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 1`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     21 |          | Indoor temperature sensor 2.   | `lab.tagroot.io@tagroot.io` | `Indoor__2`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     21 |        0 | Indoor temperature 2.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 2`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     22 |          | Indoor temperature sensor 3.   | `lab.tagroot.io@tagroot.io` | `Indoor__3`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     22 |        0 | Indoor temperature 3.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 3`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     23 |          | Indoor temperature sensor 4.   | `lab.tagroot.io@tagroot.io` | `Indoor__4`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     23 |        0 | Indoor temperature 4.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 4`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     24 |          | Indoor temperature sensor 5.   | `lab.tagroot.io@tagroot.io` | `Indoor__5`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     24 |        0 | Indoor temperature 5.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 5`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     25 |          | Indoor temperature sensor 6.   | `lab.tagroot.io@tagroot.io` | `Indoor__6`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     25 |        0 | Indoor temperature 6.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 6`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     26 |          | Indoor temperature sensor 7.   | `lab.tagroot.io@tagroot.io` | `Indoor__7`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     26 |        0 | Indoor temperature 7.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 7`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     27 |          | Indoor temperature sensor 8.   | `lab.tagroot.io@tagroot.io` | `Indoor__8`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     27 |        0 | Indoor temperature 8.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 8`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     28 |          | Indoor temperature sensor 9.   | `lab.tagroot.io@tagroot.io` | `Indoor__9`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     28 |        0 | Indoor temperature 9.          | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 9`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     29 |          | Indoor temperature sensor 10.  | `lab.tagroot.io@tagroot.io` | `Indoor_10`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     29 |        0 | Indoor temperature 10.         | `lab.tagroot.io@tagroot.io` | `Indoor Temperature 10`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     30 |          | Heater 1.                      | `lab.tagroot.io@tagroot.io` | `Heater__1`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     30 |        0 | Heater enabled 1.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 1`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     30 |        2 | Heater temperature 1.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 1`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     31 |          | Heater 2.                      | `lab.tagroot.io@tagroot.io` | `Heater__2`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     31 |        0 | Heater enabled 2.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 2`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     31 |        2 | Heater temperature 2.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 2`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     32 |          | Heater 3.                      | `lab.tagroot.io@tagroot.io` | `Heater__3`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     32 |        0 | Heater enabled 3.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 3`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     32 |        2 | Heater temperature 3.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 3`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     33 |          | Heater 4.                      | `lab.tagroot.io@tagroot.io` | `Heater__4`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     33 |        0 | Heater enabled 4.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 4`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     33 |        2 | Heater temperature 4.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 4`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     34 |          | Heater 5.                      | `lab.tagroot.io@tagroot.io` | `Heater__5`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     34 |        0 | Heater enabled 5.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 5`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     34 |        2 | Heater temperature 5.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 5`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     35 |          | Heater 6.                      | `lab.tagroot.io@tagroot.io` | `Heater__6`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     35 |        0 | Heater enabled 6.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 6`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     35 |        2 | Heater temperature 6.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 6`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     36 |          | Heater 7.                      | `lab.tagroot.io@tagroot.io` | `Heater__7`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     36 |        0 | Heater enabled 7.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 7`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     36 |        2 | Heater temperature 7.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 7`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     37 |          | Heater 8.                      | `lab.tagroot.io@tagroot.io` | `Heater__8`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     37 |        0 | Heater enabled 8.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 8`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     38 |          | Heater 9.                      | `lab.tagroot.io@tagroot.io` | `Heater__9`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     37 |        2 | Heater temperature 8.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 8`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     38 |        0 | Heater enabled 9.              | `lab.tagroot.io@tagroot.io` | `Heater Enabled 9`          | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     38 |        2 | Heater temperature 9.          | `lab.tagroot.io@tagroot.io` | `Heater Temperature 9`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     39 |          | Heater 10.                     | `lab.tagroot.io@tagroot.io` | `Heater_10`                 | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     39 |        0 | Heater enabled 10.             | `lab.tagroot.io@tagroot.io` | `Heater Enabled 10`         | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     39 |        2 | Heater temperature 10.         | `lab.tagroot.io@tagroot.io` | `Heater Temperature 10`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     40 |          | Thermostat 1.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__1`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     40 |        0 | Thermostat enabled 1.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 1`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     40 |        2 | Thermostat temperature 1.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 1`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     41 |          | Thermostat 2.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__2`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     41 |        0 | Thermostat enabled 2.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 2`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     41 |        2 | Thermostat temperature 2.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 2`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     42 |          | Thermostat 3.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__3`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     42 |        0 | Thermostat enabled 3.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 3`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     42 |        2 | Thermostat temperature 3.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 3`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     43 |          | Thermostat 4.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__4`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     43 |        0 | Thermostat enabled 4.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 4`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     43 |        2 | Thermostat temperature 4.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 4`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     44 |          | Thermostat 5.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__5`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     44 |        0 | Thermostat enabled 5.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 5`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     44 |        2 | Thermostat temperature 5.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 5`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     45 |          | Thermostat 6.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__6`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     45 |        0 | Thermostat enabled 6.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 6`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     45 |        2 | Thermostat temperature 6.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 6`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     46 |          | Thermostat 7.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__7`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     46 |        0 | Thermostat enabled 7.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 7`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     46 |        2 | Thermostat temperature 7.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 7`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     47 |          | Thermostat 8.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__8`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     47 |        0 | Thermostat enabled 8.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 8`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     47 |        2 | Thermostat temperature 8.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 8`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     48 |          | Thermostat 9.                  | `lab.tagroot.io@tagroot.io` | `Thermostat__9`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     48 |        0 | Thermostat enabled 9.          | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 9`      | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     48 |        2 | Thermostat temperature 9.      | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 9`  | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     49 |          | Thermostat 10.                 | `lab.tagroot.io@tagroot.io` | `Thermostat_10`             | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     49 |        0 | Thermostat enabled 10.         | `lab.tagroot.io@tagroot.io` | `Thermostat Enabled 10`     | `MeteringTopology` |
| `lab.tagroot.io` |  502 |     49 |        2 | Thermostat temperature 10.     | `lab.tagroot.io@tagroot.io` | `Thermostat Temperature 10` | `MeteringTopology` |

An XML file that can be used for importing devices is also available: [SimModbus.xml](SimModbus.xml).

QR Codes
----------

The following QR codes are available for ease of access to the above devices.

### Outdoor temperature sensors

![Outdoor temperature sensor 1](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__1%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 2](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__2%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 3](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__3%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 4](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__4%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 5](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__5%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 6](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__6%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 7](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__7%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 8](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__8%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 9](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor__9%3BSID%3DMeteringTopology)
![Outdoor temperature sensor 10](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DOutdoor_10%3BSID%3DMeteringTopology)

### Indoor temperature sensors

![Indoor temperature sensor 1](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__1%3BSID%3DMeteringTopology)
![Indoor temperature sensor 2](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__2%3BSID%3DMeteringTopology)
![Indoor temperature sensor 3](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__3%3BSID%3DMeteringTopology)
![Indoor temperature sensor 4](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__4%3BSID%3DMeteringTopology)
![Indoor temperature sensor 5](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__5%3BSID%3DMeteringTopology)
![Indoor temperature sensor 6](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__6%3BSID%3DMeteringTopology)
![Indoor temperature sensor 7](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__7%3BSID%3DMeteringTopology)
![Indoor temperature sensor 8](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__8%3BSID%3DMeteringTopology)
![Indoor temperature sensor 9](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor__9%3BSID%3DMeteringTopology)
![Indoor temperature sensor 10](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DIndoor_10%3BSID%3DMeteringTopology)

### Heaters

![Heater 1](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__1%3BSID%3DMeteringTopology)
![Heater 2](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__2%3BSID%3DMeteringTopology)
![Heater 3](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__3%3BSID%3DMeteringTopology)
![Heater 4](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__4%3BSID%3DMeteringTopology)
![Heater 5](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__5%3BSID%3DMeteringTopology)
![Heater 6](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__6%3BSID%3DMeteringTopology)
![Heater 7](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__7%3BSID%3DMeteringTopology)
![Heater 8](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__8%3BSID%3DMeteringTopology)
![Heater 9](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater__9%3BSID%3DMeteringTopology)
![Heater 10](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DHeater_10%3BSID%3DMeteringTopology)

### Thermostats

![Thermostat 1](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__1%3BSID%3DMeteringTopology)
![Thermostat 2](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__2%3BSID%3DMeteringTopology)
![Thermostat 3](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__3%3BSID%3DMeteringTopology)
![Thermostat 4](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__4%3BSID%3DMeteringTopology)
![Thermostat 5](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__5%3BSID%3DMeteringTopology)
![Thermostat 6](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__6%3BSID%3DMeteringTopology)
![Thermostat 7](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__7%3BSID%3DMeteringTopology)
![Thermostat 8](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__8%3BSID%3DMeteringTopology)
![Thermostat 9](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat__9%3BSID%3DMeteringTopology)
![Thermostat 10](https://lab.tagroot.io/QR/iotdisco%3AJID%3Dlab.tagroot.io%40tagroot.io%3BNID%3DThermostat_10%3BSID%3DMeteringTopology)

