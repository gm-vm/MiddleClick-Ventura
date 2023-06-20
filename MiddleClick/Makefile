CC=clang

CCFLAGS = \
    -F /System/Library/PrivateFrameworks/ \
    -framework MultitouchSupport \
    -framework IOKit \
    -framework ApplicationServices \
    -framework Cocoa \
    -framework CoreData \
    -framework AppKit \
    -framework Foundation \
    -fno-objc-arc \
    -lobjc *.m -o MiddleClick

all:
	$(CC) $(CCFLAGS)
