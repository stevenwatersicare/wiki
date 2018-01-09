## PHP Code Style

This is a demonstration on how to format switch statements. his formatting enhances the readability of a switch/case block immensely.

```php
<?php
	 /**
     * @access public
     * @param string $abbr                  Abbreviation of a state.
     * @since                               Oct 12, 2017
     * @return string                       Full name of the state.
     */
    public function switchDemo($abbr)
    {
        switch ($abbr) {
            case 'AL':
                $state = 'Alabama';
                break;
            case 'CA':
                $state = 'California';
                break;
            case 'FL':
                $state = 'Florida';
                break;
            case 'TX':
                $state = 'Texas';
                break;
            default:
                $state = 'State abbreviation does not exist!';
                break;
        }

        return $state;
    }
?>
```


1. Add a space after the if in a condition

```php 
<?php

    $a = 0;

    $b = 1;

    if ( $a == $b ) {
        echo '$a is the same as $b';
    } else {
        echo '$a is not the same as $b';
    }
    
?>
```
