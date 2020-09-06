<!DOCTYPE html>
<html>
<head>
	<title>Mad Libs Response</title>
	<meta name="author" content="Lexy Pakzaban" >
	<link rel="stylesheet"type="text/css" href="style.css"/>
	<link href="https://fonts.googleapis.com/css?family=Assistant|Playfair+Display" rel="stylesheet">
	<!-- whale image https://www.hakaimagazine.com/wp-content/uploads/header-humpbacks-and-grays.jpg -->
	<!-- grasshopper image https://upload.wikimedia.org/wikipedia/commons/b/b7/American_Bird_Grasshopper.jpg-->
	<!-- butterfly image https://www.ukbutterflies.co.uk/phpBB/files/phpbbgallery/core/source/5244d41736da6f4991172eb8b84533f9.jpg-->
	<!-- lion image http://sf.co.ua/13/07/wallpaper-2905249.jpg-->
	<!--purple lizard image https://pbs.twimg.com/profile_images/774997737901293568/T4TLreHZ_400x400.jpg-->
	<!-- pink lizrd image https://i.pinimg.com/originals/74/fb/47/74fb473bad5bfdeb5069b244760a869e.jpg-->
	<!-- green lizard image https://cdn.images.express.co.uk/img/dynamic/109/590x/lizz-1003046.jpg?r=1534219722519-->
	<!-- red lizard image http://absfreepic.com/absolutely_free_photos/small_photos/red-lizard-4288x2848_30404.jpg-->
</head>
<body>
<?php	
	
	$pluralnoun1 = $_REQUEST['pluralnoun1'];
	$pluralnoun2 = $_REQUEST['pluralnoun2'];
	$adjective1 = $_REQUEST['adjective1'];
	$liquid = $_REQUEST['liquid'];
	$animal1 = $_REQUEST['animal1'];
	$adjective2 = $_REQUEST['adjective2'];
	$noise1 = $_REQUEST['noise1'];
	$noise2 = $_REQUEST['noise2'];
	$adjective3 = $_REQUEST['adjective3'];
	$pluralnoun3 = $_REQUEST['pluralnoun3'];
	$animal2 = $_REQUEST['animal2'];
	$animal3 = $_REQUEST['animal3'];
	$bodypart = $_REQUEST['bodypart'];
	$pluralnoun4 = $_REQUEST['pluralnoun4'];
	$adjective4 = $_REQUEST['adjective4'];
	
	/* Makes the word the color chosen*/
	if($adjective3 == "purple")
	{
		$color = "violet";
	}
	
	elseif($adjective3 == "pink")
	{
		$color = "pink";
	}
	
	elseif($adjective3 == "green")
	{
		$color = "green";
	}
	
	else
	{
		$color = "red";
	}
	
	echo("<h1> A Visit To The Zoo</h1>");
	
	echo("<p> Zoos are places where wild ".$pluralnoun1." are kept in pens or cages so that ".$pluralnoun2." can come and look at them.
	There are two zoos in New York, one in the Bronx and one in ".$adjective1." Park. The Park zoo is built around a large pond filled
	with clear sparkling ".$liquid.". You will see several ".$animal1." swimming in the pond and eating fish. When it is feeding time,
	all of the animals make ".$adjective2." noises. The elephant goes ".$noise1." and the turtledoves go ".$noise2.". In one part of the
	zoo, there are <span style = 'color:".$color.";'>".$adjective3."</span> lizards who love to eat ".$pluralnoun3.". In another building, there is a spotted African ".$animal2." that
	is so fast it can outrun a/an ".$animal3.". But my favorite animal is the hippopotamus. It has a huge ".$bodypart." and eats fifty
	pounds of ".$pluralnoun4." a day. You would never know that, technically, it's nothing but an oversized ".$adjective4." pig. </p>");
	
	/* inserts a picture of the color chosen for the lizard*/
	if($adjective3 == "purple")
	{
		echo("<img src = Pictures/purple.jpg height = 200>
		<p> The purple lizard </p>");
	}
	
	elseif($adjective3 == "pink")
	{
		echo("<img src = Pictures/pink.jpg height = 200>
		<p> The pink lizard </p>");
	}
	
	elseif($adjective3 == "green")
	{
		echo("<img src = Pictures/green.jpg height = 200>
		<p> The green lizard </p>");
	}
	
	else
	{
		echo("<img src = Pictures/red.jpg height = 200>
		<p> The red lizard </p>");
	}
	
	
	/* inserts a picture of the animal chosen*/
	if($animal2 == "whale")
	{
		echo("<img src = Pictures/whale.jpg height = 200>
		<p> The spotted African whale </p>");
	}
	
	elseif($animal2 == "grasshopper")
	{
		echo("<img src = Pictures/grasshopper.jpg height = 200>
		<p> The spotted African grasshopper </p>");
	}
	
	elseif($animal2 == "butterfly")
	{
		echo("<img src = Pictures/butterfly.jpg height = 200>
		<p> The spotted African butterfly </p>");
	}
	
	else
	{
		echo("<img src = Pictures/lion.jpg height = 200>
		<p> The spotted African lion </p>");
	}
	
	
	
?>

<p><a href="MadLibsQuestions.html">Return</a></p>
</body>
</html>