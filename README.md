# open medical IoT
Open source medical IoT

Open Medical Internet of Things (IoT) provides a roadmap and open-source architecture for medical device data translation and streaming from the bedside to the cloud.  This will provide (1) high-reliability offline data acquisition and storage on the edge and (2) online push-based synchronization and federation to centralized cloud storage.

### Design
* Consumer-grade  hardware, interfaces, operating systems, protocols, databases, and standards
* Commmodity open-source hardware  (Beaglebox, Arduino, ...)
* Industry-standard ports  (USB-C interface)
* Linux-based open-source real-time OS (OpenRTOS, FreeRTOS,..)
* Web-standard APIs (REST / JSON)
* Web-standard streaming protocols (RabbitMQ,..)
* Open-source real-time integrated edge-to-cloud database (YottaDB,...)

### Device Drivers
* Device drivers and microservices written in compiled machine level languages (C, C++, Go, Rust)
* Auto-detection of device and download of necessary driver when plugged in
