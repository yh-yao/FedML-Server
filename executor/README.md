# Installation
http://doc.fedml.ai/#/installation

pip install -r requirements.txt

# Prepare Dataset
```
cd FedML/data/MNIST/
sh download_and_unzip.sh
cd ../../../
```

# Launch the HTTP Server
Set the server IP and port and then run the following script:
```
python app.py
```

# Launch the mobile device simulator
```
cd client_simulator
python3 ./client_simulator/mobile_client_simulator.py --client_uuid '0'
```