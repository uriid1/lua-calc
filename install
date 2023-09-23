#!/usr/bin/env bash

# Check lua installed
if ! [ -x "$(command -v lua)" ]; then
    echo "Error: lua is not installed!"
    exit 1
fi

# Programm name
pname='calc'

# Install
chmod +x $pname
cp $pname ~/.local/bin/
echo "$pname installed successfully in ~/.local/bin/"