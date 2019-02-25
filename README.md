
# Milestone Project One 

## Band Project

I created a website for the Hamburg Caledonian Pipes and Drums (HCPD) detailing their upcoming 
events, their history, how to contact them and a smaller subgroup with the band - µHCPD. µ for micro
as in micrograms (µg).The µ's are the band members who play the small pipes, and usually another instrument as well.

The HCPD are an actual band, please bear this in mind 
when carrying out any testing, especially regarding contact details.
 
The [project brief](https://courses.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/c75714c9636b4cf59120d60acbec6ffd/f851a16813f14b3aae7bd1e6560443cd/) required the following items.

* Photos of the band members
* A video clip
* Audio clips


### UX

The underlying premise of the project brief was the commercial imperative to develop the brand, 
this guiding principle has driven the design phase.

Strategically the vision was simple. The primary audience were fans and the primary objectives to
showcase the band's music, publicise upcoming events and increase bookings. As a secondary goal
the website should support the ongoing drive to build the fan community, both on social media and
via the emailed newsletter.

In turn this developed the following requirements and scope.

1. Visitors can:
    1. book the HCPD.
    2. view the schedule.
    3. access social media.
    4. sign up for the newsletter. 
    5. read about the band.
    6. listen to music*.
    7. watch video*.  
                                                
2. The site owner can:
    1. increase bookings
    2. promote concerts
    3. increase social media presence

To meet these requirements the following elements were developed:

* Booking form
* Contact and Social Media links
* Band schedule
* Band History
 

As a fan I can book the HCPD via `kontakt.html`

As a fan I can book the HCPD via the contact form on `index.html`

As a fan I can book the HCPD via the contact email or phone number in the `footer`

As a fan I can view the HCPD's schedule via `termine.html`

As a fan I can access or discover the HCPD's social media presence via the `footer`

As a fan I can sign up for the newsletter in the `footer`

As a fan I can learn more about the band in `Geschichte.html` or `smallpipes.html`
                                            
As a fan I can access or discover the HCPD's social media presence via the `footer`

As a fan I can hear music and see video via `smallpipes.html`*

---
\*   Practical Considerations

Audio and video files would obviously support the objective of this website and so benefit the band, however
the desired audio and video footage  of the HCPD are not currently available due to technical constraints 
regarding recording quality. An audio recording 
and a YouTube clip were included as examples.     
---

Given the four or five page brief the structure is necessarily simple. A flat structure with a collapsible 
top navigation bar provides efficient and intuitive navigation.

[Wire frames](https://s3.eu-central-1.amazonaws.com/petes-gp-bucket/HCPDupdate.bmpr) were created before coding and it was apparent that features such as breadcrumbs
and a search facility would be increasing complexity but not usability.

The colour palette for the website was developed primarily from the HCPD's Ancient Caledonian tartan, with 
additional elements chosen to reflect the Scottish connection of the band, for example the use of the same shade of
blue as the Scottish Saltire.

### Features

**Existing Features**

Home page

* providing an eyecatching opening page with multiple options to access the key areas - contact, schedule and booking - as well as social media links and newsletter sign up.

Schedule page

* The band's performance schedule.

History page

* A bilingual history of the band.

µhcpd page

* An introduction to the small pipes group of the band with video and audio.

Contact page

* The primary access route to the band for bookings and other queries with secondary links to social media.


**Future Implementations**

Obviously the band schedule displayed on `termine.html` should be dynamically updated from a database to remain 
useful to both user and owner however this was explicitly excluded by the brief.

There are links to YouTube and Twitter included in the social media bar at the foot of each page, this is for 
completeness and compliance with the brief, so far the HCPD have not implemented accounts with either service.

The contact form should be connected up but at the time I made the website I had not started the modules covering the required techniques. 

### Technologies Used

HTML5, CSS3 & SCSS

+ These languages were used to create the website with SCSS being a mid project upgrade.

[Bootstrap](https://getbootstrap.com/docs/3.3/)

* Bootstrap 3.3.7 was used to create a responsive framework

### Testing

The website has been tested on Mac and Windows laptops, an android tablet, an iPad, an android phone and an iPhone
using a mixture of Chrome, Firefox, Edge and Safari.

### Deployment

### Credits

**Content**

The text was, in the main, taken directly from the HCPD's current website. I did a 
certain level of editing on the text and in places made slight amendments to current the English translations.

**Media**

All the pictures used on this project were supplied by the HCPD's.

The small pipes video clip and the 'Flower of Scotland' recording used on used on the µHCPD's page, `smallpipes.html`, 
were both externally sourced. Mike Katz's small pipes performance from YouTube and 'Flower of Scotland' a recording
from my personal collection.

**Acknowledgements**

`http://blog.theodo.fr/2018/01/responsive-iframes-css-trick/` provided the solution for making the YouTube clip 
responsive by making me aware of Bootstrap's `.embed-responsive` class.

[Ghost CSS](http://wernull.com/2013/04/debug-ghost-css-elements-causing-unwanted-scrolling/) was very useful in 
finding the source of a couple of scrolling problems.