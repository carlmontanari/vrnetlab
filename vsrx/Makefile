VENDOR=Juniper
NAME=vSRX
IMAGE_FORMAT=qcow
IMAGE_GLOB=*.qcow2
IMAGE=ffp-12.1X47-D15.4-packetmode.qcow2

# match versions like:
# media-vsrx-vmdisk-15.1X49-D180.2.qcow2 or media-vsrx-vmdisk-17.3R2.10.qcow2
VERSION=$(shell echo $(IMAGE) | sed -e 's/[a-zA-Z\-]\+\([0-9]\+\.[0-9]\+[XR][0-9]\+[\.\-]\+[A-Z0-9]\+\)\([^0-9].*\|$$\)/\1/')

-include ../makefile-sanity.include
-include ../makefile.include
