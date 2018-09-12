# Final-Coursework-Egle-Zaleckiene

My website is for travelers mountain lovers, that are wondering  which destination to travel next.

You can browse inspiring travel destinations by continent (I didn't include Antarctica due to lack of popularity and high prices). 

If all destinations seems very attractive and you can't decide where to go next, you can use a randomizer. 

First of all you have to select the continent you want to visit and your activity interest (skiing, trekking, mountaineering). Then according to your choices written PHP algorithm randomly selects one travel destination.  

The purpose of my website is more to inspire, than to educate. User interface is very minimalist,  there is not much information provided. The main catch is a beautiful photo, that makes a person imagine himself in the surroundings.

So basically website consists of:

*navigation (icons only, appears on hover). No tool tips, names or descriptions, since I believe  icons themselves are very clear.

*continents page, where you can select a continent

*selected continent page with 5 highest mountains in a selected territory

*every mountain has their separate page with following information: elevation, country, link to a map and link to a wikipedia.

*randomizer. PHP code that generates random destination in array of your selected continent and interest. 

*contact form. Written PHP code. All entered data to form is stored to MySQL database.

Website was written using HTML, CSS and PHP languages. 



In the future I'd like to research mountain infrastructure more. Choose destinations regarding infrastructure development - not the elevation.  Due to lack of time I chose only highest mountains,but unfortunately  not all of them have well developed infrastructure for tourists. 


I also uploaded my webste to github pages, so you can easily check the responsiveness to smaller resolution devices, such as phones or a tablets -> https://1132049.github.io/inspiring-mountains/index.html.
Unfortunately github does not support php, so contact form and randomizer doesn't work.


Future improvements: I'd add searching field for better user experience, a blog, where experienced travellers could share their impressions and advices, also a  forum where people could  discuss. 


When uploading website to server I'd compress photos and code for faster browsing experience.
Some photos are already a little bit compressed, but I was afraid to worsen photo quality, since the majority of them are used to cover the backgoud and they must be in high resolution. 
So the challange is to find the balance between faster browsing and good photo quality.


