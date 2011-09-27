
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
CFLAGS   =  -fPIC  $(cflags)  -fPIC -Wall -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include -pthread -I/usr/include/glib-2.0 -I/usr/lib/glib-2.0/include -pthread 
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir) -I$(sitearchdir)  -I$(vendorarchdir) 
DEFS     = -D_FILE_OFFSET_BITS=64
CPPFLAGS = -DHAVE_RB_DEFINE_ALLOC_FUNC -DHAVE_RB_BLOCK_PROC -DHAVE_OBJECT_ALLOCATE -DHAVE_UNISTD_H -DHAVE_G_SPAWN_CLOSE_PID -DHAVE_G_THREAD_INIT -DHAVE_G_MAIN_DEPTH -DHAVE_G_LISTENV -DHAVE_RB_CHECK_ARRAY_TYPE -DHAVE_RB_EXEC_RECURSIVE -DHAVE_RB_ERRINFO -DHAVE_RB_SOURCEFILE -DHAVE_RB_SOURCELINE -DHAVE_RB_THREAD_BLOCKING_REGION -DHAVE_RUBY_NATIVE_THREAD_P -DRUBY_GLIB2_COMPILATION  $(DEFS) $(cppflags)
CXXFLAGS = $(CFLAGS)  $(cxxflags)
ldflags  = -L.  -rdynamic -Wl,-export-dynamic -pthread -pthread
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
DISTCLEANFILES = ruby-glib2.pc glib-enum-types.h glib-enum-types.c
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = 
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED)  -lgobject-2.0 -lgthread-2.0 -lrt -lglib-2.0 -lgthread-2.0 -lrt -lglib-2.0 -lpthread -lrt -ldl -lcrypt -lm   -lc
SRCS = rbgobj_enums.c rbgobj_convert.c rbglib_convert.c rbglib_int64.c rbglib_shell.c rbglib_win32.c rbglib_pollfd.c rbglib_error.c rbglib_unicode.c rbglib_messages.c rbgutil.c rbglib_mainloop.c rbglib.c rbgobj_valuearray.c rbglib_utils.c rbgobj_fundamental.c rbgobj_typeplugin.c rbgobj_typemodule.c rbgobj_valuetypes.c rbglib_maincontext.c rbgobj_strv.c rbgobj_closure.c rbglib_threads.c rbgobject.c rbglib_iochannel.c rbglib_spawn.c rbgobj_param.c rbgutil_callback.c rbgobj_type.c rbglib_i18n.c rbgobj_value.c rbglib_timer.c rbglib_fileutils.c rbgobj_typeinterface.c rbgobj_paramspecs.c rbgobj_object.c rbglib_source.c rbgobj_boxed.c glib-enum-types.c rbgobj_signal.c rbgobj_typeinstance.c rbglib_keyfile.c rbglib_bookmarkfile.c rbglib_completion.c
OBJS = rbgobj_enums.o rbgobj_convert.o rbglib_convert.o rbglib_int64.o rbglib_shell.o rbglib_win32.o rbglib_pollfd.o rbglib_error.o rbglib_unicode.o rbglib_messages.o rbgutil.o rbglib_mainloop.o rbglib.o rbgobj_valuearray.o rbglib_utils.o rbgobj_fundamental.o rbgobj_typeplugin.o rbgobj_typemodule.o rbgobj_valuetypes.o rbglib_maincontext.o rbgobj_strv.o rbgobj_closure.o rbglib_threads.o rbgobject.o rbglib_iochannel.o rbglib_spawn.o rbgobj_param.o rbgutil_callback.o rbgobj_type.o rbglib_i18n.o rbgobj_value.o rbglib_timer.o rbglib_fileutils.o rbgobj_typeinterface.o rbgobj_paramspecs.o rbgobj_object.o rbglib_source.o rbgobj_boxed.o glib-enum-types.o rbgobj_signal.o rbgobj_typeinstance.o rbglib_keyfile.o rbglib_bookmarkfile.o rbglib_completion.o
TARGET = glib2
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
install-so:
	$(INSTALL_DATA) $(srcdir)/rbglib.h $(RUBYARCHDIR)
	$(INSTALL_DATA) $(srcdir)/rbgutil.h $(RUBYARCHDIR)
	$(INSTALL_DATA) $(srcdir)/rbgobject.h $(RUBYARCHDIR)
	$(INSTALL_DATA) $(srcdir)/rbgcompat.h $(RUBYARCHDIR)
	$(INSTALL_DATA) glib-enum-types.h $(RUBYARCHDIR)

install:
	if test -n "$(pkgconfigdir)"; then			\
	  $(MAKEDIRS) $(pkgconfigdir);				\
	  $(INSTALL_DATA) ruby-glib2.pc $(pkgconfigdir);	\
	fi
