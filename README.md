# loading-value

HTML:=
 
           <!DOCTYPE html>
<html>

<head>
      <link rel="stylesheet" href="madan.css">
</head>
<body>


    <div class="loader">
      <div class="ball"></div>
      <div  class="ball"></div>
      <div  class="ball"></div>
      <span>Loading..</span>
    </div>
    

    </body>



    </html>
    
                                    #CSS:=
                                    
                                    
.loader {
    width: 195px;
    height: 350px;
    display: flex;
    flex-wrap: wrap;
    align-items: flex-end;
    justify-content: space-between;
    background-color: blue;
    background-size: cover;
   align-items: center;
}
 .loader span {
    font-size: 22px;
    text-transform: uppercase;
    margin: auto;
   
}

.ball{
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background-color: #fff;
   animation: bounce 2s alternate infinite;
}
.ball:nth-child(2){ 
animation-delay:.16s;
}
.ball:nth-child(3){
    animation-delay: .32s;
}
@keyframes bounce{
    from{
        transform:scaleX(2.25) ;
    }
    
    to{
        transform: 
        translate(-50px) scaleX(0.5);
    }
}

                                    
                                    
