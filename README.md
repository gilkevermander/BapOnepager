# BapOnepager


/* fonts */

    @font-face{
      font-family: "sofia-bold";
      src: url('../assets/fonts/bold/Sofia-Pro-Bold-Az.woff2') format('woff2'),
          url('../assets/fonts/bold/Sofia-Pro-Bold-Az.woff') format('woff');

      font-weight: 800;
      font-style: normal;
    }

    @font-face{
      font-family: "sofia-regular";
      src: url('../assets/fonts/regular/Sofia-Pro-Regular-Az.woff2') format('woff2'),
          url('../assets/fonts/regular/Sofia-Pro-Regular-Az.woff') format('woff');

          font-weight: 200;
          font-style: normal;
    }

/* general */

    img{
      display: block;
      height: auto;
    }

    *, *::before, *::after{
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      min-height: 100%;
    }
    html {
      box-sizing: inherit;
      font-size: 62.5%;
      min-height: 100%;
      background-image: url("../assets/background-stipjes.png");
      background-repeat: repeat-y;
      background-size:  auto 1224px;
    }

    body{
      font-family: sofia-regular, Helvetica, Arial, sans-serif;
      /*font-size: 21px;*/
      font-size: 18px;
      line-height: 1.7;
      display: block;
}



/* algemene stijl */

    .hidden{
      display: none;
    }

    .container{


    }

    .subtitle{
      font-family: sofia-bold, Arial, Helvetica, sans-serif  ;
      font-size: 36px;
      margin-bottom: 25px;
      text-transform: uppercase;
    }

    .subtitle__big{
      font-size: 64px;
    }


/* header */
.header__logo{
  display: block;
  height: auto;
  max-width: 100%;
}
   .header{
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
/*
    .header__logo {
    margin-left: 100px;
    margin-bottom: 50px;
    }*/

/* main */

    /*.main{
      display: flex;
      flex-flow: column;
      justify-content: center;
    }

    .content{
      margin-top: 70px;
    }*/

/* main - stappenplan */

  /*  .main__stappenplan{
    }

    .main__stappenplan-img{
      margin: -50px;
      display:block;
      height: 100%;
      margin: 0 auto;
    }*/

/* main - content*/

   

/* main - black-out*/

   .content__blackout {

    max-width: 1240px;
    }

    /* .content__blackout-box {
      background-color: #d78466;
      color: white;
      margin-left: 100px;
      height: 448px;
      border-radius: 15px;
      padding: 50px;
    }*/

/* main - budafabriek*/

   /* .content__budafabriek {
      display: flex;
      flex-flow: row-reverse;
      align-items: center;
    }

    .content__budafabriek-box {
      background-color: #342b64;
      color: white;
      margin-right: 100px;
      height: 394px;
      border-radius: 15px;
      padding: 50px;
    }*/

/* content - makers */

    .content__makers{
      display: flex;
      flex-flow: column;
      align-items: center;
    }

    .subtitle__big{
      align-self: flex-start;
    }

    .maker__img {
      margin: 0 10px;
    }

    .content__makers__grid{
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      grid-template-rows: 200px 400px;
    }

    .content__makers__text{
      max-width: 967px;
      grid-row: 1;
      grid-column: 1/4;
    }

    .content__makers__images{
      grid-row: 2;
      grid-column: 1/4;
    }



  @media only screen and (min-width: 600px) {

    }

