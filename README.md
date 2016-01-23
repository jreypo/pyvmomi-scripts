pyVmomi Scripts
---------------

Scripts to autmate different vSphere tasks. Written in Python with [pyVmomi](https://github.com/vmware/pyvmomi), the Python SDK for the vSphere API. Some of the scripts are converted from Perl or PowerCLI versions I had in my personal toolbox, I simply re-developed them in Python and tested against newest vSphere versions.

The list includes for now:
- `reconfigure_host_for_ha.py` - Performs a *Reconfigure for HA* operation on an ESXi host that is part of vSphere HA cluster. 
