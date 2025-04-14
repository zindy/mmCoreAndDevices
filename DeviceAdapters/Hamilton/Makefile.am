AM_CXXFLAGS = $(MMDEVAPI_CXXFLAGS)
deviceadapter_LTLIBRARIES = libmmgr_dal_Hamilton.la
libmmgr_dal_Hamilton_la_SOURCES = Hamilton.cpp \
				     HamiltonCommands.h \
				     HamiltonValves.h
libmmgr_dal_Hamilton_la_LIBADD = $(MMDEVAPI_LIBADD)
libmmgr_dal_Hamilton_la_LDFLAGS = $(MMDEVAPI_LDFLAGS)

if BUILD_CPP_TESTS
UNITTESTS = unittest
endif

SUBDIRS = . $(UNITTESTS)
