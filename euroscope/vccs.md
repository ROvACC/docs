## What is VCCS and how to use it?

This is the VCCS user guide, a tool used for coordination between both internal and external sectors.

VCCS is the primary mode to coordinate. If this function does not work, you can use the text via private message on EuroScope and you should reach the [OPS Team via mail](mailto:teodor.petrica@rovacc.ro).

*Note:* VCCS is a system used for Verbal Coordinations. Do not use for general chat!

VCCS or Verbal Coordination is the main used tool to coordinate any situation which are not or cannot be established using the Coordination Feature in EuroScope (level change and direct to). 

#### How do we start?

The first thing is to configure your VCCS by setting your nickname with your VATSIM CID and set a PTT to G2G. This PTT must be different from the one you have already set in AFV to communicate on the frequency. It is also recommended not to use a character key. For example, you can use Alt, Right Ctrl, Ctrl, Shift or Right Shift.

Go to Settings: Right Click on LINE 1, then left click on EDIT button:

![image](../../images/VCCS_window_extended.png)

![image](../../images/VCCS_settings.png)

![image](../../images/VCCS_mini_controller.png)

In the image above you will notice how the VCCS mini controller looks. It has 3 components: NO CALL, LINE 1 and LINE 2. For constructive reasons, only the first two components are usable at this time.

##### The first one indicates the current status of the phone

- NO CALL: The phone is free and ready to be used.

- CALLING: The phone is engaged in a call, either incoming or outgoing

- RING OFF: It indicates that the call can be stopped from ringing, but the call remains on air.

- MUTE: Indicates that the caller can be MUTED. This function can be used if the ATCO has traffic on the frequency while a VCCS call occurs.

- UNMUTE: Indicates that the caller is set to MUTE mode (see above). This function is used to return the caller's voice.

##### The second section, LINE 1, indicates the number of the telephone line used

- LINE 1: The phone is free and ready to be used on line 1.

- XXXXX: The telephone code of the calling or called station is displayed, as following:
    * background is RED: XXXXX is speaking
    * background is ORANGE: you are speaking
    * background is WHITE: you are calling the station or the station already picked up the call

#### Incoming call

![image](../../images/VCCS_incoming_call.png)

#### Outgoing call

![image](../../images/VCCS_outgoing_call.png)

#### Internal Coordination Code Descriptor

![image](../../images/VCCS_intern.png)

| Unit | Code | Call sign | CID | Frequency |
| :--: | :--: | :-------: | :-: | :-------: |
| ACC  | LOM | LRBB_L_CTR | LOM | 122.030 |
| ACC  | ARG | LRBB_A_CTR | ARG |  121.180 |
| ACC  | NAP | LRBB_N_CTR | NAP |  127.075 |
| ACC  | UP  | LRBB_U_CTR | LRUP | 132.865 |
| | | | | |
| DIR  | OP  | LROP_F_APP | DIB | 127.155 |
| | | | | |
| APP  | OP  | LROP_APP | APB | 119.415 |
| APP  | CL  | LRCL_APP | APN | 126.430 |
| APP  | AR  | LRAR_APP | APA | 123.430 |
| APP  | CK  | LRCK_APP | APC | 122.905 |
| | | | | |
| TWR  | OP  | LROP_TWR | TOP | 118.805 |
| TWR  | BS  | LRBS_TWR | TBS | 125.205 |
| TWR  | CL  | LRCL_TWR | TCL | 118.705 |
| TWR  | TM  | LRTM_TWR | TTM | 119.180 |
| TWR  | SB  | LRSB_TWR | TSB | 121.305 |
| TWR  | AR  | LRAR_TWR | TAR | 118.230 |
| TWR  | TR  | LRTR_TWR | TTR | 120.105 |
| TWR  | CK  | LRCK_TWR | TCK | 124.030 |
| | | | | |
| TWR  | SM  | LRSM_TWR | TSM | 119.655 |
| TWR  | BM  | LRBM_TWR | TBM | 118.855 |
| TWR  | SV  | LRSV_TWR | TSV | 129.955 |
| TWR  | OD  | LROD_TWR | TOD | 118.455 |
| TWR  | CV  | LRCV_TWR | TCV | 129.530 |
| TWR  | BC  | LRBC_TWR | TBC | 120.980 |
| TWR  | IA  | LRIA_TWR | TIA | 119.955 |
| TWR  | TC  | LRTC_TWR | TTC | 119.755 |
| | | | | |
| GND  | OP  | LROP_GND | GOP | 121.855 |
| GND  | BS  | LRBS_GND | GBS | 129.950 |
| GND  | TR  | LRTR_GND | GTR | 121.600 |
| | | | | |
| DEL  | OP  | LROP_DEL | DOP | 120.955 |

#### External Coordination Code Descriptor

![image](../../images/VCCS_extern.png)

