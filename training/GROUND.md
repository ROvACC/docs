# GROUND CONTROLLER

**  **


Approved by George Enciu, vACC Director

**  **

Created by Teodor G Petrică, OPS

**  **


## 1. Position overview

In this guide, we aim to define the role and service that the Ground controller (abbreviated as GND) has in aviation safety. If there is no Delivery control position at the respective airport, Ground is responsible for authorizing the flights as a DEL controller does.

When we talk about the GND controller, this is the one that authorizes the aircraft to move on the taxiways and platforms (or aprons). 

| Login Call Sign | Call sign | Frequency | ID |
| :-------------: | :-------: | :-------: | :--: |
| LROP_GND | Otopeni Ground | 121.855 | GOP |

## 2. Push-back & Start up:

The first such movement is exiting the parking position, which is often done from behind. This means that the GND must authorize the aircraft to leave the parking position, the aircraft being pushed by a special machine, called Tug or Schof. The procedure is called **Push-back**. If this push-back can be executed in more than one way, often, the GND controller must inform the pilot about the direction in which the cockpit (the place where the pilots sit) is to be pointed after the push-back procedure is completed. For example: `facing east`

In general, the authorization to exit the parking position is done at the same time as the authorization to start the engines. This also comes with the information from the GND controller to the pilot about the local pressure (QNH) found in the latest MET report.

e.g. `push and start approved, QNH 1010`

It should be mentioned that an aircraft performing the push-back procedure will block the taxiway it leaves for an average time of 4 minutes, during which time other aircraft operating in the area should wait. For this reason, if the maneuvering surface does not allow to bypass the adjacent traffic (through other taxiways), the push-back authorization must be done correctly, on time and only if there is no other traffic behind the aircraft.

If it is not possible to authorize an airplane to leave the parking position through a push-back procedure, this must be communicated to the pilot in command.

e.g. `standby, traffic behind` or `hold position due traffic`

Also, an exit from the parking position can be conditional authorized, as in the following example: `behind Airbus A320 passing left to right, push-back start up approved, QNH 1010` or `behind propeller traffic, push-back approved, facing East, QNH 1010`

There may be situations in which some aircraft (such as ATR) can start their engines in the parking position and perform a self push-back procedure carried out with the help of the engines, called **power back**. This procedure does not apply to the parking positions that are in the immediate vicinity of the terminal, due to possible safety problems that could arise during the Power back procedure.

Some parking positions are specially created and defined as *self maneuvering*. This means that the pilot will receive from the GND controller the authorization to start engines on the parking position and will go taxiing towards the runway in the forward direction.

## 3. Taxi

After the push-back (and start-up) procedure have been completed, the aircraft is ready to taxi to the runway. The pilot will receive instructions from the GND controller regarding the final point to which they are authorized to taxi, as well as the taxiways to follow between the current position and the destination position. The current taxiway often appears in the taxi clearance, and if it is missing, it is mandatory that the aircraft in the forward direction intersects with the first cleared taxiway.

In general, the pilot is not authorized to leave the yellow centerline when taxiing on the maneuvering area of an airport. Deviations from this rule are clearly specified in the SOP/LOP for each airport or by ATC.

The final point to which an aircraft is authorized to taxi is often the **holding point**, the point at where the aircraft is before the safety strip of the runway and the point at which the GND controller transfers the communication to the Tower Controller.

e.g. `taxi to holding point runway 08L via C, N`

e.g. `taxi to holding point G runway 08R via K, E, G`

In certain situations, when the traffic flow is at a higher level, it is possible to authorize progressive taxi, or to authorize hold short points during the taxi.

e.g. `taxi to holding point A runway 08R via M, hold short E` (this means the aircraft will stop before the intersection with TWY E on TWY M)

e.g. `taxi via J, K, hold short E` (this means the aircraft will stop on TWY K before the intersection with TWY E)

![alt_text](../../images/LROP_taxi.png)

### Solving of potential conflicts during taxi

```1.``` **Hold position**

When used, hold position means that the aircraft shall stop immediately or as soon as possible. 

```2.``` **Hold short of**

e.g. `hold short of I` (this means the aircraft will stop before the intersection with taxiway I; the aircraft is not allowed to enter the intersection of the current taxiway with the TWY I)

Usually, this instruction is used with *give way to* (described below).

```3.``` **Give way to**

e.g. `give way to Airbus A320 coming from right to left` (the aircraft must stop and give priority to the Airbus A320 which is coming from right to left, then the aircraft can resume taxi).

## 4. Handover

Transfer of Communication must take place when:
1. The aircraft is approaching holding position.

2. When the aircraft is **conflict-free**

3. When you no longer have to give instructions to that aircraft.

If all these three points are met, then, you can say: ```CALLSIGN contact [ICAO_TWR] on [xxx.xxx]```.

## 5. Ground Priorities

##### 5.1. Flight Rules Distinction

- Aircraft operating under IFR conditions typically receive priority during taxi operations due to their reliance on precise navigation and air traffic control instructions. This ensures that IFR flights can adhere to their assigned departure or arrival procedures without unnecessary delays.

- VFR flights, unless categorized as emergency (EMG), do not have priority over IFR traffic on the ground. Ground control provides instructions to VFR flights, coordinating their movements to minimize potential conflicts with IFR operations.

##### 5.2. Departure (DEP) and Arrivals (ARR) Priorities

- Departing flights continue to receive priority over arriving flights during taxi operations, ensuring a continuous flow of departures and minimizing congestion on runways and taxiways.

- Arriving flights may be required to yield to departing aircraft, contributing to the efficient sequencing of movements on the ground.

##### 5.3. Aircraft Weight Turbulence Categories

- Medium and heavy aircraft are typically given priority over lighter aircraft during taxi operations. This is due to the larger turning and increased distances required for these larger aircraft to navigate on the ground.

- Ground control may sequence movements to ensure that heavy aircraft have the necessary space and time to maneuver, minimizing potential conflicts with lighter traffic.

- While the Wake Turbulence Category (WTC) classifies aircraft based on size and weight, it may not comprehensively account for the broad range of performance variations, especially when comparing aircraft sharing similar WTC classifications. Larger aircraft, like the Airbus A320, featuring jet engines, generally have superior climb capabilities compared to smaller turbo shaft-powered counterparts such as the ATR 72-600. The heightened climb performance of jet-powered aircraft enables them to efficiently navigate through the departure area, reducing their ground time and mitigating the risk of congestion on taxiways and runways.

##### 5.4. Separation Standards

- Ground control ensures that there is sufficient separation between taxiing aircraft to prevent collisions or conflicts. This separation takes into account the different speeds, sizes, and turning capabilities of the aircraft involved.

##### 5.5. Emergency and Priority Handling

- In the case of emergency or priority situations, such as medical diversions, ground control may adjust the sequence of taxiing aircraft to accommodate these special cases and ensure a swift response.

## 6. Coordination

GND controller must inform TWR unit if an aircraft is taxiing to a holding point any other holding point that is not at the end of the departure runway.

