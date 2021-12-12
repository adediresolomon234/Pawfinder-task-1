<template>
<div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height bg-white p-4">
        <div class="row row-height  pt-5">
            <nav class="nav">
                    <div class="main_list d-block d-lg-none">
                            <ul class="navlinks">
                                <li><a href=""><b-icon icon="arrow-left"></b-icon></a></li>
                                <li><a href=""><img src="../assets/image 3.png" alt="" class="image-cover"></a></li>
                                <li><a href="">Powdur</a></li>
                                <li><a href=""><b-dropdown id="dropdown-left" text="Details" variant="outline-none" class="m-2 "></b-dropdown></a></li>
                            </ul>
                    </div>
            </nav>
            <div class="col-lg-6 pt-4  ">
                  <div class="temp-list d-none d-lg-block ">
                            <div id="user-cover">
                                <img src="../assets/image 3.png" alt="" class="image-cover">
                            </div>
                            <div id="back-btn">
                                <ul class="backlinks">
                                    <b-icon icon="arrow-left"></b-icon>
                                    <span class="arrow-text">Back Powdur</span>
                                </ul>
                            </div>
                </div>
                <div class="product">
                     <h4 class="product-name">Pure Sure</h4>
                </div>
                <div class="product">
                     <h4 class="product-price">$65.00</h4>
                </div>
                   <div class="product">
                        <img src="../assets/image 4.png" alt="" class="product-image ">
                </div>
                <div class="text-center p-t-136  d-none d-lg-block">
						<a class="txt2" href="#">
							Powered by <img src="../assets/svgexport-1.png" alt="" srcset=""> | Terms Privacy
							<i class="fa fa-long-arrow-right m-l-5" aria-hidden="true"></i>
						</a>
				</div>
                 
                
                </div>

               <div class="col-lg-6" id="payment-details">
                  
                 <div class="card">
                  <div class="card-body p-5  ">
                       <div class="row-payment ">
                            <div class="align-self-start mx-auto ">
                                <button class="btn btn-dark btn-lg btn-block" type="submit"><img src="../assets/XMLID 34.png" alt="" class="payment-image"></button>
                                <h1 class="apple-pay">Or pay with card</h1>
                            </div> 
                            <form role="form">
                                <div class="mb-3">
                                    <label class="dis fw-bold mb-2">Email address</label> <input class="form-control" id="control4" type="email" >
                                </div>
                            <div class="address">
                            <label class="dis fw-bold mb-2">Card details</label> <input class="form-control" id="form-img" aria-label="Default select example" value="1234 1234 1234 1234">
                            
                            <div class="d-flex"> <input class="form-control zip"  id="control1" type="text" placeholder=" MM/YY"> <input class="form-control "  id="control2"  placeholder="CCV"> </div>
                             </div>
                             <div class="my-3 cardname">
                            <label class="dis fw-bold mb-2">Name on the card</label> <input class="form-control" id="control4" type="text">
                            </div>
                        <div class="address">
                        <label class="dis fw-bold mb-3">Country or region</label> <select class="form-select" id="control5" aria-label="Default select example">
                            <option selected hidden>United States</option>
                            <option value="1">India</option>
                            <option value="2">Australia</option>
                            <option value="3">Canada</option>
                        </select>
                        <div class="d-flex"> <input class="form-control zip" id="control3" type="text" placeholder="ZIP"> </div>
                        
                        
                    </div>
                           
                            <div class="align-self-start mx-auto mt-4 ">
                                <button class="btn btn-dark btn-lg btn-block" type="submit"><span class="payment-total">Pay $65.00</span></button>
                                
                            </div>
                            </form>
                    </div> 
                </div>
                  </div>
                  
            </div>
        </div>
                 
        </div>
    </div>




</template>

