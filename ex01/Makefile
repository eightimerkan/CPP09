NAME = RPN
CC = g++
FLAGS = -Wall -Wextra -Werror -std=c++98
RM = rm -rf

.PHONY: all clean fclean re

all: $(NAME)

$(NAME): main.cpp RPN.cpp
	@$(CC) $(FLAGS) main.cpp RPN.cpp -o $(NAME)

clean:
	@$(RM) $(NAME)

fclean: clean

re: fclean all