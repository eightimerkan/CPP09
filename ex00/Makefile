NAME = btc
CC = g++
FLAGS = -Wall -Wextra -Werror -std=c++98
RM = rm -rf

.PHONY: all clean fclean re

all: $(NAME)

$(NAME): main.cpp BitcoinExchange.cpp
	@$(CC) $(FLAGS) main.cpp BitcoinExchange.cpp -o $(NAME)

clean:
	@$(RM) $(NAME)

fclean: clean

re: fclean all