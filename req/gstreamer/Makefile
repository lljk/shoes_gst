all:
	(cd ext/gstreamer && $(MAKE))
	$(MAKE) -f Makefile.lib

install:
	(cd ext/gstreamer && $(MAKE) install)
	$(MAKE) -f Makefile.lib install

site-install:
	(cd ext/gstreamer && $(MAKE) site-install)
	$(MAKE) -f Makefile.lib site-install

clean:
	(cd ext/gstreamer && $(MAKE) clean)
	$(MAKE) -f Makefile.lib clean

distclean:
	(cd ext/gstreamer && $(MAKE) distclean)
	$(MAKE) -f Makefile.lib distclean
	@rm -f Makefile.lib
