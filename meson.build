project('gtk-android', ['c', 'java'],
  version : '0.0.1')

subproject('glib', default_options: ['libmount=false', 'selinux=false', 'iconv=libc'])
subproject('harfbuzz')
subproject('libpng')
subproject('freetype2')
subproject('expat')
subproject('linux-util')
subproject('fontconfig')
subproject('libffi')
subproject('pcre')
subproject('graphene')
subproject('cairo')
subproject('pango', default_options: ['gir=false'])
subproject('gdk-pixbuf', default_options: ['x11=false', 'gir=false', 'docs=false'])
subproject('atk')
subproject('libepoxy', default_options: ['glx=no', 'x11=false'])
subproject('gtk', default_options: ['wayland-backend=false', 'x11-backend=false', 'print-backends=none', 'media=none', 'introspection=false'])

subdir('samples')
