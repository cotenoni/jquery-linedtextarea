jquery-linedtextarea
====================

Original version taken from http://alan.blog-city.com/jquerylinedtextarea.htm

## Usage
<pre>
<script>
$(function() {

  // Target all classed with ".lined"
  $(".lined").linedtextarea(
    {selectedLine: 1}
  );

  // Target a single one
  $("#mytextarea").linedtextarea();

});
</script>
</pre>

This repo contains modification made to the original version that improves performance when working with a really large dataset (> 10 000 lines). With that amount of lines the original version was proving unusable.