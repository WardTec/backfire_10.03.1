obj-$(CONFIG_RTL8187B)	+= rtl8187b.o

rtl8187b-objs := r8187_core.o \
	r8180_93cx6.o \
	r8180_wx.o \
	r8180_rtl8225.o \
	r8180_rtl8225z2.o \
	r8180_pm.o \
	r8180_dm.o \
	r8187_led.o \
	r8187_rfkill.o \
	ieee80211/dot11d.o \
	ieee80211/ieee80211_softmac.o \
	ieee80211/ieee80211_rx.o \
	ieee80211/ieee80211_tx.o \
	ieee80211/ieee80211_wx.o \
	ieee80211/ieee80211_module.o \
	ieee80211/ieee80211_softmac_wx.o \
	ieee80211/ieee80211_crypt.o \
	ieee80211/ieee80211_crypt_tkip.o \
	ieee80211/ieee80211_crypt_ccmp.o \
	ieee80211/ieee80211_crypt_wep.o

EXTRA_CFLAGS += -DCONFIG_RTL8180_PM
EXTRA_CFLAGS += -DJACKSON_NEW_8187 -DJACKSON_NEW_RX
EXTRA_CFLAGS += -DTHOMAS_BEACON -DTHOMAS_TASKLET -DTHOMAS_SKB -DTHOMAS_TURBO
EXTRA_CFLAGS += -DJOHN_IOCTL
EXTRA_CFLAGS += -DLED
#EXTRA_CFLAGS += -DLED_SHIN
#EXTRA_CFLAGS += -DSW_ANTE_DIVERSITY
EXTRA_CFLAGS += -DCPU_64BIT
EXTRA_CFLAGS += -DCONFIG_IPS
#CFLAGS += -DJOHN_HWSEC -DJOHN_TKIP
#CFLAGS += -DJOHN_DUMP_TX
#EXTRA_CFLAGS += -DJOHN_DUMP_TXPKT

#Radio On/Off debug
#EXTRA_CFLAGS += -DCONFIG_RADIO_DEBUG

#for dot11d
EXTRA_CFLAGS += -DENABLE_DOT11D
