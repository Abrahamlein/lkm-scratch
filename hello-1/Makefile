#
# Disclaimer:
# Source https://www.tldp.org/LDP/lkmpg/2.6/html/x181.html
#


obj-m += hello-1.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean

