<script setup lang="ts">
</script>

<template>
    <section id="contact">

<div class="row section-intro">
   <div class="col-twelve">

       <h5>Contact</h5>
       <h1>J'aimerais avoir de vos nouvelles.</h1>

       <p class="lead">Lorem ipsum Do commodo in proident enim in dolor cupidatat adipisicing dolore officia nisi aliqua incididunt Ut veniam lorem ipsum Consectetur ut in in eu do.</p>

   </div> 
</div>

<div class="row contact-form">

   <div class="col-twelve">

    <form name="contactForm" id="contactForm" method="post" action="">
          <fieldset>

          <div class="form-field">
                    <input name="contactName" type="text" id="contactName" placeholder="Name" value="" minlength="2" required="">
          </div>
          <div class="form-field">
                 <input name="contactEmail" type="email" id="contactEmail" placeholder="Email" value="" required="">
           </div>
          <div class="form-field">
                    <input name="contactSubject" type="text" id="contactSubject" placeholder="Subject" value="">
           </div>                       
          <div class="form-field">
                 <textarea name="contactMessage" id="contactMessage" placeholder="message" rows="10" cols="50" required=""></textarea>
           </div>                      
         <div class="form-field">
             <button class="submitform">Soumettre</button>
             <div id="submit-loader">
                <div class="text-loader">Envoi en cours...</div>                             
                     <div class="s-loader">
                              <div class="bounce1"></div>
                              <div class="bounce2"></div>
                              <div class="bounce3"></div>
                        </div>
                    </div>
          </div>

          </fieldset>
      </form>

    <div id="message-warning">            	
    </div>            
      <div id="message-success">
       <i class="fa fa-check"></i>Votre message a été envoyé, merci !<br>
      </div>

 </div>
   
</div>

<div class="row contact-info">

   <div class="col-four tab-full">

       <div class="icon">
           <i class="icon-pin"></i>
       </div>

       <h5>Où me trouver</h5>

       <p>
    2 rue de l'esviere<br>
    49100 Angers
    </p>

   </div>

   <div class="col-four tab-full collapse">

       <div class="icon">
           <i class="icon-mail"></i>
       </div>

       <h5>Envoyez-moi un e-mail à</h5>

       <p>p.noorman.pro@gmail.com<br>			     
       </p>

   </div>

   <div class="col-four tab-full">

       <div class="icon">
           <i class="icon-phone"></i>
       </div>

       <h5>Appelle moi a</h5>

       <p>Tel: (+33) 767070426<br>
       </p>

   </div>
   
</div>

</section>
</template>