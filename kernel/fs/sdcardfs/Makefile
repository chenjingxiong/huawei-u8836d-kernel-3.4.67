SDCARDFS_VERSION="0.1"

EXTRA_CFLAGS += -DSDCARDFS_VERSION=\"$(SDCARDFS_VERSION)\"

#obj-$(CONFIG_SDCARD_FS) += sdcardfs.o
obj-y += sdcardfs.o

sdcardfs-y := dentry.o file.o inode.o main.o super.o lookup.o mmap.o
