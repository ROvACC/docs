# DELIVERY CONTROLLER

**  **


Approved by George Enciu, vACC Director

**  **

Created by Teodor G Petrică, OPS

**  **


## 1. Position overview

The Delivery position is the first ATC position that a pilot usually interacts with when preparing to fly. Some airports do not have a dedicated position for Delivery, its work being delegated to the Ground or Tower controller. 

In the airspace of Romania, the only such position is at Henri Coanda International Airport, Bucharest - Otopeni. Although this training is specifically written for the Delivery control position, all this theory can also be used for the Ground or Tower control position, where there is no Delivery or Ground.

The main objective of the Delivery position is to issue Departure Clearances. These are used to give instructions to the pilots immediately after take-off until they reach the en-route system.

The Delivery controller (DEL) is the one who verifies the Flight Plan (FPL) - a document that the pilot files with VATSIM so ATC knows where the pilot intends to navigate their aircraft.

| Login Call Sign | Call sign | Frequency | ID |
| :-------------: | :-------: | :-------: | :--: |
| LROP_DEL | Otopeni Clearance Delivery | 121.950 | DOP |

## 2. IFR Clearance

Clearance is the authorization by which the pilot is informed about the point to which he is authorised to fly, the runway for take-off, the route they will follow until the route system, the level or altitude at which they will initially or finally follow and a squawk code.

### 2.1. Clearance limit

Clearance limit indicates the waypoint or airport to which the pilot is authorised to fly. It is important to mention that this limit is imposed by the type of flight plan that is submitted, specifically the Flight Rules field. Flight Rules is the field that indicates how the pilot will navigate their aircraft: either using the instruments (IFR - Instrument Flight Rules), or using landmarks, rivers, cities in sight, i.e. visually, with the terrain in sight throughout the flight (VFR - Visual Flight Rules), or a combination of the two.

A Flight Plan can be submitted as IFR, but during the flight the pilot can decide to change the type of flight to VFR, in this case speaking of a Y Flight Plan. A YFR flight behaves like an IFR flight up to the point that delimits the IFR flight from the VFR flight. The second way in which a FPL can be filled is VFR, taking off from an airfield and after a period of time the Flight Rules change to IFR. This type of FPL is called a Z Flight Plan. So, a ZFR flight is a flight that takes off as VFR and ends its flight as IFR.

_Why is it important?_

Flight Rules determine what the Clearance limit is. In the case of IFR the aircraft is authorised to the final destination, while in the case of YFR the aircraft is authorised to the last point where the aircraft flies IFR.

In phraseology, this limit clearance is authorised using the following phrases:

The aircraft is flying IFR:

`CLEARED TO CLUJ`

The aircraft is flying IFR to BUKEL then VFR, so it’s YFR:

`CLEARED TO BUKEL`

### 2.2. Departure Procedure (SID)

Departure Procedure is a standard procedure that connects the runway to the en-route system, where the planes fly or climb towards the cruise phase. These routes are called SID (Standard Instrument Departure). These routes are the most common ways by which an aircraft can receive permission to fly in the terminal area or immediately after taking off.

A SID has as its last point the first point in the flight plan.

SIDs are of two types: RNAV (area navigation) and standard. The difference between the two types is the way in which it is navigated: if in the first case, RNAV, we are talking about GPS navigation, with clearly established points that the aircraft follow in flight, in standard navigation, stations located on the ground, called navigation aids, are used through which the aircraft (and its systems) must identify at what distance it is from a certain aid and in which direction to fly in order to intercept certain predefined directions in the standard SID procedures.

As a conclusion, the major difference between the RNAV SID compared to the standard SID is the accuracy of the positioning of the aircraft in flight. That is why RNAV SID procedures are preferred in Romanian airspace where they exist. If RNAV SID are not available at an airport (such as LRCK), then standard procedures are used. 

However, there is an exception: in TMA Bucharest (LROP, LRBS) the standard procedures are suspended, so that aircraft that are not approved to fly RNAV cannot be authorised to fly standard SID. In such cases, we arrive at the second way in which a flight can be authorised to fly to the en-route system, namely using "vectors for departure".

