## EXPERIMENT 02: CREATE A COMMERCIAL WEBSITE USING HTML AND CSS
## AIM:
To create a commercial website using html and css.

## ALGORITHM:
1. Create basic html page.
2. Use div components to separate each section of the webpage.
3. Add css styling to the required components.
4. Link the css file inside the head tag of html file.
5. Run the html page and dsiplay the output.

## PROGRAM:
### TEMP.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Crystal Cafe</title>
    <link rel="stylesheet" href="temp.css">

</head>
<body style="background-image: url(back1.jpg);">

    <div class="container">
    
      
        <img src="log 1.png" class="mid logo">
        <h2 class=" mid title">Famous for its Rarity, Perfect Flavour.</h2>
        <h3 class="mid aroma">Intense Aroma & Balanced Taste</h3>
        <img src="cof1.png" class="mid coffee" style="height: 250px; width: 250px;">
        <p class="mid roast">DARK ROAST</p>
        <p class="mid roastinfo">Duls aute irure dolor in <br>&emsp;&emsp;reprehenderit <br> in volupt ate vellt essets</p>
        <img src="cof2.png" class="mid latte" style="height: 300px; width: 350px;">
        <p class="mid cup">Exceeding the Standard<p class="mid wcup">as the</p></p>
        <p class="mid wcup1"> Best Coffee in the World</p>
        <p class="mid year">Est. 1760</p>
        <p class="mid description">In the majestic Blue Mountains of Jamaica grows the <br>world's finest coffee. At elevations higher than 2000 ft <br>above sea level, the rich soil and continuous rainfall<br> combine to create conditions perfect for cultivating<br> the world's most distinguished brew, Kaelish Coffee.</p>
        <button class="mid hist">OUR HISTORY</button>
        <p class="mid info"><i>Crystal Coffee company exceeds the standard in what is already known <br>as the best coffee in the world.</i></p>
        <p class="mid info1"><i>" Jamaican Blue Mountain Coffee "</i></p>
        <button class="mid products">BROWSE OUR PRODUCTS</button>
        <img src="cof1.png" class="mid finalprod" style="height: 300px; width: 300px;">
        
    </div>
    </div>
</body>

</html>
```

### TEMP.CSS
```
body{
  margin: 0;
  background-repeat: no-repeat;
  background-size: 2000px 2000px;
}
.container{
  width: 850px;
  margin-left: auto;
  margin-right: auto;
}

#banner {
 object-fit: cover;
} 

.mid{
  position: absolute;
  top: 11%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.logo{
height:200px;
width:200px;
}

.title{
  color: #d1cece;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: lighter;
  margin-top: 8%;
}

.aroma{
  color: #d1cece;
  font-family: 'Alegreya Sans SC';
  font-weight: lighter;
  margin-top: 10%;
}

.coffee{
  margin-top: 23%;
}
.roast{
  font-family: 'Alegreya Sans SC';
  color: #d3b134;
  top: 335px;
  left: 570px;
  font-size: 20px;
  opacity: 0.7;
}

.roastinfo{
  font-family: 'Alegreya';
  color: #d1cece;
  top: 385px;
  left: 575px;
  font-size: 15px;
}

.latte{
  opacity: 0.9px;
  top: 770px;
  left: 420px;
}

.cup{
  font-family: Georgia, 'Times New Roman', Times, serif;
  color: #d3b134;
  top: 650px;
  left: 720px;
  font-size: 22px;
  font-weight: lighter;
  opacity: 0.7;
}

.wcup{
  font-family: Georgia, 'Times New Roman', Times, serif;
  color: #f2f0f0;
  top: 653px;
  left: 870px;
  font-size: 20px;
  font-weight: lighter;
}

.wcup1{
  font-family: Georgia, 'Times New Roman', Times, serif;
  color: #f2f0f0;
  top: 685px;
  left: 713px;
  font-size: 20px;
  font-weight: lighter;
}

.year{
  font-family: 'Alegreya';
  color: #d3b134;
  top: 720px;
  left: 633px;
  font-size: 15px;
  opacity: 0.7;
}

.description{
  font-family: 'Gruppo';
  color: #d1cece;
  top: 780px;
  left: 820px;
  text-align: justify;
  font-size: 20px;
}

.hist{
  top: 122%;
  left: 783px;
  padding: 15px;
  padding: 10px;
  font-size: 13px;
  background-color:transparent;
  color: #f6f3f3;
  border: 1px solid #d1cece;
  font-family: 'Alegreya Sans SC';
  cursor: pointer;
}

.hist:hover{
  background-color: #a49356;
}

.info{
  text-align: center;
  color: #d1cece;
  font-family: 'Alegreya';
  top: 1000px;
  font-size:larger ;
}

.info1{
  text-align: center;
  color: #d3b134;
  opacity: 0.9;
  font-family: 'Alegreya Sans SC';
  top: 1045px;
  font-size:larger ;
}

.products{
  top: 155%;
  left: 755px;
  padding: 15px;
  padding: 10px;
  font-size: 13px;
  background-color:#a49356;
  color: #0a0404;
  border: 1px solid #d1cece;
  font-family: 'Alegreya Sans SC';
  cursor: pointer;
}

.products:hover{
  background-color: transparent;
}

.finalprod{
  margin-top: 85%;
}


footer{
  font-size:23px;
  color:azure;
}
```
## OUTPUT:
![image](https://github.com/Evangelin-Ruth/modernweb-exper2/assets/94219798/6421b795-6dce-454d-bf06-5d533a172173)
## RESULT:
Thus,a commercial website is created using html and css.

