Aion Database BBCode
=========================
* BBCode to show item- and spelldata from Aiondatabase.com. Only for [WCF](http://www.woltlab.com/de/) and [WBB](http://www.woltlab.com/de/).

Usage
------------------
Use my [Buildscript](https://github.com/r15ch13/WCF-WBB-Package-Builder) to generate the installable package.

Copy the link to an item of Aiondatabase.com and add it to your forum to make the tooltip show up.

Use the following parameters to adjust the presentation:

    text = Displays only the item name
    small = Displays a small icon
    medium = Displays a medium icon
    large = Displays a large icon


The tooltip adapts to the language of the copied links:

    http://de.aiondatabase.com/item/100900189 = Displays a german tooltip
    http://fr.aiondatabase.com/item/100900189 = Displays a french tooltip

Example:

    [aiondb=large]http://de.aiondatabase.com/item/100900189[/aiondb]

License
----------
Copyright 2012 Richard 'r15ch13' Kuhnt

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program. If not, see <http://www.gnu.org/licenses/lgpl-3.0>.
