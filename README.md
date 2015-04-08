# Password-Strength
Simple JQuery plugin which helping to create strong passwords which could resist guessing and brute-force attacks.
[Demo](http://mkurayan.github.io/password_strength/)

**Note** This repository contain 2 versions of password_strength plugin.

1. password_strength.js Original plugin which implemented as jQuery Widget.
2. password_strength_lightweight.js This is simple implementation of the password_strength.js plugin, that does not use jQuery Widget Factory.

Both versions do the same sings and the have particulary identical code.

If you a going to extend plugin with addition functionality it will be better to use password_strength.js version because jQuery Widget Factory allows to build complex, stateful plugins based on object-oriented principles.
If you prefer a lightweight implementation which not use Widget Factory and not depend from jQuery UI you can use password_strength_lightweight.js

## How To Use
Example: $('#myPassword').strength_meter();

You can customize visual appearance, just override default style or create new one and pass it to plugin. 

Example: $("#anotherPassword").strength_meter({
            strengthMeterClass: 'custom_strength_meter'
        });
