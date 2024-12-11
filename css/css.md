# CSS i denna mapp

body {
    margin: 0px;
    padding: 0px;
    background-color:rgb(250, 253, 240);
    color:rgb(48, 48, 48);
}

#wrapper {
    margin: 0px;
    padding: 0px;

}

main {
    grid-area: mn;
}

aside {
    grid-area: as;
}

/* Header */
header {
    grid-area: hd;
    display: flex;
    align-items: center;
    justify-content:space-between;
    background-color: rgb(255 87 51);
    height: 60px;
    width: vw;
    padding: 0px;
    margin: 0px;
    border-bottom: outset rgb(213, 59, 24);
}

#loginbutton {
    background-color: turquoise;
    border: 2px rgb(39, 188, 173);
    height: 50px;
    margin: 10px;
    padding: 0 20px 0 20px;
    align-content: center;
    border-radius: 5px;
    font-size: 20px;
}

h1 {
    color: aliceblue;
    letter-spacing: 5px;
    font-size: 50px;
}


/*Navigation in header*/
nav {
    display: flex;
    background-color: rgb(250, 253, 240);
    padding: 0px;
    margin: 0px;
    justify-self: flex-end;
    align-self: flex-end;
    align-items: center;
    justify-content:space-between;
    width: 400px;
    height: 60px;
    border-left: outset rgb(249, 189, 173);
}

.navbuttons {
    background-color: rgb(255 87 51);
    height: 50px;
    margin: 10px;
    padding: 0 20px 0 20px;
    align-content: center;
}



/*Main on homepage*/
main.homepage{
    justify-self: center;
    justify-items: center;
    background-color: rgb(255 87 51);
    padding: 10px 20px 60px 20px;
    margin: 20px;
    height: fit-content;
    width: 500px;
    font-style: italic;
}

.searchbar{
    height: 30px;
    width: 250px;
    border-style: none;
    border-radius: 10px;
    padding: 0px 40px 0px 10px;
    font-size: 15px;
    letter-spacing: 2px;
    outline: none;
    background-image: url(https://cdn2.hubspot.net/hubfs/4004166/bioticresearch_website_assets/images/search_icon.png);
    background-repeat: no-repeat;
    background-position: right center;
}

.searchbar::placeholder{
    color: rgb(123, 123, 123);
    font-size: 15px;
    letter-spacing: 2px;
    font-weight: 100;
}



/*Recipe page*/

.recipe-page{
    display: grid;
    grid-template-columns: 60% 40%;
    grid-template:
    'hd hd'
    'mn as'
}


/*Main on recipe page*/

#sort-by-box {
/*    background-color: rgb(250, 253, 240);
    width: 130px;
    padding: 10px;
    margin: 15px 0px 10px 10px;
    border: 1px rgb(123, 123, 123) solid;
    border-radius: 5px; */
    position: relative;
    display: inline-block;

    background-color: #04AA6D;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
}

.sort-by-type {
/*    color: black;
    padding: 12px 16px;
    text-decoration: none; */
    display: block;
}

#recipes {
    background-color: rgb(255 87 51);
}

#recipe-section{
    display: flex;
    flex-flow: row wrap;
}

.recipe-box {
    display: flex;
    flex-direction: column;
    height: fit-content;
    width: 200px;
    margin: 10px 20px 30px 20px;
    padding: 10px 10px 0px 10px;
    background-color: rgb(255, 255, 255);
    border: 5px double rgb(250, 253, 240);

}

.recipe-img {
    align-self: center;
}

.recipe-rating {
    align-self: end;
}


/*News article aside*/

#recipe-news {
    background-color: rgb(250, 253, 240);
} 

h2 {
    margin: 10px 0px 10px 20px;
    color: rgb(181, 35, 2);
}

.news-box {
    display: flex;
    flex-direction:row;
    justify-content: flex-end;
    border: 1px solid rgb(123, 123, 123);
    padding: 10px;
    margin: 10px;
    width: 200px;
    height: fit-content;
}

/*h3 {
    justify-self: flex-start;
}*/

.news-img {
    align-self: center;
    justify-self: flex-end;
}

/*Staff page*/

#staff-page {
    justify-self: center;
    width: 600px;
}

#staff-section {
    display: flex;
    flex-wrap: wrap;
    justify-items: center;
}

.staff-box {
    height: 150px;
    width: 150px;
    margin: 20px;
    justify-items: center;
/*    border: 2px dashed rgb(123, 123, 123);*/
}



/*Links*/

a {
    color:rgb(250, 253, 240);
    text-decoration: none;
}

a:hover {
    background-color:rgb(213, 59, 24)
}

a.active {
    background-color: rgb(181, 35, 2);
    color: white;
  }
  



/* Dropdown Button */
  
  /* The container <div> - needed to position the dropdown content */
  
  /* Dropdown Content (Hidden by Default) */
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
  }
  
  /* Links inside the dropdown */
  .dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
  }
  
  /* Change color of dropdown links on hover */
  .dropdown-content a:hover {background-color: #ddd;}
  
  /* Show the dropdown menu on hover */
  .dropdown:hover .dropdown-content {display: block;}
  
  /* Change the background color of the dropdown button when the dropdown content is shown */
  .dropdown:hover .dropbtn {background-color: #3e8e41;}
  