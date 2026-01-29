# ITC-Suite_Docs
# Main directory of documentation for the ITC-Suite

##Individual tree approach to forest inventory

Most forest inventories in Canada are still produced largely through theinterpretation of images and anchored by field surveys, a tedious and costlyprocess. Improvements in the accuracy, timeliness and cost-effectiveness offorest information are badly needed, from the local to national and globallevels.
With the advent of higher-resolution satellite and aerial sensors, as well asmore sophisticated computer image analysis, Canadian Forest Serviceresearchers at the Pacific Forestry Centre have been working on a differentapproach. Instead of delineating large ensembles like forest stands and thenassessing their content, they recognized that it would be more useful forcomputers to delineate individual tree crowns (ITCs), assess their speciesand then regroup them into forest stands.
The researchers have developed the ITC Suite, consisting of about 35computer programs that use this approach. The system is semi-automatic,requiring people only to provide sample areas or trees with which to “train”the computer in species recognition, and then to assess the results.

![PRF_ITCs_Classif.jpg](./images/PRF_ITCs_Classif.jpg)



**Figure 1 - **
ITC-based forest inventory of part of the Petawawa Research Forest,Ontario.


Training the computer to consistently recognize more than a dozen speciesover the inventory area involves masking the non-forested areas and thendelineating ITCs in all of the images, classifying them into species, andregrouping them into typical forest stands (Figure 1). Precise speciescomposition and other forest information is produced for each stand in aformat directly transferable to Geographic Information Systems (Figure 2).

ITCPCD_Resuts.jpg


**Figure 2 - **
ITC-based stand information typically transferred to GeographicInformation Systems.

Aerial LiDAR data or stereo image autocorrelation is used to produce aDigital Canopy Model, which can in turn be used to assess forest stand orITC heights. Wood volumes can be calculated—using more precise speciescomposition—the conventional way, or on a stand or ITC basis as a functionof species, crown area, and height.

Images from the current generation of high-resolution satellites can also beused in ITC-based forest analysis.

Volume and biomass have already beenestimated using this approach using a combination of LiDAR and multispectral data.


In addition, the ITC Suite has been used for a variety of specializedinventories (e.g., single species or snag detection, damage and health issues,gap assessments) and has specialized modules for regenerationassessment.
While the ITC information is currently regrouped at the forest stand level, itmay soon be gathered and used directly for forest management andoperation planning. With high-resolution satellite or aerial images, precise,accurate and timely semi-automatic ITC-based forest inventories couldreplace the costly process being used today.

GDAL_ITC-Suite_Main_Fig.gif
**Figure 3 - ** ArcGIS View of the ITC-Suite


ArcGIS_ITC-Suite_Toolbox.gif 

**Figure 4 - **ArcGIS Toolbox





