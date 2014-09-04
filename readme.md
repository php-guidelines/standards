PGS Standards
=============

These standards are exactly the same as [PHP-FIG] PSR standards, with two differencies:

- you MAY use tabs for indenting
- you MAY write PHP constants `TRUE`, `FALSE`, and `NULL` in upper case

Basically, PGS standards are suitable for all PHP developers who want to be compliant
with well-known standards from the PHP-FIG, but also use tabs instead of spaces.


What standards have been passed so far?
---------------------------------------

- [PSR-0](accepted/PSR-0.md) - Autoloading Standard
- [PSR-1](accepted/PSR-1-basic-coding-standard.md) - Basic Coding Standard
- [PGS-2](accepted/PGS-2-coding-style-guide.md) - Coding Style Guide, replaces PSR-2
- [PSR-4](accepted/PSR-4-autoloader.md) - Improved Autoloader


Rationale
---------

Once used character for indentation is extremely difficult to change, especially for bigger
projects. Therefore standard [PGS-2](accepted/PGS-2-coding-style-guide.md) in comparsion
to the PSR-2 allows using tabs for indentation.

Since the [PHP documentation writes](http://php.net/manual/en/types.comparisons.php)
constants `TRUE`, `FALSE` and `NULL` in upper case letters, allows PGS-2 in comparsion
to the PSR-2 to write them in upper case too.

Using tabs or capital letters is optional. You must use the same variant in all codes
from one Vendor.

[PHP-FIG]: http://www.php-fig.org
