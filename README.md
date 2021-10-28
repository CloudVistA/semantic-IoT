# Medical IoT Project

Internet of medical Things (IoT) Project is an architecture for medical device data streaming from the bedside to the cloud. This is comprised of (1) device data acquisition and management at the edge with commodity open source hardware and (2) push-based synchronization and integrate to centralized cloud storage for online analytics. This design will evolve as discovery proceeds.


### Design Overview
* Consumer-grade commodity hardware, interfaces, operating systems, protocols, databases, and standards
* Commmodity open-source hardware  (Beaglebox, Arduino, ...)
* Industry-standard mobile-first ports  (USB-C)
* Linux-based open-source real-time OS (OpenRTOS, FreeRTOS,..)
* Web-standard APIs (REST / JSON)
* Web-standard streaming protocols (RabbitMQ,..)
* Open-source real-time integrated edge-to-cloud database (YottaDB,...)

### Device Drivers
* Device drivers and microservices written in compiled machine level languages (C, C++, Go, Rust)
* Auto-detection of device and download of necessary driver when plugged in