| Unit | Code | Call sign | CID | Frequency |
| :--: | :--: | :-------: | :-: | :-------: | 
| ADR | E | ADR_E_CTR | ADE | 130.550 |
| ADR | U | ADR_U_CTR | ADU | 130.750 |
| ADR | Full | ADR_CTR | ADR | 130.000 |
| ACC | LYBA | LYBA_CTR | BEO | 123.775 |
| APP | LYBE | LYBE_APP | ABE | 133.100 |
| APP | LYBT | LYBT_APP | ABT | 126.050 |
| | | | | |
| ACC | SOF | LBSR_CTR | SOF | 131.225 |
| ACC | VAR | LBSR_V_CTR | VAR | 134.700 |
| ACC | VB | LBSR_B_CTR | BSS | 132.950 |
| ACC | SB | LBSR_E_CTR | SES | 129.100 |
| | | | | |
| ACC | LUUU | LUUU_CTR | UU | 130.975 |
| APP | LUKK | LUKK_APP | APK | 133.300 |
| TWR | LUKK | LUKK_TWR | TKK | 118.100 |
| GND | LUKK | LUKK_GND | GKK | 121.800 |
| | | | | |
| ACC | BUU | LHCC_U_CTR | BUU | 133.535 |
| ACC | BUN | LHCC_N_CTR | BUN | 135.555 |
| ACC | BU1 | LHCC_1_CTR | BU1 | 132.790 |
| ACC | BU | LHCC_CTR | BU | 120.975 |
| ACC | BUK | LHCC_K_CTR | BUK | 127.860 |
| ACC | BU2 | LHCC_2_CTR | BU2 | 135.205 |
| | | | | |
| ACC | LVV | UKLV_CTR | LVV | 134.050 |
| ACC | KYV | UKBV_CTR | KYV | 135.150 |
| ACC | ODS | UKOV_CTR | ODS | 132.200 |
| UKR | Full | UKR_CTR | UKR | 123.475 |
| | | | | |
| EUC | SW | EUC-SW_CTR | ESW | 135.500 |
| EUC | EN | EUC-EN_CTR | EEN | 135.300 |

## Principles

- short message
- precise
- unambiguous

All time
* get it in advance
* state reason

## Subject to Verbal Coordination

- **lateral approval request**: if the traffic is requesting vectors to avoid weather and will entry the downstream sector more than 10 NM off from the initial or Flight Plan course, then you have to request a lateral approval request

Example:
Calling...
<p style="color:red;">A: Go Ahead!</p>
<p style="color:green;">B: Approval Request for ROT123 East of NARKA.</p>
<p style="color:red;">A: Go Ahead!</p>
<p style="color:green;">B: ROT123 15 miles South from NARKA due weather.</p>
<p style="color:red;">A: Approved / Negative (reason, alternate conditions)

- **vertical approval request**: if you are the upstream sector and you cannot meet the LoA, you should initiate a Vertical Approval Request

Example:
Calling...
<p style="color:red;">A: Go Ahead!
<p style="color:green;">B: Approval Request HYS456 descending FL350 (instead of 320)
<p style="color:red;">A: HYS456 is accepted descending FL350
<p style="color:green;">B: Approved 350 for HYS456.

- **request for release**: usually used for early clearance into APP area or in the lower sector

Example:
Calling...
<p style="color:red;">A: Go Ahead!
<p style="color:green;">B: Request release for climb (Craiova departure) WMT123, East of ANASA
<p style="color:red;">A: WMT123 released for climb / fully released / is not released.

- **temporary deviation from LoA**

Example:
Calling...
<p style="color:red;">A: Go Ahead!
<p style="color:green;">B: Can you offer higher level for RYR789?
<p style="color:red;">A: RYR789 is accepted climbing FL390 out of FL350.

Example:
Calling...
<p style="color:red;">A: Go Ahead!
<p style="color:green;">B: Until further notice, send all aircraft to destination Bucharest via DENAK at FL150 or above.

- **diversion**: aircraft is changing destination

Example:
Calling...
<p style="color:red;">A: Go Ahead!
<p style="color:green;">B: Check position North of Constanta ROT345
<p style="color:red;">A: Radar contact
<p style="color:green;">B: ROT345 is diverting to Otopeni via NETUL.
<p style="color:red;">A: Checked / Roger 

- any other situation not stated above

## Phraseology for coordinations using VCCS

To answer the call, you must use the left click on to LINE 1 when the phone rings. After that you have to press the set PTT and say *Go Ahead*.

The caller will also say their radio call sign, then communicate the message.

### TWR-APP Coordination

#### TWR to APP

*Note:* All IFR flights **shall be coordinated and released** by APP Unit before they enter the runway for take-off.

Exemple: The departure traffic is ROT123 and the SID is BUKEL1K

* TWR > APP: "ROT123 BUKEL"

The possible answers that can come from the APP:

* "**released**": traffic is allowed to take off without restrictions
* "**released on runway heading**": traffic is allowed to take off, with the restriction of maintaining runway heading after take off (TWR Clearance: "ROT123, when airborne maintain runway heading ...")
* "**released, FL60**": traffic is allowed to take off, with the restriction of a lower Flight Level or altitude (TWR Clearance: "ROT123, recleared, climb initial FL60" - after readback, the rest of the take-off clearance)
* "**stand-by**":  traffic is not allowed to take off; in this case, wait for a call from APP, and if APP does not call after 3 minutes, initiate a new request.

The called must end the call after the coordination is finished. To do this, the caller must say **OUT** (to make the other controller aware that you will hang up the call), then press END button to end the call.

*Note:* Verbal coordination expires 3 minutes after "released". Any delay that occurs on the ground, in the immediate vicinity of the runways and that will delay the take-off must be reported to the APP, if the actual "release message" was given.

#### APP to TWR

*Note:* APP **shall inform** TWR about all IFR and VFR (where applicable) traffic which intend to land at the specified aerodrome. The APP > TWR coordination should include the call sign of the traffic, the type of the approach (ILS, VOR, NDB, RNAV, Visual) and the runway.

Example:

* APP > TWR: "HYS789 VOR DME runway 09"

Because this is an information, TWR is not constrained to respond with a voice message. The caller should terminate the call by saying "OUT" and pressing the END button.

#### GND to TWR

Ground must **inform** TWR if an aircraft is taxiing to a holding point any other holding point that is not at the end of the runway:

* GND > TWR: "ROT456 departure from Golf 08R"