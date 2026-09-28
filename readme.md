# inline css
* Written directly inside the html tag *
 Example: <h4 style="color: blueviolet;">CSS: Cascading Style Sheets</h4>

# internal css
1. Written in the html file that we want to do style
2. Have to create a <style>...</style> tag and inside the tag the the style has been done
   Example: <head>
              <style>
            **for styling the class we will apply (.) before class name** 
              .head{
                styles will be applied inside the part
               }

            **for styling the id we will apply (#) before class name. id name has to be unique.**
               #para{
                 styles will be applied here
               }
               <style>

            </head>
   
             <header class="head">
                 <p>Welcome</p>
             </header>

             <p id="para"> Styling </p>

# External css
1. Create a separate file with a .css extention and do styling there
2. link the css file with <link> tag. *In the place of fabicon write the path of the css file*