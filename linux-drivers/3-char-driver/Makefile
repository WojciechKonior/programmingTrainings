all:
	make -C /lib/modules/`uname -r`/build M=$(PWD) modules

multifile-objs := mymodule.o

obj-m += mymodule.o

clean:
	rm -rf *.o *.ko *.mod.c .an* .lab* .tmp_versions Module.symvers Module.markers modules.order .*.cmd *.mod
