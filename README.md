<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
  <!--    <link rel="stylesheet" href="task4.css"> -->

    <title>Hello, world!</title>
  </head>
  <body>
      
      <style>
      
      .kj{
    background-size: 800px;
    background-image:url('D:/fq2.jpg' );
    background-size: contain;
     
    width: 30px;
    height: 30px;
    
}
.kt{
    background-size: 800px;
    background-image:url('D:/fq1.jpg' );
    background-size: contain;
     
    width: 30px;
    height: 30px;
    
}
.kv{
    background-size: 800px;
     
    width: 30px;
    height: 30px;
    
}
 .inputWithIcon{
         position: relative;
          }       
          
.inputWithIcon i{
         position: absolute;
    
         left: 0px;
          
   
         padding: 9px 8px;
          }
      
      
      </style>
    <script type="text/javascript">
        
        var m1=2*80;
var m2=3*100;
var m3=1*50;
var m4=m1+m2+m3;
var m5=m4-20;


function sum(){
  
 
    if(document.getElementById('n1')!=null)
        {
          
             y1=parseInt(document.getElementById('n1').value);
                m1=y1*80;
            document.getElementById('n3').innerHTML="$"+m1+".00";
             
        }
    
    
    else
        {
             
            
            m1=0;
             
            
        }
     if(document.getElementById('h1')!=null)
        {
          
             y2=parseInt(document.getElementById('h1').value);
                m2=y2*100;
            document.getElementById('h2').innerHTML="$"+m2+".00";
             
        }
    
    
    else
        {
             
            
            m2=0;
             
            
        }
    if(document.getElementById('p1')!=null)
        {
          
             y3=parseInt(document.getElementById('p1').value);
                m3=y3*50;
            document.getElementById('p2').innerHTML="$"+m3+".00";
             
        }
    
    
    else
        {
             
            
            m3=0;
             
            
        }
     
     m4=m1+m2+m3;
    document.getElementById('p4').innerHTML="$"+m4+".00";
 m5=m4-20;
     document.getElementById('p5').innerHTML="$"+m5+".00";
    
    
    
}


function dele()
{
    m4=m1+m2;
     document.getElementById('p4').innerHTML="$"+m4+".00";
    m5=m4-20;
    document.getElementById('p5').innerHTML="$"+m5+".00";
        var elem= document.getElementById('o1');
  
    elem.remove();
    

}
function dele1()
{
    m4=m3+m2;
     document.getElementById('p4').innerHTML="$"+m4+".00";
    m5=m4-20;
    document.getElementById('p5').innerHTML="$"+m5+".00";
        var elem= document.getElementById('kk1');
  
    elem.remove();
    

}
function dele2()
{
    m4=m1+m3;
     document.getElementById('p4').innerHTML="$"+m4+".00";
    m5=m4-20;
    document.getElementById('p5').innerHTML="$"+m5+".00";
        var elem= document.getElementById('kk2');
  
    elem.remove();
    

}
      </script>
      
      
      
 <nav class="navbar navbar-expand-lg navbar-light bg-light">

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
      
    <ul class="navbar-nav mr-auto">
      
      <li class="nav-item">
        <a class="nav-link" href="#">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Default Welcome Msg!&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</a>
          
          
          
      </li>
         
    
       <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"> <img src="D:\gh.jpg" width="20" height="20" alt="" >
          Language
        </a>
         <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          $&nbsp; Currency
        </a>
     
        
         
       <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
           <i class="fas fa-user-alt"></i> 
          My Acount
        </a>
      </ul>
    
       
    
          
      
       
  </div>
