bin_PROGRAMS = mentohust

sysconfdir = /etc

dist_sysconf_DATA = mentohust.conf

mentohust_SOURCES = myini.c md5.c mycheck.c dlfunc.c myfunc.c mystate.c myconfig.c mentohust.c

mentohust_SOURCES += i18n.h types.h myini.h md5.h mycheck.h dlfunc.h myfunc.h mystate.h myconfig.h

mentohust_LDADD = $(LDADD) $(DBUS_LIBS)
AM_CFLAGS = $(DBUS_CFLAGS)

if WITH_GTK2
SUBDIRS = gtk2
endif
