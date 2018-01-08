FROM base/archlinux

RUN pacman -Syy
RUN pacman -Su --noconfirm
RUN pacman -S --noconfirm git bullet libjpeg-turbo gst-plugins-base \
         luajit curl fribidi libpulse libxcomposite \
         libxinerama libxrandr libxss libinput \
         libxcursor libxp libwebp shared-mime-info \
         libxkbcommon wayland lz4 openjpeg avahi \
         libspectre libraw librsvg wayland-protocols \
         git ninja clang gcc pkgconfig check python-pip \
	 libxdamage poppler

RUN pip3 install --user meson

RUN git clone http://git.enlightenment.org/core/efl.git 
