## Welcome to PHP Fail

I just use this page to take note what's [weird] in PHP.

```php
(0 == "whatever"); //return true >_<
//from PHP 8.0 return false
```

```php
$strA = (bool)""; //false
$strB = (bool)"0"; //false
$strC = (bool)"0.0"; //true >_<
```

```php
$x=TRUE;
$y=FALSE;
$z= $y OR $x; //$z return FALSE
$z = $y || $x; //$z return TRUE
```

[syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
