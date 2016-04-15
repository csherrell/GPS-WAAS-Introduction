# GPS / WAAS Introduction

---

# WAAS Logo

---

# Schedule of Presentations

1. Introduction -  GPS / WAAS
1. Technical Instruction Book (TIB) Overview
1. WRS Type 1 Introduction
1. Terrestrial Communications System (TCS)
1. WRS Fault Isolation
1. WRS Configuration
1. Operations and Maintenance (O&M)
1. Geo Uplink Subsystem type 1

???

# Some notes about how long this will take.
* I guess my Notes
* Can use Markdown too

---

# This briefing consists of:
* Why GPS/WAAS?
* GPS Description
* GPS SIGNAL CHARACTERISTICS
* GPS Navigation Message
* GPS Capabilities

[//]: # (Markdown has no comment character, so this is a comment)
[//]: # (.center[![BryceCanyon](03983_mountrundle_3840x2160.jpg)])
[//]: # (center[![:scale 80%](03983_mountrundle_3840x2160.jpg)])
[//]: # (![](03983_mountrundle_3840x2160.jpg =384x216))

<br>
<img src="03983_mountrundle_3840x2160.jpg" alt="Mountain" style="width: 650px;" align="left"/>

---
background-image: url(03983_mountrundle_3840x2160.jpg)
background-size: 100% auto;

# WHY GPS/WAAS?
* Retirement of VORs and Cat 1 ILSs.
* More direct routing – Saving Fuel and Time.
* With WAAS, LNAV/VNAV (Lateral Navigation/Vertical Navigation) instrument landing capability is available at airports that do not have ILS

---

# ILS Characteristics and Terms
* Localizer (LOC)
* Glide Slope (GS)
* Middle Marker (MM)
* Outer Marker (OM)

---

# Categories of Landing
* CAT1  2400 ft. RVR 200 ft. Decision Height
* CAT2  1200 ft. RVR 200 ft. No Decision Height
* CAT3a 2400 ft. RVR 200 ft. Decision Height
* CAT3b 2400 ft. RVR 200 ft. Decision Height
* CAT3c 2400 ft. RVR 200 ft. Decision Height

| Category | Decision Height (DH) (feet) | Runway Visual Range (RVR) (feet)|
|----------|----------------------|--------------------------|
| I    | 200 feet | 1,800 to 2,400 feet Depending Upon Approach Lighting System |
| II   | 100 feet | 1,200 feet|
| IIIa | No DH or DH below 100 feet | Less than 700 feet|
| IIIb | No DH or DH below 50 feet  | Less than 700 feet but not less than 150 feet|
| IIIc | No DH | No RVR Limitation|

---

# Approach LAX

---

# Why GPS/WAAS? (Cont.)
* Victor airways are not direct

---

# Kotzebue, VOR

---

# Kodiak, Alaska: Runway 25 Centerline (from Alaska Air)
## Decision Height Determined by Missed Approach Missed Approach Is Climbing Left Hand Turn

---

# WHY GPS/WAAS? (Cont.)
* **Primary Means of Navigation** - Takeoff, Enroute, Approach and Landing
* **More Direct Routes** - Not Restricted by Location of Ground-Based Navigation Equipment
* **Approach with Vertical Guidance Capability** at Any Qualified U.S. Airport
* **Decommission of Older, Expensive Ground-Based Navigation Equipment** - Reduced Maintenance Costs
* **Simplify and Reduce Equipment on Board Aircraft**
* **Increase Capacity** - Reduced Separation Due to Improved Accuracy

---

# GPS Description
* Space based radio navigation system providing:
  * Precise position
  * Continuous worldwide coverage
  * Passive, unlimited number of users
  * All weather operation

---

# GPS Description (Cont.)
* GPS Segments:
  * Space segment
  * Control segment
  * User segment

---

# GPS Description (Cont.)
* Space Segment Operational constellation
  * The current GPS constellation consists of 32 satellites.
  * The GPS constellation is updated every working day.
* Orbital characteristics:
  * 6 orbital planes (55 degree declination)
  * 20,200 Km (10,900 NM) orbit
  * Orbit takes 12 hours
  * Almost circular orbits

---

# GPS Description (Cont.)
* Space Segment Operational constellation (Cont.)
---

# GPS Description (Cont.)
* Control Segment
  * Ground stations monitor the GPS satellites, checking operational health and their exact position. The master ground station transmits corrections for the satellite's ephemeris constants and clock offsets back to the satellites themselves. The satellites can then incorporate these updates in the signals they send to GPS receivers.
  * There are five monitor stations: Hawaii, Ascension Island, Diego Garcia, Kwajalein, and Colorado Springs.

---

# GPS Description (Cont.)
## User Segment
* Equipment and techniques available to users:
  * Aviation
  * Automobiles
  * Cell phones
  * Personal Navigation, etc.

---

# GPS Description (Cont.)
* User measures satellite to users ranges (R1, R2, R3, R4)
* User has data about satellite location (P1, P2, P3, P4)
* GPS Position Determination Technique
---

# GPS Description (Cont.)
* Single Satellite Ranging
  * With a single distance measurement, the user may be anywhere on the sphere determined by the position of the satellite of the radius.
---

# GPS Description (Cont.)
* Two Satellite Ranging
  * With the distance measurement from two satellites, the user's position may be anywhere on the intersections of the spheres.

---

# GPS Description (Cont.)
* Three Satellite Ranging
  * Using the distance measurement from three different satellites, the user's position may be at two points of the intersections of three spheres.

---

# GPS Description (Cont.)
* User Clock Bias Errors
  * Synchronization between satellite and receiver clock is critical. Clock bias is calculated using four satellites.
  * 1/1000 second = 186 miles of error
---

# GPS Description (Cont.)
## GPS  C/A Code
* All Satellites Transmit Simultaneously On The Same Frequency
* Spread Spectrum Signal Processing Techniques Are Used To Separate Out The Individual Signals
* The L1 Signal is Spread (BSK modulated) With A Constantly Repeating 1023 Bit Long Gold Code (Family of Orthogonal Codes) at a Rate Of 1.023 Mbps
* Every 1000th Code Repetition Always Starts Exactly on the Second
* Each Satellite Uses A Unique Code, Also Known As It’s PRN (pseudo random number)
* A Satellite’s PRN Is Synonymous With It’s Name
---

# Spread Spectrum
* Fc = chipping rate
* Fs = bit rate of data
* Process gain = Fc/ Fs
* Bandwidth of process signal is approximately that of the PRN code
* GPS received power levels -156 to -160 dBw for a 0dBIC antenna.

---

# Spread spectrum (Cont.)

|Name | Carrier Frequency   |
|-----|:-------------------:|
| L1  | 1575.42 MHz         |
| L2  | 1227.60 MHz         |
| L5  | 1176.45 MHz         |

Navigation Data at 50 bps

---

# GPS Signal Characteristics
* Two L-band frequencies: L1 = 1575.42 MHz and L2 = 1227.6 MHz. Three pseudo-random noise (PRN) ranging codes are in use.
  * The coarse/acquisition (C/A) code has a 1.023 MHz chip rate, a period of 1 millisecond (ms) and is used primarily to acquire the P-code.
  * The precision (P) code has a 10.23 MHz rate, a period of 7 days and is the principal navigation ranging code.
  * The Y-code is used in place of the P-code whenever the anti-spoofing (A-S) mode of operation is activated.

---

# GPS Signal Characteristics (Cont.)
* The C/A code is available on the L1 frequency and the P-code is available on both L1 and L2.
* The various satellites all transmit on the same frequencies, L1 and L2, but with individual code assignments. Due to the spread spectrum characteristic of the signals, the system provides a large margin of resistance to interference.
* Each satellite transmits a navigation message containing:
  * its orbital elements
  * clock behavior
  * system time and status messages.

---

# GPS Signal Characteristics (Cont.)
## Signal Generation

---

# GPS Signal Characteristics (Cont.)
* Binary Phase Shift Keying
  * Unmodulated Carrier
  * Two Bits From Data Stream
  * Two Repeats of a Code With 4 Chips Per Data Bit (GPS Has 20,460 Chips Per Bit)
  * Carrier Modulated By Code and Navigation Data

---

# GPS Signal Characteristics (Cont.)
Almanac is also provided which gives the approximate data for each active satellite. This allows the user set to find all satellites once the first has been acquired.

---

# GPS Navigation Message
* A 50 bps Message is Modulated on Top of the C/A Code
  * Ten 30 bit Words in Each 6 Second Subframe
  * 5 Sequential Repeating Subframes in Each 30 Second Frame
  * Subframes 1, 2, and 3 Always Contain the Same Information Relating to the Transmitting Satellite
  * Subframes 4 and 5 Are Multiplexed to Send a Set of Global Data Applicable to the Entire GPS Constellation (requires 25 Frames - 12.5 minutes)
* This is the GPS Navigation Message
* See the GPS Signal Performance Specification (SPS) for Details
  * http://www.navcen.uscg.gov/pubs/gps/sigspec/gpssps1.pdf

---

# GPS Navigation Message (Cont.)
* The Navigation Message is Synchronized Exactly with the Repetition of the PRN Code Such that the Beginning of Every Navigation Message Subframe Occurs Exactly on the Beginning of the PRN Code Repetition at the Top of Each GPS 6 Second Epoch
* The Navigation Message Contains Data Telling the User the Exact Time When the Beginning of the Next Subframe Will Leave the Satellite
* Extremely Precise Clocks Are Used on the Satellites to Maintain Synchronization Among All The Satellites
* To Conserve Bits, GPS Uses A Week Count, and Time of Week Count to Represent Time

---

# GPS Navigation Message (Cont.)
* In Addition to the Timing Mark Information, The Navigation Message Contains:
   * Ephemeris Parameters for this Satellite (30 sec.)
      * Keplerian Orbit Model Constants
      * Clock Correction Parameters (30 sec.)
   * Health Status (30 sec.)
   * Constants for an Ionosphere Correction Model (12.5 min.)
   * Almanac Information (12.5 min.)
      * Orbit Information and Clock Corrections for All Satellites
         * Not as precise as the ephemeris
         * Covers a period of about 6 days
      * Health Status for All Satellites

---

# GPS Navigation Message (Cont.)

|                                                                 |
|-----------------------------------------------------------------|
| Subframe 1 | SV Accuracy and Health, SV Clock Correlation Terms |
| Subframe 2 | Ephemeris Parameters                               |
| Subframe 3 | Ephemeris Parameters                               |
| Subframe 4 | Almanac and Health for SVs 25-32                   |
| Subframe 5 | Almanac and Health for SVs 1-24                    |

* Each Message is a 1500 bit Frame
  * Consists of five 300-bit Subframes
* Transmission Rate is 50 bits per Second
* Each Frame Requires 30 seconds to Transmit
  * 25 Frames Construct the Master Frame
  * Repeated Every 12.5 Minutes

---

# GPS Capabilities
## GPS Position Calculation
* The User Computes The Position of the Satellite at the Code Repetition Time of Transmit Using the Ephemeris Parameters
* The Pseudorange Propagation Delay * Speed of Light Is the Distance From the Satellite to the User
* The User Requires a Minimum of 4 Satellites to Solve for the 4 Unknowns
  * User Position (3 Dimensions)
  * User Clock Offset
* In Practice More Than 4 Satellites Are Normally in View

---

# GPS Capabilities
## Pseudorange Measurement
* Users have their own clock
* Users time stamp when they receive the beginning of a particular PRN code repetition
* The difference between the time computed from navigation message compensated for the proper code repetition cycle and the user’s time stamp is the Pseudorange Code Measurement
  * A Pseudorange Measurement consists of the sum of the propagation delay and the offset between the user’s clock and the satellite’s clock

---

# GPS Capabilities
## Levels of Service
### GPS provides two levels of service:
* Standard Positioning Service
* Precise Positioning Service .

---

# GPS Capabilities
## Standard Positioning Service
* The **Standard Positioning Service (SPS)** is a positioning and timing service is available to all GPS users on a continuous, worldwide basis with no direct charge.
   * SPS is provided on the GPS L1 frequency which contains a **Coarse Acquisition (C/A)** code and a navigation data message.
   * Positioning Accuracy of:
      * 100 meters (95 percent) horizontally
      * 156 meters (95 percent) vertically
      * time transfer accuracy to UTC within 340 nanoseconds (95 percent).

---

# GPS Capabilities
## Precise Positioning Service
* The **Precise Positioning Service (PPS)** is a highly accurate military positioning, velocity and timing service which will be available on a continuous, worldwide basis to users authorized by the U.S. **P(Y) code** capable military user equipment
   * Positioning Accuracy of at Least:
      * 22 meters (95 percent) horizontally
      * 27.7 meters vertically
      * time transfer accuracy to UTC within 200 nanoseconds (95 percent).
* PPS will be the data transmitted on the GPS L1 and L2 frequencies. PPS is for U.S. military use. It will be denied to unauthorized users by the use of cryptography.

---

# GPS Capabilities - System Modes
* Continuous Service
  * All algorithms performed
  * All messages broadcast
* Military Emergency
  * All algorithms performed (as in Continuous Service)
  * Fast Correction message altered; range correction = 0 and UDRE = maximum, to deny full accuracy to enemy

---

# GPS Capabilities - Selective Availability
## Selective Availability (SA)
The denial of full accuracy, is accomplished by manipulating navigation message orbit data (epsilon) and/or satellite clock frequency (dither)

---

# GPS Capabilities
## GPS Error Sources (budget)

| Type of Error | Definition                                  | Amount        |
|---------------|---------------------------------------------|---------------|
| Clock         | Drift, short-term and long-term, that prevents satellite broadcasts from being perfectly synchronized | 3 meters     |
| Ephemeris     | Error in measurement and calculation of satellite’s orbit | 4 meters     |
| Troposphere   | Effects of lower (ground to 8-13 km) atmosphere’s temperature, pressure, and humidity on signal propagation | 2.4-25 meters|
| Ionosphere    | Effect of upper (50 km to 500 km) atmosphere’s free electrons on signal propagation | 10-30 meters |
| Multipath     | Error caused by signals reflected from surfaces near the receiver’s antenna (such as buildings); these reflections interfere with or are mistaken for the primary signal | 2-100 meters |


---

# GPS Capabilities
## GPS SYSTEM TIME
Master Clock USNO - UTC

Composite Clock all operational Monitor Station and Satellite frequency standards - GPS system time

* GPS system time is given by its **Composite Clock (CC)**. The CC consists of all operational Monitor Station and satellite frequency standards.
* GPS system time, in turn, is referenced to the Master Clock (MC) at the USNO and steered to UTC(USNO)

---

# GPS Capabilities
## GPS Deficiencies For Civilian Navigation
* Availability
* Integrity
* Continuity
* Accuracy

---

# GPS Concepts
## Interim Summary
* Why GPS/WAAS?
* GPS Description
* GPS Signal Characteristics
* GPS Navigation Message
* GPS Capabilities

---

# Using Differential GPS to reduce GPS errors
* Receiver is placed at very accurately surveyed location
* Position is measured using GPS satellites
* Range correction is calculated by base, since it knows exactly where it is
* Correction is transmitted to neighboring receivers
* LAAS/ WAAS

---

# WAAS Functions
* Broadcasts the corrections and associated residual errors using geosynchronous satellites
* Monitors, configures, and directs repair - both automatically and manually

---

# Ionospheric Delay
* GPS signal isn’t traveling in a straight line through a vacuum
* Ionosphere’s electron content causes a curved path and a propagation delay
* Causes a range error because signal takes longer to arrive
* Can be determined by measuring two different freq L1 and L2
* “Codeless” receivers can measure Ionospheric delay without knowledge of the Y code

---

# Safety Is Paramount
**Hazardously Misleading Information (HMI) must be avoided**
* Indicated error more than true error, pilot won’t land with GPS/WAAS , even though it’s safe—misleading but not hazardous
* Indicated error less than true error, pilot will landd with GPS/WAAS, but it’s not safe—misleading and hazardous.

---

# GPS Protection and Alarm
* INSERT PICTURE

---

# GPS Availability Deficiencies
* Outage Rate and Redundancy of Satellites
* Accuracy
  * Selective Availability
  * SV Clock and Ephemeris
  * Ionosphere Delays
  * Comes Close for NPA/En route ~ 100 Meters
  * Not Close For PA, 7.6 Meters
* Integrity
  * Time To Alarm
  * Quantity of Ranging Sources For RAIM, FD, FDE

(RAIM) Receiver Autonomous Integrity Monitor<br>
(FD) Fault Detection<br>
(FDE) Fault Detection and Exclusion

---

# GPS Availability Deficiencies (Cont.)
* Accuracy Limits Application to Only NPA/Enroute
* Driven by Number and Geometry of Satellites in View
* Poor Performance in the Presence of Multiple Errors

---

# What Does WAAS Need To Do?
* **Provide Integrity** by Sending Messages to the User to Allow the User to Calculate the Guaranteed Accuracy at the User’s Location and Time
User Calculates VPL and HPL
* **Improve Overall Accuracy** So That Smaller Protection Levels Are Provided With Greater Reliability
   * Smaller Protection Levels =
      * Better Guaranteed Accuracy =
         * Lower Approach Minimums
* **Provide Additional Ranging Sources** So That the Quantity of Ranging Sources and Favorable Geometry Necessary to Support Favorable Protection Levels Is Provided to the User With Greater Reliability

---

# How WAAS Works
* **Reference Stations (WRSs)** monitor all satellites
* The Collected Data is Forwarded to Central Locations - WAAS Master Stations (WMSs)

---

# How WAAS Works (Cont.)
* Master Stations (WMSs):
  * Compute Corrections
  * Monitor Integrity
  * Generate Messages For Transmission to the Users (via GUS)
  * Monitor and Control the WAAS

---

# How WAAS Works (Cont.)
* Ground Uplink Systems (GUS)
  * Uplink Messages to the GEOs
  * Control the GEO Ranging Control Loop
  * Two Per GEO

---

# How WAAS Works (Cont.)
* Terrestrial Communications Network (TCN)
  * Backbone Network Consists of 4 Routers Interconnected By Dedicated T1 Telecommunications Lines
  * WMSs Are Co-located at Backbone Nodes
  * Feeder Arms Consist of Two, Diverse 64 Kbit Lines From Every WRS and GUS to the Backbone Network (Each Half of a Pair Going to Different Node)

---

# WAAS Architecture
* WAAS Reference Station
   * Collect GPS Navigation Data
   * Collect GEO Navigation Data
   * Collect Satellite Ranging
   * Collect Ionospheric Data
* WAAS Master Station
   * Generates Ranging Corrections
   * Generates Ionospheric Corrections
   * Generates Integrity Data
   * Generates SIS and O&M Messages
* Ground Earth Station
   * Signal Generation and Control

---

# How WAAS Works (Cont.)
* The WAAS Signal Looks Just Like a GPS Signal Except:
  * The Transmitted Data Stream is 500 Symbols Per Second (sps) Forward Error Correction (FEC) Encoded
  * The WAAS Message Modulation Rate is 250 bps versus 50 bps for GPS
  * The WAAS Message Word is 250 Bits (1 second) Long
  * WAAS Does Not Tell The User The Time of Transmission - User Assumes WAAS is Perfectly Synchronized to the 6 Second GPS Subframe

---

# How WAAS Works (Cont.)
## The WAAS Message Contains:
* For Every Satellite (GPS and GEO)
   * Ephemeris Corrections (Long Term Corrections)
   * SA Clock Corrections (Fast Corrections)
   * User Differential Range Error (UDRE)
      * A Quality Indication for Each Fast Correction
      * 99.9% Bounding of the Correction Accuracy
   * Use, Don’t Use, Not Monitored Integrity Status
      * Range of the Fast Correction
      * New MOPS Integrity Message (RTCA DO229)

---

# How WAAS Works (Cont.)
## The WAAS Message Contains (Cont.)
* Unique for the Transmitting GEO
  * GEO Ephemeris Data
  * PRN to Corrections Assignments (should be the same for all GEOs)
    * PRN Mask
  * Ionosphere Corrections for the Area Covered by the Footprint of the GEO
     * 1 Correction for Each Grid Point
     * GIVE - 99.9% Bounding of the Accuracy of the Ionosphere Vertical Delay at the Associated Grid Point
     * Grid Point Latitude/Longitude Assignments - Grid Mask

---

# How WAAS Works (Cont.)
## WAAS Corrections Improves Accuracy
* Improves Availability and Continuity
* Additional WAAS Ranging Sources
  * Improve NPA/En route Integrity by Improving the Availability of FD, and FDE (RAIM)
  * Improves Uncorrected NPA/En route Accuracy
  * Improves Availability and Continuity
* WAAS UDRE, GIVE, “Don’t Use, and “Not Monitored” Provide Integrity

---

# WAAS System Diagram

---

# WAAS/GUS Architecture
* Two  GEO satellites (CRE-138 and CRW-135) and four  GUSTs (BRE, LTN, APC and WBN) primary and a redundant GUSs are implemented with a dedicated GEO satellite.
* The two GUSTs are operationally independent and geographically separated.
  * Mitigate simultaneous loss due to natural disasters.
  * Redundant GUS radiates into a dummy load while receiving GEO and GPS satellite signals.
* A GUS consists of the SGS, RFU, antennas, and supporting equipment.

---

# WAAS/GUS Architecture (Cont.)

---

# WAAS/GUS Architecture - WAAS Block Diagram

---

# Key Functions
* WRSs Collect Data
* WMSs
   * Filter the Data
   * Calculate Precise Orbits of the Satellites
      * Requires Calculating Clock Corrections for the Receivers and Satellites (GPS & GEO)
      * Requires Removing the Ionosphere and Troposphere Delay Errors
      * Requires Compensating for:
         * The Effects of Gravity From the Earth, Moon, and Sun,
         * Abnormalities in the Motion and Rotation of the Earth,
         * The Effect of Solar Pressure on the Motion of the Satellites
         * The Effect of Motion of the Earth’s Crust
         * The Effect of Changes in Orientation of the Satellites

---

# Key Functions (Cont.)
* WMSs (Cont.)
   * Calculate the Ionosphere Delays at Each Grid Point
      * Requires Calculating the L1/L2 Bias Errors for the Receivers and GPS Satellites
      * Requires Calculating the Ionosphere Delay
* Calculate Pseudorange Fast Corrections (PFC)
    * Requires: Differencing the Calculated PR (orbit - antenna location) With the Compensated PRs (measured - active slow corrections - tropo), Composing Statistics, Calculating the PFCs and UDREs

---

# Key Functions (Cont.)
* WMSs (Cont.)
   * Schedule and Generate Messages
      * Based on the Active SIS (all WMSs need to schedule messages based on what the users see)
   * Verify Corrections
      * Two Corrections Processors at Each WMS, Operating Off Separate Streams of WRS Data
      * Proposed Outputs Checked Against Input Data and Extrapolated Across Expected Time of Validity Within Each Corrections Processor
      * Proposed Outputs of Both Corrections Processors Checked for Agreement By SPs

---

# Key Functions (Cont.)
* WMSs (Cont.)
   * Validate Corrections
      * Active Corrections Validated Against Measurements
      * Alarms/Correction Updates Generated
      * Message Content Checked
      * Message Latency Checked
   * Operate and Maintain WAAS
      * Single System, Single Operator
      * Performance and Failure Status
      * Logging and Recording

---

# Key Functions (Cont.)
* GUS
   * Control GEO Ranging
      * PRN Code to Carrier Phase Needs to be Exactly Aligned
      * Uplink Signal Needs to be Precisely Timed Such that the Downlink Leaves the GEO Exactly Synchronous With GPS
      * Steer GUS Clock to Maintain Synchronization With GPS (compensate for our clock drift relative to GPS clock drift)
   * FEC Encode and Modulate Messages

---

# Key Functions (Cont.)
* Terrestrial Communications Network (TCN)
   * Private Network
   * Two Independent Rings with diverse paths
      * 10.20x.1.xxx and 10.20x.2.xxx
   * Five Communication Nodes
      * ZLA (Palmdale, CA)
      * ZDC (Leesburg, VA)
      * ZAU (Chicago, IL)
      * ZTL (Hampton, GA)
      * ZSE (Auburn, Wa)
   * Each Site connects to two different Communication Nodes.

---

# Key Functions (Cont.)
* Operations and Maintenance (O&M)
   * Monitors all WAAS/GCCS subsystems
   * Displays alarms and alerts
   * Allows operator to reconfigure subsystems
      * Change operating mode
      * Download software
   * Allows operator initiated corrective maintenance procedures.

---

# Summary
## Purpose and History of WAAS
* Air Navigation Today
* Satellite Navigation
* WAAS Functions
* WAAS Architecture

---

# Ephemeris Representation
* Equatorial Plane
* Perogee
* Toward Vernal Equinox
* Ascending node. Lines of nodes is the intersection with the equatorial plane.

---

# Ephemeris Representation (Cont.)
* Six Keplerian Elements Describe GPS Satellite Orbit
* Shape of Orbital Ellipse
  * a Semi-Major Ellipse, 1/2 of Longest Axis
  * e Eccentricity, Measure of Ovalness, 0<e<1
Orientation of Orbit in Space with Respect to Fixed Stars
  * i Inclination, Angle Between Orbit Plane and Earth’s Equatorial Plane
     Right Ascension of Ascending Node, Angle Between Vernal Equinox and Point Where Satellite Rises Above Equatorial Plane
     Argument of Perigee, Angle Between Ascending Node and Perigee
  * f True Anomaly, Angle Between Perigee and Satellite
Equivalents Include the Mean Anomaly
