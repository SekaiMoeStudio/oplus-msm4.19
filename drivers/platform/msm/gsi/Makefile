# SPDX-License-Identifier: GPL-2.0-only

KBUILD_CFLAGS += -fno-pic -mcmodel=large

gsidbg-$(CONFIG_DEBUG_FS) += gsi_dbg.o
obj-$(CONFIG_GSI) += gsi.o gsidbg.o

obj-$(CONFIG_IPA_EMULATION) += gsi_emulation.o
