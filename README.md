# Pulse Jitter Analysis
This repository contains a python implementation of calculating jitter in pulsar data using PSRCHIVE and Tempo2 modules.
An example has been shown for the pulsar J1136+1551 using raw data from uGMRT.

This analysis was done under the guidance of Dr. Bhal Chandra Joshi for my NIUS Astronomy project.

## Prerequisites
Installing miniconda:
```
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

Installing psrchive and related packages:
```
conda config --add channels conda-forge
conda create -n pulsar psrchive
```

Once the installation is complete, activate the pulsar environment using:
```
conda activate pulsar
```
