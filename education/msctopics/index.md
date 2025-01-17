---
layout: page
title:  Potential MSc topics
permalink: /education/msctopics/
---

- - -

* Table of Content
{:toc}

- - -

## Multidisciplinary graduation BK studio: City of the Future

![](img/cityfuture.jpg){:width="600px"}

City of the Future is a multidisciplinary graduation studio focusing on the central question: how to design and develop in an integrated way a transformation area into an attractive future urban environment? It is motivated by urgent social / local issues varying among housing demand, social inclusiveness, new economy, climate adaptation, and the transitions in the areas of energy, mobility, circularity, automation and digitization.

Students of different MSc tracks (thus Geomatics students are welcome) will be dealing with various matters (e.g. spatial, policy, energy, societal) sharing insights and perspectives about the multifaceted future challenges of urban environments.

[--> Webpage of the project](https://www.tudelft.nl/en/education/programmes/masters/architecture-urbanism-and-building-sciences/msc-architecture-urbanism-and-building-sciences/master-tracks/architecture/programme/studios/city-of-the-future/)

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/)


## Improving automatic meshing for buildings

![](img/MeshConceptCFD.png){:width="600px"}
Computational fluid dynamic simulations require detailed meshes that can represent obstacles features accurately. In numerical simulations, the quality of the mesh can draw the line between good and poor results. Nowadays, mesh tools are general and they are not necessarily optimised for meshing entire cities, requiring large time investments to design and improve the mesh quality.

This MSc project focuses on developing an algorithm that create the mesh automatically around buildings by specifying a limited number of parameters that define the grid cells sizes. The mesh will be generated from a top-up perspective, initially extruding the geometrical edges to create cell layers close to the buildings. The approach will be first tested in 2D single and multiple building geometries.

Knowledge of programming in python is required.
Following elective course GEO5013 is an advantage.

**Contact:** [Clara Garcia-Sanchez](mailto:C.Garcia-Sanchez@tudelft.nl) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -


## From GIS to 3D flow simulations in urban environments

![](img/WindFlowOklahoma.png){:width="600px"}

Changes in wind can largely affect the wind pattern within cities, leading to zones with high wind speeds and areas with flow stagnation. Wind distributions in urban area depend on heterogeneous city layouts and change with new constructions. A priori knowledge of winds within a certain urban area can help to develop strategies that improve pedestrian wind comfort, help urban designs and ameliorate urban air quality. However, the chain process from the use of GIS data, to the construction of a 3D city model enriched with diverse semantics that can be used in CFD simulations is complex.  

The present MSc project goal is to start from GIS databases to generate a water tight model with different semantics, to evaluate and to design a guideline that includes the model information required to perform wind flow simulations. The test case will be built around TU Delft campus, including semantics that differentiate between buildings, green and water areas.

Knowledge of programming in python is required. 
Following elective course GEO5013 is recommended.

**Contact:** [Clara Garcia-Sanchez](mailto:C.Garcia-Sanchez@tudelft.nl)

- - -


## Guesstimation of the height of all USA buildings

![](img/zurich.png){:width="600px"}

