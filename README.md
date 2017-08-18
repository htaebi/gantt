dhtmlxGantt v.4.1
=================
[![Maintenance](https://img.shields.io/maintenance/no/2016.svg)](https://github.com/slashsBin/gantt)

[![Join the chat at https://gitter.im/dhtmlx/dhtmlx](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dhtmlx/dhtmlx) 

dhtmlxGantt is an open source JavaScript Gantt chart that helps you illustrate a project schedule in a nice-looking chart. It can show the dependencies between tasks as lines and allows you to set up different relationships between tasks (finish-to-start, start-to-start, end-to-end). dhtmlxGantt provides flexible API and a large number of event handles, which gives you the freedom to customize it for your needs. 

[http://dhtmlx.com/docs/products/dhtmlxGantt](http://dhtmlx.com/docs/products/dhtmlxGantt)


Persian Internationalisation
----------------------------
- [X] New `fa_IR` Locale
- [X] Uses Moment.js for Persian Date/Time Conversion
- [X] Translations for LightBox
- [X] Configure Iranian WorkTime & WeekEnds

### Usage
1. Install Using Bower([Exploring Ways to Install dhtmlxGantt](http://docs.dhtmlx.com/gantt/desktop__install_with_bower.html)):

    `bower require slashsBin/gantt`

1. Add DHTMLX Gantt Resources([Initializing a Gantt Chart on a Page](http://docs.dhtmlx.com/gantt/desktop__initializing_gantt_chart.html)):

    ```html
    <link rel="stylesheet" type="text/css" href="codebase/dhtmlxgantt.css">
    <script type="text/javascript" src="codebase/dhtmlxgantt.js"></script>
    ```

1. Add Persian Support:

    ```html
    <script type="text/javascript" src="moment.js"></script>
    <script type="text/javascript" src="moment-jalaali.js"></script>
    <link rel="stylesheet" type="text/css" href="codebase/skins/dhtmlxgantt_persian.css">
    <script type="text/javascript" src="codebase/locale/locale_fa.js"></script>
    <script type="text/javascript" src="codebase/ext/dhtmlxgantt_persian.js"></script>
    ```

License
----------

This software is allowed to use under GPL or you need to obtain Commercial or Enterprise License
to use it in non-GPL project. Please contact sales@dhtmlx.com for details

(c) Dinamenta UAB


Useful links
-------------

- Online  documentation
	http://docs.dhtmlx.com/gantt/
	
- Support forum
	http://forum.dhtmlx.com/viewforum.php?f=15
