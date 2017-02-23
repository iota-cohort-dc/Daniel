# Tips for Yellow Belt
*Use your validator: https://validator.w3.org/nu/#textarea
*Set a size: 1000px;
*Plan: Do HTML Code first, then do CSS
*Bring a Lunch
*Draw a small model of the project
*Get a print of the wireframe
*use the outline property:  
..*outline: 1px solid red;
*Don't forget to do CSS RESETS!!!
*To use left, right, top, bottom -- you need the position attribute.
*https://fonts.google.com fonts
*https://dabuttonfactory.com/ buttons
*http://www.colorzilla.com/gradient-editor/   great gradient maker


#Flexbox codes:

Flexbox: Add "display: flex;" to parent, and "flex: 1;" to the children and figure it out.

.menu{
    margin-left: auto;
    margin-right: auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.menu li{
    flex: 1;
    list-style-type: none;
    display: inline-block;
    border: 1px solid black;
    padding: 5px;
    margin-top: 5px;
    min-width: 100px;
    text-align: center;
}

.columns{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

/* In this case we use ^ to say, "if it starts with 'col-'" */
div[class^='col-']{  
    flex: 1;
    padding: 10px;
    margin-left: 10px;
    margin-right: 10px;
    min-width: 200px;
}
