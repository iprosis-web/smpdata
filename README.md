# smpdata
Node JS Script based on puppeteer to retrieve tariff (price) data from the site of Israel Electric Company

To run locally: 
===============
 - clone repository, get into smpdata directory
 - run npm start (OR: node app).

It will inititate the server. Then in the browser:  
  localhost:9000/16-09-2020 to get data for 16 Sep 2020.

Output: JSON with time (every 30 min) and 2 tariffs: constraibed and unconstrained.


Interacticve sait where data is taken from: https://www.iec.co.il/businessclients/pages/smp.aspx?Date=16/09/2020 
(Note difference in time format)
