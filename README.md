# Overview
🚀 This collection is designed to cover **tracking** task in
[**Supervisely**](https://supervisely.com/). Before using these apps
we recommend to try end-to-end working demo (retail labeling use case) - data and explanations are provided.

# Table of Contents

1. [About Supervisely](#-about-supervisely)
2. [Prerequisites](#Prerequisites)
3. [Apps Collection for Tracking](#-apps-collection-for-tracking)
    - [Demo data and synthetic data generation](#demo-data-and-synthetic-data)
    - [Neural Networks](#neural-networks)
    - [Integration into labeling tool](#integration-into-labeling-tool)
    - [Auxiliary apps](#auxiliary-apps)
8. [For developers](#For-developers)
9. [Contact & Questions & Suggestions](#contact--questions--suggestions)

# 🔥 About Supervisely

You can think of [Supervisely](https://supervisely.com/) as an Operating System available via Web Browser to help you solve Computer Vision tasks. The idea is to unify all the relevant tools that may be needed to make the development process as smooth and fast as possible.

More concretely, Supervisely includes the following functionality:
 - Data labeling for images, videos, 3D point cloud and volumetric medical images (dicom)
 - Data visualization and quality control
 - State-Of-The-Art Deep Learning models for segmentation, detection, classification and other tasks
 - Interactive tools for model performance analysis
 - Specialized Deep Learning models to speed up data labeling (aka AI-assisted labeling)
 - Synthetic data generation tools
 - Instruments to make it easier to collaborate for data scientists, data labelers, domain experts and software engineers

One challenge is to make it possible for everyone to train and apply SOTA Deep Learning models directly from the Web Browser. To address it, we introduce an open sourced Supervisely Agent. All you need to do is to execute a single command on your machine with the GPU that installs the Agent. After that, you keep working in the browser and all the GPU related computations will be performed on the connected machine(s).


# 🎉 Apps Collection for Tracking

To learn more about how to use every app, please go to app's readme page (links are provided).  
Just add the apps to your team to start using them.

<!-- <img src=""/> -->

Collection consists of the following apps:

## Demo data and synthetic data


#### Demo data:
- [MOT15 Lite](https://ecosystem.supervisely.com/projects/mot15-lite-project) — a stripped-down version of the MOT15 dataset. Contains 6 short clips from the original MOT15:  
3 videos in the train and 3 videos in the test.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/mot15-lite-project" src="https://imgur.com/ZtYQmgO.png" width="350px" style='padding-bottom: 10px'/>


#### Synthetic data:
-  [Synthetic videos for tracking](https://ecosystem.supervisely.com/apps/synthetic-videos-for-tracking) — an application that allows you to create synthetic videos based on an annotated project and a set of static backgrounds.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/synthetic-videos-for-tracking" src="https://imgur.com/o3RMxAU.png" width="350px" style='padding-bottom: 10px'/>

- [Lemons (Annotated)](https://ecosystem.supervisely.com/projects/lemons-annotated) — labeled lemons and kiwi. You can use them to generate synthetic videos as foregrounds example.  

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/lemons-annotated" src="https://imgur.com/SjUX1IZ.png" width="350px" style='padding-bottom: 10px'/>

- [Beautiful backgrounds](https://ecosystem.supervisely.com/projects/beautiful-backgrounds-project) — a set of 1000 backgrounds in FullHD resolution. You can use them to generate synthetic videos as backgrounds example.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/beautiful-backgrounds-project" src="https://imgur.com/I8fThhZ.png" width="350px" style='padding-bottom: 10px'/>

## Neural networks

<div align="center" markdown>

### FairMOT bundle

</div>

---


#### Main:

- [Train FairMOT](https://ecosystem.supervisely.com/apps/supervisely-ecosystem%252Ffairmot%252Fsupervisely%252Ftrain) — training dashboard with customizable hyperparameters and monitor metrics in real time

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/FairMOT/tree/master/supervisely/train" src="https://imgur.com/Mk1gpGJ.png" width="350px" style='padding-bottom: 10px'/>

- [Serve FairMOT](https://ecosystem.supervisely.com/apps/supervisely-ecosystem%252Ffairmot%252Fsupervisely%252Fserve) — deploy your model as Rest-API service and connect it with other apps from Ecosystem

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/FairMOT/supervisely/serve" src="https://imgur.com/ksDJmF0.png" width="350px" style='padding-bottom: 10px'/>

#### Additional:

- [Visualize FairMOT](https://ecosystem.supervisely.com/apps/supervisely-ecosystem%252Ffairmot%252Fsupervisely%252Fvisualize) — compare the quality of your checkpoints on the same video.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/FairMOT/supervisely/visualize" src="https://imgur.com/Ni9d1DE.png" width="350px" style='padding-bottom: 10px'/>

## Integration into labeling tool

- [Apply NN to videos project](https://ecosystem.supervisely.com/apps/apply-nn-to-videos-project) — apply served checkpoint to video project.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/apply-nn-to-videos-project" src="https://imgur.com/LDo8K1A.png" width="350px" style='padding-bottom: 10px'/>

## Auxiliary apps

#### Import

- [Import MOT](https://ecosystem.supervisely.com/apps/import-mot-format) — import MOTChallenge dataset to your Workspace as Supervisely project.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/import-mot-format" src="https://imgur.com/26bV6Nh.png" width="350px" style='padding-bottom: 20px'/>

- [Import videos by URLs from txt file](https://ecosystem.supervisely.com/apps/import-videos-by-urls-from-txt)

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/import-videos-by-urls-from-txt" src="https://imgur.com/X7ITSDa.png" width="350px" style='padding-bottom: 20px'/>

- [Import videos from cloud storage](https://ecosystem.supervisely.com/apps/import-videos-from-cloud-storage)

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/import-videos-from-cloud-storage" src="https://imgur.com/E4NBVt1.png" width="350px" style='padding-bottom: 20px'/>

#### Export

- [Export to MOT](https://ecosystem.supervisely.com/apps/export-to-mot-format) — export Supervisely videos project in MOTChallenge dataset format.

<img data-key="sly-module-link" data-module-slug="supervisely-ecosystem/export-to-mot-format" src="https://imgur.com/XLOsIRN.png" width="350px" style='padding-bottom: 20px'/>

#### Utils

- Convert Video Classes Shape (+-)
- Video objects stats for every class (+)
- Split videos (+-)
- Video stat ???
- Render video from images (+-)




# For Developers
You can use sources from from any application to create your own.

You can also refer to our documentation:

- How to Create APP (in develop 🧑🏼‍💻)
- [Learn SDK Basics with IPython Notebooks](https://sdk.docs.supervisely.com/rst_templates/notebooks/notebooks.html)  
- [Complete Python SDK](https://sdk.docs.supervisely.com/sdk_packages.html)


# Contact & Questions & Suggestions

- for technical support please leave issues, questions or suggestions in our [repo](https://github.com/supervisely-ecosystem/mmclassification). Our team will try to help.
- also we can chat in slack channel [![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
- if you are interested in Supervisely Enterprise Edition (EE) please send us a [request](https://supervisely.com/enterprise/?demo) or email Yuri Borisov at [sales@supervisely.com](sales@supervisely.com)
