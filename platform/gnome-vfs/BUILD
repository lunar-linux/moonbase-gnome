sed -e "s/AM_CONFIG_HEADER/AC_CONFIG_HEADERS/" -i configure.in &&
mv configure.in configure.ac &&

autoreconf -vfi &&

export CFLAGS+=" -Wno-implicit-function-declaration"

OPTS+=" --enable-gnutls \
        --disable-cdda  \
        --disable-openssl \
        --disable-gtk-doc \
        --disable-static \
        --disable-hal \
        --disable-howl"

default_build
