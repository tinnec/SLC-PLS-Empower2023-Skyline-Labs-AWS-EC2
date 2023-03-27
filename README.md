
# Empower Workshop: SRM Profile-Load Script

This script is a starting point for the workshop, designed to help you get up and running quickly. It includes the basic structure of a SRM Profile-Load script that will be used throughout the workshop.

## Purpose

The purpose of this workshop is to learn how to create a Profile-Load script (PLS) and how to use it to manage the "Virtual Machine" virtual function of the Skyline Labs AWS EC2 connector. 

The PLS will be responsible for starting and stopping EC2 instances, providing a convenient way to automate this process and simplify the management of an AWS environment.

By the end of the workshop, you will have gained the necessary knowledge and skills to create your own PLS, which you can then use to start and stop EC2 instances within your AWS environment. This will give you greater control and flexibility over the management of a virtual machine, allowing you to optimize your resource usage and reduce costs.

## Prerequisites

Before you start the workshop, make sure you have the following installed on your computer:

-   [Git](https://git-scm.com/)
-   [Visual Studio](https://visualstudio.microsoft.com)
-   [DataMiner Integration Studio](https://community.dataminer.services/dataminer-integration-studio-other-downloads/)
-   [Empower - SRM Prerequisites](https://catalog.dataminer.services/catalog/4119)

## Getting Started

To get started, follow these steps:

1.  Clone the repository to your local machine:
    
    ```bash
    git clone https://github.com/SkylineCommunications/SLC-PLS-Empower2023-Skyline-Labs-AWS-EC2.git
	```
    
2.  Open the automation script solution in Visual Studio and begin customizing it based on your needs.

## Usage

Once you have customized the script, you can test it by following these instructions::

1.  Publish the Automation script XML file using the DataMiner Integration Studio editor available in Visual Studio.
2.  In the Profile Load Tester element:
3.  At the top of the PLS Tester visual overview, in the _Function_ box, select the virtual function for which you want to run a test.
4.  In the _Resource_ box, select a specific virtual function resource.
5.  Click the _Apply_ button.
7.  Select the Profile Instance and optionally a service state.
8.  Click Apply.


## Resources

Here are some resources that you may find helpful:

-   [Creating Profile-Load Scripts](https://docs.dataminer.services/user-guide/Standard_Apps/SRM/srm_getting_started/implementing_virtual_functions/creating_profile_load_scripts.html)
-   [Implementing a function](https://community.dataminer.services/courses/service-resource-manager-implementing-a-function/)  
-   [Getting started with SRM and Profile-Load Scripts](https://community.dataminer.services/video/getting-started-with-srm-and-profile-load-scripts/?hilite=profile-load)
-   [DataMiner Community](https://community.dataminer.services/)