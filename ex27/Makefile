# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: groberto <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/07 14:02:38 by groberto          #+#    #+#              #
#    Updated: 2018/11/07 16:18:58 by groberto         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME	= ft_display_file

SRC		= ft_display_file.c

all: $(NAME)

$(NAME) :
	gcc -c -Wall -Werror -Wextra $(SRC)
	gcc -o $(NAME) ft_display_file.o

clean:
	rm -f ft_display_file.o 

fclean:
	rm -f $(NAME)

re: fclean all
