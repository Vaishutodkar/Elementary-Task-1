# Elementary-Task-1
<!doctype html>
<html>
    <head>
        <title> html page with materilizer </title>
        <script src="https://kit.fontawesome.com/f70cad7984.js" crossorigin="anonymous"></script>
 
        <!----------google---icons--link------>

        <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
      
        <link rel="stylesheet" type="text/css" href="materialize.css"/>
 
        <style>
            header{
            background: url("https://cdn.pixabay.com/photo/2014/05/05/19/53/keyboard-338505__340.jpg");
            background-size: cover;
            background-position: center;
            min-height: 1000px;
            font-size: 5px !important;
            }
            .section{
            padding-top: 5vw;
            padding-bottom: 4vw;
            }
           .tabs .indicator{
            background-color: #1a237e;
            } 
            .tabs .tab a:focus, .tabs .tab a:focus.active{
            background: transparent;
            } 

           @media screen and (max-width: 670px){
           header{
           min-height: 300px;
           }
           .brand-logo{
            font-size: 26px !important;
           }
           }
          .sidenav li{
           background-color: #fff;
           background-size: cover;
           font-size: 26px !important;
           }
           .sidenav{
           background: url("https://cdn.pixabay.com/photo/2017/08/07/01/41/camera-2598507__340.jpg");
           background-size: cover;
           font-size: 26px !important;
           }
      </style>
  </head>
  <body>

         <!-----nav bar----->
    
       <header>
            <nav class="nav-wrapper transparent opacity-3
                <div class="container">
                    <a href="" class="brand-logo indigo-text">Ace Photography</a>
                    <a href="#" data-target="nav-mobile" class="sidenav-trigger indigo-text"><i class="material-icons">menu</i></a>
                    <ul class="right hide-on-med-and-down">
                        <li><a href="#Photos" >Photos</a></li>
                        <li><a href="#Services" >Services</a></li>
                        <li><a href="#Contacts" >Contacts</a></li>
                        <li><a href="#" class="tooltipped btn-floating btn-small indigo darken-4" data-tooltip="This is twitter">
                        <i class="fab fa-twitter"></i>
                        </a></li>
                        <li><a href="#" class="tooltipped btn-floating btn-small indigo darken-4" data-tooltip="This is instagram">
                        <i class="fab fa-instagram"></i>
                        </a></li>
                        <li><a href="#" class="tooltipped btn-floating btn-small indigo darken-4" data-tooltip="This is facebook">
                        <i class="fab fa-facebook"></i>
                        </a></li>
                  </ul>
                  <ul id="nav-mobile" class="sidenav white" >
                        <li><a href="#Photos" >Photos</a></li>
                        <li><a href="#Services" >Services</a></li>
                        <li><a href="#Contacts" >Contacts</a></li>
                  </ul>
              </div>
         </nav>
     </header>

      <!-----grid images------>
      
        <section class="container section scrollspy" id="Photos">
            <div class="row">
                <div class="col s12 l4 offset-l1">
                    <h2 class="indigo-text text-darken-3 "> Nature</h2>
               </div>
                <div class="col s12 l4">
                   <img src="https://images.unsplash.com/photo-1420593248178-d88870618ca0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80.jpg" 
                   alt="no image" class="responsive-img materialboxed">
               </div>
               <div class="row">
                    <div class="col s12 l4 pull-l5 right-align offset-l1">
                        <h2 class="indigo-text text-darken-3"> Portraits</h2>
                  </div>
                  <div class="col s12 l4 push-l7 offset-l1">
                        <img src="https://images.unsplash.com/photo-1558507652-2d9626c4e67a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1000&q=80.jpg" 
                        alt="no image" class="tooltipped responsive-img materialboxed" data-tooltip="click on me to view full image">
                  </div>
                  <div class="row">
                        <div class="col s12 l4 offset-l">
                            <h2 class="indigo-text text-darken-3"> Cityscape</h2>
                      </div>
                      <div class="col s12 l4">
                            <img src="https://images.unsplash.com/photo-1480714378408-67cf0d13bc1b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80.jpg" 
                            alt="no image" class="responsive-img materialboxed">
                      </div>
                   </div>
              </div>
           </div>   
        </section> 
 
        <!--------------parallax----------->
        <div class="container row">
           <div class="col s12 l4">
                <h3 class="indigo-text text-darken-4">What we do..</h3>
                <p >
                    “We tend to love the things that are most scarce. 
                    The less there is of something, the more we value it.
                    But far too often, we didn’t realize it’s value until it was gone. 
                    One day our babies outgrew the constraints of infancy.
                    They learned to crawl and then pulled themselves up by whatever they could.
                    They mastered our language or their version of it! And now they think they’re going to keep growing right up! 
                    But not before we document them as toddlers. 
                    So that you’ll have photographs that make all those overwhelming feelings of motherhood and fatherhood come rushing back.”
                </p>
                <p >
                    “My favorite thing to photograph? 
                    Toddlers, without a doubt. 
                    Because they hold nothing back. 
                    Just watch how they explore the world. 
                    Their imaginations soar. And they don’t fake their emotions. 
                    My littlest guy is a toddler. I’m always racing to grab my camera because he’s almost not a toddler anymore. 
                    I can’t wait to see him grow up, but I’m going to miss the toddler him.”
                </p>
          </div>
      </div>
      <div class="parallax-container">
            <div class="parallax">
                <img src="https://cdn.pixabay.com/photo/2017/05/01/20/20/graduation-2276495_640.jpg" 
                alt="no image available" class="responsive-img">
            </div>
       </div>

       <!-----------services/tabs----------->
        <section class="container section scrollspy" id="Services">
            <div class="row">
                <div class="col s12 l6 offset-2">
                    <ul class="tabs">
                        <li class="tab col s6">
                            <a href="#photography" class="indigo-text text-darken-4">Photography</a>
                      </li>
                      <li class="tab col s6">
                            <a href="#editing" class="indigo-text text-darken-4">Editing</a>
                      </li>
                   </ul>
                   <div class="col s12" id="photography">
                        <p class="flowctext indigo-text text-darken-4">PHOTOGRAPHY</p>
                        <p >
                        “Taking pictures is savoring life intensely, every hundredth of a second.”
                        </p>
                        <p >
                            I photograph the toddler years,
                            because they’re some of the most wonderful times of development in your little one’s life.
                            They’re also the years that go by the quickest.
                        </p>
                  </div>
                  <div class="col s12" id="editing">
                        <p class="flowctext indigo-text text-darken-4">EDITING</p>
                        <p >
                            The process of editing is what I enjoy most - putting the pieces together and making sense out of them.
                       </p>
                       <p >
                        To receive footage that has been shot with editing in mind, it is a blessing.
                        </p>
                  </div>
               </div>
            </div>
        </section>

        <!-------------parallax-2----------->
     
        <div class="parallax-container">
            <div class="parallax">
                <img src="https://images.pexels.com/photos/265722/pexels-photo-265722.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260.jpg" 
                alt="no image available" class="responsive-img">
           </div>
       </div>    
       <!---------contact info------------>
    
       <section class="section container scrollspy" id="Contacts">
            <div class="row">
                <div class="col s12 l5">
                    <h3 class="indigo-text text-darken-4">Get in touch</h3>
                    <p >
                        "One mistake I often see is not being very clear where the photographer is based out of. 
                        And also photogs need to make it super easy to get in touch 
                        And provide quality content worth sticking around for."
                    </p>
                </div>
                <div class="col s12 l5 offset-2">
                    <form action="#">
                        <div class="input-field">
                            <i class="material-icons prefix">email</i>
                            <input type="email" id="email">
                            <label for="email">Your Email</label>
                       </div>
                        <div class="input-field">
                            <i class="material-icons prefix">message</i>
                            <textarea class="materialize-textarea" id="message"></textarea>
                            <label for="message">Your Message</label>
                       </div>
                       <div class="input-field">
                            <input type="text" id="date" class="datepicker">
                            <label for="date">Click to Choose a date you need me for ...</label>
                       </div>
                       <div class="input-field">
                            <p>Services required </p>
                            <p>
                                <label>
                                    <input type="checkbox">
                                    <span>Photography</span>
                                </label>
                           </p>
                           <p>
                                <label>
                                    <input type="checkbox">
                                    <span>Editing</span>
                                </label>
                            </p>
                       </div>
                       <div class="input-field center">
                            <button class="btn indigo darken-4">Submit</button>
                      </div>
                   </form>    
               </div>
           </div>
       </section> 
 
      <!------------footer------------->
      
        <footer class="page-footer grey darken-3">
            <div class="container">
                <div class="row">
                    <div class="col s12 l6">
                        <h5>About us</h5>
                        <p >
                            
                        </p>
                   </div>
                   <div class="col s12 l4 offset-2">
                        <h5> Connect</h5>
                        <ul>
                            <li><a href="#" class="grey-text text-lighten-3">
                                <i class="fa fa-facebook-square"></i>
                                Facebook</a>
                            </li>
                            <li><a href="#" class="grey-text text-lighten-3">
                                <i class="fa fa-instagram"></i>
                                Instagram</a>
                            </li>
                            <li><a href="#" class="grey-text text-lighten-3">
                                <i class="fa fa-twitter"></i>
                                Twitter</a>
                            </li>
                            <li><a href="#" class="grey-text text-lighten-3">
                                <i class="fa fa-whatsapp"></i>
                                Whatsapp</a>
                            </li>
                       </ul>
                   </div>
               </div>
           </div>
           <div class="footer-copyright grey darken-4">
                <div class="container center-align">&copy;2019 Ace photography</div>
            </div>
       </footer>  
      
        <!-----javascript code----->
        
        <script src="jquery-3.4.1.slim.js"></script>

        <script src="  https://code.jquery.com/jquery-3.4.1.min.js"></script>

        <script src="materialize.js"></script>
  
        <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
      
        <!--------initilizers--------->

        <script> 
            $(document).ready(function(){
            $(".sidenav").sidenav();
            $(".materialboxed").materialbox();
            $(".parallax").parallax();
            $(".tabs").tabs();
            $(".datepicker").datepicker({
            disableWeekends: true
            });
            $(".tooltipped").tooltip();
            $(".scrollspy").scrollSpy();
            });
       </script>
   </body>
</html>
