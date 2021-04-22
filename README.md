
<!-- ## Micro Meta App -->

**_Micro Meta App_ is an open, easy to use, and powerful software platform to capture and manage Microscopy Metadata on the basis of the [4DN-BINA extension](https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-01) of the [OME data model](https://docs.openmicroscopy.org/ome-model/6.1.1/developers/model-overview.html) which is published on Arxiv.org [here](https://arxiv.org/abs/1910.11370).**

----
![Micro Meta App screenshots]({{site.baseurl}}/images/Micro-Meta App_composite screenshot.png){: .center-image }


## The current version is stable beta v1.0.0-b1-1!

This is the latest stable *beta* release and is available as follows:

### Application
* The latest version of the Javascript [Electron](https://www.electronjs.org/) desktop application can be downlowaded [here](https://github.com/WU-BIMAC/MicroMetaApp-Electron/releases/latest) 

### Source code
* Javascript [React](https://reactjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-React)
* Javascript [Electron-wrapped](https://www.electronjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Electron)
* Prototype [OMERO](https://www.openmicroscopy.org/omero/scientists/) plugin is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Omero)

<!-- See the [changelog]() for more details. -->

> **Important!** In order to get started please follow the step-by-step instructions available [here](https://micrometaapp-docs.readthedocs.io/en/latest/index.html). In addition a full complement of [**video tutorials**](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/VideoTutorials.html) are also available!


### What can you do with Micro-Meta App?
With this version of the Micro-Meta App you can:

1) Use the [**Manage Instrument**](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/ManageInstrument.html) of the App to document the Hardware Specifications of **_transmitted light, epifluorescence, structured-light and TIRF light microscopes_** based on the **Core and Basic extension** of the [**v2.0 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-01) Microscopy Metadata model.

2) Use the [**Manage Settings**](https://micrometaapp-docs.readthedocs.io/en/latest/docs/tutorials/ManageSettings.html) component of the App to document the Image Acquisition Settings that were used to collect a specific image dataset.  In this section the user selects a previously created Microscoe.json file, an image that was acquired using the selected Microscope, import available Microscopy Metadata from the file header using Bio-Formats, collect missing Image Acquisition Settings and create a specific Settings.json file.

**Highlights include:**
* Updated data model including several new hardware components descrbed in the **Core and Basic extension** of the [**v2.00 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-00) Microscopy Metadata model.
* Manage Settings component of the application to import image metadata from file headers using Bio-Formats.
* Several bug fixes ([link](https://github.com/WU-BIMAC/MicroMetaApp-React/issues))
> **Important!** It is not recommended to mix different version of Micro Meta App for working on Microcope or Settings files. 
If you started a project using in a previous version of the App please first **save your file with the latest version** and then proceed with collecting image acquisiton settings. 

> **Important!** If you started your project with an **alpha version of the app** please let us know and we will help you with the transition.


## Coming soon!

The next version will include several new features including:

* Full implementatino of the Confocal/Advanced extension of the [**v2.0 of the 4DN-BINA-OME**](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-01) Microscopy Metadata model, which will allow to document **_Confocal and other Super-Resolution Miscoroscppy experiments_**.
* Automated Material and Methods writing through integration with MethodsJ2

## Future directions! 

* Facilitated import of vendor information and a better integration with the OMERO server.
Stay tuned!

----
## Other news

### June 2020: Micro Meta App featured on Medium!
A Chan Zuckerberg Initiative Medium article featuring the work of Caterina Strambio De Castillia and developemnt of Micro Meta App is available ([here](https://medium.com/@cziscience/5-imaging-scientists-share-insights-1ece553e9da3))!

### May 2020: Micro Meta App presented at the OME Community Forum!
The talk entitled "Adaptable Community Standards and Intuitive Metadata Collection Tools for Quantitative Microscopy" in which Caterina Strambio De Castillia presented the Micro Meta App at the [2020 OME Community Meeting](https://www.openmicroscopy.org/events/ome-community-meeting-2020/) is available [here](https://www.openmicroscopy.org/events/ome-community-meeting-2020/day2/).

----
**Please remember to cite Micro Meta App if you use it in your work!**

_Micro Meta App_ is produced at the <a href="https://www.umassmed.edu/pmm/">University of Massachusetts Medical School</a>.

The software is developed in collaboration with the <a href="http://dcic.4dnucleome.org/">4D Nucleome (4DN) Data Integration and Coordination Center</a>, as part of research projects funded by the <a href="https://commonfund.nih.gov/4DNucleome">NIH funded 4DN program</a>.
