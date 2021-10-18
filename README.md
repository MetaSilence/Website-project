# Website-project
My school website project

The bears title is placed depending on the size of the webpage. Use in full screen for best results. 

Ignore my image formating for better grading quality. 

The size of my urls is like that because for some reason it doesn't want to display a tinyfied url.

Here are my "inspirations" for my code: 

formspark gave me my form code, though i did get their product and they have a free shoutout everytime someone sends a message. 

w3 didn't give me my navbar, though i stole the color scheme. (I made my navbar using CSS grid, not toying with padding.)

Also, since my code does not include any Js (my form is built in html and the working part are in the back end of a server somewhere.), I'll add some js example that should work if put in an html file.


        nom : <input type="text" id="InputNom" value=""> <br>
        message : <input type="text" id="InputMessage" value=""> <br>
        <button id="button1" onclick="affiche()">Allo</button>
        <div id="affiche"></div>
        <script>
            function affiche() {
                console.log("debug");
                var nom = document.getElementById("InputNom").value;
                var message = document.getElementById("InputMessage").value;
                var affiche= document.getElementById("affiche");
                
                var text = "Merci pour votre message " + nom;
            
                affiche.innerHTML= text;
            }
        </script>

Thats about it.
