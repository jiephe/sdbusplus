# sdbusplus
for test &amp; debug dbus api

# build step
git clone https://github.com/jiephe/sdbusplus.git

cd sdbusplus

meson build -Dtests=disabled -Dbuildtype=debug

cd build 

ninja
