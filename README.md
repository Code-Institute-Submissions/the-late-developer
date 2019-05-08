README.md

The Monkees – Band Website

Milestone Project: User-Centric Frontend Development - Code Institute

The ‘band’s’ brief has told me that they want to reach both their old fans and potential new ones and provide a place where those people can hear clips from the back catalogue as well as promote new material as it becomes available.
As well as showcasing their music they want to be able to advertise their availability to perform at special events for their fans such as weddings and Christmas parties.
They would also like to build a social media presence and therefore provide links to their gradually developing Facebook, Twitter and You Tube platforms.
UX

My intention was to provide a simple, uncluttered single point of access for all things connected to the band.  As part of this approach and taking a mobile first view I decided that a single scrolling page with well defined sections would work better than multiple pages.  With the addition of both a top and bottom fixed navigation bar, the top one shrinking to a hamburger icon on smaller devices and the bottom one having simple icon links, would enable rapid movement through the site to areas of interest or jump to associated media.
I considered the needs of different users thus:

    •	As a long-time fan I want to be able to find out what the band are up to now and to hear about new performances or albums on a regular basis.
    •	As someone new to the band and wanting to find out more I want a single place to be able to listen to their music and see old clips from their TV series and performances.
    •	I want to have easy links to the band’s other social media platforms.
    •	As the band management I want to be able to build a database of fans to be able to promote the band’s gigs, new recordings and their older material.

I roughly sketched out by hand a view of how these sections might work, their order in the scroll and content that might be included. I then set about providing a shell for each section and adding content gradually, checking appearance and functionality at each stage.

Features

    •	A collapsing navigation bar takes up less room on smaller screens and enables fast navigation to the required section.
    •	A slideshow at the entry view provides immediate interest, enables the user to either know they are at the right place or encourage the uninitiated to look further.
    •	The head photos expand, upon focus, to reveal a brief detail of interest.
    •	There are embedded YouTube videos of both a significant song from their back-catalogue and a compilation of snippets from their TV show that gives a sense of the fun and good feeling that they conveyed, again encouraging new users to want to see more and provide nostalgia to old ones.
    •	The Spotify player is focussed on a Monkees playlist that plays short sections from a wide range of their music.
    •	The Live Dates section advertises their next performances with working links to the respective booking offices.
    •	There is a form with a subject dropdown to encourage both the building of a contact list and take enquiries for possible band engagements as well as ‘other’ enquiries or messages.
    •	The News section is there to showcase current activities and band related ones e.g. a spoof tribute act.

Features Left to Implement

    •	The Shop is currently pointing to Amazon pages but could be developed for new material including direct downloads with an eCommerce platform.

Technologies Used

1.	HTML5 for general structure
2.	CSS3 for styling
3.	Bootstrap (3.4.0) including their JS elements, for layout, slideshow and navigation.
4.	Font Awesome icons and Google Fonts have also been employed.

Testing

I have tested the site using multiple browsers (Chrome, Edge, Firefox, Opera, Safari) and all links and displays work and appear as expected, satisfying the requirements of the various users.  The site also performs well on multiple mobile devices (iPhone, 5, to X ;  Samsung Galaxy, Sony Xperia).
During the testing phase I realised that there was a problem in display at smaller resolutions that appeared to relate to the embedded YouTube players.  This was satisfactorily resolved with use of the embed-responsive and -item classes, within the iframe, from Bootstrap.
There is no back-end currently to accommodate the contact list information.

1.	All Navbar links jump to the correct section in the site, or open new tabs for external links.
2.	The Navbar reduces to a hamburger icon on smaller resolutions.
3.	Both header and footer navbars are fixed position.
4.	Head photos when clicked extend to reveal further information. Hover response highlights hidden action.
5.	All 3 embedded players work appropriately.
6.	Live Date ticket links open the appropriate booking office pages.
7.	The Contact Us form displays guide instructions and requires an email style address to be entered to be valid.
8.	The Amazon shop item links also work appropriately.

Scaling and operation also works appropriately on the different formats mentioned.
However, there is a display issue on the iPad yet to be satisfactorily addressed.

Deployment

Deployment is being made to GitHub.

Credits

Content

Although a technical educational exercise based around a real band and therefore using certain real content e.g. member details in the ‘Heads’ section obtained from Wikipedia, other content was created to fit the brief, slightly blurring reality and attempting to provide a little humour in places. 
    •	The information for the ‘heads’ section was gleaned from the Wikipedia articles for each band member linked from the main page found here.
    •	The solution for responsive embedding of YouTube videos was found at Codepen.

Media
    
    •	A number of photos were provided as part of the brief, with Pexels background stock image library being used for a background shot and Freepik for certain icons. For more authenticity due to the real subject, other Google search images were used e.g. ‘real’ band shots, some from Googles cache, where the original source pages no longer exist.

Links

    •	Again, for greater realism where possible, operating links to equivalent sites have been employed. 

Acknowledgements

The Bootstrap carousel and navbar were tweaked and utilised for the slideshow and both top and bottom navigation links.  
This is for non-profit educational use only and acknowledgement is made to the owners of any trademarks and copyrights etc.
