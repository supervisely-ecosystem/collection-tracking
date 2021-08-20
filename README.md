# Overview
🚀 This collection is designed to cover **tracking** task in
[**Supervisely**](https://supervise.ly/). Before using these apps
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

You can think of [Supervisely](https://supervise.ly/) as an Operating System available via Web Browser to help you solve Computer Vision tasks. The idea is to unify all the relevant tools that may be needed to make the development process as smooth and fast as possible.

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
- MOT15 [project] (+-)
- MOT15 Lite [3 videos, each 15 sec] [project] (-)

---

#### Synthetic data:
- Synthetic videos for tracking [app] (+)
- Lemons annotated [project] (+)
- Beautiful backgrounds [project] (-)


## Neural networks

<div align="center" markdown>

### FairMOT bundle

</div>


#### Main:

- Train FairMOT (+)
- Serve FairMOT (+)

#### Additional:

- Visualize FairMOT (+)

## Integration into labeling tool

- Apply NN to videos project (+)

## Auxiliary apps

#### Import

- Import MOT (+-)
- Import videos by URLs from txt file (+)
- Import videos from cloud storage (+)

#### Export

- Export to MOT (+-)

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
- [Learn SDK Basics with IPython Notebooks](https://sdk.docs.supervise.ly/rst_templates/notebooks/notebooks.html)  
- [Complete Python SDK](https://sdk.docs.supervise.ly/sdk_packages.html)


# Contact & Questions & Suggestions

- for technical support please leave issues, questions or suggestions in our [repo](https://github.com/supervisely-ecosystem/mmclassification). Our team will try to help.
- also we can chat in slack channel [![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack)
- if you are interested in Supervisely Enterprise Edition (EE) please send us a [request](https://supervise.ly/enterprise/?demo) or email Yuri Borisov at [sales@supervise.ly](sales@supervise.ly)
