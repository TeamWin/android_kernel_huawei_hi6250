-include $(srctree)/drivers/hisi/modem/config/product/$(OBB_PRODUCT_NAME)/config/balong_product_config.mk
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/ccore/$(CFG_PLATFORM)/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/dsp/$(CFG_PLATFORM)/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/acore/$(CFG_PLATFORM)/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/acore/$(CFG_PLATFORM)/drv/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/common/$(CFG_PLATFORM)/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/platform/common/$(CFG_PLATFORM)/soc/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/adrv/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/drv/acore/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/drv/common/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/drv/common/include/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/nv/tl/drv/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/nv/product/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/nv/tl/oam/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/nv/tl/lps/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/phy/lphy/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/config/nvim/include/gu/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/taf/common/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/include/taf/acore/
subdir-ccflags-y += -I$(srctree)/drivers/hisi/modem/config/product/$(OBB_PRODUCT_NAME)/config

obj-$(CONFIG_HISI_BALONG_MODEM) +=drv/

ifneq ($(OBB_SEPARATE),true)
obj-$(CONFIG_HISI_BALONG_MODEM) +=oam/ ps/ taf/ 

#ifeq ($(CFG_FEATURE_IMS),FEATURE_ON)
obj-$(CONFIG_HISI_BALONG_MODEM) +=ims/
#endif

endif
