# Train Scheduler (Basic - Recommended)

    Overview:

    In this project, I am creating a train schedule application that incorporates Firebase to host arrival and departure  data. Your app will retrieve and manipulate this information with Moment.js. This website will provide up-to-date information about various trains, namely their arrival times and how many minutes remain until they arrive at their station.
    
    
## Instructions: 

1. Setup:

   * We'll leave that up to you -- however you like. Just make sure you're using Firebase to store data, GitHub to backup your project, and GitHub Pages to host your finished site.

2. Rules:

  * Make sure that your app suits this basic spec:
  
  * When adding trains, administrators should be able to submit the following:
    
    + Train Name
    + Destination 
    + First Train Time -- in military time
    + Frequency -- in minutes
  
  * Code this app to calculate when the next train will arrive; this should be relative to the current time.
  
  * Users from many different machines must be able to view same train times.
  
  * Styling and theme are completely up to you. Get Creative!

        #### Bonus:
        
        1.  Consider updating your "minutes to arrival" and "next train time" text once every minute. This is significantly more challenging; only attempt this if you've completed the actual activity and committed it somewhere on GitHub for safekeeping (and maybe create a second GitHub repo).
        2. Try adding `update` and `remove` buttons for each train. Let the user edit the row's elements-- allow them to change a train's Name, Destination and Arrival Time (and then, by relation, minutes to arrival).
        3. As a final challenge, make it so that only users who log into the site with their Google or GitHub accounts can use your site. You'll need to read up on Firebase authentication for this bonus exercise.


____________________
<sub> &copy; Paul Xu at Univerversity of Toronto School of Continuing Studies Coding Boot Camp in March 2019 </sub>
