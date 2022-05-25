<a href="https://www.osgp.org/" target="_new"><img src="https://www.dabbler.dk/wp-content/uploads/2022/05/OSGP.png"></a>
<hr>
<H1>:point_right:Official <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> Documentation for MEP (Multipurpose Expansion Ports) and Optical interfaces in OSGP Smart Meters:point_left:</H1>

:notebook_with_decorative_cover:<b>Contents</b><br>
This repository holds the latest version of the official released documentation for the MEP (Multipurpose Expansion Port) and the Optical interface found in many OSGP Smart Meters (i.e. Smart Meters from <a href="https://www.networkedenergy.com/">NES (Networked Energy Services)</a>.<br>
Note: These Meters were previously manufactured and sold with the "Echelon" brand name.<br>

:trophy:<b>History</b><br>
This repository was originally created by <a href="https://www.linkedin.com/in/kilsgaard/" target="_new">Graves Kilsgaard</a> and <a href="https://www.linkedin.com/in/gertlynge/" target="_new">Gert Lynge</a> from <a href="https://www.dabbler.dk" target="_new">www.dabbler.dk</a>, but with massive support from <a href="https://www.networkedenergy.com/" target="_new">NES</a> and <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a>.<br>
Full credits and a very special "Thank You!" to these people for helping us make this possible:<br>
<ul>
  <li><a href="https://www.linkedin.com/in/markossel/" target="_new">Mark Ossel</a>, Board Member at <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> and Sr. Vice President at <a href="https://www.networkedenergy.com/" target="_new">NES</a></li>
  <li><a href="https://www.linkedin.com/in/sven-hartmeier/" target="_new">Sven Hartmeier</a>, Member <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> Workgroup standards and Technical Training Manager at <a href="https://www.networkedenergy.com/" target="_new">NES</a></li>
</ul>
See <a href="https://www.dabbler.dk" target="_new">www.dabbler.dk</a> for blog entries about the journey Graves and Gert had to make this possible..<br>
<br>
:electric_plug:<b>OSGP Meter Customer Interface Development Guide (MEP Interface)</b><br>
The document was previously called "MEP Client Developer’s Guide" and describes how to develop a device that implements the MEP (Multipurpose Expansion Port) protocol. The MEP protocol is a client/server protocol used to exchange OSGP Smart Meter device data, status information, and alarm data between the smart meter and an attached client device.<br><br>
The document introduces the MEP protocol, including definitions of the data tables and procedures you will use when programming your MEP server with the MEP protocol. It is intended for those developing devices for use with the MEP protocol, and assumes some background knowledge of the OSGP Smart Meter you are using. The OSGP Alliance recommends that you review the appropriate user document(s) (e.g. the "OSGP Protocol specification" and any specific "Smart Meter user manual") before developing your MEP client.<br><br>
The document also assumes some knowledge of the "ANSI C12.19 (1997) Utility Industry End Device Data Tables" protocol document. Most general information regarding the rules of this protocol is not repeated here. You can find the "ANSI C12.19 Utility Industry End Device Data Tables" document online at <a href="http://www.nssn.org" target="_new"> http://www.nssn.org</a> or <a href="http://webstore.ansi.org" target="_new">http://webstore.ansi.org</a>.<br><br>
The MEP protocol is supported by all current OSGP Smart Meter firmware versions. Most of the features (and the associated tables and procedures) described in this document are available to all these device types. Exceptions to this are noted throughout the document, as this version of the MEP Client Developer’s Guide describes some features that are only available to devices running the most recently released firmware versions.<br>
<br>
:electric_plug:<b>Optical Port Programmer’s Guide</b><br>
The document is generally intended for use with OSGP Standard compatible Meters. The OSGP Standard is accepted as open standard and described by various international standard organizations:<br>
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
<br>
The document assumes knowledge of the meter version you are using. The OSGP Alliance recommends that you review the documentation for your meter model in its entirety before using the information in this manual to read and write the meter tables:<br>
<ul>
  <li>Your OSPG Standard compatible Meter’s User’s Guide, for the currently installed Firmware Version</li>
</ul>
<br>
This document also assumes knowledge of the following protocol documents. General information regarding the rules of these protocols is not repeated here.<br>
<ul>
  <li>ANSI C12.18 (1996) Optical Port Protocol</li>
  <li>ANSI C12.19 (1997) Utility Industry End Device Data Tables</li>
</ul>
<br>
For topics pertaining to M-Bus device data, knowledge of the following specifications is assumed.<br>
<ul>
  <li>EN 13757-3, April 2002</li>
  <li>The M-Bus: A Documentation, version 4.8</li>
<ul>
