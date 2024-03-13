ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
ifneq (,$(filter AI2202,$(ASUS_BUILD_PROJECT)))
$(warning build dtbo for AI2202...)

dtbo-$(CONFIG_ARCH_WAIPIO) += AI2202-EVB-overlay.dtbo
dtbo-$(CONFIG_ARCH_WAIPIO) += AI2202-SR-overlay.dtbo
dtbo-$(CONFIG_ARCH_WAIPIO) += AI2202-SR2-overlay.dtbo
dtbo-$(CONFIG_ARCH_WAIPIO) += AI2202-ER-overlay.dtbo
dtbo-$(CONFIG_ARCH_WAIPIO) += AI2202-ER2-2-overlay.dtbo

AI2202-EVB-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
AI2202-SR-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
AI2202-SR2-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
AI2202-ER-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
AI2202-ER2-2-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
endif
endif

-always-y       := $(dtb-y)
-subdir-y       := $(dts-dirs)
-clean-files    := *.dtb *.dtbo