# bim2bemtranslator
The gbXML translator is a newly created middleware solution built on Python. This transaltor facilitates the conversion of Building Information Modeling (BIM) models from the gbXML format, to Energy Plus model, the IDF format. gbXML is an open-source schema tailored for containing the necessary data for energy simulations and IDF is a format for Building Energy Modeling (BEM) files supported by the EnergyPlus simulation engine.

This tool functions by mapping various building properties from the gbXML schema to the IDF data format. It extracts details such as geometry, thermal properties, heat gains, occupancy/lighting/equipment schedules, and HVAC specifics from the gbXML file and converts them into IDF data classes. Furthermore, it incorporates default schedules, HVAC objects, and output objects from a library to supplement any missing data.

To seamlessly integrate the gbXML translator into the BIM environment, a user interface has been developed and deployed as a BIM tool (refer to Figure 09). The visual representation of the mapping of data classes can be observed in Figure 10.
(https://github.com/Udaragithub/bim2bemtranslator/blob/main/Images/Research%20Gap%20and%20Proposed%20Tool%20(15).png)
