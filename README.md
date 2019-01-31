# elasticsearch


If using static hosts files:

    ./build_aws_static_inventory.sh
    
Deploy elasticsearch and kibana

    ./deploy hostsfile datanexus demo aws us-east-1 development none
    
    
Kibana runs on port 5601

    ssh -i aws-us-east-1-demo-broker-development-private-key.pem 10.10.1.78 -L 5601:10.10.2.78:5601

