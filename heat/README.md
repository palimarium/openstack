

#Heat - How to launch the stack

heat stack-create -f auto_scaling_demo.yml 
    -P key_name='toshiba' 
    -P flavor='m1.tiny' 
    -P image='cirros-0.3.4-x86_64' 
    -P availability_zone='nova'
    -P private_net_id='d399aba9-8733-4498-91ab-7d56c39b6002' auto_scaling_demo
