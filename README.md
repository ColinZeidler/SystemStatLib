# SystemStatLib
Library that handles gathering system stats on windows and linux

# Structure and API
## CPU
### CPUMonitor class
Values:
* cpu count
 
API:
* uint getCPUCount()
* double getCPUUse(uint core)
* double getCPUAverage()

### CPU Data struct
* uint cpunumber
* double cpuuseage

## RAM
### RAMMonitor class
Values:
* total ram

API:
* uint getRAMTotal()
* uint getRAMUseCount()
* uint getRAMFreeCount()
* double getRAMUsePercent()

### RAM Data struct
* uint totalram
* uint usedram
* uint freeram

## Network
### NetMonitor class
Values:
* adapter count

API:
* uint getAdapterCount()
* uint getUlSpeed(uint adapter)
* uint getDlSpeed(uint adapter)

### Network data struct
* uint adapternum
* uint ulspeed
* uint dlspeed
