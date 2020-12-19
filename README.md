# device_template_config
 Create device configuration based on a template and implement it 
 implement the configuration on network deivces on the host files

## Roles used 
   template_config - implement configuration to a network device based on his model

### template_config role 
      Variables : 
        1. model - decide to what kind of model the operation should be happening
        2. type - decide what is the role of this specific device (office access / office backbone / data      center access)
      description : 
        the role would based on the device model would implement a configuration using a jinja2 template that is specific to this model and type     
    
## main playbook 
    device_template_config  - runs the template_config model on all junos devices 

    
    
    
