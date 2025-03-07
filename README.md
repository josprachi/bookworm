# Bookworm [![Translation status](https://hosted.weblate.org/widgets/bookworm/-/svg-badge.svg)](https://hosted.weblate.org/engage/bookworm/?utm_source=widget) [![Build Status](https://travis-ci.org/babluboy/bookworm.svg?branch=master)](https://travis-ci.org/babluboy/bookworm) [![Snap Status](https://build.snapcraft.io/badge/babluboy/bookworm.svg)](https://build.snapcraft.io/user/babluboy/bookworm) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FZP8GK839VGQC)
A simple, focused eBook reader.

Author: Siddhartha Das

Read the books you love without having to worry about the different format complexities like epub, pdf, mobi, cbr, etc. This version supports EPUB, MOBI, FB2, PDF, FB2 and Comics (CBR and CBZ) formats with support for more formats to follow soon.

Check the Bookworm website for details on features, shortcuts, installation guides for supported distros : https://babluboy.github.io/bookworm/


## Building, Testing, and Installation

You'll need the following dependencies to build and run on Ubuntu/Debian based distros:
* unzip
* poppler-utils
* unar
* html2text
* python2
* libgtk-3-dev
* libgee-0.8-dev
* libgranite-dev
* libsqlite3-dev
* libxml2-dev
* webkit2gtk-4.0
* libwebkit2gtk-4.0-37
* libpoppler-glib-dev
* meson
* valac
* gettext
* curl
* ninja
* appstream

Run the command below to install the above on Ubuntu and Debian distros:
    sudo apt-get install unzip poppler-utils unar html2text python2 libgtk-3-dev libgee-0.8-dev libgranite-dev libsqlite3-dev libxml2-dev webkit2gtk-4.0 libwebkit2gtk-4.0-37 libpoppler-glib-dev meson valac gettext curl ninja appstream

Run `meson build` to configure the build environment and run `ninja test` to build

    git clone https://github.com/babluboy/bookworm.git
    cd bookworm
    meson build --prefix=/usr
    mkdir -p build && cd build
    ninja

To install, use `ninja install`, then execute with `com.github.babluboy.bookworm`

    sudo ninja install
    com.github.babluboy.bookworm


## Screenshots

![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/BookwormLibraryView.png)
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/BookwormReadingView.png)

Two Page View
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/TwoPageView.png)

Bookworm Dark Mode
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/DarkModeLibraryView.png)
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/DarkModeReadingView.png)

Library List View
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/LibraryListView.png)

Bookworm Preferences
![screenshot](https://raw.githubusercontent.com/babluboy/bookworm/gh-pages/images/PreferencesDialog.png)

