# CentOS-ISO-Downloader
A quick python script to list, test speed and download a CentOS ISO image. I'm using it just to avoid going on CentOS mirrorlist and lookup the URL to wget. 

## Setup
Just get the main py script.

## Usage
`./get-centos.py (-v)`

The only argument is currently just `-v`, which enables script's verbose and interactive execution. It's basically showing the URLs the script fetched from mirrorlist, along with the speed, and it asks for downloading (instead of going ahead and download without confirmation) the latest ISO.
