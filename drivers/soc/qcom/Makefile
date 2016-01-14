# When adding new entries keep the list in alphabetical order
CFLAGS_scm.o :=$(call as-instr,.arch_extension sec,-DREQUIRES_SEC=1)

# obj-y 					+= hotplug/

obj-$(CONFIG_MSM_LIMITER) += msm_limiter.o
obj-$(CONFIG_MSM_HOTPLUG) += msm_hotplug.o
obj-$(CONFIG_INTELLI_HOTPLUG) += intelli_hotplug.o
obj-$(CONFIG_BRICKED_HOTPLUG) += bricked_hotplug.o
obj-$(CONFIG_ALUCARD_HOTPLUG) += alucard_hotplug.o
