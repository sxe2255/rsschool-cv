- Name:
	- Ilya Kanapelka
- Contacts:
	- Phone: +375291398321
	- Email: sxe8.91@gmail.com
- Summary:
	> At the moment, I working for the "Farnell" at the engineer and I handle the repairing of atms. I finished courses "*Website development using HTML, CSS and JavaScript*" and I want evolve and develop as a web developer.
- Skills:
	* Html
	* CSS
	* JavaScript
	* GitHub
- Code example:
    ``` 
        if(canvas.getContext){ /* работает только с канвас*/
            let x = event.layerX;
            let y = event.layerY; //координаты клика
            let ctx = canvas.getContext("2d");
            let pixel = ctx.getImageData(x, y, 1, 1); // получаю значения пикселя по координате
            let data = pixel.data;
            rgba = 'rgba(' + data[0] + ', ' + data[1] + ', ' + data[2] + ', ' + (data[3] / 255) + ')';
            if (current_color.style.backgroundColor != rgba){
                prev_color.style.backgroundColor = current_color.style.backgroundColor; 
            }
            current_color.style.backgroundColor = rgba;
         }
    ```
- Experience:
    **Temporarily absent**
- Education:
	1. Higher education:
		- 2011-2016 BSUIR (Faculty: Information security in telecommunication)
		- 2016-2018 BSUIR Master Degree (Faculty: Information security in telecommunication)
	2. Courses:
		- 2018 IT-Academy: Website development using HTML, CSS and JavaScript
- English level:
    - A2