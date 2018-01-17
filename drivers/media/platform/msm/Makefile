#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
<<<<<<< HEAD
ifeq ($(CONFIG_MACH_XIAOMI_MIDO),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_mido_v2/
=======
ifeq ($(CONFIG_MACH_XIAOMI_MARKW),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_markw/
>>>>>>> 51990ee... drivers: media: platform: msm: port markw camera
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_AIS) += ais/
obj-y += sde/
