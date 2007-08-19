.PHONY: all install uninstall

SCRIPT=fortune-zh

all:fortune-zh

install: $(SCRIPT)
	install -m 0755 $< $(DESTDIR)/usr/bin
	ln -sf fortune-zh $(DESTDIR)/usr/bin/fortune-sc
	ln -sf fortune-zh $(DESTDIR)/usr/bin/fortune-tc

uninstall: $(SCRIPT)
	rm -rf $(DESTDIR)/usr/bin/$(SCRIPT)
