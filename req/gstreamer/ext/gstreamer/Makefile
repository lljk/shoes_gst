
SHELL = /bin/sh

#### Start of system configuration section. ####

srcdir = .
topdir = /home/jk/.rvm/rubies/ruby-1.9.1-p378/include/ruby-1.9.1
hdrdir = /home/jk/.rvm/rubies/ruby-1.9.1-p378/include/ruby-1.9.1
arch_hdrdir = /home/jk/.rvm/rubies/ruby-1.9.1-p378/include/ruby-1.9.1/$(arch)
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
prefix = $(DESTDIR)/home/jk/.rvm/rubies/ruby-1.9.1-p378
exec_prefix = $(prefix)
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(includedir)/$(RUBY_INSTALL_NAME)-$(ruby_version)
vendordir = $(libdir)/$(RUBY_INSTALL_NAME)/vendor_ruby
sitedir = $(libdir)/$(RUBY_INSTALL_NAME)/site_ruby
mandir = $(datarootdir)/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(datarootdir)/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = $(DESTDIR)/usr/include
includedir = $(prefix)/include
localstatedir = $(prefix)/var
sharedstatedir = $(prefix)/com
sysconfdir = $(prefix)/etc
datadir = $(datarootdir)
datarootdir = $(prefix)/share
libexecdir = $(exec_prefix)/libexec
sbindir = $(exec_prefix)/sbin
bindir = $(exec_prefix)/bin
rubylibdir = $(libdir)/$(ruby_install_name)/$(ruby_version)
archdir = $(rubylibdir)/$(arch)
sitelibdir = $(sitedir)/$(ruby_version)
sitearchdir = $(sitelibdir)/$(sitearch)
vendorlibdir = $(vendordir)/$(ruby_version)
vendorarchdir = $(vendorlibdir)/$(sitearch)

CC = gcc
CXX = g++
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -Wl,-R -Wl,$(libdir) -L$(libdir) -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -Wl,-R -Wl,$(libdir) -L$(libdir) -l$(RUBY_SO_NAME)-static
OUTFLAG = -o 
COUTFLAG = -o 

RUBY_EXTCONF_H = 
cflags   = $(optflags) $(debugflags) $(warnflags)
optflags = -O2
debugflags = -g
warnflags = -Wall -Wno-parentheses
CFLAGS   =  -fPIC  $(cflags)  -fPIC -Wall -I/usr/include/gstreamer-0.10 -I/usr/include/libxml2 -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include -pthread -I/usr/include/gstreamer-0.10 -I/usr/include/libxml2 -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include -pthread -DHAVE_GST_OVERLAY -I/usr/include/gstreamer-0.10 -I/usr/include/libxml2 -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include -pthread -DHAVE_GST_PBUTILS 
INCFLAGS = -I. -I/home/jk/shoes2/req/glib2/ext/glib2 -I/home/jk/shoes2/req/glib2/ext/glib2 -I/home/jk/shoes2/req/glib2/ext/glib2 -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir) -I$(sitearchdir)  -I$(vendorarchdir) 
DEFS     = -D_FILE_OFFSET_BITS=64
CPPFLAGS = -DHAVE_RB_DEFINE_ALLOC_FUNC -DHAVE_RB_BLOCK_PROC -DHAVE_OBJECT_ALLOCATE -DHAVE_UNISTD_H -DHAVE_GST_INTERFACES_XOVERLAY_H -DRUBY_GST_COMPILATION  $(DEFS) $(cppflags)
CXXFLAGS = $(CFLAGS)  $(cxxflags)
ldflags  = -L.  -rdynamic -Wl,-export-dynamic -pthread -pthread -pthread
dldflags = 
archflag = 
DLDFLAGS = $(ldflags) $(dldflags) $(archflag)
LDSHARED = $(CC) -shared
LDSHAREDXX = $(CXX) -shared
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = ruby
RUBY_SO_NAME = ruby
arch = i686-linux
sitearch = i686-linux
ruby_version = 1.9.1
ruby = /home/jk/.rvm/rubies/ruby-1.9.1-p378/bin/ruby
RUBY = $(ruby)
RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = $(RUBY) -run -e rmdir -- -p
MAKEDIRS = mkdir -p
INSTALL = /usr/bin/install -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp

#### End of system configuration section. ####

preload = 

