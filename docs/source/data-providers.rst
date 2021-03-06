
==============
Data providers
==============

Do you have datasets that would be suitable to be published in the CRD? Or are you starting a new data collection process with the final data product being uploaded to the CRD? Please take a look at this section’s content to guide your work.

Data quality standards
^^^^^^^^^^^^^^^^^^^^^^

All datasets published via the CRD must meet **CRD Data quality requirements and standards**. This ensures the consistency of high quality and reliability of each dataset, which serves the future data users. High-quality datasets can be used for reliable decision making, education and research.

Download data quality requirements and checklist of the standards applied in the Climate Risk Database through the CRD:

- `Data quality requirements and standards <https://geonode.resilienceacademy.ac.tz/documents/398>`_

- `Data quality requirements and standards (TURP) <https://geonode.resilienceacademy.ac.tz/documents/182>`_ - this version is for data acquisition projects under the TURP program.


The elements of these documents are highlighted below.

Metadata
********

Metadata describes the dataset and its lineage, and therefore it is as crucial an element as the geospatial dataset itself. All datasets published in the Climate Risk Database must have metadata in a standardized format.

The Climate Risk Database follows the International Organization for Standardization’s metadata standards. More detailed, the ISO 19115 Geographic Information - Metadata standard.

Example: `Nungwi Trees <https://geonode.resilienceacademy.ac.tz/layers/geonode_data:geonode:nungwi_trees#more>`_ dataset has a great set of metadata. The dataset, the collection process and the project behind it has been clearly explained, as well as the consistency and completeness of the data.

Download the metadata instruction through the CRD: `Metadata instruction <https://geonode.resilienceacademy.ac.tz/documents/144>`_


Attribute metadata
******************

Attribute metadata describes the attributes of **vector** datasets. Attribute metadata must be created for all vector datasets - the information about attribute names, their description, value type and value range helps the data user to understand what the attributes mean and how they can be used.

The Climate Risk Database follows the International Organization for Standardization’s metadata standards (ISO 19115 Geographic Information - Metadata) with minor modifications.

Example: `Dar es Salaam Historical Flood Depths <https://geonode.resilienceacademy.ac.tz/layers/geonode_data:geonode:dar_es_salaam_historical_flood_depths>`_ has a great set of attribute metadata (click **Attributes** under the map).

Download the attribute metadata instruction through the CRD: -	`Attribute metadata instruction <https://geonode.resilienceacademy.ac.tz/documents/145>`_

Spatial geometry and connectivity
*********************************

Good geometrical quality/topological connectivity for vector datasets means that the vector objects have been created carefully, and no unintentional errors are tolerated. This is case-specific for different datasets, and the data provider must be aware of the best practices in their field.

For example:

- Geometric lines representing a two-way road can be drawn from either direction, whereas in drainage network data the direction of the geometry lines should be parallel with the flow of water in the drainage segment. All lines in road network dataset must be connected (since all roads are connected in the real world as well), but some drainage segments might be independent compared to other segments in the same area.
- A polygon data representing Wards in Dar es Salaam region must not have any gaps or overlappings between each other, but polygon data representing only forested areas can have independent polygons with gaps around them.

GIS software has tools or plugins to check the most general connectivity rules. In case of more specific connectivity rules (such as drainage lines), independent software or algorithms may be used. Check the geometric quality of your dataset by using those connectivity rules that can be applied to your case.

CRD provides a quick instruction how to use the QGIS Topology Fix tool to check the connectivity:

- `Tool: Check and Fix Geometries, QGIS <https://geonode.resilienceacademy.ac.tz/documents/150>`_
- `Tool: Check and Fix Geometries, ArcGIS Pro <https://geonode.resilienceacademy.ac.tz/documents/406>`_


Attributes and values
*********************

The attributes and values of datasets must be relevant for the phenomenon the dataset represents. Relevant attributes are always case-specific, and recognizing them is easiest when the goal of the data acquisition process is clear. To make sure all values are recorded correctly, all individuals taking part in the acquisition process must understand what the attributes and values mean and how they should be recorded. Training is crucial part to minimize the human errors and uneven quality of the dataset.

In the final data product, the values should be consistent (e.g. no “type = football” and “type = Football”), be of appropriate format (e.g. numbers in Integer or Decimal format and texts in String format) and all attributes should be complete (i.e. no empty observations). In case of empty observations, “NA” should be recorded, and the reasons of the “NA” should be carefully explained in the metadata. See an example of this in the metadata section Data Quality Statement of `Nungwi Buildings <https://geonode.resilienceacademy.ac.tz/layers/geonode_data:geonode:nungwi_buildings>`_ dataset.

Visualisation
*************

