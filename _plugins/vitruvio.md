---
layout: detail
fullpreview: true
order-of-appearance: 4
draft: false

name: vitruvio
title: ArcGIS CityEngine for Unreal Engine
platform: Unreal Engine
logo: vitruvio.png
github: https://github.com/Esri/cityengine_for_unreal

teaser-image: vitruvio_teaser_image.jpg

hero-title: ArcGIS CityEngine for Unreal Engine
hero-subtitle: CityEngine Plugin for Unreal Engine
hero-content:
  - type: video
    name: faOdiVcxRG4

description: ArcGIS CityEngine for Unreal Engine (formerly Vitruvio) is a plugin for Unreal Engine (UE). It enables the use of CityEngine CGA rules for the generation of procedural buildings in the Unreal Editor or at runtime.

gallery:
  - image: vitruvio_gallery_1.jpg
  - image: vitruvio_gallery_2.jpg
  - image: vitruvio_gallery_3.jpg
  - image: vitruvio_gallery_4.jpg

introduction: With CityEngine for Unreal Engine, game designers or artists do not have to leave Unreal Engine to make use of the procedural modeling power of CityEngine. The buildings stay procedural all time and artists can change the height, style and appearance of buildings easily with a parametric interface. In addition, buildings can also be generated at runtime.<br/>CityEngine for Unreal Engine requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. The download section below provides links to the several RPKs which can be used out-of-the-box. <br/><br/><strong><i>ArcGIS CityEngine for Unreal Engine is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted. Please refer to the licensing section below for more detailed licensing information.</strong></i>

callout: true
callout-text: Help us improve ArcGIS CityEngine for Unreal Engine&#58
callout-button: Take the survey
callout-link: https://survey123.arcgis.com/share/8e812fdce4174a92bfe3deeb8f092d1c

ressource-1-title: Downloads
ressource-1-text: Download the latest version of ArcGIS CityEngine for Unreal Engine here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/Esri/vitruvio/blob/main/doc/installation.md

ressource-2-title: Documentation
ressource-2-text: A full documentation of ArcGIS CityEngine for Unreal Engine is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/vitruvio/blob/master/doc/usage.md

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/Esri/vitruvio

examples:
  - title: New York
    text: This example showcases how CityEngine for Unreal Engine can be used in combination with the <a href="https://developers.arcgis.com/unreal-engine/">ArcGIS MapsSDK for Unreal Engine</a> and Esri's feature services to stream building footprints and automatically generate buildings using CityEngine for Unreal Engine's C++ API.</br></br>Notes&colon;</br><ul><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a>.</li><li>Please make sure to <a href="https://developers.arcgis.com/unreal-engine/install-and-set-up/">install ArcGIS MapsSDK (v2.0.0) for Unreal Engine</a>.</li><li>Please make sure to setup <a href="https://developers.arcgis.com/unreal-engine/authentication/#api-key-authentication">API key authentication</a> in the MapsSDK for Unreal Engine.</li><li>The rules are from the International City example of CityEngine.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_2_1.jpg
    files:
      - title: New York Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.3/CE_for_UE55_NewYork.zip

  - title: Zurich
    text: This example showcases how CityEngine for Unreal Engine's Blueprint API can be used to read Asset Metadata from CityEngine's Datasmith exports to generate buildings from footprints.</br></br>Notes:</br><ul><li>The rules are from the International City example of CityEngine.</li><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a> before running the examples.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_6_1.jpg
    files:
      - title: Zurich Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.3/CE_for_UE55_Zurich.zip

  - title: Boston Asset Replacements
    text: This example features rules from the <a href="https://www.esri.com/arcgis-blog/products/city-engine/3d-gis/bring-your-arcgis-cityengine-models-to-life-in-unreal-engine-with-automated-asset-replacements/">Boston Blogpost</a>. It showcases high quality game engine asset replacements in CityEngine for Unreal Engine.</br></br>Notes&colon;</br><ul><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a> before running the examples.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_5_1.jpg
    files:
      - title: Boston Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.2/CE_for_UE55_Boston.zip

  - title: Paris
    text: This example features a small part of Paris. The building footprints are exported from CityEngine using <a href="https://doc.arcgis.com/en/cityengine/latest/help/cityengine-help-get-map-data.htm">Get Map Data</a>. Large parts of Paris were re-styled by Haussmann which earned the nickname the "Wall-City", because of continuous balconies running from facade to facade. The latter can be generated by selecting the higher level of detail.</br></br>Notes:</br><ul><li>The rules are from the Paris example of CityEngine.</li><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a> before running the examples.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_3_2.jpg
    files:
      - title: Paris Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.2/CE_for_UE55_Paris.zip

  - title: Medieval City
    text: This example features buildings in a European medieval style.</br></br>Notes&colon;</br><ul><li>The building rules are from the Medieval City example of CityEngine.</li><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a> before running the examples.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_1_1.jpg
    files:
      - title: Medieval City Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.2/CE_for_UE55_MedievalCity.zip

  - title: NYC 2259
    text: This example features New York city 240 years into the future, inspired by the great 1998 motion picture The Fifth Element.</br></br>Notes&colon;</br><ul><li>The rules are adapted from the NYC2259 example of CityEngine.</li><li>The rules assign custom Unreal Materials to the building facades which can be found in the Content/Materials folder.</li><li>Please make sure to <a href="https://github.com/Esri/cityengine_for_unreal/blob/master/doc/installation.md">install CityEngine for Unreal Engine</a> before running the examples.</li></ul></br></br>Downloads&colon;
    images:
      - image-name: vitruvio_ex_4_1.png
    files:
      - title: NYC 2259 Example
        link: https://github.com/Esri/cityengine_for_unreal/releases/download/v2.2/CE_for_UE55_NYC2259.zip

legal: <ul><li>ArcGIS CityEngine for Unreal Engine is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted.</li><li>CityEngine for Unreal Engine is under the same license as the included <a href="./cityenginesdk#legal-section">CityEngine SDK</a>.</li><li>All content in the "Examples" directory/section is licensed under the APACHE 2.0 license. You may obtain a copy of this license at <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">https://www.apache.org/licenses/LICENSE-2.0</a>.</li><li>For questions or enquiries, please contact <a href= "mailto:cityengine-info@esri.com">cityengine-info@esri.com</a></li></ul>
---
