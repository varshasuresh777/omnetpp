
OMNeT++
========================

1. Download and Install Omnet++.
2. Download,Install INET Framework and Import to Omnet++.
3. Create a new project named "experiment"
4. Add inet to the project by clicking to properties--> project references --> click inet --> apply and close. 
5. Open package.net file under "src" and copy the code from " PackageNedFile".
5. Add initialization file "Omnet.ini" from "src" and copy the code from "INIFile"
6. Add "OSPFConfig.xml" file from "src" and copy the code from "INIFile".
7. Add "filters.xml" from "src" and copy the code from "FiltersXMLFile".
8. Save and build project 
10. Go to ini file and simulate the project. 
11. Simulate for all the three configurations( DROP TAIL WITHOUT TRAFFIC SHAPING AND POLICING, DROP TAIL WITH TRAFFIC SHAPING AND POLICING,ROUND ROBIN WITH TRAFIIC SHAPING AND POLICING)
12. Close the simulation file.
13.We get results under "src" file as "sca" and "vec". Double clicking any one of files we get ".anf" file.
14.Get ".anf" file for the three configurations. 
15.Observe the end to end delay, queuing time, packets sent and received, packets dropped. 
