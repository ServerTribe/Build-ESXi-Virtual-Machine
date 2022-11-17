
# Build ESXi Virtual Machine




## Project Blueprints


### Deploy and Install VMWare Drivers on Windows


### Deploy and Install VMWare Tools on RHEL/CentOS


### Kickstart ESXi Linux Virtual Machine

```markdown
To install the PowerCLI for VMWare
sudo yum install https://github.com/PowerShell/PowerShell/releases/download/v6.2.3/powershell-6.2.3-1.rhel.7.x86_64.rpm
sudo pwsh -Command "Install-Module VMware.PowerCLI"

PowerCLI reference is available at : 
https://pubs.vmware.com/vsphere-51/index.jsp?topic=%2Fcom.vmware.powercli.cmdletref.doc%2FNew-VM.html
```

### Kickstart ESXi Windows Virtual Machine





## Project Parameters


| Name | Type | Script Reference |
| ---- | ---- | ---------------- |
| Base Dir | Text | `basedir` |
| Boot ISO Dir | Text | `bootisodir` |
| CPU Count | Text | `cpucount` |
| ESXi Host | Basic Node | `esxihost` |
| Guest OS Type | Text | `guestostype` |
| Network Name | Text | `networkname` |
| PowerCLI Node | Linux/Unix Node | `powerclinode` |
| PowerCLI Node User | Linux/Unix Credential | `powerclinodeuser` |
| Ram Size MB | Text | `ramsizemb` |
| Storage Pool | Text | `storagepool` |
| vCenter Host | Basic Node | `vcenterhost` |
| vCenter User | Basic Credential | `vcenteruser` |
| Virtual Machine | Basic Node | `virtualmachine` |
| Virtual Machine: Linux | Linux/Unix Node | `virtualmachinelinux` |
| Virtual Machine User | Basic Credential | `virtualmachineuser` |
| Virtual Machine User: Linux | Linux/Unix Credential | `virtualmachineuserlinux` |
| Virtual Machine User: WIndows | Windows Credential | `virtualmachineuserwindows` |
| Virtual Machine: Windows | Windows Node | `virtualmachinewindows` |
| Windows Administrator | Windows Credential | `windowsadministrator` |




## Project Files


| Name | Type |
| ---- | ---- |
| RHEL VMWare Tools | Large Archives |
| Win VMWare Drivers | Large Archives |




# ServerTribe

*ServerTribe’s mission* is to provide the community access to intuitive and
flexible open-source IT automated and orchestrated SysOps processes.

This is an *Attune Project* that contains IT automated and orchestrated
processes.

Attune is your flexible IT Automation & Orchestration solution, a
self-documenting central source of reusable proven processes, files and
backups to build and maintain your IT/OT infrastructure. Attune can be
configured to perform any process or task that a System Administrator or
Database Administrator would perform through a terminal.

The *Attune Community Edition* can be
[downloaded for free](https://www.servertribe.com/comunity-edition/)
from our [ServerTribe website](https://www.servertribe.com/). You can learn
more about Attune through [ServerTribe's YouTube Channel](https://www.youtube
.com/channel/UCLRvZajNQXfQPJnYFdeXZ3w).


Thank you.
