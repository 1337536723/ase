#
# Makefile for Datastore
#

CC_PTHREAD_FLAGS			 = -lpthread
CC_FLAGS                     = -c 
CC_OUTPUT_FLAGS				 = -o
CC                           = gcc
RM                           = rm
RM_FLAGS                     = -f

TARGET  =   test
OBJS    =   datastore.o  test.o

all:	$(OBJS)
	$(CC) $(CC_OUTPUT_FLAGS) $(TARGET) $(OBJS)
	
test:
	echo ./test100
	echo ./test100

.c.o:
	$(CC) $(CC_FLAGS) $<

clean:

	$(RM) $(RM_FLAGS)  $(OBJS) $(TARGET) *.bak