# vbam-libretro-pack
Special versions of vbam-libretro for RetroArch

# How to setup for each pack
- Unzip the package you want
- cd /src/libretro
- make

After all these commands, you will get the .so file for RetroArch

# How to use the libraries
- Solo mode : retroarch -L /Your directory/vbam_libretro.so File.gba
- Server mode (2 Players mode ) : retroarch -L /Your directory/vbam_2PServ_libretro.so File.gba
- Server mode (3 Players mode ) : retroarch -L /Your directory/vbam_3PServ_libretro.so File.gba
- Server mode (4 Players mode ) : retroarch -L /Your directory/vbam_4PServ_libretro.so File.gba
- Client mode (To connect to PC Server mode in local mode ) : retroarch -L /Your directory/vbam_client_libretro.so File.gba
