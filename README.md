# vbmeta patcher ci

## Basic Information

A CI to patch vbmeta images to disable verification on them

Using this CI service you'll be able to upload vbmeta images and then download a patched one that has had verification disabled

Using the CI service it'll be the equivalent of ```fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img```

## How to use it

Fork the repo
Upload any img files into the "blobs" folder
Run the ci
