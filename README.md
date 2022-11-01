# Hospital-landing-page

 @media (min-width:320px) {

    /* body{
        width: 100%;
        height: auto;
        justify-content: center;
        position: relative;
        font-size: 60%;
        align-items: center;
    } */
    /* html{
        font-size: 40%;
    }  */
     #menu-btn {
        display: inline-block;
    }

    .myHeader .navbar {
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background:#16a085;
        padding: 2rem 0;
        transform: scaleY(0);
        transform-origin: top;
        text-align: center;
    } 

    main .container{
        flex-wrap: wrap;
        margin-left: 2rem;
        justify-content: center;
        align-items: center;
       
    }
    
    h1 {
        font-size: 2.5rem;
        /* line-height: .4; */
    }
    p{
        font-size: 2rem;
    }


 main .container.medcineImg img {
   
        /* width: 40rem;
        height: auto;
        margin-top: 2rem; */
       
    }
    /* .home .image img {
        width: 30rem;
    }

    .box-container .box .image img {
        width: 20rem;
    }

    .box-container .box {
        margin: 2rem;
        margin-left: 9.1rem;
    }

    .box-container .box h3 {
        font-size: 3.4rem;
        font-weight: bolder;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .box-container .box p {
        font-size: 2rem;
        font-weight: lighter;
    } */

    /* .fa-times {
        transform: rotate(180deg);
    }

    #myHeader .navbar.active {
        transform: scaleY(1);
    }

    #myHeader .navbar a {
        display: block;
        background: var(--White);
        border-radius: .5rem;
        color: #16a085;
        margin: 1.5rem;
        padding: 1rem 2rem;
        font-size: 2.5rem;
    } */

    /* .container .box .img img {
        width: 34rem;
        box-shadow: 2px 2px 3px black;
    }


    .container .box {
        margin: 1rem;
        margin-left: 2rem;
    } */
}


@media (max-width:768px) {
    #menu-btn {
        display: inline-block;
    }

    header .navbar {
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background: var(--Dark-Blue);
        padding: 2rem 0;
        transform: scaleY(0);
        transform-origin: top;
        text-align: center;
    }

  
}


@media (max-width:600px) {

     html{
        /* font-size: 50.1%; */
    } 

    main .container {
        flex-wrap: wrap;
        margin: 2rem;
        justify-content: center;
        align-items: center;
    }

    h1 {
        font-size: 2rem;
    }

    /* .medcineimg img {
        width: 100%;
        height: auto;
        margin-top: 2rem;
    } */

    main .container .content h1 {
        margin-top: -2rem;
        line-height: 2;
    }

    main .container .content p {
        margin-left: 1rem;
    }

    /* about us */
    .section .container {
        flex-wrap: wrap;
        margin: 2rem;
    }

    .section .container img {
        width: 100%;
        height: auto;
        margin-top: 2rem;
    }

    .section .container .content2 h1 {
        margin-top: -1rem;
        line-height: 1.5;
        margin-left: 3rem;
        margin-bottom: 2rem;

    }

    .section .container .content2 p {
        margin-left: 3rem;
    }

    .section .container .content2 button {
        margin-left: 11rem;
    }

    /* doctors section */
    .ourDoctors .upper-doctors{
        flex-wrap: wrap;
        margin: 6rem;
    
    }
    .book-now .bookUs{
        flex-wrap: wrap;
        margin: 2rem;
      
    }

    .book-now .bookUs img{
        width: 100%;
        height: auto;
        margin-top: 2rem; 
        padding-left: 16rem;
        
    }

    .book-now .bookUs .form-group {
        height:39;
    
    }

    .book-now .bookUs .form-group input{
        height: 4rem;
        width: 36rem;
    }

    .book-now .bookUs .form-group button {
        margin-left: 11rem;
    }
}