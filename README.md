# simple-calculator
A simple basic calculator using html css and javascript 
does all the bsic arthmethic operations



@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.container{
    width: 450px;
    background: #212121;
    box-shadow: 0 0 30px #2121216b;
    padding: 3.5em 2.5em;
    color: white;
    position: relative;
    display: flex;
    align-items: center;
    flex-direction: column;
     margin-bottom: 70px;
}
.container .author{
    margin-top: 1em;
    background: linear-gradient(to right, #16A085, #f4D03F);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.btn{
    width: 150px;
    height: 40px;
    position: absolute;
    bottom: -8%;
    background: linear-gradient(to right, #16A085, #f4D03F);
    color: white;
    border: none;
    cursor: pointer;
    font-size: 1.3em;
    box-shadow: -10px 20px 50px #16A0848e,10px 20px 50px #f4D03F98 ;
}