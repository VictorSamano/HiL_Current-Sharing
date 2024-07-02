
<h2 align="center" style=>
Controller hardware in the loop platform for evaluating Current-Sharing and Hot-Swap in Microgrids
</h2>
<p class="margen" align="justify">
The PV.xlsx contains the addresses and normalized power values to initialize the LUT that emulates the photovoltaic panel.
</p>
<p align="justify">
The LabVIEW2 folder contains the LabVIEW project named CurShar.lvproj with all its dependencies. This project includes the DB1 and DB2 programs. The VI file called Iniciar.vi allows the photovoltaic panel LUT initialization for its emulation. For DB1, its instance can be found in the BESS instance, meanwhile the WIND instance is used for DB2. Before executing the HIL platform, modify the IP address of the previous instances, then execute the VIs called FPGA.vi and RTP_Bus_v2.vi.
</p>
<p align="justify">
The Acquisition folder includes the LabVIEW project adquisicion.lvproj and all its dependencies. The data acquisition of the platform is executed from the VI called RTP.vi
</p>
<p align="justify">
This work was developed under a LabVIEW MyRIO 2015 version.
</p>
