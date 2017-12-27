---
layout: misc
title: Contact
---

<main class="container">
  <header class="page-header">
    <h1 class="entry-title">Contact</h1>
  </header>
    
    <div class="row">
      <div class="col-lg-6">
        <form role="form" action="https://formspree.io/ccardiff@dal.ca" method="POST">
          <input type="hidden" name="_next" value="//site.io/thanks.html" />
          <input type="hidden" name="_subject" value="Website query" />
          <input type="text" name="_gotcha" style="display:none" />

          <div class="form-group">
            <label for="InputName">Your Name</label>
            <input type="text" class="form-control" name="name" id="InputName" placeholder="Enter Name" required>
          </div>
          <div class="form-group">
            <label for="InputEmail">Your Email</label>

            <input type="email" class="form-control" id="InputEmail" name="_replyto" placeholder="Enter Email" required>
          </div>
          <div class="form-group">
            <label for="InputMessage">Message</label>

            <textarea name="InputMessage" id="InputMessage" class="form-control" rows="5" required></textarea>
          </div>
          
          <input type="submit" name="submit" id="submit" value="Submit" class="btn btn-info pull-right"> 
      </form>
    </div>
    <hr class="hidden-lg">
    <div class="col-lg-5 col-md-offset-1">
      <address>
        <p class="lead">Cassandra Cardiff<br>
        Oxford, Oxfordshire</a><br>
        Email: ccardiff@dal.ca</p>
    </address>
    </div>
  </div>
</main>
