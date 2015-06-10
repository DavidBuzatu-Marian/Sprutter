# Sprutter
Takes a heavily-packed sprite sheet with no padding between sprites/tiles and adds padding or spacing. Can also create a "gutter" around seamless tiles, filling the padding with the tile's edge pixels, preventing seams from appearing when using the tile in a 3D rendering environment due to interpolation.

Can also remove padding/spacing from a sprite sheet.

Optionally it can generate an ".atlas" file to be used with LibGDX Asset Manager.

# Install
1. Once you have downloaded the scripts, copy or move them to one of your Plugins directories. Plugin folders can be found in the Preferences: Folders → Plug-Ins.
2. Open or Restart The Gimp.

# Usage
1. Open the desired sprite sheet in which you want to add the gutter.
2. From the menus select Filters → Sprite Sheet → Add/Remove Gutter.
3. Choose your settings and press "OK".

# License & Credits
Version 1.1

GIMP plugin to add padding/gutter to 2D Spritesheets
Copyright 2012 David 'The Visible Man' Braun

LibGDX atlas generator by Luca "Voidburn" Vignaroli

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See <http://www.gnu.org/licenses/> for a copy of the GNU General Public License