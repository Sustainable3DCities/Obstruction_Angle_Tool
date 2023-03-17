# OA-tool

This folder contains the Jupyter notebook ipynb-file with the code for the OA-tool. The tool is developed in ArcPy and needs an installed version of ESRI ArcGIS Pro v. 2.8 or later to run. 

There are currently two versions of the tool available:

- **OA_tool_v1.ipynb**: Outputs a 3D window Multipatch Feature Layer. A column containing the obstruction angle value has been added to the attribute table of the layer. 


- **oa_tool_export_obstruction_point.ipynb**: Outputs a 3D window Multipatch Feature Layer. A column containing the obstruction angle value has been added to the attribute table of the layer. The notebook also outputs a *csv-file* containg the following columns:
  - **FID**: refers to FID of the window (Feature ID from ESRI ArcGIS Pro's Multipatch Feature Layer for the 3D windows)
  - **w_id**: refers to the window ID (unique for every window)
  - **obstr_x_coord**: longitude of the obstruction point yielding the highest OA for a given window
  - **obstr_y_coord**: latitude of the obstruction point yielding the highest OA for a given window
  - **obstr_z_coord**: elevation of the obstruction point yielding the highest OA for a given window
