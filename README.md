# Mongo-dB
Mongo dB replica set on  local machine.

# MongoDB Replica Set Setup Script
	This script automates the process of installing and setting up a MongoDB replica set with specific configurations.

# Prerequisites
	- Ubuntu 22.04
	- MongoDB 5.0

# Usage
	1. Clone this repository.
	2. Make sure MongoDB is not already running on the specified ports.
	3. Execute the script: `./setup_mongo_replica_set.sh`

# Configuration
	- MongoDB Version: 5.0
	- Replica Set Name: rs0
	- WiredTiger Cache Size: 1GB
	- MongoDB Port Numbers: 27017, 27018, 27019 (arbiter)
	- MongoDB Data Directory: /mongo_data
	- MongoDB Log Directory: /mongo_logs

# Additional Notes
	- The script assumes Ubuntu 22.04 as the operating system.
	- Ensure that MongoDB installation for Ubuntu is referenced appropriately.
		https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu/
