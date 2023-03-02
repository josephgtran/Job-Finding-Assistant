# Job-Finding-Assistant
Website that inputs a users resume and matches them with a job.

DESCRIPTION:

This is a set of scripts that reads in a users resume in pdf file, and automatically matches them to a job.

   1)  User uploads resume and inputs desired job and location.
   2)  Two functions work in parralel;
         a) A resume parser - parses resume for "rare"  words and stores them in tempoary container. 
         b) From the inputed "Job" and "Location", sends a request to job site, and retrives the HTML code
              i) Retriver to get the HTML code
              ii) Parser to look for the "rare" words within the HTML file, if it finds one add 1 to 
                       The algortihm works by 
                           1 Parser - Look for specific HTML tags that the job description might be under, 
                             and is stored in a variable. WORK ON THIS!!!!
                           2 Another parsing process takes place, where the jobs with and the keywords are 
                             used to choose job description and store them somewhere.
                           3 It outputs the results.
    3) The script is hosted on. a.          
