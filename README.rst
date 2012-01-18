Django Teambox Icons
********************

A free icon set for popular extensions, repackaged for use with `Django Media
Tree <https://github.com/philomat/django-media-tree>`_: AAC, AI, AIFF, AVI, C,
CPP, CSS, DAT, DMG, DOC, EXE, FLV, GIF, H, HPP, HTML, ICS, JAVA, JPG, KEY, MID,
MP3, MP4, MPG, PDF, PHP, PNG, PPT, PSD, PY, QT, RAR, RB, RTF, SQL, TIFF, TXT,
WAV, XLS, XML, YML, ZIP.

Original package: https://github.com/teambox/Free-file-icons

Copyright: (cc) 2009 Teambox Technologies

Copyright of closed and open folder icon: (cc) 2012 Samuel Luescher

License: GNU AFFERO GENERAL PUBLIC LICENSE


Installation
============

Put ``teambox_icons`` in your ``INSTALLED_APPS`` setting::

    INSTALLED_APPS = (
        # ...your apps here...
        'teambox_icons',
    )

Then add the desired icon folder to your ``MEDIA_TREE_ICON_DIRS`` setting (valid
choices are ``16px``, ``24x32px``, and ``48px``)::

    MEDIA_TREE_ICON_DIRS = (
        'teambox/24x32px',  # the new folder under your static root
        'media_tree/img/icons/mimetypes',  # default icon folder
    )


LICENSE
=======

Copyright (C) 2009. Pablo Villalba Villar

Copyright (C) 2009. Teambox Technologies, S.L.

Copyright of closed and open folder icon: (C) 2012 Samuel Luescher

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU Affero General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option) any
later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along
with this program. If not, see http://www.gnu.org/licenses/.