libpath = . $(libdir)
LIBPATH =  -L. -L$(libdir) -Wl,-R$(libdir)
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = ruby-gstreamer.pc
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = 
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED) -lgstinterfaces-0.10  -lgstreamer-0.10 -lxml2 -lgthread-2.0 -lrt -lglib-2.0 -lgmodule-2.0 -lgobject-2.0 -lgstreamer-0.10 -lxml2 -lgthread-2.0 -lrt -lglib-2.0 -lgmodule-2.0 -lgobject-2.0 -lgstpbutils-0.10 -lgstreamer-0.10 -lxml2 -lgthread-2.0 -lrt -lglib-2.0 -lgmodule-2.0 -lgobject-2.0 -lpthread -lrt -ldl -lcrypt -lm   -lc
SRCS = rbgstregistry.c rbgst-element-factory.c rbgst-pad-template.c rbgstindex.c rbgst-object.c rbgstparse.c rbgst-pad.c rbgstindexentry.c rbgst-x-overlay.c rbgstclockentry.c rbgst-system-clock.c rbgst-private.c rbgsttagsetter.c rbgst-static-pad-template.c rbgst-query.c rbgst-seek.c rbgst-event.c rbgsttag.c rbgst-plugin-feature.c rbgst-child-proxy.c rbgstxml.c rbgst-element.c rbgst-type-find-factory.c rbgst-value.c rbgst-bin.c rbgst-message.c rbgst-index-factory.c rbgst-install-plugins.c rbgst-static-caps.c rbgst-structure.c rbgst-mini-object.c rbgst-ghost-pad.c rbgst-caps.c rbgst-buffer.c rbgst-plugin.c misc.c rbgst-bus.c rbgstformat.c rbgst-pipeline.c rbgst.c rbgstquerytype.c rbgst-clock.c
OBJS = rbgstregistry.o rbgst-element-factory.o rbgst-pad-template.o rbgstindex.o rbgst-object.o rbgstparse.o rbgst-pad.o rbgstindexentry.o rbgst-x-overlay.o rbgstclockentry.o rbgst-system-clock.o rbgst-private.o rbgsttagsetter.o rbgst-static-pad-template.o rbgst-query.o rbgst-seek.o rbgst-event.o rbgsttag.o rbgst-plugin-feature.o rbgst-child-proxy.o rbgstxml.o rbgst-element.o rbgst-type-find-factory.o rbgst-value.o rbgst-bin.o rbgst-message.o rbgst-index-factory.o rbgst-install-plugins.o rbgst-static-caps.o rbgst-structure.o rbgst-mini-object.o rbgst-ghost-pad.o rbgst-caps.o rbgst-buffer.o rbgst-plugin.o misc.o rbgst-bus.o rbgstformat.o rbgst-pipeline.o rbgst.o rbgstquerytype.o rbgst-clock.o
TARGET = gst
DLLIB = $(TARGET).so
EXTSTATIC = 
STATIC_LIB = 

BINDIR        = $(bindir)
RUBYCOMMONDIR = $(sitedir)$(target_prefix)
RUBYLIBDIR    = $(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(sitearchdir)$(target_prefix)
HDRDIR        = $(rubyhdrdir)/ruby$(target_prefix)
ARCHHDRDIR    = $(rubyhdrdir)/$(arch)/ruby$(target_prefix)

TARGET_SO     = $(DLLIB)
CLEANLIBS     = $(TARGET).so 
CLEANOBJS     = *.o  *.bak

all:    $(DLLIB)
static: $(STATIC_LIB)

clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-rb-default clean-rb
		@-$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES)

distclean-rb-default::
distclean-rb::
distclean-so::
distclean: clean distclean-so distclean-rb-default distclean-rb
		@-$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		@-$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		@-$(RMDIRS) $(DISTCLEANDIRS)

realclean: distclean
install: install-so install-rb

install-so: $(RUBYARCHDIR)
install-so: $(RUBYARCHDIR)/$(DLLIB)
$(RUBYARCHDIR)/$(DLLIB): $(DLLIB)
	$(INSTALL_PROG) $(DLLIB) $(RUBYARCHDIR)
install-rb: pre-install-rb install-rb-default
install-rb-default: pre-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
$(RUBYARCHDIR):
	$(MAKEDIRS) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .cxx .cpp .C .o

.cc.o:
	$(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cxx.o:
	$(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.cpp.o:
	$(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.C.o:
	$(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $<

.c.o:
	$(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $<

$(DLLIB): $(OBJS) Makefile
	@-$(RM) $(@)
	$(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)



###
install:
	if test -n "$(pkgconfigdir)"; then			\
	  $(MAKEDIRS) $(pkgconfigdir);				\
	  $(INSTALL_DATA) ruby-gstreamer.pc $(pkgconfigdir);	\
	fi
