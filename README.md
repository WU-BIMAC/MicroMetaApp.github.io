
<!-- ## Micro Meta App -->

**_Micro Meta App_ is an open, easy to use, and powerful software platform that provides an intuitive visual guide to capture and manage Microscopy Metadata on the basis of the [4DN-BINA extension](https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-01) of the [OME data model](https://docs.openmicroscopy.org/ome-model/6.1.1/developers/model-overview.html)**

> **News!** Micro-Meta App was developed as part of a global community initiative that led to multiple publications features on a recent Nature Methods FOCUS ISSUE entitled **[Reporting and reproducibility in microscopy](https://www.nature.com/collections/djiciihhjh)**. 

> For a complete description of Micro-Meta App consult our recent publications on **[Nature Methods](https://doi.org/10.1038/s41592-021-01315-z)** and **[BioRxiv.org](https://doi.org/10.1101/2021.05.31.446382)**.

> **Important!** In order to get started please follow these **[step-by-step instructions](https://micrometaapp-docs.readthedocs.io/en/latest/index.html)** and **[video tutorials](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/VideoTutorials.html)**

> **Note!** If you intend to use Micro-Meta App **on MacOS you might encounter difficulties un-zipping and launching the MacOS Zip**. To address these issues please follow the **instructions specified in this [VIDEO](https://vimeo.com/529609242)**

----
![Micro Meta App screenshots]({{site.baseurl}}/images/Micro-Meta App_composite screenshot.png){: .center-image }

## What can you do with Micro-Meta App?
With Micro-Meta App you can:

1) Use the [**Manage Instrument**](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/ManageInstrument.html) of the App to document the Hardware Specifications of **_transmitted light, epifluorescence, structured-light and TIRF light microscopes_** based on the **Core and Basic extension** of the [**v2.0 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-01) Microscopy Metadata model.

2) Use the [**Manage Settings**](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/ManageSettings.html) component of the App to document the Image Acquisition Settings that were used to collect a specific image dataset.  In this section the user selects a previously created Microscoe.json file, an image that was acquired using the selected Microscope, import available Microscopy Metadata from the file header using Bio-Formats, collect missing Image Acquisition Settings and create a specific Settings.json file.

## The current version is stable beta 1.3.3-b1-1!

This is the latest stable *beta* release and is available as follows:

### Application
* The latest version of the Javascript [Electron](https://www.electronjs.org/) desktop application can be downlowaded [here](https://github.com/WU-BIMAC/MicroMetaApp-Electron/releases/latest) 

### Source code
* Javascript [React](https://reactjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-React)
* Javascript [Electron-wrapped](https://www.electronjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Electron)
* Prototype [OMERO](https://www.openmicroscopy.org/omero/scientists/) plugin is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Omero)

### Major changes

<!-- See the [changelog]() for more details. -->

**Highlights include:**
* Updated data model including several new hardware components descrbed in the **Core and Basic extension** of the [**v2.00 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-00) Microscopy Metadata model.
* Manage Settings component of the application to import image metadata from file headers using Bio-Formats.
* Improved GUI usability
* Several bug fixes ([link](https://github.com/WU-BIMAC/MicroMetaApp-React/issues))

> **Important!** It is not recommended to mix different versions of Micro Meta App for working on Microcope or Settings files. 
If you started a project using in a previous version of the App please first **save your file with the latest version** and then proceed with collecting image acquisiton settings. 

> **Important!** If you started your project with an **alpha version of the app** please let us know and we will help you with the transition.

## Example datasets

> **AVAILABLE EXAMPLE FILES** Publicly available example files and a tutorial video for the use of Micro-Meta App are available [here](https://doi.org/10.5281/zenodo.4891883) from Zenodo.org.

## Want to learn more?

> For a thorought description of the 4DN-BINA-OME (NBO) Microscopy Metadata Specifications consult our recently posted manuscript **"Towards community-driven metadata standards for light microscopy: tiered specifications extending the OME model"**, which is available on BioRxiv.org [here](https://www.biorxiv.org/node/1919775.external-links.html).

> If you are a newby and you want to learn more about the importance of metadata and quality control to ensure full reproducibility, quality and scientific value in light microscopy, please take a look at our recently posted overview manuscript entitled **"A perspective on Microscopy Metadata: data provenance and quality control"**, which is available on ArXiv.org [here](https://arxiv.org/abs/1910.11370).

## Coming soon!

The next version will include several new features including:

* Full implementatino of the Confocal/Advanced extension of the [**v2.0 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-01) Microscopy Metadata model, which will allow to document **_Confocal and other Super-Resolution Miscoroscppy experiments_**.
* More intuitive GUI
* Initial integration of the of the Calibration/Performance extension of the [**v2.0 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-01) Microscopy Metadata model, which will allow to document **_Intensity Calibration, Optical Calibratin and Mechanical Calibration_**.
* Automated Material and Methods writing through integration with MethodsJ2

## Future directions! 

* Facilitated import of vendor information and a better integration with the OMERO server.
Stay tuned!

----
## Other news!

### June 2021: Micro-Meta App workshops featured at the 2021 ELMI Meeting
A series of [three workshops](https://www.elmi2021.org/sponsors/workshop-schedule.html)on the use of Micro-Meta App were presented at the [2021 ELMI Meeting](https://www.elmi2021.org/)!

### June 2021: Micro-Meta App flash-talk and demo presented at the 2021 OME Community Meeting
A [flash-talk](https://www.youtube.com/watch?v=LO2-5U_9s6w&list=PL-oOCWFUMH51ACy8QhTYc4ppaoICJQDU_&index=2) and a [live-demo](https://www.openmicroscopy.org/events/ome-community-meeting-2021/day1/) on the use of Micro-Meta App were presented at the [2021 OME Community Meeting](https://www.openmicroscopy.org/events/ome-community-meeting-2021/)!

### June 2020: Micro Meta App featured on Medium!
A Chan Zuckerberg Initiative Medium article featuring the work of Caterina Strambio De Castillia and developemnt of Micro Meta App is available ([here](https://medium.com/@cziscience/5-imaging-scientists-share-insights-1ece553e9da3))!

### May 2020: Micro Meta App presented at the OME Community Forum!
The talk entitled "Adaptable Community Standards and Intuitive Metadata Collection Tools for Quantitative Microscopy" in which Caterina Strambio De Castillia presented the Micro Meta App at the [2020 OME Community Meeting](https://www.openmicroscopy.org/events/ome-community-meeting-2020/) is available [here](https://www.openmicroscopy.org/events/ome-community-meeting-2020/day2/).

----
## Credits!

**Please remember to cite Micro Meta App if you use it in your work!**

_Micro Meta App_ is produced at the <a href="https://www.umassmed.edu/pmm/">University of Massachusetts Medical School</a>.

The software is developed in collaboration with the <a href="http://dcic.4dnucleome.org/">4D Nucleome (4DN) Data Integration and Coordination Center</a>, as part of research projects funded by the <a href="https://commonfund.nih.gov/4DNucleome">NIH funded 4DN program</a>.
