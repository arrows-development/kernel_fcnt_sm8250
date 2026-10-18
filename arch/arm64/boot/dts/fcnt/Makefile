# SPDX-License-Identifier: GPL-2.0
# FCNT arrows 5G (F-51A, amaterasu)

dtb-$(CONFIG_MACH_FCNT_AMATERASU) += \
	amaterasu-kona.dtb \
	amaterasu-kona-v2.dtb \
	amaterasu-kona-v2.1.dtb

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_MACH_FCNT_AMATERASU) += \
	amaterasu-ffrd-rev1-sku0-overlay.dtbo \
	amaterasu-ffrd-rev2-sku0-overlay.dtbo \
	amaterasu-ffrd-rev2-sku1-overlay.dtbo \
	amaterasu-ffrd-rev3-sku3-overlay.dtbo \
	amaterasu-ffrd-rev4-sku3-overlay.dtbo \
	amaterasu-ffrd-rev5-sku3-overlay.dtbo \
	amaterasu-ffrd-rev6-sku3-overlay.dtbo \
	amaterasu-ffrd-rev7-sku0-overlay.dtbo \
	amaterasu-ffrd-rev7-sku3-overlay.dtbo \
	amaterasu-ffrd-r-rev0-sku3-overlay.dtbo \
	amaterasu-ffrd-r-rev1-sku3-overlay.dtbo

amaterasu-ffrd-rev1-sku0-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev2-sku0-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev2-sku1-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev3-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev4-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev5-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev6-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev7-sku0-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-rev7-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-r-rev0-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
amaterasu-ffrd-r-rev1-sku3-overlay.dtbo-base := amaterasu-kona.dtb amaterasu-kona-v2.dtb amaterasu-kona-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
