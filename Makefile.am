lib_LTLIBRARIES = ircRelay.la

ircRelay_la_SOURCES = ircRelay.cpp
ircRelay_la_CPPFLAGS= -I$(top_srcdir)/include -I$(top_srcdir)/plugins/plugin_utils
ircRelay_la_LDFLAGS = -module -avoid-version -shared
ircRelay_la_LIBADD = $(top_builddir)/plugins/plugin_utils/libplugin_utils.la

AM_CPPFLAGS = $(CONF_CPPFLAGS)
AM_CFLAGS = $(CONF_CFLAGS)
AM_CXXFLAGS = $(CONF_CXXFLAGS)

EXTRA_DIST = \
	LICENSE.md \
	README.md \
	ircRelay.def \
	ircRelay.sln \
	ircRelay.vcxproj \
	ircRelay.vcxproj.filters

MAINTAINERCLEANFILES =	\
	Makefile.in
