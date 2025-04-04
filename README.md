@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #4e2804;
}

.topnav {
  overflow: hidden;
  background-color: transparent;
position:absolute;
top:0px;
right:80px;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: rgb(230, 165, 140);
  color: black;
}

.topnav a.active {
  background-color: #a05234;
  color: white;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 630px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
    
  }
}

@media screen and (max-width: 630px) {
  .topnav.responsive {position: absolute;
    position: absolute;
    right: 1px;
    top: 1px;}
  
  .topnav.responsive .icon {
    position: absolute;
    right: 1px;
    top: 1px;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
.navbar-brand {
	color: rgba(255, 192, 167, 0.932);
  font-size: 30px;
 font-family: Georgia, 'Times New Roman', Times, serif;
  letter-spacing: 2px;
  position: absolute;
  top: 20px;
  left: 60px;
}

.img-slider{
  position: relative;
  width: 800px;
  height: 500px;
  margin: 10px;
  background: #1D212B;
}

.img-slider .slide{
  z-index: 1;
  position: absolute;
  width: 100%;
  clip-path: circle(0% at 0 50%);
}

.img-slider .slide.active{
  clip-path: circle(150% at 0 50%);
  transition: 2s;
  transition-property: clip-path;
}

.img-slider .slide img{
  z-index: 1;
  width: 100%;
  border-radius: 5px;
}

.img-slider .slide .info{
  position: absolute;
  top: 0;
  padding: 15px 30px;
}

.img-slider .slide .info h2{
  color: #fff;
  font-size: 40px;
  text-transform: uppercase;
  font-weight: 800;
  letter-spacing: 2px;
}



.img-slider .navigation{
  z-index: 2;
  position: absolute;
  display: flex;
  bottom: 30px;
  left: 50%;
  transform: translateX(-50%);
}

.img-slider .navigation .btn{
  background: rgba(255, 255, 255, 0.5);
  width: 12px;
  height: 12px;
  margin: 10px;
  border-radius: 50%;
  cursor: pointer;
}

.img-slider .navigation .btn.active{
  background: #2696E9;
  box-shadow: 0 0 2px rgba(0, 0, 0, 0.5);
}

@media (max-width: 1326px){
  .img-slider{
    width: 600px;
    height: 375px;
  }

  .img-slider .slide .info{
    padding: 10px 25px;
  }

  .img-slider .slide .info h2{
    font-size: 30px;
  }

 

  .img-slider .navigation{
    bottom: 25px;
  }

  .img-slider .navigation .btn{
    width: 10px;
    height: 10px;
    margin: 8px;
  }
}

@media (max-width: 710px){

  .navbar-brand {
    font-size: 20px;
    top:20px;
    left:15px;
  }

  .img-slider{
    width: 400px;
    height: 200px;
    top: 20px;
  }


  .img-slider .slide .info{
    padding: 10px 20px;
  }

  .img-slider .slide .info h2{
    font-size: 30px;
  }

  .img-slider .navigation{
    bottom: 15px;
  }

  .img-slider .navigation .btn{
    width: 8px;
    height: 8px;
    margin: 6px;
  }
}

@media (max-width: 420px){
  .img-slider{
    width: 320px;
    height: 200px;
  }

  .img-slider .slide .info{
    padding: 5px 10px;
  }

  .img-slider .slide .info h2{
    font-size: 25px;
  }

  .img-slider .navigation{
    bottom: 10px;
  }
}![5](https://github.com/user-attachments/assets/f3cb11d6-c7a0-4317-b892-febd3f96ec82)
![6](https://github.com/user-attachments/assets/a56c1faa-c44f-448d-8526-2a84fffbbcc9)
![4](https://github.com/user-attachments/assets/e9e0f773-0d90-427b-ae7d-97d2cf51f3e4)
![2](https://github.com/user-attachments/assets/8b71acbe-a23a-40d5-b1b4-f4b78dabf878)
![1](https://github.com/user-attachments/assets/d04c680c-431e-4470-a5b5-b5cf27e544b2)
