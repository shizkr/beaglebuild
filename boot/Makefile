boot.scr: bootcmd
	mkimage -A arm -O linux -T script -C none -a 0 -e 0 -n "Beagleboard-xM boot script" -d bootcmd boot.scr

all : boot.scr

clean :
	rm boot.scr
