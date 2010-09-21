SUBDIRS = skins

install-exec-hook:
	$(PYTHON) $(srcdir)/genmetaindex.py $(DESTDIR)$(datadir)/meta/skin_*.xml > $(DESTDIR)$(datadir)/meta/index-enigma2-skins.xml

uninstall-hook:
	$(RM) $(DESTDIR)$(datadir)/meta/index-enigma2-skins.xml