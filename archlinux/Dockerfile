FROM base/archlinux

RUN pacman -Syu

RUN pacman -S --noconfirm git bullet libjpeg-turbo gst-plugins-base \
         luajit curl fribidi libpulse libxcomposite \
         libxinerama libxrandr libxss libinput \
         libxcursor libxp libwebp shared-mime-info \
         libxkbcommon wayland lz4 openjpeg avahi \
         libspectre libraw librsvg wayland-protocols \
         git meson ninja clang gcc pkgconfig check

RUN git clone http://git.enlightenment.org/core/efl.git 
