# jquery-ui-datepiker_custom-date-highlighter
you can Easily highlight dates on jquery ui datepiker with external csv file

##sample useage


###put js and css file after jquery and jquery ui files
```

<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>

<script src="http://code.jquery.com/ui/1.11.3/jquery-ui.js"></script>
<link rel="stylesheet" type="text/css" href="http://code.jquery.com/ui/1.11.3/themes/smoothness/jquery-ui.css" />

<!--plugin js file and css file-->
<script src="datepicker-customdate-heighlighter.min.js"></script>
<link rel="stylesheet"  type="text/css" href="datepicker-customdate-heighlighter.css" />
```

##useage

```
<script>
$(document).ready(function(){
$( ".selector" ).highlightdater('dates.csv');  //dates.csv  your csv file path
});
</script>

<input class="selector" type="text">
```





