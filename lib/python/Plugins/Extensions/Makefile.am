installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = LDteam OpenIPTV TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer SocketMMI DVDBurn Modem Volume_adjust ProgrammlistenUpdater RemoteStreamConvert

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if VUSOLO4K
SUBDIRS += MiniTV
endif

if VUULTIMO4K
SUBDIRS += MiniTV
endif

if HAVE_WETEK_XBMC
SUBDIRS +=  StartKodi
endif

install_PYTHON = __init__.py
