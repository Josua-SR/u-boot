#
# Copyright 2019 SolidRun ltd.
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx8mm_solidrun.o mmc.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing.o
obj-$(CONFIG_IMX8M_DDR4) += ddr4_timing.o
endif