</nav>
      <div class="container mt-5 mb- 4" >
      <div class="row" >
      
        <div class="col- mb-3">
           <img src="D:\OP1.png" width="50" height="50" alt="" >
          </div>
          <div class="col-md-3 mb-3">
          <font Size="5">OPENING TIME</font><BR>
          
          
          9.00AM-10.00PM
          
         
          </div>
        
           <div class="col-md-4 mb-3">
      <img src="D:\fy7.jpg" width="120" height="120" alt="" >
                </div>
          <div class="col-md-4 mb-3">
              <div class="inputWithIcon">
              <input type="text" value="" width="600" height="200" placeholder="Search"  >
              
      </div>
            </div>
          </div>
           </div>
      
      
      
      
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
 
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Home <span class="sr-only">(current)</span></a>
      </li>
         <li class="nav-item active">
        <a class="nav-link" href="#">CLOTHING <span class="sr-only">(current)</span></a>
      </li>
         <li class="nav-item active">
        <a class="nav-link" href="#">EQUIPMENTS <span class="sr-only">(current)</span></a>
      </li>
         <li class="nav-item active">
        <a class="nav-link" href="#">BLOG <span class="sr-only">(current)</span></a>
      </li>
         <li class="nav-item active">
        <a class="nav-link" href="#">PAGES <span class="sr-only">(current)</span></a>
      </li>
    <li class="nav-item active">
        <a class="nav-link" href="#">CONTACTUS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="sr-only">(current)</span></a>
      </li>
      <img src="D:\ft4.jpg" width="150" height="100" alt="" >
    </ul>
     
   
  </div>
</nav>
      
      <div class="container mt-5 mb- 4" >
      <div class="row" >
          <div class="col-md-11 mb-3">
           <nav class="navbar navbar-expand-lg navbar-light bg-light">
 
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
          
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home >  <span class="sr-only">(current)</span></a>
      </li>
         <li class="nav-item active">
        <a class="nav-link" href="#"><font color="red" > Cart </font><span class="sr-only">(current)</span></a>
      </li>
        
      
    </ul>
   
  </div>
</nav>
          </div> 
          </div>
      </div>
      


      <div class="container mt-5 mb- 4" >
  <div class="row" >
 <div class="col-md-8 mb-3">
<form  >
<div class="form-row" >
<h4>Shopping Cart </h4>
</div>

  <div class="form-row" >
    <div class="col-md-6 mb-3">
      </div>
      <table class="table table-bordered">
          
  <thead>
    <tr>
      
      <th scope="col">Image</th>
      <th scope="col">Product Name</th>
      <th scope="col">Model</th>
      <th scope="col">Quantity</th>
      <th scope="col">Unite Price</th>
      <th scope="col">Total</th>
    </tr>
  </thead>
  <tbody>
    <tr id="kk1">
      <th scope="row"> <img src="D:\fy1.jpg" width="120" height="120" alt="" ></h4></th>
      <td>Blandit Blandit</td>
      <td>Product 1</td>
      <td><div class="row" > <input type="text" class="kv" id="n1"   value="2"><input type="button" class="kt"  name="button" onclick="sum()"></button><input type="button" class="kj" name="butto" onclick="dele1()" ></button></div></td>
         <td id="n2" >$ 80.00</td>
      <td ><p id="n3" o>$160.00</p></td>
    </tr>
    <tr id="kk2">
      <th scope="row"><img src="D:\fy2.jpg" width="120" height="120" alt="" ></th>
      <td>Deliver Wide</td>
      <td>Product2</td>
        <td><div class="row" > <input type="text" class="kv" id="h1"   value="3"><input type="button" class="kt"  name="button" onclick="sum()" ></button><input type="button" class="kj" name="butto" onclick="dele2()" ></button></div></td>
        <td>$100.00</td>
        <td id="h2">$300.00</td>
    </tr>
    <tr id="o1">
      <th scope="row"><img src="D:\fy3.jpg" width="120" height="120" alt="" ></th>
      <td colspan="1">Hat</td>
      <td>Product 3</td>
        <td><div class="row" > <input type="text" class="kv" id="p1"  value="1"><input type="button" class="kt"  name="button" onclick="sum()" ></button><input type="button" class="kj" name="butto" onclick="dele()" ></button></div> </td>
        <td>$50.00</td>
        <td id="p2">$50,00</td>
    </tr>
  </tbody>
</table>
   
  <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</p>
       <div class="col-md-5 mb-3">
      <table class="table table-bordered">
          
  <thead>
    <tr>
      
      <th scope="col">Sub-Total:</th>
      <th  id="p4">$510.00</th>
      
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Discount </th>
      <td>$20.00</td>
      
    </tr>
    <tr>
      <th scope="row">Total:</th>
      <td id="p5">$490.00</td>
      
    </tr>
   
  </tbody>
</table>
          
          
    </div>
      <div class="col-md-10 mb-3">
      <button type="button" class="btn btn-light">Continue Shoping</button>
      </div>
      <div class="btn-group-toggle" data-toggle="buttons">
  <label class="btn btn-secondary active">
    <input type="checkbox" checked> Checkout
  </label>