In phraseology, this SID is attached to the take-off runway, if that SID is not uniquely used from a single runway.

The aircraft will take off from Otopeni from runway 08L via SOKRU1K SID:

`SOKRU1K DEPARTURE RUNWAY 08L`

The aircraft will take off from Cluj from runway 25 via IRLOX1M:

`IRLOX1M DEPARTURE`

Note: because LROP SID SOKRU1K is a SID from both 08L and 08R, naming the runway is mandatory; but in Cluj, IRLOX1M is a procedure used only from runway 25, which means that the explicit read is not mandatory, but it is recommended.

### 2.3. Vectors

As mentioned before, an aircraft that cannot fly RNAV in areas where there are no standard procedures or they are suspended will receive "vectors for departure" clearance. However, there could be other reasons why an aircraft could be authorised in this way, for example, aircraft that do not intend to join the en-route system, that fly local or that make training flights, i.e. those that will fly local and they will land or practice approach procedures to the runway in service.

If the DEL controller does not find a suitable SID for the flight (according to the Flight Plan), they must coordinate instructions with the APP or ACC unit above.

<p style="color:red;">LROP_DEL: Approach, Otopeni Delivery

<p style="color:green;">LROP_APP: Go ahead

<p style="color:red;">LROP_DEL: ROT123, request vectors for departure for IFR to Baneasa.

<p style="color:green;">LROP_APP: Released, on runway heading, climb 4000 ft

Notes: since the aircraft takes off from Otopeni and flies to Baneasa, an airport located in the same TMA and at a very short distance, a SID cannot be assigned. In this case, the DEL controller coordinates with LROP_APP (Bucharest Approach) the take-off instructions which, later, the DEL controller will include in the clearance of the aircraft.

If the APP or ACC unit is not online, this coordination will not take place, and the pilot will receive instructions from the DEL Controller as follows:

`AFTER DEPARTURE, FLY AT OWN DISCRETION`

### 2.4. Initial Climb Clearance

Initial Climb Clearance is the altitude (measured in feet) or flight level (measured in hundreds of feet) to which the aircraft is authorised to climb. As a general rule, according to the semicircular flight rule in Romania and Moldova, aircraft flying westbound will fly at an EVEN level, and those flying eastbound will fly at an ODD level, unless other procedures are in place.

The maximum authorised level that a Controller lower in position than ACC can authorise is FL280 (westbound) and FL270 (eastbound).

As a general rule, for separation, two planes flying on the same SID and taking off one after the other will receive a different flight level clearance: the first will receive a maximum of FL280 (westbound) and FL270 (eastbound), if no other local procedures exist, and the second plane will be cleared to climb 2000 ft lower than the first. This rule is applied for each individual SID, i.e. for each traffic flow.

A practical example: flights from LROP via SOKRU and via BUKEL. The first plane flying to SOKRU climbs to FL280, the second plane flying to SOKRU climbs to FL260, the third plane flying to SOKRU climbs to FL240 and so on. After that, the first plane flying towards BUKEL (being another flow) will climb to FL280, the second towards BUKEL will climb to FL260 and so on. 

An already used flight level becomes available when the aircraft to which that level was assigned no longer appears in the Departure List, i.e. it has taken off.

It should be noted that during the initial climb authorization (at clearance), the flight level or the altitude to which the pilot is cleared to climb must not exceed the flight level or the altitude that the pilot intends to maintain during the cruise phase of the flight.

In phraseology, there are two phrases used to authorize an aircraft to climb to a certain altitude or flight level.

The first, when there are no speed or altitude restrictions between two points on that SID:

`CLIMB FL280`

And the second, when there is at least one speed or altitude restriction in the SID:

`CLIMB VIA SID FL280`

### 2.5. Transponder Code

The transponder is a device installed in the plane used to identify the aircraft and correlate the target with the flight plan. What you need to know about the transponder is that aircraft are required to use it in controlled airspace and that it can be operated in 3 modes.

Functionality of the transponder: the pilot of the aircraft set a code in the transponder, a code that is transmitted to the radar, the radar identifies a position from where a signal is emitted and is transmitted to the CWP (controller work position), where ATC is tasked with identifying the aircraft that displays a certain code and link or correlate the target on the screen with the flight plan related to that aircraft. As a DEL controller, your job is not to identify the aircraft on the radar because you work in a non-radar environment, but only to instruct the pilot to set a certain transponder code.

