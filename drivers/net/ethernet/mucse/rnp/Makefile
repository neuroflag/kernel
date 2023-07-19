# SPDX-License-Identifier: GPL-2.0
# Copyright(c) 1999 - 2018 Intel Corporation.
#
# Makefile for the Intel(R) 82575 PCI-Express ethernet driver
#

# obj-$(CONFIG_IGB) += igb.o

# igb-objs := igb_main.o igb_ethtool.o e1000_82575.o \
#             e1000_mac.o e1000_nvm.o e1000_phy.o e1000_mbx.o \
#             e1000_i210.o igb_ptp.o igb_hwmon.o
obj-$(CONFIG_IGB) := rnp.o
rnp-objs :=   \
		rnp_main.o \
		rnp_common.o \
		rnp_debugfs.o \
		rnp_ethtool.o \
		rnp_lib.o \
		rnp_mbx.o \
		rnp_pcs.o \
		rnp_n10.o \
		rnp_n500.o \
		rnp_phy.o \
		rnp_mbx_fw.o\
		rnp_sriov.o \
		rnp_param.o \
		rnp_compat.o \
		rnp_sysfs.o \
		rnp_dcb.o \
		rnp_ptp.o \
		rnp_mpe.o