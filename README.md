#Master page template in PHP
HTML, CSS and PHP

![Home page]()
![About page]()
![Contact page]()

This is a simple template that carries the same header and footer throughout a website. It also styles the active link when you are on that page.

The header and footer is located in the folder called "includes". Header will include navigation and footer our copyright.

Home page 
  <?php
	$page_title = 'Contact';
	$thisPage='contact';
	include ('./includes/header.html');
?>
<!-- Content -->

<h1><?php echo $page_title ?></h1>
<p>Bacon ipsum dolor amet pork loin pancetta filet mignon strip
	steak salami sirloin pork doner. Rump porchetta bresaola, spare
	ribs ball tip brisket t-bone shankle chicken. Shankle prosciutto
	chuck, shoulder bacon flank short ribs pork chop kielbasa pig
	cupim. Tri-tip landjaeger pancetta pork, chuck t-bone biltong ham
	pork loin. Turkey tail chuck, shank bresaola capicola corned beef
	short loin. Shoulder picanha kielbasa, andouille leberkas tongue
	doner jerky ham hock sausage cupim frankfurter rump spare ribs pork
	belly.
</p>
<!-- Content ends -->
<?php
	include ('./includes/footer.html');
?>



     

