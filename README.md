# Edge-DataSet
Dataset for IoT, Fog and Edge-based experiments

## Great IoT, Sensor and other Data Sets Repositories
https://www.datasciencecentral.com/profiles/blogs/great-sensor-datasets-to-prepare-your-next-career-move-in-iot-int

## The datasets are publicly released to facilitate research in Edge Computing in Australia
https://github.com/swinedge/eua-dataset

## Telecom DataSet
The dataset, provided by Shanghai Telecom, contains more than 7.2 million records of accessing the Internet through 3,233 base stations from 9,481 mobile phones. 
http://sguangwang.com/TelecomDataset.html 

## PhysioNet DataSet
https://physionet.org/about/database/

## CRAWDAD DataSet
https://crawdad.org/

## Taxi Trajectory Data
Shanghai Qiangsheng Taxi GPS data trace (2018-04-01). A polular taxi GPS data trace recently used in many works.
It cloud be combined with Shanghai Telecom DataSet to create an edge environment for V2V or V2X applications.
https://www.dropbox.com/s/sv0az2dpba2xfi6/qiangshengchuzuqichexingcheshuju.zip?dl=0

Or you can download from the original Shanghai SODA competition here (need register)
http://soda.shdataic.org.cn/data/?cid=1


# Simulation for Cloud-Edge Environments

## CloudSimSDN(-NFV)
https://github.com/Cloudslab/cloudsimsdn
Can simulate both networking and computing events in edge, edge-cloud or iter-clouds environments.
Moreover, it implements modules such as auto-scaling and load balancing policy for VM, container, and SFC (VNF).

Other extensions based on CloudSimSDN include: (1) live VM/VNF/Container migration, multiple migration scheduling and planning; (2) live container migration in edge environments and user mobility across different Edge coverage; (3) framework for live VM/Container migration scheduling induced by user mobility (such as vehicle movement from one Mobile Edge Center (MEC) to another).


## iFogSim
An edge computing extension based on CloudSim by simply mapping cloud components to the edge ones which focus on the simulation of container placement policy in edge environments. However, there are some drawbacks in terms of no network communication simulation which supported in CloudSimSDN.
