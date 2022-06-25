
### Acceleration
| Name | Type | Optional |
| ---- | ---- | -------- |
| linearVelocity | [Velocity](typedefs.md#Velocity) | YES |
| angularVelocity | [Velocity](typedefs.md#Velocity) | NO |
| linearAcceleration | [Velocity](typedefs.md#Velocity) | YES |
| angularAcceleration | [Velocity](typedefs.md#Velocity) | NO |

---

### AdBlue
| Name | Type | Optional |
| ---- | ---- | -------- |
| capacity | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| warning | [EngineWarning](typedefs.md#EngineWarning) | NO |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### AirPressure
| Name | Type | Optional |
| ---- | ---- | -------- |
| warning | [AirPressureWarning](typedefs.md#AirPressureWarning) | NO |
| emergency | [AirPressureEmergency](typedefs.md#AirPressureEmergency) | NO |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### AirPressureEmergency
| Name | Type | Optional |
| ---- | ---- | -------- |
| factor | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| enabled | [133](typedefs.md#133) | NO |

---

### AirPressureWarning
| Name | Type | Optional |
| ---- | ---- | -------- |
| factor | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| enabled | [133](typedefs.md#133) | NO |

---

### AuxLight
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Blinker
| Name | Type | Optional |
| ---- | ---- | -------- |
| left | [BlinkerStatus](typedefs.md#BlinkerStatus) | NO |
| right | [BlinkerStatus](typedefs.md#BlinkerStatus) | NO |

---

### BlinkerStatus
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |
| active | [133](typedefs.md#133) | NO |

---

### Brakes
| Name | Type | Optional |
| ---- | ---- | -------- |
| retarder | [Retarder](typedefs.md#Retarder) | NO |
| airPressure | [AirPressure](typedefs.md#AirPressure) | NO |
| temperature | [Temperature](typedefs.md#Temperature) | NO |
| parking | [Parking](typedefs.md#Parking) | NO |
| motor | [Motor](typedefs.md#Motor) | NO |

---

### Cabin
| Name | Type | Optional |
| ---- | ---- | -------- |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| position | [Position](typedefs.md#Position) | NO |
| acceleration | [Acceleration](typedefs.md#Acceleration) | NO |
| offset | [Offset](typedefs.md#Offset) | NO |

---

### Chassis
| Name | Type | Optional |
| ---- | ---- | -------- |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Company
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Controls
| Name | Type | Optional |
| ---- | ---- | -------- |
| input | [ControlsInput](typedefs.md#ControlsInput) | NO |
| game | [ControlsGame](typedefs.md#ControlsGame) | NO |

---

### ControlsGame
| Name | Type | Optional |
| ---- | ---- | -------- |
| steering | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| throttle | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| brake | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| clutch | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### ControlsInput
| Name | Type | Optional |
| ---- | ---- | -------- |
| steering | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| throttle | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| brake | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| clutch | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### CruiseControl
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| enabled | [133](typedefs.md#133) | NO |
| kph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| mph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Differential
| Name | Type | Optional |
| ---- | ---- | -------- |
| ratio | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| lock | [DifferentialLock](typedefs.md#DifferentialLock) | YES |

---

### DifferentialLock
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### Electric
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### Engine
| Name | Type | Optional |
| ---- | ---- | -------- |
| oilPressure | [EngineStatus](typedefs.md#EngineStatus) | NO |
| waterTemperature | [EngineStatus](typedefs.md#EngineStatus) | NO |
| batteryVoltage | [EngineStatus](typedefs.md#EngineStatus) | NO |
| rpm | [Rpm](typedefs.md#Rpm) | NO |
| oilTemperature | [OilTemperature](typedefs.md#OilTemperature) | NO |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| enabled | [133](typedefs.md#133) | NO |

---

### EngineStatus
| Name | Type | Optional |
| ---- | ---- | -------- |
| warning | [EngineWarning](typedefs.md#EngineWarning) | NO |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### EngineWarning
| Name | Type | Optional |
| ---- | ---- | -------- |
| factor | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| enabled | [133](typedefs.md#133) | NO |

---

### EventFerry
| Name | Type | Optional |
| ---- | ---- | -------- |
| source | [TravelSource](typedefs.md#TravelSource) | NO |
| destination | [TravelDestination](typedefs.md#TravelDestination) | NO |
| target | [TravelDestination](typedefs.md#TravelDestination) | NO |
| amount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | YES |

---

### EventRefuel
| Name | Type | Optional |
| ---- | ---- | -------- |
| active | [133](typedefs.md#133) | NO |

---

### EventTollgate
| Name | Type | Optional |
| ---- | ---- | -------- |
| amount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | YES |

---

### EventTrain
| Name | Type | Optional |
| ---- | ---- | -------- |
| source | [TravelSource](typedefs.md#TravelSource) | NO |
| destination | [TravelDestination](typedefs.md#TravelDestination) | NO |
| target | [TravelDestination](typedefs.md#TravelDestination) | NO |
| amount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | YES |

---

### Events
| Name | Type | Optional |
| ---- | ---- | -------- |
| job | [EventsJob](typedefs.md#EventsJob) | NO |
| refuelPaid | [EventsRefuelPaid](typedefs.md#EventsRefuelPaid) | NO |
| fine | [EventsFine](typedefs.md#EventsFine) | NO |
| ferry | [EventFerry](typedefs.md#EventFerry) | NO |
| train | [EventTrain](typedefs.md#EventTrain) | NO |
| tollgate | [EventTollgate](typedefs.md#EventTollgate) | NO |
| refuel | [EventRefuel](typedefs.md#EventRefuel) | NO |

---

### EventsCruiseControl
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |
| currentSpeed | [Speed](typedefs.md#Speed) | NO |
| speedLimit | [Speed](typedefs.md#Speed) | NO |
| cruiseControlSpeed | [Speed](typedefs.md#Speed) | NO |

---

### EventsFine
| Name | Type | Optional |
| ---- | ---- | -------- |
| offence | [FineOffence](typedefs.md#FineOffence) | NO |
| amount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | YES |

---

### EventsJob
| Name | Type | Optional |
| ---- | ---- | -------- |
| delivered | [EventsJobDelivered](typedefs.md#EventsJobDelivered) | NO |
| started | [EventsJobStarted](typedefs.md#EventsJobStarted) | NO |
| cancelled | [EventsJobCancelled](typedefs.md#EventsJobCancelled) | NO |
| finished | [EventsJobFinished](typedefs.md#EventsJobFinished) | NO |

---

### EventsJobCancelled
| Name | Type | Optional |
| ---- | ---- | -------- |
| penalty | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | NO |
| startedTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| cancelledTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |

---

### EventsJobCancelledVerbose
| Name | Type | Optional |
| ---- | ---- | -------- |
| cargo | [JobCargo](typedefs.md#JobCargo) | NO |
| expectedDeliveryTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| destination | [JobLocation](typedefs.md#JobLocation) | NO |
| cancelledTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| income | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| isSpecial | [133](typedefs.md#133) | NO |
| market | [JobMarket](typedefs.md#JobMarket) | NO |
| penalty | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| plannedDistance | [JobPlannedDistance](typedefs.md#JobPlannedDistance) | NO |
| source | [JobLocation](typedefs.md#JobLocation) | NO |
| startedTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |

---

### EventsJobDelivered
| Name | Type | Optional |
| ---- | ---- | -------- |
| timeTaken | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| startedTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| deliveredTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| earnedXP | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| cargoDamage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| distance | [EventsJobDeliveredDistance](typedefs.md#EventsJobDeliveredDistance) | NO |
| autoParked | [133](typedefs.md#133) | NO |
| revenue | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | NO |

---

### EventsJobDeliveredDistance
| Name | Type | Optional |
| ---- | ---- | -------- |
| km | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| miles | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### EventsJobDeliveredVerbose
| Name | Type | Optional |
| ---- | ---- | -------- |
| autoParked | [133](typedefs.md#133) | NO |
| isSpecial | [133](typedefs.md#133) | NO |
| cargo | [JobCargo](typedefs.md#JobCargo) | NO |
| market | [JobMarket](typedefs.md#JobMarket) | NO |
| cargoDamage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| distance | [EventsJobDeliveredDistance](typedefs.md#EventsJobDeliveredDistance) | NO |
| earnedXP | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| expectedDeliveryTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| deliveredTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| plannedDistance | [JobPlannedDistance](typedefs.md#JobPlannedDistance) | NO |
| revenue | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| startedTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| timeTaken | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| destination | [JobLocation](typedefs.md#JobLocation) | NO |
| source | [JobLocation](typedefs.md#JobLocation) | NO |

---

### EventsJobFinished
| Name | Type | Optional |
| ---- | ---- | -------- |
| active | [133](typedefs.md#133) | NO |

---

### EventsJobStarted
| Name | Type | Optional |
| ---- | ---- | -------- |
| autoLoaded | [133](typedefs.md#133) | NO |
| active | [133](typedefs.md#133) | NO |

---

### EventsJobStartedVerbose
| Name | Type | Optional |
| ---- | ---- | -------- |
| autoLoaded | [133](typedefs.md#133) | NO |
| cargo | [JobCargo](typedefs.md#JobCargo) | NO |
| expectedDeliveryTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| destination | [JobLocation](typedefs.md#JobLocation) | NO |
| income | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| isSpecial | [133](typedefs.md#133) | NO |
| market | [JobMarket](typedefs.md#JobMarket) | NO |
| plannedDistance | [JobPlannedDistance](typedefs.md#JobPlannedDistance) | NO |
| source | [JobLocation](typedefs.md#JobLocation) | NO |

---

### EventsRefuelPaid
| Name | Type | Optional |
| ---- | ---- | -------- |
| amount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| active | [133](typedefs.md#133) | YES |

---

### FineOffence
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Fuel
| Name | Type | Optional |
| ---- | ---- | -------- |
| capacity | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| warning | [EngineWarning](typedefs.md#EngineWarning) | NO |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| avgConsumption | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| range | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Game
| Name | Type | Optional |
| ---- | ---- | -------- |
| sdkActive | [133](typedefs.md#133) | NO |
| paused | [133](typedefs.md#133) | NO |
| timestamp | [GameTimestamp](typedefs.md#GameTimestamp) | NO |
| simulationTimestamp | [GameTimestamp](typedefs.md#GameTimestamp) | NO |
| renderTimestamp | [GameTimestamp](typedefs.md#GameTimestamp) | NO |
| pluginVersion | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| version | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| game | [GameNestedGame](typedefs.md#GameNestedGame) | NO |
| telemetryVersion | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| time | [GameTime](typedefs.md#GameTime) | NO |
| maxTrailerCount | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| scale | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### GameNestedGame
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| name | [150](typedefs.md#150) | NO |

---

### GameTime
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| unix | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### GameTimestamp
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Head
| Name | Type | Optional |
| ---- | ---- | -------- |
| position | [Position](typedefs.md#Position) | NO |
| offset | [Offset](typedefs.md#Offset) | NO |

---

### Hook
| Name | Type | Optional |
| ---- | ---- | -------- |
| position | [Position](typedefs.md#Position) | NO |

---

### Job
| Name | Type | Optional |
| ---- | ---- | -------- |
| expectedDeliveryTimestamp | [JobTimestamp](typedefs.md#JobTimestamp) | NO |
| plannedDistance | [JobPlannedDistance](typedefs.md#JobPlannedDistance) | NO |
| cargo | [JobCargo](typedefs.md#JobCargo) | NO |
| isSpecial | [133](typedefs.md#133) | NO |
| destination | [JobLocation](typedefs.md#JobLocation) | NO |
| source | [JobLocation](typedefs.md#JobLocation) | NO |
| market | [JobMarket](typedefs.md#JobMarket) | NO |
| income | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### JobCargo
| Name | Type | Optional |
| ---- | ---- | -------- |
| mass | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| unitMass | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| isLoaded | [133](typedefs.md#133) | NO |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### JobCity
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### JobLocation
| Name | Type | Optional |
| ---- | ---- | -------- |
| city | [JobCity](typedefs.md#JobCity) | NO |
| company | [Company](typedefs.md#Company) | NO |

---

### JobMarket
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### JobPlannedDistance
| Name | Type | Optional |
| ---- | ---- | -------- |
| km | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| miles | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### JobTimestamp
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| unix | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### LicensePlate
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [150](typedefs.md#150) | NO |
| country | [LicensePlateCountry](typedefs.md#LicensePlateCountry) | NO |

---

### LicensePlateCountry
| Name | Type | Optional |
| ---- | ---- | -------- |
| name | [150](typedefs.md#150) | NO |
| id | [150](typedefs.md#150) | NO |

---

### LiftAxle
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |
| indicator | [LiftAxleIndicator](typedefs.md#LiftAxleIndicator) | NO |

---

### LiftAxleIndicator
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### LightStatus
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### Lights
| Name | Type | Optional |
| ---- | ---- | -------- |
| auxFront | [AuxLight](typedefs.md#AuxLight) | NO |
| auxRoof | [AuxLight](typedefs.md#AuxLight) | NO |
| dashboardBacklight | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| blinker | [Blinker](typedefs.md#Blinker) | NO |
| parking | [Parking](typedefs.md#Parking) | NO |
| beamLow | [LightStatus](typedefs.md#LightStatus) | NO |
| beamHigh | [LightStatus](typedefs.md#LightStatus) | NO |
| beacon | [LightStatus](typedefs.md#LightStatus) | NO |
| brake | [LightStatus](typedefs.md#LightStatus) | NO |
| reverse | [LightStatus](typedefs.md#LightStatus) | NO |
| hazard | [LightStatus](typedefs.md#LightStatus) | YES |

---

### Make
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Model
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [150](typedefs.md#150) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Motor
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### NavSpeedLimit
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| kph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| mph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Navigation
| Name | Type | Optional |
| ---- | ---- | -------- |
| nextRestStop | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| distance | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| time | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| speedLimit | [NavSpeedLimit](typedefs.md#NavSpeedLimit) | NO |

---

### Offset
| Name | Type | Optional |
| ---- | ---- | -------- |
| position | [Position](typedefs.md#Position) | NO |
| orientation | [Orientation](typedefs.md#Orientation) | NO |

---

### OilTemperature
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Options
| Name | Type | Optional |
| ---- | ---- | -------- |
| mmfName | [150](typedefs.md#150) | YES |

---

### Orientation
| Name | Type | Optional |
| ---- | ---- | -------- |
| heading | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| pitch | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| roll | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Parking
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---

### Position
| Name | Type | Optional |
| ---- | ---- | -------- |
| X | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| Y | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| Z | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Retarder
| Name | Type | Optional |
| ---- | ---- | -------- |
| steps | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| level | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Rpm
| Name | Type | Optional |
| ---- | ---- | -------- |
| max | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Speed
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| kph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| mph | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Telemetry
| Name | Type | Optional |
| ---- | ---- | -------- |
| opts | [Options](typedefs.md#Options) | NO |
| data | [TelemetryData](typedefs.md#TelemetryData) | NO |
| game | [130](typedefs.md#130) | NO |
| job | [130](typedefs.md#130) | NO |
| navigation | [130](typedefs.md#130) | NO |
| trailers | [130](typedefs.md#130) | NO |
| trailer | [130](typedefs.md#130) | NO |
| truck | [130](typedefs.md#130) | NO |

---

### TelemetryData
| Name | Type | Optional |
| ---- | ---- | -------- |
| controls | [Controls](typedefs.md#Controls) | NO |
| events | [Events](typedefs.md#Events) | YES |
| game | [Game](typedefs.md#Game) | NO |
| job | [Job](typedefs.md#Job) | NO |
| navigation | [Navigation](typedefs.md#Navigation) | NO |
| substances | [Substances](typedefs.md#Substances) | YES |
| trailer | [Trailer](typedefs.md#Trailer) | NO |
| trailers | [183](typedefs.md#183) | NO |
| truck | [Truck](typedefs.md#Truck) | NO |

---

### Temperature
| Name | Type | Optional |
| ---- | ---- | -------- |
| value | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Trailer
| Name | Type | Optional |
| ---- | ---- | -------- |
| wheels | [183](typedefs.md#183) | NO |
| attached | [133](typedefs.md#133) | NO |
| cargo | [TrailerDamageValue](typedefs.md#TrailerDamageValue) | NO |
| chassis | [TrailerDamageValue](typedefs.md#TrailerDamageValue) | NO |
| acceleration | [Acceleration](typedefs.md#Acceleration) | NO |
| hook | [Hook](typedefs.md#Hook) | NO |
| position | [Position](typedefs.md#Position) | NO |
| orientation | [Orientation](typedefs.md#Orientation) | NO |
| model | [Model](typedefs.md#Model) | NO |
| accessoryId | [150](typedefs.md#150) | NO |
| bodyType | [150](typedefs.md#150) | NO |
| make | [Make](typedefs.md#Make) | NO |
| brand | [Make](typedefs.md#Make) | NO |
| chainType | [150](typedefs.md#150) | NO |
| licensePlate | [LicensePlate](typedefs.md#LicensePlate) | NO |
| damage | [TrailerDamage](typedefs.md#TrailerDamage) | NO |
| liftAxle | [LiftAxle](typedefs.md#LiftAxle) | YES |

---

### TrailerDamage
| Name | Type | Optional |
| ---- | ---- | -------- |
| cargo | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| chassis | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| wheels | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| total | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TrailerDamageValue
| Name | Type | Optional |
| ---- | ---- | -------- |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TrailerWheel
| Name | Type | Optional |
| ---- | ---- | -------- |
| lift | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| liftable | [133](typedefs.md#133) | NO |
| liftOffset | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| onGround | [133](typedefs.md#133) | NO |
| position | [Position](typedefs.md#Position) | NO |
| powered | [133](typedefs.md#133) | NO |
| radius | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| rotation | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| simulated | [133](typedefs.md#133) | NO |
| steerable | [133](typedefs.md#133) | NO |
| steering | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| substance | [WheelSubstance](typedefs.md#WheelSubstance) | NO |
| suspDeflection | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| velocity | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TrailerWheelSubstance
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Transmission
| Name | Type | Optional |
| ---- | ---- | -------- |
| forwardGears | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| reverseGears | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| selectors | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| slot | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| slots | [183](typedefs.md#183) | NO |
| gear | [TransmissionGear](typedefs.md#TransmissionGear) | NO |
| gearRatiosForward | [183](typedefs.md#183) | NO |
| gearRatiosReverse | [183](typedefs.md#183) | NO |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| selector | [183](typedefs.md#183) | NO |
| shifterType | [150](typedefs.md#150) | NO |

---

### TransmissionGear
| Name | Type | Optional |
| ---- | ---- | -------- |
| selected | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| displayed | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TransmissionSlot
| Name | Type | Optional |
| ---- | ---- | -------- |
| handlePosition | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| selector | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| gear | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TravelDestination
| Name | Type | Optional |
| ---- | ---- | -------- |
| name | [150](typedefs.md#150) | NO |
| id | [150](typedefs.md#150) | NO |

---

### TravelSource
| Name | Type | Optional |
| ---- | ---- | -------- |
| name | [150](typedefs.md#150) | NO |
| id | [150](typedefs.md#150) | NO |

---

### Truck
| Name | Type | Optional |
| ---- | ---- | -------- |
| transmission | [Transmission](typedefs.md#Transmission) | NO |
| brakes | [Brakes](typedefs.md#Brakes) | NO |
| wheels | [183](typedefs.md#183) | NO |
| lights | [Lights](typedefs.md#Lights) | NO |
| fuel | [Fuel](typedefs.md#Fuel) | NO |
| adBlue | [AdBlue](typedefs.md#AdBlue) | NO |
| engine | [Engine](typedefs.md#Engine) | NO |
| differential | [Differential](typedefs.md#Differential) | NO |
| speed | [Speed](typedefs.md#Speed) | NO |
| cruiseControl | [CruiseControl](typedefs.md#CruiseControl) | NO |
| cabin | [Cabin](typedefs.md#Cabin) | NO |
| chassis | [Chassis](typedefs.md#Chassis) | NO |
| odometer | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| electric | [Electric](typedefs.md#Electric) | NO |
| wipers | [Wipers](typedefs.md#Wipers) | NO |
| head | [Head](typedefs.md#Head) | NO |
| hook | [Hook](typedefs.md#Hook) | NO |
| acceleration | [Acceleration](typedefs.md#Acceleration) | NO |
| position | [Position](typedefs.md#Position) | NO |
| orientation | [Orientation](typedefs.md#Orientation) | NO |
| make | [Make](typedefs.md#Make) | NO |
| brand | [Make](typedefs.md#Make) | NO |
| model | [Model](typedefs.md#Model) | NO |
| licensePlate | [LicensePlate](typedefs.md#LicensePlate) | NO |
| damage | [TruckDamage](typedefs.md#TruckDamage) | NO |
| liftAxle | [LiftAxle](typedefs.md#LiftAxle) | YES |

---

### TruckDamage
| Name | Type | Optional |
| ---- | ---- | -------- |
| cabin | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| chassis | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| engine | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| transmission | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| wheels | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| total | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### TruckWheel
| Name | Type | Optional |
| ---- | ---- | -------- |
| substance | [WheelSubstance](typedefs.md#WheelSubstance) | NO |
| radius | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| suspDeflection | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| velocity | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| steering | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| rotation | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| lift | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| liftOffset | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| position | [Position](typedefs.md#Position) | NO |
| steerable | [133](typedefs.md#133) | NO |
| simulated | [133](typedefs.md#133) | NO |
| powered | [133](typedefs.md#133) | NO |
| liftable | [133](typedefs.md#133) | NO |
| onGround | [133](typedefs.md#133) | NO |
| damage | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### Velocity
| Name | Type | Optional |
| ---- | ---- | -------- |
| X | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| Y | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| Z | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |

---

### WatchOptions
| Name | Type | Optional |
| ---- | ---- | -------- |
| interval | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | YES |

---

### WheelSubstance
| Name | Type | Optional |
| ---- | ---- | -------- |
| id | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) | NO |
| name | [150](typedefs.md#150) | NO |

---

### Wipers
| Name | Type | Optional |
| ---- | ---- | -------- |
| enabled | [133](typedefs.md#133) | NO |

---
