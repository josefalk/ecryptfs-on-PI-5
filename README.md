# ecryptfs-on-PI-5 on on NVMe Partition:

Encrypt Home Directory in Raspberry PI 5 NVMe.

The setup ment to have a sperate partition for the home directory in the same NVMe disk and encrypt it using ecryptfs

## Description

Encrypting an NVMe drive on a Raspberry Pi is a good way to protect your data in case the drive is lost or stolen. You can use the Linux built-in encryption tools to achieve this. Here's a step-by-step guide to encrypt your NVMe drive on a Raspberry Pi.

To avoid removing the NVMe every time you install PI OS on it, I prepared the SD card, Install PI OS in it, I insert it (Pi will boot from SD by default) and then I can install PI OS on NVMe drive and partition it in the same time.

### Prepare and partition the NVMe:

You can prepare the NVMe from USB reader of course, It will be similar steps.
