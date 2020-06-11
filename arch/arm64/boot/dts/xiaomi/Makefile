ifeq ($(CONFIG_MACH_XIAOMI_SANTONI_TREBLE),y)
dtb-$(CONFIG_MACH_XIAOMI_SANTONI_TREBLE) += santoni-bleed-treble.dtb
else
dtb-$(CONFIG_MACH_XIAOMI_SANTONI) += santoni-bleed.dtb
endif

ifeq ($(CONFIG_MACH_XIAOMI_LAND_TREBLE),y)
dtb-$(CONFIG_MACH_XIAOMI_LAND_TREBLE) += msm8937-wt88537-treble.dtb
else
dtb-$(CONFIG_MACH_XIAOMI_LAND) += msm8937-wt88537.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