There are 4 operating modes of the transponder:

1. STBY (stand-by): transponder is off; no signal is send to the radar
2. ModeA: only the current position is send to the radar
3. ModeC: the current position and altitude is send to the radar
4. ModeS: is the most complicated mode, because in addition to ModeC's transmission capability, ModeS can also transmit other data about the aircraft, such as indicated air speed, mach number or fuel on board.

    Note: In addition to the previously mentioned, a ModeS transponder has the ability to automatically correlate the target with the FPL, which means that it is not necessary to use an unique code compared to other aircraft. Thus, capable aircraft will be assigned squawk code 1000.


In Romanian airspace, aircraft flying in controlled airspace are required to use a ModeC transponder and use it in ON mode the entire time the aircraft is moving, whether on the apron, taxiway, runway or in the air.

In phraseology, the allocation of the squawk code is done using the following phrase:

`SQUAWK 2710` (squawk two seven one zero)

`SQUAWK 1000` (squawk one thousand)

Note: squawk codes are codes of 4-digits in base-8. This means that each digit is 0...7 inclusive.

Note: the code is automatically given by EuroScope for IFR flights after pressing the mouse left button in the ASSR column, and for VFR flights, 67xx codes are set manually.

### 2.6. VFR Clearance 

#### 1. VFR traffic pattern

VFR traffic pattern is the flight that is performed around a runway, being the simplest training for new pilots, but also a maintenance exercise for old pilots, consisting of a "rectangle" around the runway, through which the pilot practices take-off, 4 90 degree turns on the same side and a landing.

For this type of flight, ATC DEL is responsible to transmit to the pilot the runway from which he will take off and execute the traffic pattern, the direction they will turn (left or right), the altitude to climb to, as well as a squawk code.

#### 2. Cross country flight

A cross-country flight means that an aircraft takes off from point A and lands at point B. Most of the time, such a flight crosses several controlled airspaces where there are reporting points. If the flight takes off from a controlled airspace, ATC DEL shall clear the aircraft to exit the controlled airspace or the control zone of the departure aerodrome via a designated waypoint.

## 3. Work with EuroScope

![alt_text](../../images/DEPLIST.png)


Departure List is the most representative list that the DEL Controller uses because it contains all the necessary information for ATC DEL to be able to read the clearance.

Let’s decode the list columns:

DS - departure stand (the parking position where the aircraft is parked)

K - the clearance checkbox (if not checked than the clearance is not read)

FR - flight rules: I stands for IFR, V stands for VFR

C/S -  call sign

RWY - runway for departure

SID - standard instrument departure identificator

CFL - cleared flight level (or the initial climb)

TYPE - aircraft type (ICAO code), followed by the wake category letter

T - transponder capability: A stands for ModeA/C, S stands for ModeS

ASSR - assigned squawk code

ADEP - departure aerodrome (ICAO code)

ADES - destination airport (ICAO code)

RFL - requested or final level in the cruise phase of the flight

C - type of communication (/v - voice only, /r - the pilot can receive voice, but will reply via text, /t - text only)

ACST - aircraft status (or ground status)

## 4. Examples

AFR15ZF cleared to Paris via SOKRU1K DEPARTURE, runway 08L, climb FL280, squawk 3201.

DLH6YA cleared to Muenchen, via SOKRU1K DEPARTURE, runway 08L, climb FL260, squawk 1717.

KLM38W cleared to Amsterdam, via SOKRU1K DEPARTURE, runway 08L, climb FL240, squawk 2122.

WZZ49YH cleared to LIRN via POLUN1K DEPARTURE, runway 08L, climb FL280, squawk 7503.

T7BGD cleared to Frankfurt, via SOKRU1K DEPARTURE, runway 08L, climb FL220, squawk 2123.

IMX802F cleared to Malmo, via BUKEL1K DEPARTURE, runway 08L, climb FL 240, squawk 3257.

## 5. DCL 

(TO BE ADDED)
