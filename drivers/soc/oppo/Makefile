obj-$(CONFIG_OPPO_COMMON_SOFT)	+=  device_info/
obj-$(CONFIG_OPPO_DEVICE_IFNO)	+=  project_info/
obj-y +=  oppo_healthinfo/
#ifdef VENDOR_EDIT
#/* Yu.Kun@CN.NFC.Basic.Hardware, 2020/03/24, Add for oppo nfc chipset */
obj-$(CONFIG_OPPO_NFC)     +=  oppo_nfc/
#endif /* VENDOR_EDIT */

#Bin.Xu@BSP.Kernel.Stability.OPPO_SHUTDOWN_DETECT, 2020/05/11, Add for shutdown_detect
obj-$(CONFIG_OPPO_SHUTDOWN_DETECT)  +=  oppo_shutdown_detect/
#ifdef VENDOR_EDIT
#/*LiCheng@ODM.BSP.Sensor, 2020/05/22, Add for sensor smem */
obj-y +=  sensor/
#endif /* VENDOR_EDIT */

#//zhenwenxian@BSP.Power.Basic, 2017/01/12, Add for NV recovery
obj-$(CONFIG_RECORD_MDMRST)     +=  oppo_mdmrst/
#endif /* VENDOR_EDIT */
obj-$(CONFIG_OPPO_HYPNUS)     +=  oppo_hypnus/

#ifdef VENDOR_EDIT
#GaoTing.Gan@PSW.MultiMedia.MediaServer, 2019/03/07, Add for kevent feedback
obj-y +=  oppo_kevent_feedback/

#ifdef VENDOR_EDIT
#//wenbin.liu@PSW.Kernel.MM, 2018/05/23, Add for Healthinfo monitor
obj-y     +=  oppo_healthinfo/
#endif /* VENDOR_EDIT */

#/ifdef VENDOR_EDIT
#xuyechen@sensor.bsp.kernel, Add for sensor devinfo
obj-y +=  sensor/
#//endif

#ifdef OPLUS_FEATURE_LOWMEM_DBG
#Hailong.Liu@BSP.Kernel.MM, 2020/06/17, Add for dump mem when shrink
obj-$(CONFIG_OPLUS_FEATURE_LOWMEM_DBG)	+=  lowmem_dbg/
#endif /* OPLUS_FEATURE_LOWMEM_DBG */

#ifdef VENDOR_EDIT
#/* Hank.liu@TECH.PLAT.Storage, 2020-02-18, add oppo iomonitor driver*/
obj-$(CONFIG_OPPO_IOMONITOR)    +=  oppo_iomonitor/
