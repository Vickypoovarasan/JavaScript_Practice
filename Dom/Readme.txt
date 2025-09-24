what is dom ?

    ==> When a page loads, the browser creates a tree like struture of the HTML
    ==> This struture is called DOM (Document object model)

 ==> Java script can read and change tha struture..

 DOM struture..

 Document
    -HTML
        -body
            -h1
            -p


2. How do we acces the element.?

    ==> we use selectors..

        document.getElementById("Id")         ==> Select by ID..

        document.getByClassName("Class")      ==> Select by Class..(Collection)

        document.getByTagName("p")            ==> Select by Tagname..(Collection)

        document.querySelector("selector")    ==> first element..(CSS style selector)

        document.querySelectorAll("selector") ==> all matching elements


3. How to do we change element.?

        .textcontent                  ==> Change only the text..

        .innerHTML                    ==> Change text + HTML inside..

        .style                        ==> change CSS (Color, font, etc..)

        .setAttribute(Name, vale)     ==> set setAttribute

        .classList.add/remove/toggle  ==> add or remove CSS classes


4. Events.?

        An event is an action like 
                * click
                * typing
                * hover
                * submit

        We use ( addEventListener ) to listen to Events

    example code...

        button.addEventListener("click",
            function(){
                alert("Button Clicked")
            }
        )