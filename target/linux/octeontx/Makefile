# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2018 OpenWrt.org

include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=octeontx
BOARDNAME:=Octeon-TX
FEATURES:=squashfs ramdisk targz pcie gpio rtc usb fpu

KERNEL_PATCHVER:=5.10

define Target/Description
	Build images for Octeon-TX CN80XX/CN81XX based boards
endef

include $(INCLUDE_DIR)/target.mk

KERNELNAME:=Image

$(eval $(call BuildTarget))
