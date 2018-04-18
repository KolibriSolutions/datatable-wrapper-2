# datatable-wrapper-2
A wrapper script around DataTables and YADCF, with support for horizontal scrolling.

Improved version of https://github.com/KolibriSolutions/datatable-wrapper-1


Created by Jeroen 2016-2018, Marketplaces ELE. Kolibri Solutions
General init script for all datatables, including copy and csv export.
make sure your table has the class ".datatable" for styling with metroui

* make sure values in cells in HTML are not wrapped in spaces, or select2 will fail display. HTMLminify fixes this.
* make sure table is wrapped in div.double-scroll to enable horizontal scrolling
* use $('table.datatable').dt_wrapper([yadcf_filters])
* It is not possible to filter columns that have 'searchable:false' in datatables.
* Make sure to include the following files:
* * jquery.dataTables.yadcf.js
* * jquery.dataTables.yadcf.css
* * buttons.html5.min.js
* * dataTables.buttons.min.js
* * datatables.min.js
* * jquery.datatables.yadcf.js
* * jquery.doubleScroll.js (for horizontal scrolling on top of table.)
* * select2.min.js
* * select2.min.css or custom.css

* @summary     DataTables
* @file        dt_wrapper.js
* @author      Jeroen van Oorschot, Kolibri Solutions
* @contact     kolibrisolutions.nl
* @copyright   Copyright 2016-2018 Kolibri Solutions
* @license: MIT	