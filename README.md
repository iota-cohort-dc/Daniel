# Daniel
Dan's code for web fun


Yellow Belt Code:

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
