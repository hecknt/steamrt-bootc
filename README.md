# Steam Runtime Bootc

A container image built off of the Steam Runtime (yes, the steam runtime, not SteamOS) that is made to be bootable with bootc.

<img width="2558" height="1367" alt="image" src="https://github.com/user-attachments/assets/ff1a0e68-a580-43c5-b404-5a1e10d04983" />

## Building

In order to get a running steamrt-bootc system you can run the following steps:
```shell
just build-containerfile # This will build the containerfile and all the dependencies you need
just generate-bootable-image # Generates a bootable image for you using bootc!
```

Then you can run the `bootable.img` as your boot disk in your preferred hypervisor.

## Notes

Please don't fucking use this
