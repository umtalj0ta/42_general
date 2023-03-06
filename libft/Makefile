COMPILER = gcc
LIBRARY = libft.a
AR = ar rcs
CFILES= ft_strlen.c ft_isdigit.c ft_isalpha.c
OBJECTS= ft_isdigit.o ft_strlen.o ft_isalpha.o

.c.o: $(CFILES)
	$(COMPILER) -c -o $@ $<

$(LIBRARY): $(OBJECTS)
	$(AR) $@ $^

all: $(LIBRARY)

clean:
	rm -f $(OBJECTS) $(LIBRARY)
fclean: clean
	rm $(LIBRARY)

re: clean all
