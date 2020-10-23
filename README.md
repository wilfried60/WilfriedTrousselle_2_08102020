# WilfriedTrousselle_2_08-10-2020.

/* conteneur activité pour écran inférieur à 1435px */
@media all and (max-width: 1435px){
    header{
        width: 99%;
    }

    .conteneur-activite{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        margin-bottom: 35px;
    }
    
    .conteneur-activite figcaption p{
        font-size: 0.9em;
        font-weight: bold;
        text-align: left;
        margin-left: 20px;
    }

.conteneur-activite figure {
    -webkit-box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
    -moz-box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
    box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
    margin:40px;
    width: 350px;
    margin-top: 23px;
    overflow: hidden;
    
}
.conteneur-2-block{
    width: 100%;
    align-items: center;
    flex-direction: row;
    height: 120px;
}

.conteneur-activite-block:nth-child(1){
    order:1;
 }

 .conteneur-activite-block:nth-child(2){
    order:2;
}

.conteneur-activite-block:nth-child(3){
    order:3;
    
}

.conteneur-activite-block:nth-child(4){
    order:4;
}
.img-1{
    width: 100%;
    height: 120px;
    object-position: 0 -25px;
}

.img-2{
    width: 100%;
    height: 120px;
    object-position: 0 -160px;
}

.img-3{
    width: 100%;
    height: 120px;
    object-position: 0 -25px;

}


.img-4{
    width: 100%;
    height: 120px;
    object-position: 0 -25px;

}

.img-5{
    width: 100%;
    height: 120px;
    object-position: 0 -8px;

}

.img-6{
    width: 100%;
    height: 120px;
    object-position: 0 -40px;

}

  

}

/* mode d'affichage pour écran inférieur à 900px */
@media all and (max-width: 900px){
    #hebergement{
        flex-wrap: wrap;
    }


    .conteneur-hebergement{
        order: 2;
        background:#f2f2f2;
        margin: auto;
        width: 98%;
        margin-top: 20px;

    }
    .populaire{
        min-width: 70%;
    }

    aside{
        order: 1;
        width: 98%;
        margin: auto;
        margin-top: 20px;
    }

    figure{
        width: 320px;
        margin: 30PX;
        margin-top: 40px;

    }
    

    .img-box img{
        
        width: 98%;
    }

    .conteneur-activite{
        margin:auto;
        justify-content: center;
    }


footer{
    width: 100%;
    margin: auto;
    margin-top: 30px;
}

.block-footer{
    flex-direction: column;
    justify-content: flex-start;
}

.block-footer ul:nth-child(2){
    margin-left: 0;
}

.block-footer ul:nth-child(3){
    margin-left: 0;
}

}

/* mode d'affichage pour écran inférieur à 869px */

@media all and (max-width: 869px){

    .conteneur-hebergement{
        order: 2;
        background:white;
        margin: auto;
        width: 98%;

    }

    figure{
        margin: 10px;
        width: 350px;
        margin-top: 10px;

    }

}

/* mode d'affichage pour écran inférieur à 846px */

@media all and (max-width: 846px){

aside{
    order: 1;
    width: 98%;
    margin: auto;
}

.populaire{
    min-width: 0;
    max-width: 350px;
}
}

/* mode d'affichage pour écran inférieur à 552px */

@media all and (max-width: 400px){
   
   
    #formulaire{
        width: 90%;
        margin: auto;
     margin-top: 50px;
    }

    #localisation{
        width: 77%;
        font-weight: bold;

    }

    input{

        height: 35px;
        border: solid 1px #d0d5da ;
    }

    .recherche{

       display: none;
    }

    .circle-search{
        display: inline;
        position: absolute;
        width: 40px;
        height: 40px;
        background: #0065FC;
        margin-left: -12px;
        border-radius:15px;
        color: white;
        cursor: pointer;
        text-align: center;
        line-height: 2.2;
        margin-top: -1px;

    }

    .filtre:nth-child(1){
        width: 100%;

    }

    .filtre:nth-child(2){
        margin:0;
        margin-top: 10px;

    }

    .filtre:nth-child(3){
        margin:0;
        margin-top: 10px;

    }

    .filtre:nth-child(4){
        margin:0;
        margin-top: 10px;

    }

    .filtre:nth-child(5){
        margin:0;
         margin-top: 10px;

    }

    .info{
        margin-bottom: 20px;
    }

    #hebergement{
        flex-wrap: wrap;
    }

    figure{
        margin: auto;
        width: 98%;
        margin-top: 10px;

    }

    .populaire{
        width: 90%;
    }
    
    .img-box{
        flex-direction: column;
    }

    .img-box img{
        width: 98%;
    }

    .conteneur-activite{
        flex-direction: column;
        width: 99%;
    }

    .conteneur-2-block{
        flex-direction: column;
        margin: 0;
        height: auto;
    }
    
    .conteneur-activite figure {
        -webkit-box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
        -moz-box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
        box-shadow: 0px 0px 7px 0px rgba(0,0,0,0.69);
        margin:15px;
        width: 95%;
        margin:auto;
        margin-top: 23px;
        overflow: hidden;
    
    }

    


}

