---
title: "payment_landing"
date: 2022-12-07T11:03:45+05:30
---

<section class="back-image" style="background-image:url('/images/stack.jpg');">     
<div class="main-pge">
<p class="str-12">Account hfkiw84qoq-oeoms9654-8215flalofjwje</p>
    <p class="str-21">Valid through DATE</p>
</div>
<div class="d-flex justify-content-center">
            <div class="col-md-5 p-5 shadow-sm border rounded-5 border-primary">
                    <div class="accordion">
        <div class="box active">
            <div class="label">MAKE PAYMENT</div>
      <div class="content">
              <div class="container">
   <div class="row c1">
    <div class="col-sm-4 cll-1"> 
 <figure>
  <img class="bx-img" src="/images/s.png" alt="Logo">  
</figure>
    </div>
    <div class="col-sm-8 cll-2">
    <p class="str-1"> Pay or subscribe with Stripe</p>
    <p class="str-2"> Redirect to Stripe checkout to complete transaction.</p>
    </div>
     </div>
      <div class="row c2">
    <div class="col-sm-4 cll-1">
 <figure>
  <img class="bx-img" src="/images/crypto.png" alt="Logo">  
</figure>
    </div>
    <div class="col-sm-8 cll-2">
    <p class="str-1"> Pay with Crypto</p>
    <p class="str-2"> Pay with Crypto currency.</p>
    </div>
     </div>
      <div class="row c3">
    <div class="col-sm-4 cll-1">
      <figure>
  <img class="bx-img" src="/images/cash.png" alt="Logo">  
</figure>
    </div>
    <div class="col-sm-8 cll-2">
    <p class="str-1"> Pay with Cash</p>
    <p class="str-2"> Pay with Cash by mail.</p>
    </div>
     </div>
</div>
</div>
</div>               
  </div>
 </div>

</div>
    <p class="text-3"> <i class="fa fa-plus-circle" aria-hidden="true"></i>ADD DEVICE</p>  
</div>
         
</section>


<script type="text/javascript">
  
let label = document.querySelectorAll(".box")



label.forEach((e)=>{
    e.addEventListener("click", ()=>{
        removeClass()
        e.classList.toggle("active")
    })
})

function removeClass(){
    label.forEach((e)=>{
        e.classList.remove("active")
    })
}


</script>