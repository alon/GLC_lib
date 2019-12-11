debian packaging is very basic, misses all dependency information, and requires the following ppa and packages:

sudo add-apt-repository ppa:beineri/opt-qt-5.11.3-xenial
sudo apt update
sudo apt install libc6 libexpat1 libgcc1 libgl1-mesa-glx libglapi-mesa libglib2.0-0 \
    libicu55 libpcre3 libpng12-0 libstdc++6 libx11-6 libx11-xcb1 \
    libxau6 libxcb1 libxcb-dri2-0 libxcb-dri3-0 libxcb-glx0 libxcb-present0 \
    libxcb-sync1 libxdamage1 libxdmcp6 libxext6 libxfixes3 libxshmfence1 \
    libxxf86vm1 qt511base qt511declarative zlib1g