Good visualisation is at the core of impactful and truthful geospatial data. In case you want the dataset to have a specific visualisation when it is displayed in the Climate Risk Database, make sure you send a visualisation file with the data. Visualisations can be saved to an .SLD file (Styled Layer Descriptor) for example in QGIS, which then can be uploaded to the CRD as such.

Download an instruction for creating SLD files in QGIS from the CRD:
-	`Instruction: Creating SLD in QGIS <https://geonode.resilienceacademy.ac.tz/documents/135>`_

File format
***********

To ensure accessibility, all files - the dataset and metadata - must be in machine readable formats. Approved file formats are the following:

- Vector datasets: ESRI shapefile, Zipped shapefile, Geopackage, GeoJSON, or CSV with coordinates
- Raster datasets: TIFF, GZIP
- Metadata and attribute metadata: Excel-sheets
- Visualisation: SLD format

License
*******

All datasets must be shared under a license. License tells data users how they can use the data without violating data owner’s rights. License can determine for example whether the data can be modified, re-shared or used for commercial purposes and how the owner should be acknowledged.

Climate Risk Database and Resilience Academy are advocates for open data and information sharing. This means the data users have open access to the datasets and they are free to download and use them for their own purposes. Therefore, CRD recommends an open license for the publishable datasets. Most common open licenses are, for example:

- Open Data Commons Open Database License (ODbL)
- Creative Commons Attribution 4.0
- Creative Commons Attribution Share-Alike 4.0
- Creative Commons Attribution Share-Alike Non-Commercial 4.0
- Other Creative Commons 4.0 variations

For example: All World Bank owned datasets published in the CRD are licensed under Creative Commons Attribution 4.0 (CC-BY 4.0), which means the users are allowed to copy, modify and distribute data in any format for any purpose, including commercial use. Users are only obligated to give appropriate credit (attribution) and indicate if they have made any changes, including translations. `Read more about Creative Commons licenses: <https://creativecommons.org/about/cclicenses/>`_
All OpenStreetMap related datasets must follow the terms of licenses of OpenStreenMap Foundation. OpenStreetMap licenses their data under Open Data Commons Open Database License (ODbL). Read more: <https://www.openstreetmap.org/copyright>



Submitting data
^^^^^^^^^^^^^^^

If you have geospatial data that would be great for sharing in the Climate Risk Database, kindly contact the CRD Data managers’ team first.
Agree how you will submit the datasets: via sending the files to the CRD Data managers’ team, or by uploading them directly to the Climate Risk Database.
In case of uploading data yourself requires registration and updating your profile information. See instructions for registering from the section above.
If you would prefer the CRD Data managers’ team to upload the data, that is also possible.

Thank you for contributing to our community by providing your data to the Climate Risk Database!

Upload layer
************

Download visual instructions: `Instruction: Upload layers to CRD. <https://geonode.resilienceacademy.ac.tz/documents/127>`_

1.	Click **Layers** in the top navigation bar, and then click **Upload layers** from the top-right corner.
2.	Follow the instructions of the upload page. Files needed for vector datasets in Shapefile format are: .shp .shx .dbf .prj. File needed for raster datasets in TIFF format is: .tif.
3.	Click **Upload files** and wait until they have been successfully loaded.
4.	Change the permission settings, if relevant. The permissions can be changed afterwards, too.
5.	Click **Edit metadata**. See the next section.

Edit metadata
*************

Download visual instructions: `Instruction: CRD Metadata Wizard. <https://geonode.resilienceacademy.ac.tz/documents/138>`_

1.	Fill in all metadata fields of the **Metadata Wizard** that opens up. Use the visual instructions as a guideline,
if needed. Don’t forget to fill in attribute metadata for vector layers!
2.	When you are ready, click **Update**. You are redirected to the layer page.
3.	If you want to edit the metadata later, click **Editing tools** from the right-hand side menu, and choose Wizard under the Metadata section.
4.	If you want to edit layer permissions, scroll the page down and click **Change Layer Permission** from the right-hand side menu.

Upload style
************

Custom styles can (and should!) be uploaded to CRD to override the default styling that is created automatically when a layer is uploaded to CRD.
The style must be a SLD (Styled Layer Descriptor) file, which can be exported from QGIS.
Find instructions for creating a SLD file from the document `Instruction: Creating SLD in QGIS. <https://geonode.resilienceacademy.ac.tz/documents/135>`_

1.	Go to the layer page of that specific layer of which you want to style with the SLD file you have created. **Note**: you must be signed in, and have permissions to edit the layer in order to edit its style!
2.	Click **Editing Tools**. Choose **Upload** from the Styles section of the pop-up-window.
3.	Drag-and-drop or choose the SLD file and click **Upload files**.
4.	Click **Layer info** to view the new style in action!
5.	If you encounter any problems, please contact the CRD Data managers. Sometimes the GeoNode-platform can be a bit tricky when updating styles.

Upload layer through command line
*********************************

