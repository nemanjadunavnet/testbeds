---
short_name: fortiss MLAB
name: fortissimo Mobility Lab
testbed_url: https://www.fortiss.org/en/research/living-lab/detail/fortissimo
provider_logo: logos/fortiss.png
city_country: Munich, Germany
domains: Automotive, Aerospace, Health
use-cases: Complex, safety-critical cyber-physical systems; Model-based systems engineering, incremental integration testing; fault-injection testing.
contact: Tiziano Murano munaro@fortiss.org
license: LGPL v3.0 (Simulation)
partner_access: Yes (Simulated online; Physical on-site)
testbed_stage: Testbeds
description: The fortissimo Mobility Lab demonstrates how model-based systems engineering (MbSE) concepts can be leveraged to design and implement safe, adaptive, and reliable software and system architectures within a flexible development process. The demonstrator platform includes physical rovers as well as their digital twins. The fortissimo Rovers are based on heavily modified scale 1 to 10 RC cars, equipped with a LIDAR, ultrasound sensors, and an RGB camera. The fortissimo Simulation closely replicates the dynamics and sensor properties of the physical rovers using the Gazebo simulation environment, while providing a standardized interface for their behavior specifications by means of the FMI standard. In both cases, the automotive use case includes advanced driver assistance systems (ADAS) and autonomous driving (AD) functions. The fortissimo Mobility Lab is unique in its ability to demonstrate the model-based engineering of safety critical cyber-physical systems – from its conception to its verification and validation.
descriptionimage: images/fortissmo.png
concept: MBSE concepts for designing (e.g., the SPES methodology), developing (e.g., product line management), integrating (e.g., Co-Simulation), and testing (e.g., defect-based testing) complex cyber-physical systems.
technology: AutoFOCUS3; co-Simulation by means of the Functional Mock-up Interface (FMI)
hardware: Converted RC cars (scale 1:10); Raspberry Pis, Tinkerforge sensor and actuator platform (ultrasound, lidar, engine management unit), 3D-Printed hardware racks, RGB cameras, Microsoft Xbox Bluetooth controllers.
software: (Simulated) FMI, ROS, Gazebo, FMI adapter for ROS. (Physical) AutoFOCUS3, Ansible, Ubuntu, custom drivers, libraries, and glue code linking generated code to the target hardware.
---
