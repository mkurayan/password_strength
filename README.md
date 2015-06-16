# Password-Strength
This JQuery plugin helps to create a strong passwords which could resist brute-force attacks.

**Note** This repository contains two versions of password_strength plugin.

1. password_strength.js - Original plugin, implemented as an jQuery Widget.
2. password_strength_lightweight.js - This is a simple implementation of the password_strength.js plugin which does not use jQuery Widget Factory.

Both versions of the plugin do the same sings and have particularly identical code.

If you are going to extend plugin with an additional functionality it will be better to use original password_strength.js, because jQuery Widget Factory allows to build complex, stateful plugins based on object oriented design principles.
If you prefer the simpler implementation, which does not use Widget Factory and does not depend from jQuery UI you should use password_strength_lightweight.js

## How To Use

[Demo](http://mkurayan.github.io/password_strength/)

Example: $('#myPassword').strength_meter();

You can customize visual appearance, just override default style or create new one and pass it to plugin. 

Example: $("#anotherPassword").strength_meter({
            strengthMeterClass: 'custom_strength_meter'
        });
