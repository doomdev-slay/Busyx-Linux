
# Running Busyx


WARNING: Download the source code from releases please! Otherwise you will not have all the files!

You can get the latest linux bzImage here: https://kernel.org/

To compile new version of initramfs run:


    make initramfs

# Tests:

To run Busyx in QEMU simply use the test script

      ./test


# Arch package

The prebuilt package for pacman can be seen in releases.
When downloaded run:

    pacman -U busyx-0.1-1-x86_64.pkg.tar.zst
    busyx

The OS will start in QEMU immediately. 
Problem: You must be in the source code directory.

