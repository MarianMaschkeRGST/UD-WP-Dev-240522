# UD-WP-Dev

Wordpress development course

# List of wp functions

Display name of website

<?php bloginfo('name')?>

Display tagline of website

<?php bloginfo('description')?>

# Php basics

## While Loop

Why while loop and not for each? Thats what wordpress uses to go over posts

<?php 
    $names = array('Brad', 'John', 'Jane', 'Meowsalot')
?>

<?php 
    $count = 0;
    while($count < count($names)) {
        echo "<p> My name is $names[$count]</p>";
        $count++;
    }
?>
