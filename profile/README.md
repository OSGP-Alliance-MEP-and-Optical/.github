<a href="https://www.osgp.org/" target="_new"><img src="https://www.dabbler.dk/wp-content/uploads/2022/05/OSGP.png"></a>
<hr>
<H1>:point_right:Official <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> Repository for MEP (Multipurpose Expansion Port) and Optical interface documentation:point_left:</H1>

:alarm_clock:<b>Work in progress</b><br>
<b>!!! IMPORTANT: This is work in progress. Documents are not yet released here, but will be soon. Stay tuned! !!!</b><br>

:notebook_with_decorative_cover:<b>Contents</b><br>
This repository holds the official release of the documentation for the MEP (Multipurpose Expansion Port) and the Optical interface found in many OSGP Smart Meters.
OSGP Smart Meters, i.e. meters from <a href="https://www.networkedenergy.com/">NES (Networked Energy Services)</a>.<br>
Note: These Meters were previously also named "Echelon".<br>

:trophy:<b>History of this repository</b><br>
This repository was originally created by Graves Kilsgaard and Gert Lynge from <a href="https://www.dabbler.dk" target="_new">www.dabbler.dk</a>, but with massive support from <a href="https://www.networkedenergy.com/" target="_new">NES</a> and <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a>.<br>
See <a href="https://www.dabbler.dk" target="_new">www.dabbler.dk</a> for blog entries telling the story of our journey to get this documentation released.<br>

:electric_plug:<b>OSGP Meter Customer Interface Development Guide (MEP Interface)</b><br>
This document was previously called "MEP Client Developer’s Guide" and describes how to develop a device that implements the MEP (Multipurpose Expansion Port) protocol. The MEP protocol is a client/server protocol used to exchange OSGP Smart Meter device data, status information, and alarm data between the smart meter and an attached client device.<br>
The document introduces the MEP protocol, including definitions of the data tables and procedures you will use when programming your MEP server with the MEP protocol. It is intended for those developing devices for use with the MEP protocol, and assumes some background knowledge of the OSGP Smart Meter you are using. The OSGP Alliance recommends that you review the appropriate user document(s) (e.g. the OSGP Protocol specification and any specific Smart Meter user manual) before developing your MEP client.<br>
This document also assumes some knowledge of the ANSI C12.19 (1997) Utility Industry End Device Data Tables protocol document. Most general information regarding the rules of this protocol is not repeated here. You can find the ANSI C12.19 Utility Industry End Device Data Tables document online at <a href="http://www.nssn.org" target="_new"> http://www.nssn.org</a> or <a href="http://webstore.ansi.org" target="_new">http://webstore.ansi.org</a>.<br>
The MEP protocol is supported by all current OSGP Smart Meter firmware versions. Most of the features (and the associated tables and procedures) described in this document are available to all these device types. Exceptions to this are noted throughout the document, as this version of the MEP Client Developer’s Guide describes some features that are only available to devices running the most recently released firmware versions.<br>

:electric_plug:<b>Optical Port Programmer’s Guide</b><br>
This document is generally intended for use with OSGP Standard compatible Meters. The OSGP Standard is accepted as open standard and described by various international standard organizations:<br>
<ul>
<li>ETSI TS 104 001 Open Smart Grid Protocol; (Application Layer 7)</li>
<li>ETSI TS 103 908 Power Line Telecommunications (PLT) BPSK Narrow Band Power Line Channel for Smart Metering Applications. (Layer 1)</li>
<li>IEC/ISO 14908 Control network layer (Layers 2-6)</li>
<li>CEN/CENELEC CLC/TS 50586 Open Smart Grid Protocol</li>
<li>IEC 62056-8-8, DLMS/COSEM Suite - Communication Profile for ISO/IEC 14908 series networks</li>
</ul>
<br>
The document provides information you will find useful when reading meter tables to perform the following tasks over the meter’s optical port interface:<br>
<ul>
<li>Reading the meter's utility serial number</li>
<li>Reading meter firmware version</li>
<li>Reading on-demand register data</li>
<li>Reading historical register data</li>
<li>Reading load profile data</li>
<li>Reading M-Bus data</li>
<li>Reading the meter alarms</li>
<li>Reading the event log</li>
<li>Reading instantaneous measurement values</li>
</ul>
