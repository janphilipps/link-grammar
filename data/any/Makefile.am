
DICTS=                           \
      4.0.affix                  \
      4.0.constituent-knowledge  \
      4.0.dict                   \
      4.0.knowledge              \
      4.0.regex

dictdir=$(pkgdatadir)/any
dict_DATA = $(DICTS)

EXTRA_DIST = $(DICTS)

# The make uninstall target should remove directories we created.
uninstall-hook:
	-rmdir $(dictdir)
