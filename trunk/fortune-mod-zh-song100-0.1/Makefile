FORTUNE_DIR = /usr/share/fortune
NAME=zh-song100

$(NAME).dat: $(NAME)
	strfile $(NAME)

install:
	install -m 0644 $(NAME) $(NAME).dat $(FORTUNE_DIR)

uninstall:
	rm $(FORTUNE_DIR)/$(NAME) $(FORTUNE_DIR)/$(NAME).dat
