FORTUNE_DIR = /usr/share/fortune

lunyu.dat: lunyu
	strfile lunyu

install:
	cp lunyu lunyu.dat $(FORTUNE_DIR)

uninstall:
	rm $(FORTUNE_DIR)/lunyu $(FORTUNE_DIR)/lunyu.dat
