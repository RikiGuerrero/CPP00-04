NAME = ScavTrap
CC = g++
CPPFLAGS = -Wall -Werror -Wextra -std=c++98

SOURCES = ClapTrap.cpp \
		ScavTrap.cpp \
		main.cpp \

HEADERS = ClapTrap.hpp \
		ScavTrap.hpp

all: $(NAME)

$(NAME): $(SOURCES) $(HEADERS)
	$(CC) $(CPPFLAGS) $(SOURCES) -o $(NAME) 

clean:
	rm -f $(NAME)