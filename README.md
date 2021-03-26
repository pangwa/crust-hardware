# Crust Hardware List
This is a list of hardwares which could run [Crust Sworker](https://github.com/crustio/crust-sworker) nodes.

# General
Before checking the CPU models in this list, please goto [Intel Ark](https://ark.intel.com) site and ensure the CPU supports *Software Guard Extension(SGX)*.


Please try to avoid using the not worked CPU models, you're in a good chance of wasting your money if you try to build a crust miner using these models.
# Known Works CPU/Motherboards

| CPU Model | Motherboard | Reported At | Comments |
| ------------- |:-------------:| ------:|-----:|
| i5-10400 | AsRock B460 Pro4| 2021-03-26 | |
| i3-10300 | AsRock B460 Pro4| 2021-03-26 | |
| i5-9600KF | * | 2021-03-26 | Recommended from [offical wiki](https://wiki.crust.network/docs/en/nodeHardwareSpec) |
| i7-7700k| * | 2021-03-26 | Recommended from [offical wiki](https://wiki.crust.network/docs/en/nodeHardwareSpec) |


# Known Not Work CPU/Motherboards
| CPU Model | Motherboard | Reported At | Comments |
| ------------- |:-------------:| ------:|-----:|
| i5-10500 | AsRock B460 Pro4| 2021-03-26 | Just not work, might a BIOS issue |


# Contribution
Submit your working/not working CPU/Motherboards by opening an issue or a Pull Request! Please include both your CPU model and Motherboard model in the report!