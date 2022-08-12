#!/bin/bash

CB=$(xclip)

qrencode -o - "$CB" --foreground=000000 --background=ffffff --size=30 | feh - &
sleep 20
pkill feh
exit

