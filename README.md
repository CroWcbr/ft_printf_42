# ft_printf
## Info
![image](https://user-images.githubusercontent.com/94758944/165583853-aef06027-dae6-4b36-a830-7187335a6cae.png)

## How to use
- make
- make bonus

## Mandatory part:
- %c print a single character.
- %s print a string of characters.
- %p the void * pointer argument is printed in hexadecimal.
- %d print a decimal (base 10) number.
- %i print an integer in base 10.
- %u print an unsigned decimal (base 10) number
- %x print a number in hexadecimal (base 16) with lowercase.
- %X print a number in hexadecimal (base 16) with uppercase.
- %% print a percent sign.

## Bonus part:
- '-' left-justify within the given field width; Right justification is the default.
- '0' left-pads the number with zeroes (0) instead of spaces when padding is specified.
- '.' the precision in not specified in the format string, but as an additional integer value argument preceding the argument that has to be formated.
- '#' used with x or X specifiers the value is preceeded with 0x or 0X respectively for the values different than zero.
- (space) if no sign is going to be written, a blank space is inserted before the value.
- '+' forces to preceed the result with a plus or minus sign (+ or -) even for positive numbers. By default, only negative numbers are preceded with a - sign.
