
<!-- ## Micro Meta App -->

**_Micro Meta App_ is an open, easy to use, and powerful software platform to capture and manage Microscopy metadata on the basis of the [4DN-BINA extension](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-00) of the [OME data model](https://docs.openmicroscopy.org/ome-model/6.1.1/developers/model-overview.html) which is published on Arxiv.org [here](https://arxiv.org/abs/1910.11370).**

----

## The current version is stable beta v0.46.1-b1-0!

This is the first stable *beta* release and is available as follows:

### Application
* The Javascript [Electron](https://www.electronjs.org/) desktop application can be downlowaded [here](https://github.com/WU-BIMAC/MicroMetaApp-Electron/releases/tag/0.46.1-b1-0) 

### Source code
* Javascript [React](https://reactjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-React)
* Javascript [Electron-wrapped](https://www.electronjs.org/) implementation is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Electron)
* Prototype [OMERO](https://www.openmicroscopy.org/omero/scientists/) plugin is [available here](https://github.com/WU-BIMAC/MicroMetaApp-Omero)

<!-- See the [changelog]() for more details. -->

In addition to a polished Manage Instrument component and the implementation of [v2.00](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-00) of the 4DN-BINA-OME Microscopy Metadata model, this version introduces the Manage Settings component of the dataflow. 
In this component, the user can select a previously created Microscoe.json file, an image that was acquired using the selected Microscope, import available Microscopy Metadata from the file header using Bio-Formats, collect missing Image Acquisition Settings, and create a specific Settings.json file.


**Highlights include:**
* Updated data model including several new hardware components ([link](https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v02-00))
* Manage Settings component of the application
* Several bug fixes ([link](https://github.com/WU-BIMAC/MicroMetaApp-React/issues))

**Find the full documentation [here](https://micrometaapp-docs.readthedocs.io/en/latest/index.html)**

## Coming soon!

**Highlights!!**
The next version will include several new features including automated Material and Methods writing, facilitated import of vendor information and a better integration with the OMERO server.
Stay tuned!

> **Important!** It is not recommended to mix different version of Micro Meta App for working on Microcope files. If you started a project in a previous version, it is probably best to continue with that version - or even better start again with the latest version.

![Micro Meta App screenshots]({{site.baseurl}}/images/Micro-Meta App_composite screenshot.png){: .center-image }

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
