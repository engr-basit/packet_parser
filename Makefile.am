AUTOMAKE_OPTIONS = subdir-objects

bin_PROGRAMS = packet_parser

packet_parser_SOURCES = \
    src/parser.c \
    src/ethernet/ethernet.c

packet_parser_CPPFLAGS = -I./include -I/usr/local/include
packet_parser_LDFLAGS  = -lm