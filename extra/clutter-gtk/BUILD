sedit "s/^LIBS = @LIBS@$/LIBS = @LIBS@ -lm/" examples/Makefile.in &&
sedit "s/\(gtk_clutter_viewport_LDADD = .*\)/\1 -lgthread-2.0/" examples/Makefile.in &&
sedit "s:\(--include=Gtk-2.0\):\1 -I/usr/include/gtk-2.0/:" clutter-gtk/Makefile.in &&

default_build
