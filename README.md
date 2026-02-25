# Marathon Fastfetch

This repo contains a collection of marathon-based fastfetch themes.

# Installation Instructions

1. Extract the folders ```ascii``` and ```themes``` to an appropriate directory. For example ```~/.config/fastfetch/``` or ```/usr/share/fastfetch/```.

2. In ```themes```, edit the .jsonc file you want to use and make sure the ```logo: source:``` attribute is edited to reflect the absolute path to the correct .txt file in the ```ascii``` folder.

# Usage

Then to use, run fastfetch as so:

```fastfetch --config <path/to/config/file>```

To auto launch add the above command to your .bashrc file.

# Notes

These were designed with the default ghostty terminal in mind. Other terminals may have different aspect ratios for the ascii.

To generate your own ascii at custom aspect ratios, use the Image2ASCII program I wrote here: https://github.com/akqqa/cpp_practice/tree/main/Image2ASCII
