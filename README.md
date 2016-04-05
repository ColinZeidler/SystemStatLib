# SystemStatLib
Library that handles gathering system stats on windows and linux

# Structure and API
## CPU
Values:
* cpu count
 
API:
* uint getCPUCount()
* double getCPUUse(uint core)
* double getCPUAverage()

## RAM
Values:
* total ram

API:
* uint getRAMTotal()
* uint getRAMUseCount()
* uint getRAMFreeCount()
* double getRAMUsePercent()

## Network
Values:
* adapter count

API:
* uint getAdapterCount()
* uint getUlSpeed(uint adapter)
* uint getDlSpeed(uint adapter)
