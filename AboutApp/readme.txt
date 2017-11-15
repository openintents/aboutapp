﻿ ****************************************************************************
 *                                                                          *
 *   Copyright (C) 2009-2012 pjv (and others, see About dialog)             *
 *                                                                          *
 *   OI About is free software: you can redistribute it and/or modify       *
 *   it under the terms of the GNU General Public License as published by   *
 *   the Free Software Foundation, either version 3 of the License, or      *
 *   (at your option) any later version.                                    *
 *                                                                          *
 *   OI About is distributed in the hope that it will be useful,            *
 *   but WITHOUT ANY WARRANTY; without even the implied warranty of         *
 *   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the          *
 *   GNU General Public License for more details.                           *
 *                                                                          *
 *   You should have received a copy of the GNU General Public License      *
 *   along with OI About.  If not, see <http://www.gnu.org/licenses/>.      *
 *                                                                          *
 *                                                                          *
 *   The idea, window layout, and elements are based on GtkAboutDialog.     *
 *   See http://library.gnome.org/devel/gtk/stable/GtkAboutDialog.html      *
 *   and http://www.gtk.org.                                                *
 *                                                                          *
 ****************************************************************************
 
OI About is an extension that shows detailed information about an application.

To obtain the current release, visit
  http://www.openintents.org


----------------
release: 1.1
date: 2012-01-29

- high-resolution icon for Android 2.3 and later.
- support for about.xml (Google Code-in task by Matěj Konečný, issue 248)
- list more languages for translations.
- new icons and translations by Google Code-in students

----------------
release: 1.0.3
date: 2011-05-01

- support moving app to SD card.
- new optional tab for recent changes.
- show translators of all languages.
- fix crash if no icon is supplied.
- support Android 2.3.
- translations into various languages.

----------------
release: 1.0.2
date: 2009-10-14

- Update to Android-1.6 (screensize and density).
- translations: Chinese (simplified), Japanese, Lao,
  Portugese

----------------
release: 1.0.1
date: 2009-01-13

- Fix blackening of license text while touching.
- translations: Dutch, French, German, Spanish

----------------
release: 1.0.0
date: 2009-01-12

- First public release.

Features: 
- Shows general info, credits, and license tabs.
- Retrieves information from application manifest
  through default tags and metadata.
- Optionally, all fields can be modified through
  intent extras.
