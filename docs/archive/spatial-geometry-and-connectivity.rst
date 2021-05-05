=================================
Spatial geometry and connectivity
=================================

Good geometrical quality/topological connectivity for vector datasets means that the vector objects have been created carefully, and no unintentional errors are tolerated. This is case-specific for different datasets, and the data provider must be aware of the best practices in their field.

For example:

- Geometric lines representing a two-way road can be drawn from either direction, whereas in drainage network data the direction of the geometry lines should be parallel with the flow of water in the drainage segment. All lines in road network dataset must be connected (since all roads are connected in the real world as well), but some drainage segments might be independent compared to other segments in the same area.
- A polygon data representing Wards in Dar es Salaam region must not have any gaps or overlappings between each other, but polygon data representing only forested areas can have independent polygons with gaps around them.

GIS software has tools or plugins to check the most general connectivity rules. In case of more specific connectivity rules (such as drainage lines), independent software or algorithms may be used. Check the geometric quality of your dataset by using those connectivity rules that can be applied to your case.

CRD provides a quick instruction how to use the QGIS Topology Fix tool to check the connectivity:	`Tool: Topology Checker, QGIS <https://geonode.resilienceacademy.ac.tz/documents/150>`_

A comprehensive open online learning course regarding geospatial data quality can be found from Resilience Academy’s Digicampus profile (requires Gmail registration):
-	`Module 2: Geospatial data quality & management <https://digicampus.fi/course/view.php?id=493>`_

Attributes and values
^^^^^^^^^^^^^^^^^^^^^

The attributes and values of datasets must be relevant for the phenomenon the dataset represents. Relevant attributes are always case-specific, and recognizing them is easiest when the goal of the data acquisition process is clear. To make sure all values are recorded correctly, all individuals taking part in the acquisition process must understand what the attributes and values mean and how they should be recorded. Training is crucial part to minimize the human errors and uneven quality of the dataset.

In the final data product, the values should be consistent (e.g. no “type = football” and “type = Football”), be of appropriate format (e.g. numbers in Integer or Decimal format and texts in String format) and all attributes should be complete (i.e. no empty observations). In case of empty observations, “NA” should be recorded, and the reasons of the “NA” should be carefully explained in the metadata. See an example of this in the metadata section Data Quality Statement of `Nungwi Buildings <https://geonode.resilienceacademy.ac.tz/layers/geonode_data:geonode:nungwi_buildings>`_ dataset.

Visualisation
^^^^^^^^^^^^^

Good visualisation is at the core of impactful and truthful geospatial data. In case you want the dataset to have a specific visualisation when it is displayed in the Climate Risk Database, make sure you send a visualisation file with the data. Visualisations can be saved to an .SLD file (Styled Layer Descriptor) for example in QGIS, which then can be uploaded to the CRD as such.
Download an instruction for creating SLD files in QGIS from the CRD:
-	`Instruction: Creating SLD in QGIS <https://geonode.resilienceacademy.ac.tz/documents/135>`_

File format
^^^^^^^^^^^

To ensure accessibility, all files - the dataset and metadata - must be in machine readable formats. Approved file formats are the following:

- Vector datasets: ESRI shapefile, Zipped shapefile, Geopackage, GeoJSON, or CSV with coordinates
- Raster datasets: TIFF, GZIP
- Metadata and attribute metadata: Excel-sheets
- Visualisation: SLD format

License
^^^^^^^

All datasets must be shared under a license. License tells data users how they can use the data without violating data owner’s rights. License can determine for example whether the data can be modified, re-shared or used for commercial purposes and how the owner should be acknowledged.

Climate Risk Database and Resilience Academy are advocates for open data and information sharing. This means the data users have open access to the datasets and they are free to download and use them for their own purposes. Therefore, CRD recommends an open license for the publishable datasets. Most common open licenses are, for example:

- Open Data Commons Open Database License (ODbL)
- Creative Commons Attribution 4.0
- Creative Commons Attribution Share-Alike 4.0
- Creative Commons Attribution Share-Alike Non-Commercial 4.0
- Other Creative Commons 4.0 variations

For example: All World Bank owned datasets published in the CRD are licensed under Creative Commons Attribution 4.0 (CC-BY 4.0), which means the users are allowed to copy, modify and distribute data in any format for any purpose, including commercial use. Users are only obligated to give appropriate credit (attribution) and indicate if they have made any changes, including translations. `Read more about Creative Commons licenses: <https://creativecommons.org/about/cclicenses/>`_`
All OpenStreetMap related datasets must follow the terms of licenses of OpenStreenMap Foundation. OpenStreetMap licenses their data under Open Data Commons Open Database License (ODbL). `Read more: <https://www.openstreetmap.org/copyright>`_`
