# hyprdeb
hyprland from sources for debian trixie

``
# - COMMONS

git
cmake
meson
ninja-build
pkg-config

# - NOTES
# git clone --recursive --branch v0.8.1 https://github.com/hyprwm/hyprutils.git

libpixman-1-dev

# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.6.3 https://github.com/hyprwm/hyprlang.git
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr 
# cmake --build ./build --config Release --target hyprlang -j`nproc 2>/dev/null || getconf _NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.1.12 https://github.com/hyprwm/hyprcursor.git
libcairo-dev
libzip-dev
librsvg2-dev
libtomlplusplus-dev
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf _NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.4.5 https://github.com/hyprwm/hyprwayland-scanner.git
libpugixml-dev
# cmake -DCMAKE_INSTALL_PREFIX=/usr -B build
# cmake --build build -j `nproc`
# sudo cmake --install build

# git clone --recursive --branch v0.1.5 https://github.com/hyprwm/hyprgraphics.git
libmagic-dev
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.9.2 https://github.com/hyprwm/aquamarine.git
libgles-dev
libseat-dev
libinput-dev
libgbm-dev
libdrm-dev
libdisplay-info-dev
hwdata
wayland-protocols
libwayland-dev
libopengl-dev
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf _NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.1.0 https://github.com/hyprwm/hyprland-qt-support.git
qt6-base-dev
qt6-wayland
qt6-declarative-dev
qml6-module-qtcore
qml6-module-qtquick-layouts
qt6-tools-dev
qt6-tools-dev-tools
qt6-charts-dev
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -DINSTALL_QML_PREFIX=/lib/qt6/qml -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.1.4 https://github.com/hyprwm/hyprland-qtutils.git
libqt6core5compat6    
qt6-base-dev
qt6-wayland-dev    
qt6-wayland
qt6-declarative-dev 
qt6-base-private-dev
qml6-module-qtcore 
qt6-3d-dev 
qt6-5compat-dev    
libqt6waylandclient6    
qml6-module-qtwayland-client-texturesharing
# cmake --no-warn-unused-cli -DCMAKE_BUILD_TYPE:STRING=Release -DCMAKE_INSTALL_PREFIX:PATH=/usr -S . -B ./build
# cmake --build ./build --config Release --target all -j`nproc 2>/dev/null || getconf NPROCESSORS_CONF`
# sudo cmake --install build

# git clone --recursive --branch v0.6.4 https://github.com/hyprwm/hyprland-protocols.git
# meson setup build
# sudo meson install -C build

# git clone --recursive --branch v0.49.0 https://github.com/hyprwm/Hyprland.git
libxcb-errors-dev
libre2-dev
libudis86-dev
libinotify-ocaml-dev
# git clone https://github.com/JaKooLit/Debian-Hyprland.git
# Debian-Hyprland/assets/libglaze
libxcursor-dev
libxfixes-dev
libxcb-icccm4-dev
libxcb-composite0-dev
libxcb-res0-dev
# sed -i 's/kb_layout = us/kb_layout = fr/g' src/config/defaultConfig.hpp
# make all && sudo make install
# sudo make install

# hypridle hyprlock wallpaper daemon
``
