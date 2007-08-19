FORTUNE_DIR = /usr/share/fortune
NAME=zh-joke

$(NAME).dat: $(NAME)
	strfile $(NAME)

install:
	install -m 0644 $(NAME) $(NAME).dat $(FORTUNE_DIR)
	ln -sf $(NAME) $(FORTUNE_DIR)/$(NAME).u8
	install -m 0755 gfortune-$(NAME) /usr/bin

uninstall:
	rm $(FORTUNE_DIR)/$(NAME) $(FORTUNE_DIR)/$(NAME).dat $(FORTUNE_DIR)/$(NAME).u8 /usr/bin/gfortune-$(NAME)
