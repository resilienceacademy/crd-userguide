===============
submitting-data
===============

If you have geospatial data that would be great for sharing in the Climate Risk Database, kindly contact the CRD Data managers’ team first.
Agree how you will submit the datasets: via sending the files to the CRD Data managers’ team, or by uploading them directly to the Climate Risk Database.
In case of uploading data yourself requires registration and updating your profile information. See instructions for registering from the section above.
If you would prefer the CRD Data managers’ team to upload the data, that is also possible.

Thank you for contributing to our community by providing your data to the Climate Risk Database!

Upload layer
^^^^^^^^^^^^

Download visual instructions: Upload layers to CRD.

1.	Click Layers in the top navigation bar, and then click Upload layers from the top-right corner.
2.	Follow the instructions of the upload page. Files needed for vector datasets in Shapefile format are: .shp .shx .dbf .prj. File needed for raster datasets in TIFF format is: .tif.
3.	Click Upload files and wait until they have been successfully loaded.
4.	Change the permission settings, if relevant. The permissions can be changed afterwards, too.
5.	Click Edit metadata. See the next section.

Edit metadata
^^^^^^^^^^^^^

Download visual instructions: `Instruction: CRD Metadata Wizard. <https://geonode.resilienceacademy.ac.tz/documents/138>`_

1.	Fill in all metadata fields of the Metadata Wizard that opens up. Use the visual instructions as a guideline,
if needed. Don’t forget to fill in attribute metadata for vector layers!
2.	When you are ready, click Update. You are redirected to the layer page.
3.	If you want to edit the metadata later, click Editing tools from the right-hand side menu, and choose Wizard under the Metadata section.
4.	If you want to edit layer permissions, scroll the page down and click Change Layer Permission from the right-hand side menu.

Upload style
^^^^^^^^^^^^

Custom styles can (and should!) be uploaded to CRD to override the default styling that is created automatically when a layer is uploaded to CRD.
The style must be a SLD (Styled Layer Descriptor) file, which can be exported from QGIS.
Find instructions for creating a SLD file from the document `Instruction: Creating SLD in QGIS. <https://geonode.resilienceacademy.ac.tz/documents/135>`_
From this document you also find visual instructions of how to upload the SLD file to CRD.

1.	Go to the layer page of that specific layer of which you want to style with the SLD file you have created. Note: you must be signed in, and have permissions to edit the layer in order to edit its style!
2.	Click Editing Tools. Choose Upload from the Styles section of the pop-up-window.
3.	Drag-and-drop or choose the SLD file and click Upload files.
4.	Click Layer info to view the new style in action!
5.	If you encounter any problems, please contact the CRD Data managers. Sometimes the GeoNode-platform can be a bit tricky when updating styles.

Upload layer through command line
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Download instructions: `Upload data using command line. <https://geonode.resilienceacademy.ac.tz/documents/132>`_
You can upload data to CRD through the command line. This is useful, for example, when

- The dataset is simply too big to be uploaded through a web interface,
- You would like to import some data from the mass storage programmatically,
- You would like to import some tables from a DataBase or
- You need to process the data first and, maybe, transform it to another format.

Upload documents
^^^^^^^^^^^^^^^^

In case you have documents, such as reports, additional information or map images you would like to attach to your dataset,
they can be also uploaded to the Climate Risk Database and linked to your data. To upload documents you must be a registered member of Climate Risk Database,
and you must be signed in. In case you would like the CRD Data managers’ team to upload the documents,
please submit the documents to them with relevant metadata (see point 5 below).

1.	Navigate to Resources → Document in the top navigation bar.
2.	Click Upload Documents from the top-right corner.
3.	Choose the file you want to upload, and give it a title. If the document is attached to a dataset, choose the dataset from the drop-down menu. Set the permissions for the dataset (this can be done later as well).
4.	Click Upload.
5.	Fill in the metadata for the dataset. Note that not all of the metadata fields are relevant for all documents. Fill in at least the Title, Abstract, Keywords, Date, License, Language and Purpose.
6.	Click Update when you are finished.
7.	Check that everything looks good on the document’s page. If you want to edit the metadata, click Edit Document → Wizard or Change Permissions if you want to change the permissions of the document.
