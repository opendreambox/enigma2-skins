SUBDIRS = skins

metadir = $(datadir)/meta
meta_DATA = index-enigma2-skins.xml
CLEANFILES = index-enigma2-skins.xml

index-enigma2-skins.xml: $(top_srcdir)/genmetaindex.py $(top_srcdir)/skins/*/meta/skin_*.xml
	$(AM_V_GEN)$(PYTHON) $^ > $@
