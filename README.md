# UniSeb8266
Universal Sensorboard with ESP8266.

## Usage
### Tasmota
UniSeb8266 is designed to operate with Tasmota. Use the following template string:
```
{"NAME":"UniSeb8266","GPIO":[640,0,608,0,352,1312,0,0,0,1760,1,1728,1,0],"FLAG":0,"BASE":18}
```
### Power sources
There are different options to power the board:
| power source           | SJ1 jumper position |
| ---------------------- | ------------------- |
| HLK-PM01 230V-Module   | 'module'            |
| RT9400 PoE-Module      | 'module'            |
| 5V connector           | 'connector'         |
| D1-Mini USB connector  | no jumper required  |

### 3-pin connector J1
Use SJ2 to change usage of pin2:
| pin 2 utilization | SJ2 jumper position |
| ----------------- | ------------------- |
| 3.3V              | '3V3'               |
| gpio D5           | 'D5'                |

Pin3 is fixed to D0.

## Examples
PM sensor mounted on diy box
<br>
<img src="https://user-images.githubusercontent.com/56123159/227915670-f2075cf2-77e5-45ec-9488-90ddec3b1913.jpg" width="70%">
<img src="https://user-images.githubusercontent.com/56123159/227915654-e8049cbe-7eb7-47cf-8b9e-fe5d6e51b5f9.jpg" width="70%">
