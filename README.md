# GooglPHP

**A PHP class for shorting/expanding URLs with the *official* Goo.gl API.**

## Usage:
    <?php
    // Require the GooglPHP class.
    require_once 'GooglPHP.php';

    // Shorten an URL.
    $strLongUrl = 'http://www.github.com';
    if ($strShortUrl = GooglPHP::shortURL($strLongUrl)) {
        echo $strLongUrl . ' shortened: ' . $strShortUrl . '<br>';
    }

    // Expand an URL.
    $strShortUrl = 'http://goo.gl/ddom'; // www.linux.com
    if ($strLongUrl = GooglPHP::expandURL($strShortUrl)) {
        echo $strShortUrl . ' expanded: ' . $strLongUrl . '<br>';
    }
    ?>

## Bugs?
If you run into a problem, feel free to contact me. I will help you if my time allows it. However, support is not guaranteed.

## Wishes?

Add your wish to the project wiki or send me an email.
