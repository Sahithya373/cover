# Ex-06 Book Front Cover Page Design
## Date: 28/10/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgba(7, 0, 0, 0.562);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(tale.jpg);
            background-size: cover;
        }
        .insight{
            color: rgba(11, 3, 3, 0.359);

        }
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgba(7, 0, 0, 0.359);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'times new roman', times new roman, times new roman;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;   
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgba(8, 8, 8, 0.359);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgba(11, 0, 0, 0.879);">
            </div>
            <div class="booktitle">
                <h1>EVERY DOG HAS ITS DAY</h1></div>
            <div class="subtitle">
                "Every Dog Has Its Day" is a proverbial expression implying that everyone will experience success, recognition, or good fortune at some point in their lives, emphasizing the cyclical nature of life's ups and downs. It highlights the notion of perseverance and the cyclical nature of life's fortunes.
            </div>
            <div class="mypic">
                <img src="57465.JPG" width="100" height="100" alt="50">
            </div>
            <div class="id">
                <hr style="color: rgba(10, 0, 0, 0.476);">
            </div>
            <div class="author">
               <p><b>S. SAHITHYA</b></p>
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
    </body>
</html>
```


## OUTPUT:
![Alt text](<Screenshot (32).png>)

![Alt text](<Screenshot (33).png>)

![Alt text](<Screenshot (34).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
