#
# Copyright (C) 2016-2017 Dan Luedtke <mail@danrl.com>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=WireGuard Status
LUCI_DEPENDS:=+wireguard-tools +kmod-wireguard
LUCI_PKGARCH:=all

PKG_MAINTAINER:=Dan Luedtke <mail@danrl.com>

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
