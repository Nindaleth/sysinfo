# Sysinfo

Cross platform (Windows only right now) way to find common system resources like, os, os version, machine name, IPs, home and system directories for Nim.

Example:

```nim
import sysinfo
echo "MachineGuid: ", getMachineGuid()
echo "OsName: ", getOsName()
echo "OsVersion: ", getOsVersion()
echo "CpuName: ", getCpuName()
echo "CpuGhz: ", getCpuGhz(), "GHz"
echo "FreeMemory: ", getFreeMemory().float / 1024 / 1024 / 1024, "GB"
```
