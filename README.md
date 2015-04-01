# Password-Strength
Simple JQuery plugin which measure of the effectiveness of a password in resisting guessing and brute-force attacks. 

Example: $('#myPassword').strength_meter();

You can customize visual appearance, for this just override default style or create new one and pass it to plugin. 
Example: $("#anotherPassword").strength_meter({
            strengthMeterClass: 'custom_strength_meter'
        });
