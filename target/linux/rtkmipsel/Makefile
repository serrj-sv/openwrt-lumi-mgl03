#
# Copyright (C) 2006-2008 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=mipsel
BOARD:=rtkmipsel
BOARDNAME:=Realtek mipsel SOC
SUBTARGETS:=rtl8197f
FEATURES:=squashfs usb nand ubifs
KERNEL_PATCHVER:=3.18

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for Realtek based boards
endef

$(eval $(call BuildTarget))
