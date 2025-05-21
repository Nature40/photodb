# PhotoDB

# **PhotoDB has been merged into [AudioDB](https://github.com/envima/audiodb).**

For current releases of AudioDB/PhotoDB refer to [https://github.com/envima/audiodb](https://github.com/envima/audiodb)

---
---
---

*Outdated information:*

This repository contains sources, documentation and release packages of PhotoDB.  

Requirements: [Java 11 (or newer)](https://adoptium.net)

Supported operation systems: **Ubuntu** and **Windows**

PhotoDB releases: https://github.com/Nature40/photodb/releases

# Deployment on Ubuntu

Install Java, e.g.:

```bash
sudo apt update
sudo apt install openjdk-11-jdk
java -version
```

Download PhotoDB package, extract and make excutable:
```bash
unzip *.zip
chmod +x *.sh
```

# Running on Ubuntu

Start PhotoDB server:

```bash
./photodb.sh
```

Open PhotoDB web-interface on a browser.
Local URL with default port 8080:

http://127.0.0.1:8080/

Stop server by key crtl-c or by closing the terminal.


# Deployment on Windows

Install [Java](https://adoptium.net)

Download PhotoDB [package](https://github.com/Nature40/photodb/releases) and extract.

# Running on Windows

Start PhotoDB server: Run the start script from the **command line** or just **double click** at the script file:

```
win_photodb.cmd
```

Open PhotoDB web-interface on a **web browser**.  
Local URL with default port 8080:

http://127.0.0.1:8080/

Stop server by key **ctrl-c** or by closing the terminal.

# Configuration

PhotoDB settings are in YAML file `config.yaml`
