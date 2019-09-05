# Cisco DNA Center Retrieve the Device Information for a Device


This is a Python sample code to showcase how to retrieve the Cisco DNA Center device information for the device with the specified hostname

**Cisco Products & Services:**

- Cisco DNA Center

**Tools & Frameworks:**

- Python environment

**Usage**

- $ python dnac_device_info.py PDX-9300

The above example will:
 - verify if the device with the {hostname} is managed by Cisco DNA Center
 - if yes, retrieve the information for the device with the hostname {PDX-9300}
 - if no, notify the device is not managed by Cisco DNA Center

- Sample output

The device information for the device with the name: PDX-9300


{

    "type" : "Cisco Catalyst 9300 Switch" , 
    "macAddress" : "70:d3:79:be:28:00" , 
    "lineCardId" : "" , 
    "locationName" : null , 
    "managementIpAddress" : "10.93.130.43" , 
    "memorySize" : "NA" , 
    "platformId" : "C9300-48U" , 
    "reachabilityFailureReason" : "" , 
    "reachabilityStatus" : "Reachable" , 
    "series" : "Cisco Catalyst 9300 Series Switches" , 
    .....
    "instanceUuid" : "13606691-e5bf-4f21-91d8-858a2363a099" , 
    "instanceTenantId" : "5bef48543c584b0088491a83" , 
    "id" : "13606691-e5bf-4f21-91d8-858a2363a099"

}


**License**

This project is licensed to you under the terms of the [Cisco Sample Code License](./LICENSE).
