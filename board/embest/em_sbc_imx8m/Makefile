#
# Copyright 2016 Freescale Semiconductor
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += em_sbc_imx8m.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-$(CONFIG_IMX8M_LPDDR4) += lpddr4_timing.o
endif
