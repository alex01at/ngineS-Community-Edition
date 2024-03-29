## ngineS Community Edition
The Ultimate PHP Social Network Platform

This repository is empty but it enables everyone who is usig a clone of Sngine to contribute for a community edition.
- You can post issues
- we can have projects
- a Wiki is available where people can contribute

Extra code we post here under T3Social will be available under a GPL/AGPL or LGPL v.3 license as long as Sngine itself is not licensed clearly under GPLv.2+ or GPLv.3 itself.

# About used Licenses in the core code by Zamblek Team

The Zamblek team is using the community edition of TinyMCE and this one is GNU LGPL v.2 and therfore also the complete code has to be released under GNU LGPL2 or be another GPL license when it is linked

According to GNU LGPLv.2 it says:
5. .... However, linking a "work that uses the Library" with the Library creates an executable that is a derivative of the Library (because it contains portions of the Library), rather than a "work that uses the library". The executable is therefore covered by this License. Section 6 states terms for distribution of such executables.
https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html

```
tinymce/tinymce is licensed under the
GNU Lesser General Public License v2.1
Primarily used for software libraries, 
the GNU LGPL requires that derived works 
be licensed under the same license, but 
works that only link to it do not fall 
under this restriction. 
There are two commonly used versions of the GNU LGPL.
```
https://github.com/tinymce/tinymce/blob/develop/LICENSE.TXT
check the conditions which clearly state - SAME license, commercial and private use and distribution possible - Disclose the source code! - 

and there are more codes which force the license to GNU GPLv.2 - i.e. GNU gettext - https://www.gnu.org/software/gettext/manual/html_node/Licenses.html#Licenses
```
The files of this package are covered by the licenses indicated in each particular file or directory. Here is a summary:

The libintl and libasprintf libraries are covered by the 
GNU Lesser General Public License (LGPL). A copy of the 
license is included in GNU LGPL.
The executable programs of this package and the libgettextpo 
library are covered by the GNU General Public License (GPL). 
A copy of the license is included in GNU GPL.
```

- i.e. he is using "gettext" which is also GNU GPL v.2 (actually now MIT - https://github.com/php-gettext/Gettext/blob/master/LICENSE - but he is using a GNU version)

php-gettext - Zamblek Team is using a GNU GPLv.2 Version in Sngine
```
Copyright (c) 2005 Steven Armstrong <sa at c-area dot ch>
   Copyright (c) 2009 Danilo Segan <danilo@kvota.net>
   Drop in replacement for native gettext.
   This file is part of PHP-gettext.
   PHP-gettext is free software; you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation; either version 2 of the License, or
   (at your option) any later version.
   PHP-gettext is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.
   You should have received a copy of the GNU General Public License
   along with PHP-gettext; if not, write to the Free Software
   Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
```

streams.php - Zamblek Team is using a GNU GPLv.2 Version in Sngine
```
/*
   Copyright (c) 2003, 2005, 2006, 2009 Danilo Segan <danilo@kvota.net>.
   This file is part of PHP-gettext.
   PHP-gettext is free software; you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation; either version 2 of the License, or
   (at your option) any later version.
   PHP-gettext is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.
   You should have received a copy of the GNU General Public License
   along with PHP-gettext; if not, write to the Free Software
   Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
*/
```

pids dropin is GNU GPL. v.2 - Zamblek Team is using a GNU GPLv.2 Version in Sngine
```
/*
   Copyright (c) 2003,2004,2005,2009 Danilo Segan <danilo@kvota.net>.
   Copyright (c) 2005,2006 Steven Armstrong <sa@c-area.ch>
   This file is part of PHP-gettext.
   PHP-gettext is free software; you can redistribute it and/or modify
   it under the terms of the GNU General Public License as published by
   the Free Software Foundation; either version 2 of the License, or
   (at your option) any later version.
   PHP-gettext is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU General Public License for more details.
   You should have received a copy of the GNU General Public License
   along with PHP-gettext; if not, write to the Free Software
   Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
*/
```

HTML Purifyer is LGPL v2 like Jquery (that is also MIT)
```
/*
    HTML Purifier 4.13.0 - Standards Compliant HTML Filtering
    Copyright (C) 2006-2008 Edward Z. Yang
    This library is free software; you can redistribute it and/or
    modify it under the terms of the GNU Lesser General Public
    License as published by the Free Software Foundation; either
    version 2.1 of the License, or (at your option) any later version.
    This library is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    Lesser General Public License for more details.
    You should have received a copy of the GNU Lesser General Public
    License along with this library; if not, write to the Free Software
    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
 */
```

 PHP Mailer is LGPL too
```
 /**
 * PHPMailer Exception class.
 * PHP Version 5.5.
 *
 * @see       https://github.com/PHPMailer/PHPMailer/ The PHPMailer GitHub project
 *
 * @author    Marcus Bointon (Synchro/coolbru) <phpmailer@synchromedia.co.uk>
 * @author    Jim Jagielski (jimjag) <jimjag@gmail.com>
 * @author    Andy Prevost (codeworxtech) <codeworxtech@users.sourceforge.net>
 * @author    Brent R. Matzelle (original founder)
 * @copyright 2012 - 2020 Marcus Bointon
 * @copyright 2010 - 2012 Jim Jagielski
 * @copyright 2004 - 2009 Andy Prevost
 * @license   http://www.gnu.org/copyleft/lesser.html GNU Lesser General Public License
 * @note      This program is distributed in the hope that it will be useful - WITHOUT
 * ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
 * FITNESS FOR A PARTICULAR PURPOSE.
 */
```
 and Smarty itself is GNU LGPLv.3
 
http://www.olafsw.de/compatibility-lgpl2-lgpl3/
 this solves the compatibility issues. 
 In other words all code which until now had been released has to be GNU GPL.v.2 or any later version of GPL because of the used GNU GPLv.2 Gettext code integrated to Sngine.

As an addition to twhat had been written already:
Here is a short overview of GPL licenses used in the combined work of Sngine. For what I see the only suitable license for the whole work would be GPLv.3 or AGPLv.3 and for our t3.social we are using AGPLv.3.
Because it is using the GPL licenses also the whole combined work has to be licensed under GNU GPL. THis again means that the code can be modified, distributed, copied according to the license conditions of GNU GPL. (as I am not a lawyer you might get a clear answer from a lawyer or the FSF directly).
https://www.gnu.org/licenses/gpl-faq.en.html#AllCompatibility

