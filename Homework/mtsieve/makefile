###############################################################################
# Date: June 28th, 2021
# Pledge: I pledge my honor that I have abided by the Stevens Honor System.
# Description: Makefile for mtsieve
###############################################################################

CC     = gcc
C_FILE = $(wildcard *.c)
TARGET = $(patsubst %.c,%,$(C_FILE))
CFLAGS = -g -Wall -Werror -pedantic-errors

all:
	$(CC) $(CFLAGS) $(C_FILE) -o $(TARGET) -lm -pthread
clean:
	rm -f $(TARGET) $(TARGET).exe
