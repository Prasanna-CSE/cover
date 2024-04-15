# Ex.06 Book Front Cover Page Design
## Date:15/04/24

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
	<head>
        <style>
            .first{
                
                margin-left: 40%;
                background-image: url("CP.jpg");
                background-size: cover;
                background-repeat: no-repeat;
                width: 30%;
                height: 100%;
                max-width: 60%;
            }
            .second{
                padding: 20px;
            }
            img{ padding: 5px;
  width: 100px;
 
                
            }
            .third{
              
                margin-top: 80px;
                border-bottom: 3px  rgb(252, 249, 247) solid ;
            }
            #four{
                color: rgb(255, 99, 71);
            }
        </style>

		<title>app</title>
	</head>
	<body>
        
        <div class="first" id="four">
            <div class="second">
            <span style="border-bottom: 3px rgb(210, 103, 27) solid; color:rgb(252, 250, 250); ;">EXPERT INSIGHT</span>
            <div style="font-size: 48px; padding-top: 10px; padding-bottom: 10px;">ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING FOR CODERS</div>
            <div style="padding-right: 20px; margin-bottom: 10px; width: 70%;margin-top: 20px; ">From BigData to SmallData</div>
            
            <div class="third">
            <span style="color: rgb(255, 255, 255); font-weight: 600; margin-right: 150px;">SECOND EDITION</span>
            <span style="width: 10px ;height: 10%;"><img src="Prasanna.jpg"></span>
            
        </div>
       <div style="margin-top:50px ; font-size: 20px; font-weight:1000;color: rgb(255, 255, 255);">
            <span>PRASANNA L</span>
            <span style="margin-left:160px ;">SEC</span>
        </div>
       
        </div>
        </div>
    
            
    
        
	</body>
	
</html>
```

## OUTPUT:
![alt text](<Screenshot (107).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
