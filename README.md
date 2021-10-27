# open medical IoT
Open source medical IoT

Open Medical Internet of Things (IoT) is an open-source event-oriented architecture for medical device data streaming from the bedside to the cloud. This is comprised of (1) offline medical device data acquisition, storage, management, and display on the edge and (2) online push-based synchronization and federation to centralized cloud storage.

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
