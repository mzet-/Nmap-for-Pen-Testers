This Nmap fork contains additional (curated and verified) NSE scripts useful during pen tester's day to day duties. 

Currently scripts for detecting following vulnerabilities are added:

### Multiple memory corruptions in OpenSLP as used in VMware ESXi

**IDs:** CVE-2019-5544, CVE-2020-3992, CVE-2021-21974

**Script:** [vmware-svrloc-vulns.nse](https://github.com/mzet-/Nmap-for-Pen-Testers/blob/master/scripts/vmware-svrloc-vulns.nse)

**Vulnerability details:** 

**Pull request in upstream:** `https://github.com/nmap/nmap/pull/2266`

**Script author:** mzet

**Deployment:** 

```
cd nmap/
wget https://raw.githubusercontent.com/mzet-/Nmap-for-Pen-Testers/master/scripts/vmware-svrloc-vulns.nse -O scripts/vmware-svrloc-vulns.nse
wget https://raw.githubusercontent.com/mzet-/Nmap-for-Pen-Testers/master/nselib/srvloc.lua -O nselib/srvloc.lua
./nmap --script-update
```

### Cisco SIET

```
https://github.com/Sab0tag3d/SIETpy3/blob/main/cisco-siet.nse
```
