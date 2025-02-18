NAME = Phonebook
CC = g++
CPPFLAGS = -Wall -Werror -Wextra -std=c++98

SOURCES = main.cpp \
		PhoneBook.cpp \
		Contact.cpp

HEADERS = PhoneBook.hpp \
		Contact.hpp

RM = rm -f

all: $(NAME)

$(NAME): $(SOURCES) $(HEADERS)
	$(CC) $(CPPFLAGS) $(SOURCES) -o $(NAME) 

clean:
	$(RM) $(NAME)