obj-m += hello1.o
obj-m += hello2.o
obj-m += hello3.o
obj-m += hello4.o
obj-m += hello5.o
obj-m += chardev.o
obj-m += procfs1.o
obj-m += procfs2.o
obj-m += procfs3.o
obj-m += procfs4.o
startstop-objs := start.o stop.o
all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
