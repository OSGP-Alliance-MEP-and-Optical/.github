<a href="https://www.osgp.org/" target="_new"><img src="https://www.dabbler.dk/wp-content/uploads/2022/05/OSGP.png"></a>
<hr>
<H1>:point_right:The official <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> Repository with documentation for the MEP (Multipurpose Expansion Port) and Optical interfaces found in many OSGP Smart Meters:point_left:</H1>

:alarm_clock:<b>Work in progress</b><br>
<b>!!! IMPORTANT: This is work in progress. Documents are not yet released here, but will be soon. Stay tuned! !!!</b><br>

:notebook_with_decorative_cover:<b>Contents</b><br>
This repository holds the official release of the documentation for the MEP (Multipurpose Expansion Port) and the Optical interface found in many OSGP Smart Meters.
OSGP Smart Meters includes (but are not excusively) meters from <a href="https://www.networkedenergy.com/">NES (Networked Energy Services)</a>.<br>
Note: These Meters were previously also named "Echelon".<br>

:trophy:<b>History of this repository</b><br>
This repository was originally created by Graves Kilsgaard and Gert Lynge from <a href="https://www.dabbler.dk" target="_new">www.dabbler.dk</a>, but with massive support from <a href="https://www.networkedenergy.com/" target="_new">NES</a> and <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a>.<br>
We both have access to multiple installations with OSGP Smart Meters from <a href="https://www.networkedenergy.com/">NES</a> and Echelon, and have wonderes for years if we could somehow read the consumption in an intelligent way using Arduinos, ESPs or Raspberry PIs. Unfortunately our research showed that tinkeres like us have tried that for years - mostly without any success at all.<br>
We were not able to find much info. and for sure no real detailed documentation on neither the MEP nor the Optical interface and protocol. So the project for getting to the data was put on hold for a while.<br>
Until 2020 where we attended the small danish Tinkering gathering <a href="https://sommerhack.dk/" target="_new">Sommerhack 2020</a>. We attended some of the presentations there about Smart meters and the power distribution grid etc. And we were inspired to put more efford into the project.<br>
After more research, a lot of dead ends and frustration, we finally reached out to <a href="https://www.networkedenergy.com/">NES</a>. To our surprise, NES were very interested in getting the interface and protocol specifications released to Tinkeres.<br>
The requirement were that the documents should be released by <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> and before release the documentation needed some updating and rework.<br>
I the meantime we signed an NDA (Non-Disclosure Agreement) so we could get started in Tinkering with some hard- and software.<br>
As the work on these documents was not a high priority project for <a href="https://www.networkedenergy.com/">NES</a>, <a href="https://www.osgp.org/" target="_new">OSGP Alliance</a> and us, this unfortunately ended up taking a while.<br>
<a href="https://sommerhack.dk/" target="_new">Sommerhack 2021</a> went by, this time Graves and Gert did a presentation on a working prototype for MEP - and the promising future with the release of the documentation. And writing this, with <a href="https://sommerhack.dk/" target="_new">Sommerhack 2022</a> just around the corner, we are preparing this repository to be ready as soon as the documents are released.

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
