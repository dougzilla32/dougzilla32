# SweepNPark

Sweep N' Park is a navigation app that helps users find parking in San Francisco by visualizing street sweep and tow-away restrictions on a map.

> 🔒 Private Repository

Technologies: `parking`

---

## Sweep N' Park San Francisco

### Overview

Sweep N' Park is a navigation app that helps users find parking in San Francisco by visualizing street sweep and tow-away restrictions on a map. It highlights streets where parking is likely to be available, especially focusing on areas where restrictions have recently ended.

### Features

* Interactive Map Visualization: Color-coded streets to indicate different parking restrictions.
* Time and Date Planning: Explore parking availability for any time and date with an intuitive picker interface.
* Location-Based Search: Quickly find streets near specific addresses or landmarks.
* Detailed Street Information: Tap any street to see comprehensive information about parking rules, meters, and time limits.
* User-Friendly Interface: Clean design with easy-to-use controls and helpful tooltips.

### Technical Highlights

* Swift and UIKit: Built with modern Swift using UIKit for the UI.
* MapKit and Google Maps: Integration of advanced mapping technologies.
* Complex UI Coordination: Custom date/time picker implementation, animations, and map interaction.
* Grid-Based Performance Optimization: Efficient rendering of thousands of street segments.

### Architecture and Design Patterns

* Model-View-Controller (MVC): Clean separation of data models, UI components, and controllers.
* Protocol-Oriented Programming: Extensive use of Swift protocols for flexibility and modularity.
* Background Processing: Multi-threaded operations for smooth UI experience.

### Development Challenges

* Data Visualization: Creating an intuitive visual representation of complex parking rules.
* Performance Optimization: Very smooth scrolling and zooming with thousands of map elements.
* Memory Management: Efficiently handling large datasets of street information.
* Complex UI Interactions: Coordinating multiple overlapping UI elements.

### Color Legend

|                      Color&nbsp;&nbsp;                       | Parking restriction              |
| :----------------------------------------------------------: | :------------------------------- |
|           ![green](SweepNPark/Resources/LineLightGreen.png)&nbsp;&nbsp;           | Unrestricted                     |
|       ![greendash](SweepNPark/Resources/LineLightGreenDash.png)&nbsp;&nbsp;       | Parking spaces are limited (< 5) |
|        ![graydash](SweepNPark/Resources/LineLightGrayDash.png)&nbsp;&nbsp;        | There are no parking spaces      |
| ![blue](SweepNPark/Resources/LineBlue.png)&nbsp;&nbsp;![streep-sweeper](SweepNPark/Resources/PreviewStreetSweeper.png)&nbsp;&nbsp; | Street sweeping is active        |
| ![red](SweepNPark/Resources/LineRed.png)&nbsp;&nbsp;![tow-truck](SweepNPark/Resources/PreviewTowTruck.png)&nbsp;&nbsp; | Tow-away is active               |
| ![psychedelicPurple](SweepNPark/Resources/LinePsychedelicPurple.png)&nbsp;&nbsp;![car-purple](SweepNPark/Resources/HatchbackParkedPurple.png)&nbsp;&nbsp; | Street sweeping just ended       |
| ![darkOrange](SweepNPark/Resources/LineDarkishOrange.png)&nbsp;&nbsp;![car-orange](SweepNPark/Resources/HatchbackParkedOrange.png)&nbsp;&nbsp; | Tow-away just ended              |
|  |  |
| ![green](SweepNPark/Resources/ParkingMeterGreen.png) ![lime](SweepNPark/Resources/ParkingMeterLime.png) ![yellow](SweepNPark/Resources/ParkingMeterYellow.png) <br> ![orange](SweepNPark/Resources/ParkingMeterOrange.png) ![red](SweepNPark/Resources/ParkingMeterRed.png) | **<span style="color:green">$0-1</span>&nbsp;&nbsp;&nbsp; <span style="color:lime">$1-2</span>&nbsp;&nbsp;&nbsp; <span style="color:#CCCC00">$2-3</span> <br><br> <span style="color:orange">$3-4</span>&nbsp;&nbsp;&nbsp; <span style="color:red">&gt;$4</span>** |
| ![short-term](SweepNPark/Resources/ParkingMeterShortTerm.png)&nbsp;&nbsp; | Short term parking meter |
| ![restricted](SweepNPark/Resources/ParkingMeterRestricted.png)&nbsp;&nbsp; | Restricted parking meter |
| ![time-limit-1](SweepNPark/Resources/TimeLimit1.png)&nbsp;&nbsp;![time-limit-2](SweepNPark/Resources/TimeLimit2.png)&nbsp;&nbsp;![time-limit-4](SweepNPark/Resources/TimeLimit4.png)&nbsp;&nbsp; | Time limit is in effect          |
| ![free-parking](SweepNPark/Resources/FreeParking.png)&nbsp;&nbsp; | Free (unrestricted) parking        |

### Map Controls

|              Tap&nbsp;&nbsp;&nbsp;              | Action                                                    |
| :---------------------------------------------: | :-------------------------------------------------------- |
|  ![userguide](SweepNPark/Resources/UserGuideButton.png)&nbsp;&nbsp;  | Display the user guide, feedback form, settings and about |
|           ![mag](SweepNPark/Resources/Mag.png)&nbsp;&nbsp;           | Search for an address or place                            |
| ![locationArrow](SweepNPark/Resources/LocationArrow.png)&nbsp;&nbsp; | Jump to the current location                              |
|         ![filter](SweepNPark/Resources/Filter.png)&nbsp;&nbsp;       | Map detail filtering options                              |
|         ![today](SweepNPark/Resources/Today.png)&nbsp;&nbsp;         | Jump to the current time and date                         |

### Screenshots

<table>
  <tr>
    <td align="center"><img src="Media/AppStoreConnect/iPhone%206.5%20inch/Screenshots/Info.png" width="400"/></td>
    <td align="center"><img src="Media/AppStoreConnect/iPhone%206.5%20inch/Screenshots/Sweep.png" width=400"/></td>
  </tr>
  <tr><td colspan="2" style="height: 30px;"></td></tr>
  <tr>
    <td align="center"><img src="Media/AppStoreConnect/iPhone%206.5%20inch/Screenshots/Meters.png" width="400"/></td>
    <td align="center"><img src="Media/AppStoreConnect/iPhone%206.5%20inch/Screenshots/Tow-away.png" width="400"/></td>
  </tr>
</table>
