# SliverPHP Quick Run
**Created by EmoticonYT**

A streamlined bash script to automate the SliverPHP activation bypass for iPad 2,1 and legacy iOS devices.

### Usage
Run this one-liner in the macOS Terminal:

`curl -LO "https://raw.githubusercontent.com/EmoticonYT/resources/refs/heads/main/sliverphp/quickrun.sh"; bash quickrun.sh && rm -rf quickrun.sh /tmp/sliverphp`

### Requirements
* macOS
* Any iDevice on iOS < 7.1 (Not including iOS 1.x-3.x and possibly 4.x-5.x), (iPad 2 supports all versions except possibly iOS 4.x-5.x but this is unconfirmed)
* USB Connection

### How it Works
1. Downloads the script and verifies the environment.
2. Validates the connected hardware/firmware compatibility.
3. Hosts a local activation server to handle the request.
4. Automatically cleans up all files and processes upon completion.
