NAME = libft.a

FLAGS = -Wall -Werror -Wextra -g

SRC = ft_atoi.c \
		  ft_isalpha.c \
		  ft_bzero.c \
		  ft_isalnum.c \
		  ft_isascii.c \
		  ft_isdigit.c \
		  ft_isprint.c \
		  ft_count_words.c \
		  ft_memalloc.c \
		  ft_memccpy.c \
		  ft_memcmp.c \
		  ft_itoa.c \
		  ft_memdel.c \
		  ft_memchr.c \
		  ft_putchar.c \
		  ft_memcpy.c \
		  ft_putchar_fd.c \
		  ft_memset.c \
		  ft_memmove.c \
		  ft_putendl.c \
		  ft_putendl_fd.c \
		  ft_putnbr_fd.c \
		  ft_putstr.c \
		  ft_putstr_fd.c \
		  ft_putnbr.c \
		  ft_strcat.c \
		  ft_strchr.c \
		  ft_strclr.c \
		  ft_strdel.c \
		  ft_strdup.c \
		  ft_strndup.c \
		  ft_strcmp.c \
		  ft_strcpy.c \
		  ft_striter.c \
		  ft_strequ.c \
		  ft_striteri.c \
		  ft_strlen.c \
		  ft_strmapi.c \
		  ft_strjoin.c \
		  ft_strnjoin.c \
		  ft_freejoin.c \
		  ft_strncat.c \
		  ft_strmap.c \
		  ft_strncmp.c \
		  ft_strncpy.c \
		  ft_strnequ.c \
		  ft_strnew.c \
		  ft_strrchr.c \
		  ft_strstr.c \
		  ft_strsub.c \
		  ft_tolower.c \
		  ft_toupper.c \
		  ft_strnstr.c \
		  ft_strtrim.c \
		  ft_wordlen.c \
		  ft_strsplit.c \
		  ft_strlcat.c \
		  ft_lstnew.c \
		  ft_lstdelone.c \
		  ft_lstdel.c \
		  ft_lstadd.c \
		  ft_lstiter.c \
		  ft_lstmap.c \
		  ft_lstdelelem.c \
		  ft_lstaddback.c

OBJ = $(SRC:.c=.o)

INCLUDE = libft.h

all: $(NAME)

%.o : %.c $(INCLUDE)
	@gcc $(FLAGS) -c $<

$(NAME): $(OBJ)
	@ar rc $(NAME) $(OBJ)
	@echo "LIBFT COMPILED"
	@ranlib $(NAME)

clean:
	@rm -rf $(OBJ)

fclean: clean
	@rm -rf $(NAME)

re: fclean all
