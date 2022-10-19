# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: hcherpre <hcherpre@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/10/19 18:05:39 by hcherpre          #+#    #+#              #
#    Updated: 2022/10/19 18:09:37 by hcherpre         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME =		Fixed

SRCS =		main.cpp Fixed.cpp

C++ =		c++

CFLAGS =	-Wall -Wextra -Werror -std=c++98

RM =		rm -rf

all:		${NAME}

${NAME}:
	@${C++} ${CFLAGS} ${SRCS} -o ${NAME}

clean:		
	@${RM}

fclean:		clean
	@${RM} ${NAME}

re:			fclean all

.PHONY:		all clean fclean re