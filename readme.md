# Lightweight Bootstrap 4 theme for Mottie's tablesorter

A lightweight sass bootstrap 4 theme for [mottie's tablesorter](https://mottie.github.io/tablesorter/docs/)

The tablesorter does come with a bootstrap theme, but it makes a
  sortable table look completely different to any other table.
  This theme just adds the sorting icons to the header, and leaves
  the rest of the table untouched.

## Usage

sass:

    @import "~@rickselby/tablesorter-bootstrap-sass/bootstrap-4";

js:

    $('#tablesorter').tablesorter({
        theme : 'bootstrap-4',
    });

    // Or set it as a default somewhere:
    $.extend( true, $.tablesorter.defaults, {
        theme : 'bootstrap-4',
    });
