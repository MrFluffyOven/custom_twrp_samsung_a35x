# Android device tree for samsung SM-A356E (a35x)

# Clone
    git clone https://github.com/MrFluffyOven/custom_twrp_samsung_a35x.git -b twrp-12.1 device/samsung/a35x

# Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_a35x-eng; mka recoveryimage
