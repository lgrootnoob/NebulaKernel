obj-$(CONFIG_PM_DEVFREQ)			+= devfreq.o
obj-$(CONFIG_DEVFREQ_GOV_SIMPLE_ONDEMAND)	+= governor_simpleondemand.o
obj-$(CONFIG_DEVFREQ_GOV_PERFORMANCE)		+= governor_performance.o
obj-$(CONFIG_DEVFREQ_GOV_POWERSAVE)		+= governor_powersave.o
obj-$(CONFIG_DEVFREQ_GOV_USERSPACE)		+= governor_userspace.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_ADRENO_TZ)		+= governor_msm_adreno_tz.o
obj-$(CONFIG_ADRENO_IDLER)			+= adreno_idler.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_CPUFREQ)		+= governor_msm_cpufreq.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_BW_HWMON)		+= governor_bw_hwmon.o
obj-$(CONFIG_SIMPLE_GPU_ALGORITHM)		+= simple_gpu_algorithm.o
obj-$(CONFIG_DEVFREQ_GOV_MSM_CACHE_HWMON)	+= governor_cache_hwmon.o
obj-$(CONFIG_ARCH_MSM_KRAIT)			+= krait-l2pm.o


# DEVFREQ Drivers
obj-$(CONFIG_LGE_DEVFREQ_DFPS)  += g3_display.o
ccflags-$(CONFIG_LGE_DEVFREQ_DFPS) += -I$(srctree)/drivers/video/msm/mdss

obj-$(CONFIG_ARM_EXYNOS4_BUS_DEVFREQ)	+= exynos4_bus.o