<script>
export default {
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav {
    width: 100%;
    height: 65px;
    position: relative;
    line-height: 65px;
    text-align: center;
    z-index: 1;
}

.nav div.logo a:hover {
    color: #00E676;
}

.nav div.main_list {
    height: 65px;
    padding: 20px;
}

.nav div.main_list ul {
    width: 100%;
    height: 65px;
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

.nav div.main_list ul li {
    width: auto;
    height: 65px;
    padding: 0;
    padding-right: 3rem;
}

.nav div.main_list ul li a {
    text-decoration: none;
    color: rgb(0, 0, 0);
    line-height: 65px;
    font-size: 15px;
    font-family: 'Poppins', sans-serif;;
    
}

.nav div.main_list ul li a:hover {
    color: #08daff;
}
.main_list{
    margin-right: -3px;
 
}

.nav {
    padding-top: 20px;
    padding-bottom: 20px;
    -webkit-transition: all 0.4s ease;
    transition: all 0.4s ease;
}

@media screen and (max-width:455px) {
   
    .nav div.logo {
        margin-left: 15px;
    }

    .nav div.main_list ul {
        width: 100%;
        height: 65px;
        display: flex;
        list-style: none;
        margin: 0;
        padding: 0;
            
    }
    .nav div.main_list ul li {
        width: 40px;
        text-align: right;
        position: relative;
    }
    .nav div.main_list ul li a {
        text-align: center;
        width: 50%;
        font-size: 10px;
        padding: 20px;
        color: #111;
    }
    .nav div.media_button {
        display: block;
    }
}


#user-cover{
   position: relative;
   right: 150px;
   margin-bottom: 0;
}
.backlinks{
   position: relative;
   right: 148px;
   font-size: 14px;
   margin-top: 20px;
   padding-top: 0;
   
}

.b-icon{
    margin-right: 1rem;
}
.arrow-text{
    font-family: 'poppins';
}
 .product-name{
   position: relative;
   font-size: 20px;
   right: 113px;
   margin-top: 20px;
   padding-top: 16px;
   color: #8792A2;   
} 
.product-price{
   position: relative;
   font-size: 40px;
   right: 93px;
   font-family: 'poppins';
   font-weight: 500 ;
   color: rgb(12, 12, 12);
}
.product-image{
   margin-top: 50px;
   border-radius: 10px;
  
}

#payment-details{
        box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.08);
        
}
@media screen and (max-width:991px){
    #payment-details{
        box-shadow:none;
        
    }
     .product-price{
        position: relative;
        font-size: 30px;
        right: 0px;
        font-family: 'poppins';
        font-weight: 500 ;
        color: rgb(12, 12, 12);
 }
        .product-name{
        position: relative;
        font-size: 15px;
        right: 0px;
        margin-top: 20px;
        padding-top: 16px;
        color: #8792A2;  
        }
                
        .product-image{
        width: 145px;
        margin-top: 50px;
        border-radius: 10px;
        
        
        }
}
@media screen and (max-width:320px){
    .product-price{
        position: relative;
        font-size: 30px;
        right: 0px;
        font-family: 'poppins';
        font-weight: 500 ;
        color: rgb(12, 12, 12);
 }
    .product-name{
        position: relative;
        font-size: 15px;
        right: 0px;
        margin-top: 20px;
        padding-top: 16px;
        color: #8792A2;  
 }
        
        .product-image{
        width: 145px;
        margin-top: 50px;
        border-radius: 10px;
        
        }
}
 .txt2 {
  font-family: 'Poppins';
  font-size: 13px;
  line-height: 1.5;
  color: #666666;
  word-spacing: 10px;
  text-decoration: none;
  
}
.text-center{
  padding-top: 60px;
}
    .apple-pay{
        display: flex;
        flex-direction: row;
        font-size: 16px;
        font-family: 'poppins';
        margin-top:30px;
        color: #8792A2;
        margin-right: -12px;
        
    }
    .apple-pay:before , .apple-pay:after{
        content:"";
        flex: 0.2;
        border-bottom: 1.5px solid;
        margin: auto;
        color: #8792A2;
        font-family: 'poppins';
        opacity: 0.5;
    }
    .apple-pay:before{
        margin-right:10px ;
    }
    .apple-pay:after{
        margin-left: 10px;
    }
    .btn-dark{
        width: 100%;
        font-family: 'poppins';
    }
    .form-control{
        height: 40px;
        border-radius: 8px 8px 0px 0px;
        border: 1px solid rgba(60, 66, 87, 0.12);
        box-sizing: border-box;
        box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.08), 0px 1px 1px rgba(0, 0, 0, 0.04);
        color: #8792A2;

    }
    .form-select{
       height: 40px;
        border-radius: 8px;
        border: 1px solid rgba(60, 66, 87, 0.12);
        box-sizing: border-box;
        box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.08), 0px 1px 1px rgba(0, 0, 0, 0.04);  
    }
    #control1{
        border-radius: 0px 0px 0px 8px ;
    }
    #control2{
        border-radius: 0px 0px 8px 0px ;
    }
    #control4{
        border-radius: 8px ;
    }
    #control3{
         border-radius: 0px 0px 8px 8px ;
    }
    #control5{
         border-radius: 8px 8px 0px 0px ;
    }
    #form-img{
    display: block;
    width: 100%;
    padding: 0.375rem 2.25rem 0.375rem 0.75rem;
    -moz-padding-start: calc(0.75rem - 3px);
    font-size: 15px;
    font-weight: 400;
    line-height: 1.5;
    color:#8792A2;
    background-color: #fff;
    background-image: url("../assets/Discover.png"), url("../assets/Americanexpress.png"), url("../assets/Mastercard.png");
    background-repeat: no-repeat;
    background-position: right 0.75rem center,right 2.2rem center,right 3.7rem center;
    background-size: 16px 12px;
    }
    #control2{
    display: block;
    width: 100%;
    padding: 0.375rem 2.25rem 0.375rem 0.75rem;
    -moz-padding-start: calc(0.75rem - 3px);
    font-size: 15px;
    font-weight: 400;
    line-height: 1.5;
    color:#8792A2;
    background-color: #fff;
    background-image: url("../assets/CVCCard.png");
    background-repeat: no-repeat;
    background-position: right 0.75rem center;
    background-size: 18px 12px;
    }
    .payment-total{
        color: #8792A2;;
    }

   .fw-bold{
       float: left;
       font-family: 'poppins';
   }
   .card{
       border: none !important;
   } 
 .p-5{
     width: 500px;
    margin-right: auto; margin-right: auto;
 }
 @media screen and (max-width:991px){
     .p-5{
       margin-right: auto;
       margin-left: auto;
     }
 }
 @media screen and (max-width:500px){
     .p-5{
       width:370px ;
       margin-right: auto;
       margin-left: auto;
     }
 }
  @media screen and (max-width:375px){
     .p-5{
       width:336px ;
       margin-right: auto;
       margin-left: auto;
     }
     
 }
 @media screen and (max-width:320px){
     .p-5{
       width:336px ;
       margin-right: auto;
       margin-left:-19px;
     }
 }
</style>
