#
# Makefile for the Novatek NT36xxx touchscreen driver.
#

# Each configuration option enables a list of files.

EXTRA_CFLAGS += $(call cc-option,-Wno-incompatible-pointer-types,)

obj-$(CONFIG_TOUCHSCREEN_NVT_E7S) += nt36xxx.o nt36xxx_fw_update.o nt36xxx_ext_proc.o nt36xxx_mp_ctrlram.o
