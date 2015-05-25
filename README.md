# jquery ui date picker custom date heighlighter
you can Easily  Heighlight dates on jquery ui datepicker with external csv file
highlight specific dates in Jquery UI Datepicker. It pretty simple actually, 

Here are steps which we will be following to highlight particular dates in datepicker:

    We use csv file to hold the dates which will be highlighted.
    We will utilize  datepicker beforeShowDay function to add custom CSS classes to the dates in csv
 


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





