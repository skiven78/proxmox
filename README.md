Some Proxmox hepler scripts from me..

<details>
<summary markdown="span">Logitech Media Server 8.5.2 LXC</summary>

<h1 align="center" id="heading"> Logitech Media Server LXC </h1>

To create a new Logitech Media Server LXC, run the following in the Proxmox web shell.

```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/skiven78/proxmox/refs/heads/main/ct/lms_container.sh)"
```
<h3 align="center" id="heading">Default Settings:  2GB RAM - 16GB Storage - 2vCPU</h3>

After the script completes, If you're dissatisfied with the default settings, click on the LXC, then on the **_Resources_** tab and change the **_Memory_**, **_Cores_** and **_Root Disk_** (Resize disk) settings to what you desire. Changes are immediate.


____________________________________________________________________________________________

</details>