Download instructions: `Instruction: Upload data using command line. <https://geonode.resilienceacademy.ac.tz/documents/132>`_

You can upload data to CRD through the command line. This is useful, for example, when

- The dataset is simply too big to be uploaded through a web interface,
- You would like to import some data from the mass storage programmatically,
- You would like to import some tables from a DataBase or
- You need to process the data first and, maybe, transform it to another format.

Upload documents
****************

In case you have documents, such as reports, additional information or map images you would like to attach to your dataset,
they can be also uploaded to the Climate Risk Database and linked to your data. To upload documents you must be a registered member of Climate Risk Database,
and you must be signed in. In case you would like the CRD Data managers’ team to upload the documents,
please submit the documents to them with relevant metadata *(see point 5 below)*.

1.	Navigate to **Resources → Document** in the top navigation bar.
2.	Click **Upload Documents** from the top-right corner.
3.	Choose the file you want to upload, and give it a title. If the document is attached to a dataset, choose the dataset from the drop-down menu. Set the permissions for the dataset (this can be done later as well).
4.	Click **Upload**.
5.	Fill in the metadata for the dataset. Note that not all of the metadata fields are relevant for all documents. Fill in at least the Title, Abstract, Keywords, Date, License, Language and Purpose.
6.	Click Update when you are finished.
7.	Check that everything looks good on the document’s page. If you want to edit the metadata, click **Edit Document → Wizard or Change Permissions** if you want to change the permissions of the document.


Quality control
^^^^^^^^^^^^^^^

Before the dataset can be published for the wider audience, the CRD Data managers’ team will quality check it and make sure the data meets CRD’s data quality requirements and standards. To read more about these, please see the section above **“Data quality standards”**.

The CRD Data managers’ team will use the following instructions to run a systematic quality control for the data. These quality control instructions are created to match the data quality requirements and standards discussed above. You as a data provider are also free to use these documents to guide your work.

-	`Quality control instructions (vector) <https://geonode.resilienceacademy.ac.tz/documents/154>`_
-	`Quality control instructions (raster) <https://geonode.resilienceacademy.ac.tz/documents/158>`_

In case of quality issues or further questions, the CRD Data managers’ team will contact you. Usually questions are related to metadata which needs additional information. When the quality check is done and the CRD Data managers’ team has approved your dataset, it will be published. You will be informed when the data is up and running and ready to be downloaded


Contacting
^^^^^^^^^^

Resilience Academy
******************

Contact Resilience Academy in general inquiries by emailing to "resilienceacademytz@gmail.com".

CRD Data managers
*****************

Contact the Climate Risk Database data management team in matters of discussing datasets that could be uploaded to CRD, the details of quality standards, or when other advice related to data is needed.
CRD Data managers’ team members can be found from **Community → Community groups → Data Managers → Click the group icon**.
Here you can see the CRD Data Managers and their contact information. Contact one or all of them via sending email. They are happy to help!


Training
^^^^^^^^

Open online learning courses
****************************

To learn more about Resilience Academy / CRD data curation protocols, to enhance data curation skills, to learn more about geospatial data management, complete this open-access Data curation skills learning module, developed by the Resilience Academy.
The course platform requires a Gmail-registration. 

- `Mini-module: Data curation skills <https://digicampus.fi/course/view.php?id=1041&section=1>`_


Resilience Academy has also developed eight geospatial data related online learning courses, open for everyone. The courses are aimed for university students, but also experts in the field and they contain useful content for everyone working with geospatial data.
Find descriptions and links for all courses from `Resilience Academy website: <https://resilienceacademy.ac.tz/learning-resources/>`_ .
Course platform requires a Gmail-registration. Relevant content for data providers are for example on these courses:

- `Module 2: Geospatial data quality & management <https://digicampus.fi/course/view.php?id=493>`_
- `Module 3: Geospatial data visualisation <https://digicampus.fi/course/view.php?id=948>`_
- `Module 6: Community mapping for improved resilience planning <https://digicampus.fi/course/view.php?id=1014>`_

Tool instructions
*****************

A list of useful tools for geospatial data management can be found in the CRD, just navigate to **Resources → Tools**.
The Resilience Academy has created instructions for using these tools and they can be downloaded via the CRD as well.

Events and trainings
********************

Resilience Academy has hosted a number of events to train geospatial experts in data management related issues.
Some of these events has been recorded and the recordings can be found from the Resilience Academy YouTube-channel, under the playlist `Data quality, data management, data sharing online training <https://youtube.com/playlist?list=PLHZ-OHNG6he6qXleatlOaXotKK4N_xo-5>`_. 

Resilience Academy might host open training sessions for all in the future as well.
Keep an eye on the Resilience Academy’s social media channels, such as Twitter (`@Tanzania_RA <https://twitter.com/Tanzania_RA>`_) to hear more about them.
