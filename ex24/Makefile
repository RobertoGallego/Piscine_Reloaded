# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: groberto <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/07 14:02:38 by groberto          #+#    #+#              #
#    Updated: 2018/11/07 14:48:09 by groberto         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME	= libft.a

SRC_DIR	= srcs

INC_DIR	= includes

$(NAME): all

all:
	gcc -c -Wall -Werror -Wextra $(SRC_DIR)/*.c -I$(INC_DIR)
	ar rcs $(NAME) *.o
	ranlib $(NAME)

clean:
	rm -f *.o

fclean:
	rm -f $(NAME)

re: fclean all
