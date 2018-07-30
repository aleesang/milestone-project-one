<h1>THE PROJECT</h1>

<h2>WHAT IS IT?</h2>

Build a static (front-end only) website for a 1960's rock band called The Monkees. For the purposes of this project, I have chosen to build a website for an artist named Fiona Apple.

<h2>BRIEF</h2>

- Primary target audiences are the fans and potential fans who wish to use the site to see and hear clips from the back catalog, and any new material as it becomes available.
- Use the site to showcase the music and publicise availability to perform at events such as weddings and Christmas parties.
- The following assets to be showcased on the website:
    - Photos
    - A video clip
    - Audio clips
    - Links to Facebook, Twitter and YouTube pages etc.

<h2>PURPOSE OF WEBSITE</h2>

Based on the brief, the aim of the website (in both functionality and design) was produce a functional website that essentially showcasws Fiona Apppe's music to 
current and new fans. 

<h4> The initial stages </h4>

- researched Fiona Apple's social media, fan sites, and news articles to help me build a picture of the audience I was targeting, as well as help me create a "story" of what purpose her website would serve.
- mapped out what pages were needed.
- sketched ideas for a "one page" layout, and "multi-page" layout to get ideas of functionality and usability.
- draft up rough ideas of content that would appear and where.
- settled on final design.

After playing with different and potential ideas for the design, as well as taking into consideration the user experience of today's music fans, 
it was decided that the following would be implemented:

<h4>Page layout</h4> 

- The one page layout seemed to fit the solution of drawing in new fans, as well as catering to the current fan base by having content presented in a simple one page "summary" of
  who Fiona Apple is, in an easy and workable fashion for the user.
- This kind of layout is also suited for mobile users who are already used to a linear experience type of behaviour when scrolling through their phone.
- The design concept I was striving for was a visually compelling experience, to keep users wanting to see more with images and visuals dominating the design, rather than have to read through loads of content.
- I wanted to avoid users navigating to different pages as I wanted to hold their attention as much as possible on the main page they are viewing to promote engagement. Having said that, it was important to me also to not have too much written content on the page as I did not want to disrupt the flow of the "Visual" aspect that influences the design. For any "written content" heavy stuff, I decided to place into the Bootstrap Modal so the user could still view content in a popup, but it will still allow them to remain on the page they are viewing.

<h4>Colours and Fonts</h4>

- Colour scheme decided on was an earthy toned colour scheme of browns, dark colours with a pop of pastel for the headings and links. This was decided on, based on the
  artwork that she has used for her albums, the kinds of music video's she has made, and the photoshoots she has appeared in... all have a similar colour scheme, or at least
  mostly warm-dark toned colours. I wanted keep within this theme for the website.

- Fonts were also important and decided on a clean, minimalist style fonts. The headers and navigation bar has the same font, whereas the body and footer links and button font,
  have the same style applied.

<h4>Navigation</h4>

The navigation style I chose to use was a fixed navigation, due to the one page layout design. The fixed navigation allows for a user friendly experience on this site, as
there are 7 sections (pages).

<h4>Music and Videos accessible via "External Media" Accounts</h4> 

I chose to use embedded music and videos via spotify and youtube, respectively, as these are two of the main places that i've found that users listen to and view music the most. Most music lovers
would either use one or the other, so would be fitting to allow them to play music from Fiona via these platforms, which in turn would allow them to create a playlist of 
their own quite easily.

The other thing about using external sites to promote Fiona's music, is that her albums are actually available on viable platforms such as iTunes, and Amazon. I decided to place "Buy from..." buttons 
to promote users to those sites should they wish to download her music or buy them as those sites are easily accessible.

<h4>Promoting her Instagram</h4>

It should be noted that Fiona does not have a social media presence except for an official facebook page that is mostly run by fans. For the purposes of the project, I decided to "pretend"
she is active on Instagram (which is her official fan instagram account) and show fans or potential fans that if they want to connect with her and her life, that instagram would be the way to do it. I 
also decided to show a snippet of her pics that link to that pic on instagram, to make "following" her that much easier.

<h1>HOW IT WAS BUILT</h1>

- The main framework used to help build the website was Bootstrap V4.1. 
- Icons used were fron Font Awesome. 
- Fonts were Google Fonts.

<h4>Plugins</h4>

https://stackpath.bootstrapcdn.com/bootstrap/4.1.2/css/bootstrap.min.css
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css
https://code.jquery.com/jquery-3.3.1.slim.min.js
https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js
https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js

<h4>Resources</h4>

- https://getbootstrap.com/
- https://www.w3schools.com/
- https://stackoverflow.com/
- https://bootsnipp.com/ (for ideas on how the Photo gallery and Instagram layout could be coded)
- https://codepen.io/ (ideas on how to make my video responsive)
- slackbot Forums 

<h4>Code/Framework Used Per Section</h4>

<u>Navigation</u>
- Bootstrap Navbar

<u>About</u>
- Modal for the popup biography

<u>Music</u>
- Bootstrap Grid system
- Bootstrap Dropdown menu buttons

<u>Videos</u>
- Bootstrap Grid system

<u>Photo Gallery</u>
- Bootstrap Grid system and Modal for popup photos

<u>Tour</u>
- Bootstrap Grid system
- Bootstrap Modal Popup
- Bootstrap Form

<u>Follow</u>
- Bootstrap Grid system

<u>Footer</u>

- Bootstrap for layout. Modal for Privacy Policy. Font Awesome for Social Media icons.

* Font Awesome was used on all headers.
* Any code I may have referenced that was not taken from bootstrap or w3schools, I have noted accordingly on the HTML doc and CSS stylesheet.

<h1>HOW IT WAS TESTED</h1>

<h4>Summary</h4>

- During and throughout the build, this was tested on google chrome using devTools, and testing responsiveness using the device toolbar. 
- Also used the elements and style sections of the devTools to troubleshoot coding that seemed to affect my page layout when I couldn't quite work out what the issue was. My mentor reminded me of this tip.
- Also tested responsiveness by resizing the window everytime I implemented a new piece of code.
- AND also tested it physically viewing it on mobile, tablet, mac and windows laptop, windows desktop, and different browsers (firefox, safari, google chrome, opera)

<h4>What was tested</h4>

- External links (to her social media, to buy her album, spotify and youtube)
- Internal links (the navbar to ensure anchors were referenced to the right sections, and the link to right the modal popups)
- Forms for signup of newsletter and enquiry for event booking (if the required field was triggered when i clicked submit without an email address)
- Margins for the containers (page sections) as fixed navbar alters the margins slightly that when you click on the link to take you to an anchor point, the navbar covers the heading. Changed margins in css to accommodate correct anchor point.
- Checked button sizes so they were responsive and large enough to be clicked
- Checked images to ensure they were responsive and displayed appropriately on smaller screens
- Checked modal-dialog size in smaller screen to ensure it displayed properly.
- Ensuring header was resized when viewing on smaller screens (aka mobile) and amending padding-bottom to account for navbar covering half the image when viewing on a smaller screen.
- Ensuring content had no grammatical errors.
- Checked margins and padding of container (sections) to ensure the content within it didn't look disproportionate on smaller screens.
- Ensured the iframes were being responsive and displayed properly.
- HTML and CSS validation via w3.org. 

<h1>HOW IT WAS DEPLOYED</h1>

- Used GitHub Pages to deploy final version (https://aleesang.github.io/milestone-project-one)
- Tested the final published version in the same manner as I documented above in the How It was Tested section
- 








