#
# Copyright (C) 2011-2012 Synopsys, Inc. (www.synopsys.com)
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#

KBUILD_CFLAGS	+= -Iarch/arc/plat-arcfpga/include

obj-y := platform.o irq.o
obj-$(CONFIG_SMP)		+= smp.o
obj-$(CONFIG_ARC_IDE)		+= arc_ide.o