The project [Open City Model](https://github.com/opencitymodel/opencitymodel) by [BuildZero.Org](http://buildzero.org) provides a height for each of the 125,192,184 buildings in the USA.
They took the [footprints from Microsoft](https://github.com/Microsoft/USBuildingFootprints) and estimated their heights.
It can be seen that several buildings are at the same height, and the methodology they used is not documented.

The aim of this project is to develop a methodology to improve their results, in particular using machine learning and the [results we obtained for the Netherlands](https://3d.bk.tudelft.nl/hledoux/pdfs/17_ceus_3dnoelevation.pdf).


**Contact:** [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -



## Automatic reconstruction of historical 3D city models

![](img/delft_1600.jpg){:width="500px"}


Several cities are currently attempting to reconstruct historial 3D models of their cities, see for instance [Rotterdam before/during/after WWII](https://www.stadsarchief.rotterdam.nl/rotterdam3d).
As far I know, all the efforts have been made manually, by hiring several students to draw buildings from historical photos.

The aim of the project is to investigate how historical 3D models of cities can be *automatically* reconstructed.
The idea is to use [2D topographic maps](https://www.topotijdreis.nl) and other sources (eg cadastre) and infer the height of buidings, [maybe with machine learning](https://3d.bk.tudelft.nl/hledoux/pdfs/17_ceus_3dnoelevation.pdf).

**Contact:** [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Modelling tree topology effects on wind

![](img/FlowAroundTrees.png)

Urban landscapes incorporate vegetation elements that serve for different purposes. In open spaces trees can be used to ameliorate air quality, while in other locations they can help to mitigate heat island effects or to improve pedestrian wind comfort. Flow simulations in urban canopies usually oversight resolving tree structures. However, trees have been shown to always affect the wind flow, in some cases with non-negligible impacts.

In this MSc thesis we will simulate explicitly the wind around diverse tree topologies. The results will be compared with standard approaches that approximate the drag imposed by the tree on the wind flow. The study goal is twofold: 1) we will analyze the effect of different tree shapes, and their impact on the flow structure; 2) we will evaluate the performance of  traditional drag approaches and explore potential improvements.

Knowledge of programming in python is highly desirable.

**Contact:** [Clara Garcia-Sanchez](mailto:C.Garcia-Sanchez@tudelft.nl)

## Calculating Street Widths

![](img/RoadWidthMScTopicFull.png){:width="700px"}

This project will be in partnership with researchers in the department of Urbanism examining the relationship between street design and automated vehicles. As part of this thesis you will examine ways to automatically calculate the width of roads (this is considered the total width including pedestrian walkways and cycling lanes). Part of this process will require you to find ways to automatically classify intersection areas as well as develop methods to automatically partition road segments. 

Knowledge of a programming language (preferably Python) is highly recommended.

**Contact:** [Anna Labetski](mailto:a.labetski@tudelft.nl)

## Versioning of 3D spatial data

[![Versioning comic](img/version.jpg)](https://www.geeksaresexy.net/2018/08/26/versioning-important-comic/)

This topic is about the investigation of versioning mechanisms for 3D spatial data, with an emphasis on city models and datasets produced by municipalities. The main aim of the project is to implement existing versioning solutions across different 3D exchange formats and evaluate them. It is, also, about proposing new methods to handle the issue.

As part of the thesis you will have to identify specific use cases, such as the updating of existing 3D city models with new data in a way that ensures that revisions are maintained. You will have to communicate with stakeholders, such as municipalities or organisations that deal with multiple iterations of 3D data.

Knowledge of programming in Python is required.

**Contact:** [Stelios Vitalis](mailto:s.vitalis@tudelft.nl)

## Handling massive 3Di datasets in 3D City Database

The project is about exploring 3DcityDB for managing massive input and output data for [3Di](http://www.3di.nu).
3Di Water management is a web based application for detailed hydraulic computations using high resolution datasets.
The aim is to: (1) create a data warehouse (i.e. a central repository) for 3D datasets used in hydraulic modelling by integrating 3DCityDB with 3Di, (2) use the integrated 3D city and 3Di area models for different applications such as visualization.
 
The project is in collaboration with Nelen en Schuurmans, Utrecht.
Prior knowledge of databases and programming in Python or C/C++ is required.

**Contact:** [Jonas van Schrojenstein](mailto:jonas.vanschrojenstein@nelen-schuurmans.nl) and [Kavisha](http://3d.bk.tudelft.nl/kavisha)


## Sensor standards overview

Create an overview of the standards landscape related to sensors and observations that explains the scope of each of these standards, their application to practical use cases, impact on Spatial Data Infrastructures and mechanisms by which they may be combined. 
Are these standards, for example, overlapping in their application domain, or are they complementary? 
Are there gaps that need to be addressed? 

Different standards organizations are working on standards related to sensors and the measurements they produce: [ISO](https://www.iso.org/), the [OGC](http://www.opengeospatial.org), the [W3C](https://www.w3.org), the [IETF](https://www.ietf.org), and countless non-standardized community or platform-specific protocols and formats. These standards range from mature to early development stage, and from low level communication IoT protocols to ontologies describing sensor semantics.

This project is done in cooperation with [Geonovum](https://www.geonovum.nl/), the govermental organisation responsible for developing geo-standards.

**Contact:** [Linda van den Brink](l.vandenbrink@geonovum.nl) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)

## Moving objects on the Web

Describing trajectories and paths of moving objects requires a different approach to describing static ones. Research how best to support Web applications that generate or use data concerning moving objects. Use cases include transportation, tourism, migration, location-based services, travel blogs and wildlife tracking. There is an OGC standard for [Moving features](http://www.opengeospatial.org/standards/movingfeatures), but the XML encoding is too complex and verbose - not lightweight enough to conduct, for example, enhanced (near) real-time operations involving moving objects, via the Web.


This project is done in cooperation with [Geonovum](https://www.geonovum.nl/), the govermental organisation responsible for developing geo-standards.

**Contact:** [Linda van den Brink](l.vandenbrink@geonovum.nl) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)


## Develop a framework for sharing sensor data

![](img/slimmestad-alg.png)

The ISO/OGC standard [Observations and Measurements](http://www.opengeospatial.org/standards/om) (O&M) provides a model for the exchange of information about sensor observations. 
It’s a rather concise and abstract model and it has always raised questions about how to create a profile in order to use it in practice. 
A framework for this is needed.

Creating a profile involves the definition of an information model that extends the [abstract O&M model](http://portal.opengeospatial.org/files/?artifact_id=41579). 
O&M is defined in UML. 
In addition, there is an XML-based exchange format, the [O&M GML encoding](http://portal.opengeospatial.org/files/?artifact_id=41510), a [JSON implementation](https://portal.opengeospatial.org/files/64910), and a linked data based ontology called [Semantic Sensor Network ontology](https://www.w3.org/TR/vocab-ssn/). 
All of these may play a role in the framework, but the central question of this MSc topic is how to create a working O&M profile.

A practical case for the study could be the [Base Registry Underground](https://www.basisregistratieondergrond.nl), which will contain a lot of sensor data such as groundwater measurements and soil quality observations. 

This project is done in cooperation with [Geonovum](https://www.geonovum.nl/), the govermental organisation responsible for developing geo-standards.

**Contact:** [Linda van den Brink](l.vandenbrink@geonovum.nl) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)


- - -

## Linked data: Extend CityJSON with machine-readable semantics

![](img/ld.jpg)

[CityJSON](http://www.cityjson.org) is based on JavaScript Object Notation, a lightweight data-interchange format primarily used on the Web. 
However, JSON is just syntax, without any machine-readable knowledge about the meaning (semantics) of the data. Currently, the only way to figure out what the data in a CityJSON file means (e.g. what is a building?) is to read the [CityGML](https://www.citygml.org) specification (assuming you know where to find it), something only humans can do. 

The aim of this MSc project is to find out how to encode the meaning of CityJSON files in a machine-readable way, directly embedded or linked in the JSON document, and to discover what benefits (or disadvantages) this would bring. This could be done by creating a vocabulary which describes the keys that can be used in CityJSON, basically a CityGML vocabulary or (simple) ontology; and using [JSON-LD](https://json-ld.org/) to map the keys in CityJSON to this vocabulary. 

The "LD" in JSON-LD stands for "[linked data](https://www.w3.org/wiki/LinkedData)". 
Once CityJSON-LD is created, we effectively have a lightweight linked data format for CityGML. 
But this is not a benefit in itself. 
The project would go on to explore the advantages and disadvantages of working with CityJSON-LD, as opposed to just CityJSON.

This project is done in cooperation with [Geonovum](https://www.geonovum.nl/), the govermental organisation responsible for developing geo-standards.

**Contact:** [Linda van den Brink](l.vandenbrink@geonovum.nl) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)

- - -


## 3D digital urban regulations to use GeoBIM for building permission checks

The automation of urban regulation checks for the planning use case requires the urban regulations to be archived in a digital and spatial (3D) format.
This project aims at the definition of an effective way to store those regulations digitally and spatially, for their use in checking urban regulations compliancy of new buildings through GeoBIM integrated information. The studied solution could start from extending [CityGML](https://www.citygmlwiki.org), employing [INSPIRE](https://inspire.ec.europa.eu/data-model/approved/r4618-ir/html/) data model, or other available standards.
In collaboration with [EuroSDR](http://www.eurosdr.net) and [Kadaster](https://www.kadaster.nl)

**Contact:** [Francesca Noardo](https://3d.bk.tudelft.nl/fnoardo/), [Ken Arroyo Ohori](http://tudelft.nl/kenohori) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)

- - -
## Extracting information from BIM models for GeoBIM building permission use case

The integration of geoinformation with BIM information can be very effective for automatically checking urban regulations. However, not all the information which is present in BIM is necessary for regulations checking. Moreover, BIMs designed in actual practice sometimes have different characteristics than the ones expected by academy. At the same time too much detail hinders data processing and designers are reluctant to share all the details about their designs.
In this study, the aim is to understand which information is needed for checking some critical regulation where GeoBIM information can be useful, as it could be obtained from a sample of more complex BIMs modelled by designers and practitioners, and develop a tool to filter, derive/extract and generalise the required information to be used for the integration with a 3D city model and the checks of the selected regulations.
In collaboration with [EuroSDR](http://www.eurosdr.net) and [Kadaster](https://www.kadaster.nl)

**Contact:** [Francesca Noardo](https://3d.bk.tudelft.nl/fnoardo/), [Ken Arroyo Ohori](http://tudelft.nl/kenohori) and [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter)

- - -

## Flat roofs

![](img/flatroofs.png) 

Several applications require information about the geometry of a building's roof, particularly whether it is flat or not. In theory this information can be derived from a point cloud. But deciding if a roof is flat is not always straightforward, and different domains have different definitions for *flat*. Think about calculating water runoff, or finding roofs with a potential terraces. Thus better if we can say something about the area of the flat surface in a roof, if there is any.

The aim of this MSc project is to develop a method for computing the area of the flat surface in a roof from a point cloud, and identify whether the roof has structure that consists of multiple levels. Additionally, the work can be extended to modelling multi-level roofs (aka. [LoD1.3](http://doi.org/10.1016/j.compenvurbsys.2016.04.005)). Ultimately, to goal is to incorporate such a method in [3dfier](https://github.com/tudelft3d/3dfier) and it should therefore be computationally efficient.

Knowledge of a programming language like python is required. You should also be comfortable with, or at least have the strong desire to learn some statistics.

The topic is done in collaboration with Rijkswaterstaat.

**Contact:** [Balázs Dukai](https://3d.bk.tudelft.nl/bdukai/) and [Ravi Peters](https://3d.bk.tudelft.nl/rypeters/)

- - -


## Develop a framework to handle massive CityJSON files

![](img/cityjson.jpg){:width="200px"}

As an alternative format for the [CityGML](https://www.citygml.org) data model, we have recently developed [CityJSON](http://www.cityjson.org), it uses [JavaScript Object Notation](http://json.org).
The aim of CityJSON is to offer an alternative to the GML encoding of CityGML, which can be verbose and complex (and thus rather frustrating to work with).
CityJSON aims at being easy-to-use, both for reading datasets, and for creating them.
It was designed with programmers in mind, so that tools and APIs supporting it can be quickly built.

While a CityJSON file is [about 6X compacter](https://github.com/tudelft3d/cityjson/wiki/Compression-factor-for-a-few-open-CityGML-datasets) than the equivalent CityGML file, very large areas (like the [whole of city of Berlin](https://www.businesslocationcenter.de/en/downloadportal)) are still problematic.

The aim of this MSc project is to design a framework to deal with such massive CityJSON files.
The potential solution is to design a tiling scheme, and find a way to make it work with a web-based viewer, eg [Cesium](https://cesiumjs.org/) or [three.js](https://threejs.org/).
There is an emerging standard about the tiling of 3D GIS datasets ([3D Tiles](https://github.com/AnalyticalGraphicsInc/3d-tiles)), which should probably be reused/modified.

Knowledge of Python and of web technologies (javascript; although that can be learned with the project) is enough.

**Contact:** [Hugo Ledoux](http://tudelft.nl/hledoux) and [Stelios Vitalis](mailto:s.vitalis@tudelft.nl)

- - -

## Develop a Blender addon with a complete set of tools for CityJSON files

![](img/blender_cityjson.png){:width="500px"}

[Blender](https://www.blender.org/) is a 3D modelling tool with the ability to be extended through the Python programming language. 
Through the [BlenderGIS](https://github.com/domlysz/BlenderGIS) addon it can incorporate GIS functionality for the manipulation of 3D geospatial datasets.

The aim of this MSc project is to create an addon that adds the ability in Blender to import/export and manipulate all aspects of a 3D city model in [CityJSON format](http://www.cityjson.org). 
The addon should be able to:

* Import/export CityJSON files
* Incorporate the tools of [cjio](https://github.com/tudelft3d/cjio) for validation and reporting of the data
* Allow editing of the city object semantic information, including geometric constraints according to [ISO 19107](http://geovalidation.bk.tudelft.nl/val3dity/docs/definitions/)
* Provide searching functionality for the city objects

Knowledge of Python is enough.

**Contact:** [Stelios Vitalis](mailto:s.vitalis@tudelft.nl) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Extraction of characteristics of buildings from aerial imagery

![](img/readaar.jpg){:width="350px"}

This project is done in cooperation with [Readar](http://www.readar.com).
Readaar was founded in 2016 and extracts all kind of information from aerial imagery.
To do this they combine remote sensing with machine learning.

Readaar has already developed a method to generate point clouds and 3D building models from stereo imagery.
The next step is to translate this into useful insights like:

  - how many solar panels can we fit on the roof,
  - what is the roof type,
  - how many floors does the building have.

The focus of the student within this project will be on using the datasets to develop methods that extract (data mining) the insights that Readaar's customers want to have.

[More information is found there.](https://readar.com/jobs/internship-deep-learning-on-aerial-imagery/)

*Contact:* [Hugo Ledoux](http://tudelft.nl/hledoux) + [Sven Briels](mailto:svenbriels@readar.com)


- - -

## Interoperability between BIM IFC & BEM gbXML

![](img/ifc_gbxml.png){:width="400px"}

The aim of the project is to investigate the interoperability between two popular standards in the BIM (Building Information Modelling) and BEM (Building Energy Modelling) domains: [IFC](https://www.buildingsmart.org/about/what-is-openbim/ifc-introduction/) and [gbXML](http://www.gbxml.org). The goal is to compare and identify the schematic mapping between these two standards and develop a (Python/C++) prototype based on these mappings for data conversion. Real world gbXML datasets are to be generated for testing in gbXML energy simulations using tools such as EnergyPlus, Revit or IES.

Prior knowledge of programming in Python or C++ is required.

*Contact:* [Kavisha](http://3d.bk.tudelft.nl/kavisha), [Francesca Noardo](https://3d.bk.tudelft.nl/fnoardo/) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Handling massive 3D data using NoSQL databases

![](img/NOSQL.jpg){:width="400px"}

The project is about exploring NoSQL databases for storing massive 3D data. The main test dataset is the TIN generated from national elevation model of the Netherlands (AHN3) with a point density of over 10 points/m2. Several data structures have been proposed for the representation and storage of TINs in memory and in databases. A few of those data structures ([here](https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLI-B2/123/2016/)) are to be tested with the generated TIN models to account for their geometry, topology, storage, indexing, and loading times in a NoSQL database and compare the results with already available results of testing with Postgres/PostGIS database to analyse the performance of NoSql vs. SQL databases.

Prior knowledge of databases and programming in Python or C++ is required.

*Contact:* [Kavisha](http://3d.bk.tudelft.nl/kavisha) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Point cloud normal estimation based on the 3D medial axis transform

![](img/wrong_normal_orientation.png){:width="400px"}

Point clouds, unstructured collections of 3D points in space, are nowadays collected with different acquisition methods, eg photogrammetry and LiDAR.
While current point clouds are dense and offer an accurate representation of real-world objects and landscapes, they lack structure and semantics.

The aim of this project is to properly *orient* a point cloud, ie to find an approximation of the normal at each point; this normal should point outwards.
Surface normals are essential for different processing of a point cloud, eg visualisation, shadow analysis or segmentation.

"Standard" methods, eg [that function in PCL](http://pointclouds.org/documentation/tutorials/normal_estimation.php), usually find the nearest points of a given point, fit a plane, and choose between the 2 possible normals (up or down) based on a viewpoint.
The problem is that in practice, eg with the [AHN3 dataset](http://www.ahn.nl), we do not have that information.

The topic involved building on our work with the [3D medial-axis transform (MAT)](https://3d.bk.tudelft.nl/projects/3dsm/) and use the 3D MAT of a point cloud as a base to obtain high quality normals with a proper orientation.

It is possible to use Python for this project, although some knowledge of C++ would surely help.

**Contact:** [Ravi Peters](http://tudelft.nl/rypeters) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Improvements (trees, bridges, viaducs) to 3dfier

![](img/3dfier.png){:width="600px"}

We have developed a software, [3dfier](https://github.com/tudelft3d/3dfier), to automatically construct 3D city models from 2D GIS datasets (e.g. topographical datasets) and LiDAR/pointcloud datasets.
The software creates a 3D model by lifting every polygon to 3D, and the semantics of every polygon is used to perform the lifting.
That is, water polygons are extruded to horizontal polygons, buildings to LOD1 blocks, roads as smooth surfaces, etc. Every polygon is triangulated (constrained Delaunay triangulation) and the lifted polygons are "stitched" together so that one digital surface model (DSM) is constructed.
Our aim is to obtain one DSM that is error-free, i.e. no intersecting triangles, no holes (the surface is watertight), where buildings are integrated in the surface, etc.

The aim of this MSc project is to further develop some lacking features of 3dfier, it could be one of the following:

  1. adding 3D representation of trees by *iconisation*, ie by inserting a parametric template that has the general shape/dimension of a tree. This implies automatically finding this, and a good start is the methodology described in [this paper (Section 4.2)](https://infoscience.epfl.ch/record/206788/files/paper.pdf)
  2. adding bridges and other man-made structures (such as viaducs) by first modelling them with [Esri CityEngine](http://www.esri.com/software/cityengine) and then "stitching" them to the 3D model.

These topics can be done with Python as a post-processing of 3dfier.

**Contact:** [Hugo Ledoux](http://tudelft.nl/hledoux) and [Tom Commandeur](mailto:t.j.f.commandeur@tudelft.nl)


- - -

## 3D visualization of massive TINs

![](img/cesiumproject.jpg){:width="400px"}

Visualization is an important and complex issue in the context of 3D city models. The enormous amount of data to be fetched, the heterogeneity of data sources, and the complexity of rendering are only a few parts of this challenge. The project aims at investigating 3D tiling schemes for efficiently visualizing massive TINs using [Cesium](https://cesiumjs.org) 3D webglobe.
The knowledge of programming in C++ is required.

*Contact:* [Kavisha](http://3d.bk.tudelft.nl/kavisha) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## 3D Cadastre

![](img/3DCadastre.png){:width="700px"}

Since more than 15 years, lots of studies have been done on 3D Cadastre to register multilevel ownership in a transparent and proper way.
In 2016, we realised the first 3D cadastral situation [3D cadastral registration]( https://3d.bk.tudelft.nl/news/2016/03/21/3DKadaster.html) in the Netherlands.
But still research is needed to develop a solution for 3D cadastral registration that covers all issues. An MSc thesis could focus on one of them, such as how to validate a 3D cadastral plan that was created from a BIM model? Traditionally, a 2D cadastral boundary is checked by surveyors in the field. What are the requirements for 3D cadastral boundaries? How can they be generated accordingly? And how can they be validated? How can a BIM model serve as input for this? Another issue is about how to maintain and exchange 3D data about property boundaries? And how to go beyond the limited visualisation and navigation possibilities of 3D PDF?

*Contact:* [Jantien Stoter](http://3d.bk.tudelft.nl/jstoter) and [Hugo Ledoux](http://tudelft.nl/hledoux)

- - -

## Automatic generalisation of depth contours

![](img/bathycontours.png){:width="500px"}

For some years, we have been working on a novel method to automatically generate "good" depth-contours for hydrographic charts.
Our latest results, based on the [MSc thesis of Ravi Peters](http://repository.tudelft.nl/view/ir/uuid%3A5977a99b-0875-44b4-abe1-09288bf2aed1/) and published in that [paper](https://3d.bk.tudelft.nl/hledoux/pdfs/14_marinegeo.pdf), have been picked up by major companies who are implementing it.

The aim of the proposed project is to improve the results.
That is, we can at this moment generate smooth contours for most seabed types, but the generation is applied for the whole dataset and a human must decide when the results are okay.
The student would have to focus on automatically applying the algorithms only where they are needed and design methods to assess when sufficiently good results have been achieved.

The [code of the project](https://github.com/Ylannl/Surfonoi) is in C++, but probably possible to make do with Python.

**Contact:** [Hugo Ledoux](http://tudelft.nl/hledoux) and [Ravi Peters](http://tudelft.nl/rypeters)


- - -

## Snap rounding in a triangulation

![](img/triangulation.png){:width="500px"}

The most common way to do edge-matching or to clean small inconsistencies within and between datasets is to apply snapping (point-to-point or point-to-line).
However, simple snapping creates many problems, including topological changes and inconsistencies.
Snap rounding extends this method in order to give robustness guarantees, but current implementations, such as [the one in CGAL](http://doc.cgal.org/latest/Snap_rounding_2/index.html), are *extremely* slow.
Related to this, in the project [pprepair](https://github.com/tudelft3d/pprepair), we have previously used a constrained triangulation as a robust method to repair polygons and planar partitions.
Using this approach topological errors are automatically fixed.
We therefore believe that using a triangulation as a base structure is an intuitive and efficient way to optimize snap rounding, since we can perform simple snapping and recover from topological errors afterwards.

The existing prototype ([pprepair](https://github.com/tudelft3d/pprepair) that needs to be extended has been developed in C++, thus the knowledge of C++---or a strong desire to learn it---is necessary.

**Contact:** [Ken Arroyo Ohori](http://tudelft.nl/kenohori)

- - -

## Learning to Synthesize Detailed 3D Building Models

<img src="img/synthesis.png" style="width: 400px;"/>

LoD1 or LoD2 building models can be relatively easily generated from building footprints and point cloud data. However, such models lack meaningful geometric detailed façade structures (e.g., doors, windows, and balconies), making them unsuitable for real-world applications such as visualization and simulation. The goal of this MSc thesis is to develop an algorithm that can automatically synthesize semantically meaningful façade details onto the given coarse models. The resulted models will have a plausible style conforming to the images of real-world buildings.

**Required Skills**: 
Proficient in one programming language, either C/C++ or Python; experiences in mesh processing; willing to follow courses on machine learning (in particular Deep Learning) before or at the beginning of the project.

**Contact**: [Liangliang Nan](https://3d.bk.tudelft.nl/liangliang/)


- - -

## Outer Surface Extraction for Complex 3D Models

<img src="img/repair_urban_models.png" style="width: 800px;"/>

The number of 3D building models is explosively increasing. These models can be easily obtained by applying state-of-the-art modeling/reconstruction techniques, or by manual creation using various software packages. It is quite common to observe errors and imperfections in these models, such as gaps, holes, self-intersections, duplicated geometry (e.g., double walls), non-manifold (e.g., more than two polygons meeting at the same edge). Applications, such as simulation, digital fabrication (e.g., 3D printing), and model editing tools, can only accept clean surface models as input, which restricts the existing models to visualization purpose only. It becomes extremely difficult to eliminate these flaws when a certain combination of them are present. 

In this project, we would like to develop robust algorithms and tools that can automatically resolve these commonly found issues in 3D models. We would expect the method to produce a closed surface representation of a building. With such a representation, a 3D building is partitioned into disjoint interior and exterior spaces without ambiguity.

**Required Skills**: 
Proficient in one programming language (e.g., C/C++ or Python); experiences in mesh processing; machine learning (in particular Deep Learning) is a bonus.

**Contact**: [Liangliang Nan](https://3d.bk.tudelft.nl/liangliang/)

- - -

## Coupling 3D city models with Ladybug tools for environmental analyses

<img src="img/ga_ladybug.jpg" style="width: 600px;"/>

The MSc thesis will focus on interoperability between the Ladybug tools and CityGML-based 3D city models. The [Ladybug Tools](https://www.ladybug.tools/) are a collection of free applications that support environmental design and education. They are among the most comprehensive, connecting 3D Computer-Aided Design (CAD) interfaces to a host of validated simulation engines.

Particular attention will be paid to energy-related topics in order verify how and to which extent the CityGML [Energy ADE](http://www.citygmlwiki.org/index.php/CityGML_Energy_ADE) (Application Domain Extension) can be used to deliver and store additional energy-related data needed by the Ladybug tools.

The students’ task will consist in choosing (together with the supervisors) a specific application covered by a Ladybug tool, to analyse the software and data requirements of the selected Ladybug  tool(s) and to perform a mapping to the CityGML/Energy ADE data model. In addition, proper interfaces will have to be developed and tested by means of a concrete case study.
This topic is available for up to **two students** (each one choosing a different application area).

Prerequisites: Knowledge of CityGML and its ADE mechanism. A bonus is experience with the CityGML 3D City Database and the associated tools. A programming language of choice (e.g. Java or Python) will be used.

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and [Jantien Stoter](https://3d.bk.tudelft.nl/jstoter/)

- - -

## Interaction between urban heat islands and semantic 3D city models

<img src="img/ga_haagsehitte.jpg" style="width: 300px;"/>

This summer was exceptionally hot and the Netherlands suffered two consecutive heat waves, which had severe negative impacts on human health and the urban environment caused by drought. The department of Urbanism is running Netatmo weather station network with more than 100 stations all across the city of the Hague. This means there is a rich data set which allows to study the formation of the **urban heat islands** in relation to the direct, local built environment around these sensors.

The MSc thesis will focus on investigating how a semantically enriched, CityGML-based **3D city model** can help in understanding and forecasting urban heat islands. Additionally, based on a real case study, the 3D city model will be used to analyse qualitatively and quantitatively how certain physical urban conditions can contribute to (reducing) the heat island effect.

This MSc thesis will be jointly supervised by the 3D Geoinformation group and the group of Environmental Technology and Design.

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and Alexander Wandl

- - -

## Urban metabolism and semantic 3D city models

<img src="img/ga_urbanmining.jpg" style="width: 500px;"/>

This thesis topic is connected to the Horizon 2020 Research Project REPAiR: Resource management in peri-urban areas, going beyond urban metabolism. The project has developed a 2D urban mining model of the Amsterdam metropolitan area.

The MSc thesis will focus on defining and implementing a 3D “urban mining” model which will help to investigate and quantitatively describe where, when, and how many critical materials can be obtained (“extracted”) from existing, ageing cities/neighbourhoods in order to be directly reused or recycled in the context of circular economy. A CityGML-based 3D city model of a real case study area will represent the main source of integrated spatial and non-spatial information the 3D urban mining model will be implemented onto.

This MSc thesis will be jointly supervised by the 3D Geoinformation group and the group of Environmental Technology and Design.

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and Alexander Wandl

- - -

## Integrated modelling of utility networks in the urban environment

<img src="img/ga_xander_network.jpg" style="width: 500px;"/>

In the framework of Smart Cities, the MSc thesis will focus on interoperability issues when it comes the heterogeneous utility networks (e.g. gas, water, electricity, sewage, district heating, telecommunications, etc.) that are found in the urban environment.
Starting from a CityGML-based 3D city model, the Msc. thesis will focus on testing and further extending the Utility Network ADE (Application Domain Extension), based on a concrete case study which will be agreed upon with the student. A possible application area is in the energy sector, e.g. when it comes to coupling networks to specific simulation programs.
The image shown here is taken from the [Msc thesis of Xander van den Duijn](https://repository.tudelft.nl/islandora/object/uuid:fed24b16-cf95-4fa0-a109-ece6e91b61e9?collection=education) (2018) and is an example - and a starting point - of the overall topic of the thesis proposed here.

Prerequisites: Knowledge of CityGML and its ADE mechanism, FME and Enterprise Architect are required. A bonus is experience of the CityGML 3D City Database and the associated tools.

**Contact**: [Giorgio Agugiaro](https://3d.bk.tudelft.nl/gagugiaro/) and [Jantien Stoter](https://3d.bk.tudelft.nl/jstoter/)


- - -

## Computation of spatial extent for massive point cloud datasets

![](img/alphashape.png)


Given a (classified) LAS pointcloud, how to (re)generate its spatial extent?

Finding the bounding-box (or the convex hull, or with a raster solution) is in most cases not sufficient, as the image above shows.

A better solution is to use the alpha-shape of the set of points, but this is impossible with massive datasets (which are often very common in practice).


*Contact:* [Hugo Ledoux](https://3d.bk.tudelft.nl/hledoux) 
