````markdown
# Cloud Lab Results

## Linux Environment

I used KillerCoda to work with an Ubuntu Linux environment and perform basic system checks. The activity helped me understand how to use Linux commands to check the resources and configuration of a computer system.

---

## 1. Operating System

I used the following command:

```bash
cat /etc/os-release
````

### Result

* Operating System: Ubuntu 24.04.4 LTS
* Version: 24.04.4 LTS (Noble Numbat)
* Distribution ID: ubuntu

The command displayed information about the Linux operating system running in the KillerCoda environment.

---

## 2. CPU Information

I used the following command:

```bash
lscpu
```

### Result

* Architecture: x86_64
* CPU(s): 1
* CPU Model: Intel Xeon E312xx (Sandy Bridge, IBRS update)
* CPU Speed: 2.0 GHz

The command displayed information about the processor and the available CPU resources in the Linux environment.

---

## 3. Memory Information

I used the following command:

```bash
free -h
```

### Result

* Total Memory: 1.9 GiB
* Used Memory: 429 MiB
* Free Memory: 851 MiB
* Available Memory: 1.4 GiB
* Total Swap: 1.0 GiB

The command showed how much memory was available, being used, and free in the Linux environment.

---

## 4. Disk Information

I used the following command:

```bash
df -h
```

### Result

* Main Filesystem: /dev/vda1
* Total Size: 19G
* Used Space: 5.4G
* Available Space: 13G
* Usage: 30%
* Mounted on: /

The command displayed the available storage space and how much of the disk was currently being used.

---

## 5. Network Information

I used the following command:

```bash
ip addr
```

### Result

* Network Interface: enp1s0
* IP Address: 172.30.1.2/24
* Network Status: UP

The command displayed the network interfaces and IP address assigned to the Linux environment.

---

## 6. Linux Commands Used

| Command               | Purpose                                       |
| --------------------- | --------------------------------------------- |
| `cat /etc/os-release` | Checks the Linux operating system and version |
| `lscpu`               | Displays CPU information                      |
| `free -h`             | Displays memory information                   |
| `df -h`               | Displays disk space information               |
| `ip addr`             | Displays network information                  |

---

## 7. My Observation

After completing the Linux lab, I learned how to check the operating system, CPU, memory, disk space, and network information using Linux commands. The activity helped me understand how a Linux environment can be inspected through the terminal.

I also learned that these commands are useful for checking system resources and understanding the configuration of a computing environment. This activity gave me a better understanding of how Linux can be used in cloud computing and server administration.

```
```
