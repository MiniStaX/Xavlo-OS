After Updating Any File Follow These Commands In The Terminal Below
============================================================================

$ docker run --rm -it -v "%cd%":/root/env xavlo-os
## Wait For The Input Prompt To Pop-Up
$ make build-x86_64
## Wait For It To Finish
$ exit
## Wait For It To Exit
$ qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso