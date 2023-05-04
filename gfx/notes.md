# Install ImageMagick
sudo apt-get install imagemagick --fix-missing

## Convert to uncompressed 4-bit
convert symplr_logo-4.svg -depth 4 -type palette -compress none symplr8-5.bmp
