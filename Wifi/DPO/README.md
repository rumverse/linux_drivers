For some Linux systems, due to updates in the compiler, you will need to apply the patch to struct for property to int to kguid.

To apply,
cd /to/this/README.md/file/directory
patch -p0 < rt2870-mt7601Usta-kuid_t-kgid_t.patch

Original patch from - http://www.arnelborja.com/compiling-rt2870-wifi-driver-in-fedora/
