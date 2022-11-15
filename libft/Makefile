# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: aamhal <aamhal@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/10/22 10:32:49 by aamhal            #+#    #+#              #
#    Updated: 2022/11/03 18:48:27 by aamhal           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SOURCE = ft_isalpha.c \
            ft_isdigit.c \
            ft_isalnum.c \
            ft_isascii.c \
            ft_isprint.c \
            ft_strlen.c \
            ft_memset.c \
            ft_bzero.c \
            ft_memcpy.c \
            ft_memmove.c \
            ft_strlcpy.c \
            ft_toupper.c \
            ft_tolower.c \
            ft_strchr.c \
            ft_strrchr.c \
            ft_strncmp.c \
            ft_memchr.c \
            ft_memcmp.c \
            ft_calloc.c \
            ft_strdup.c \
            ft_atoi.c \
            ft_strlcat.c \
            ft_strnstr.c \
            ft_substr.c \
            ft_strjoin.c \
            ft_putchar_fd.c \
            ft_putendl_fd.c \
            ft_putstr_fd.c \
            ft_putnbr_fd.c \
            ft_itoa.c \
            ft_strtrim.c \
            ft_striteri.c \
            ft_strmapi.c \
            ft_split.c
            
NAME = libft.a

CC = cc

FLAGS = -Wall -Wextra -Werror

RM = rm -f

OBJECTS    = $(SOURCE:.c=.o)

%.o : %.c libft.h
	$(CC) $(FLAGS) -c $< -o $@

$(NAME) : $(OBJECTS)
	ar rc $(NAME) $(OBJECTS)
    
all: $(NAME)
    
clean:
	$(RM) $(OBJECTS) 

fclean: clean
	$(RM) $(NAME) 

re: fclean all
