/* General styles */
body {
    font-family: "pacifico" , cursive;
    margin: 0;
    padding: 0;
    background: url('https://png.pngtree.com/background/20230524/original/pngtree-some-blue-pills-and-capsules-laying-around-one-another-picture-image_2710878.jpg') no-repeat center center fixed;
    background-size: cover;
    color: #f7f1f1;
}

header {
    color: rgb(215, 235, 245);
    text-align: center;
    background-color: #e2dddd33;
    font-family: "Stylish", serif;
    font-weight: 400;
    font-style: normal;
    font-size: x-large;
  
}

header p{
    font-size: 35px;
    margin-top: -25px;
}


.menu {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    background-color:cadetblue;
    padding : 10px;
    margin-top: -34px;
}

.menu > a{
   color: white;
}

nav a:hover {
    background-color: #ddd;
    color: #f3ebeb;
}

.container {
    padding: 20px;
    margin: 10px auto;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    font-size: x-large;
    width: 80%;
    border-radius: 10px;
    background: rgba(0, 0, 0, 0.7);
}

/* Main content styles */
main {
    padding: 20px;
    background: rgba(0, 0, 0, 0.7);
    margin: 20px;
    border-radius: 10px;
}

/* Introduction section styles */
.introduction {
    margin-bottom: 40px;
}

.introduction h2 {
    font-size: 2em;
    margin-bottom: 10px;
}

/* Medicine types section styles */
.medicine-types {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.medicinesdiv
{
    display : flex;
    flex-direction: row;
    justify-content: space-between;
}

.medicine-card {
    background: #ffffff;
    border: 1px solid #dddddd;
    border-radius: 10px;
    box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.1);
    margin: 10px;
    padding: 20px;
    width: calc(33% - 40px);
    text-align: center;
}

.medicine-card img {
    max-width: 100%;
    border-radius: 10px;
}

.medicine-card h3 {
    margin-top: 15px;
    font-size: 1.5em;
}

.medicine-card p {
    font-size: 1em;
    margin-top: 10px;
}


/* Footer styles */
footer {
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    text-align: center;
    padding: 10px 20px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

main > section >div >div >h3{
 color: black;
}
main > section >div >div >p{
    color: black;
   }
.medicinetext
{
    color : white
}

footer p {
    margin: 0;
}