</div>
       </div>
</form>
</div>
 

<div class="col-md-4 mb-3">
 

<div class="row" >
<div class="col-md-6 mb-3">
<table class="table table-bordered" >
  <thead>
   
      
      <img src="D:\ft1.jpg" width="300" height="400" alt="" ><br>
        
    <img src="D:\ft2.jpg" width="300" height="400" alt="" ><br>
      
   
  
  
    
</thead>

</table>
</div>
  </div>
 </div>
 </div>
      
      





<!-- Footer -->
<footer class="page-footer font-small footer-light  bg-light lighten-5">

  

  <!-- Footer Links -->
  <div class="container text-center text-md-left mt-5">

    <!-- Grid row -->
    <div class="row mt-3 dark-grey-text">

      <!-- Grid column -->
      <div class="col-md-3 col-lg-4 col-xl-3 mb-4">

        <!-- Content -->
        <h6 class="text-uppercase font-weight-bold">ACCESSORIES</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>Here you can use rows and columns to organize your footer content. Lorem ipsum dolor sit amet,
          consectetur
          adipisicing elit.<BR>
            
            <ul class="list-unstyled list-inline text-center">
      <li class="list-inline-item">
        <a class="btn-floating btn-fb mx-1">
          <i class="fab fa-facebook-f"> </i>
        </a>
      </li>
      <li class="list-inline-item">
        <a class="btn-floating btn-tw mx-1">
          <i class="fab fa-twitter"> </i>
        </a>
      </li>
      <li class="list-inline-item">
        <a class="btn-floating btn-gplus mx-1">
         
            <i class="fas fa-wifi"></i>
        </a>
      </li>
      <li class="list-inline-item">
        <a class="btn-floating btn-li mx-1">
           <i class="fab fa-stripe-s"></i>
        </a>
      </li>
      <li class="list-inline-item">
        <a class="btn-floating btn-dribbble mx-1">
          <i class="fab fa-dribbble"> </i>
        </a>
      </li>
               
     
       
       
      
                
    </ul>
            </p>

      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold">MY ACCOUNT</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>
         MY Account
        </p>
        <p>
          Order History
        </p>
        <p>
          Wish List
        </p>
         <p>
          Newsletter
        </p>

      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold">INFORMATION</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>
          About Use
        </p>
        <p>
         Delivery Information
        </p>
        <p>
          Privacy Policy
        </p>
       
        <p>
          Terms & Coditions
        </p>
      </div>
        
        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold">EXTRAS</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
        <p>
        Brands
        </p>
        <p>
         Gift Vouchers
        </p>
        <p>
          Affiliates
        </p>
        <p>
          Spcials
        </p>

      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-3 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">

        <!-- Links -->
        <h6 class="text-uppercase font-weight-bold">Contact</h6>
        <hr class="teal accent-3 mb-4 mt-0 d-inline-block mx-auto" style="width: 60px;">
       <div class="row" >  <p><div class="col- mb-3">
           <i class="fas fa-map-marker-alt"></i></div>
           <div class="col-md-10 mb-3">
               8901 Marmora Road,Glasgow D0489 GR, New York</div></p></div>
        
        <div class="row" > <p>
            <div class="col- mb-3">
               
             <i class="fas fa-phone-square-alt"></i></div>
           <div class="col-md-1 mb-3">
                 (0123)456789<BR>
               (0987)654321</div></p></div>
        <p>
          <i class="fas fa-envelope mr-3"></i> admin@bootexperts.com</p>
        

      </div>
      <!-- Grid column -->

    </div>
    <!-- Grid row -->

  </div>
  <!-- Footer Links -->

  <!-- Copyright -->
 
  
  <!-- Copyright -->
<div class="card-footer bg-dark">
    
        
   <font color="white">Copyright 2015 <font color="Red" >BootExperts</font>Allrights reserved&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </font>
       
    
    <i class="fab fa-cc-visa" color="white"  ></i>
    <i class="fab fa-cc-paypal" color="white"></i>
    <i class="fab fa-cc-discover" color="red"></i>
    <i class="fas fa-globe-asia" color="blue"></i>
    <i class="fas fa-map-marked" color="red"></i>
    
  
</footer>


  
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
     <script src="all.min.js"></script>

  </body>
</html>
