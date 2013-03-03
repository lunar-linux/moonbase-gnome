(
    # see https://bugzilla.gnome.org/show_bug.cgi?id=670316
    sed -e 's:glib/gregex.h:glib.h:' -i configure &&

    default_build

) > $C_FIFO 2>&1
