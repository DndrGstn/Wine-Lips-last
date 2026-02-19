### Wine Lips Website Project Documentation
Project Overview

The Wine Lips website is designed to reflect the band's vibrant, energetic, and psychedelic style. The site is visually engaging while providing fans with easy access to information about the band, their music, merch, and tour dates.

Pages

Home Page – A visual introduction to the band, showcasing their happy, cool aesthetic.
<img width="1920" height="1032" alt="Screenshot 2025-12-10 010128" src="https://github.com/user-attachments/assets/6cd52353-258f-4f1b-880d-80ec4f258974" />

About Page – A section where fans can learn more about the band, their history, and their origins.

<img width="1920" height="1032" alt="Screenshot 2025-12-10 010151" src="https://github.com/user-attachments/assets/11fc261a-6a66-4d2d-8cc4-c8a531c87451" />

Merch Page – An online store for purchasing clothing, bags, vinyl, and albums. Links to Bandcamp for transactions.
<img width="1920" height="1032" alt="Screenshot 2025-12-10 010220" src="https://github.com/user-attachments/assets/31d9c721-d6e4-4e8c-b796-11bcc9f21a26" />

Tour Page – Lists upcoming tour dates and includes a signup form to receive updates about tours and album releases.
<img width="1920" height="1032" alt="Screenshot 2025-12-10 010253" src="https://github.com/user-attachments/assets/c69c94ed-2150-4abd-a387-19953f3a8cfe" />

### Design & Planning

I chose to design this website for Wine Lips because I love their energetic, psychedelic aesthetic and wanted to expand it into an engaging web experience. The site uses a retro, 70s-inspired visual style while remaining functional, simple, and user-friendly.

Goal: To create a website that allows visitors to:

Quickly learn about the band

Explore their music and merch

View tour dates

Sign up for updates

## Uses Stories
User Story 1 — New Visitor

As a first-time visitor,
I want to quickly understand who Wine Lips are and what they do,
so that I can decide whether to explore their music, merch, and tour dates.

User Story 2 — Returning Fan

As a returning fan,
I want fast access to the latest tour information and merch,
so that I can stay updated on upcoming shows and support the band.

### Wireframes

<img width="979" height="639" alt="wireframe" src="https://github.com/user-attachments/assets/816ed47b-6944-4bb7-8fcc-d0adf203fe5b" />

### Typography
Font: Arial

Reason: Clean, easily readable, and works well with the retro aesthetic.
### Colour Scheme
Vibrant, psychedelic colours to match the band’s style.

<img width="1868" height="326" alt="colour scheme" src="https://github.com/user-attachments/assets/9955d3ad-dc37-4048-94b4-a99f32e7fb44" />

## Features and Navigation

Navigation: Top bar with links to Home, About, Merch, and Tour.

Home Page: Introduces the band visually.

About Page: Provides background information about the band.

Merch Page: Links externally to Bandcamp for purchasing albums and merchandise.

Tour Page: Lists upcoming events and includes a signup form for newsletters and updates.

Responsive Design: Works across different devices and screen sizes.

Footer: Contains copyright and navigation links.

### Other features
I implemented a signup form that allows visitors to subscribe for updates from the band. By joining the mailing list, users can receive information about new tours, album releases, and other important announcements. This feature helps keep fans engaged and ensures they never miss out on upcoming events or new music.
## Technologies Used

List of technologies used for your project...
HTML

CSS

Bootstrap

GitHub (for deployment)

ChatGPT (assistance and guidance)

YouTube tutorials (for navbar and layout help)

## Testing
Browser Testing
Microsoft Edge
<img width="1920" height="1032" alt="Screenshot 2025-12-10 010151" src="https://github.com/user-attachments/assets/567cc36e-167d-4370-8b5d-2062b181f549" />

iPhone
<img width="946" height="2049" alt="image" src="https://github.com/user-attachments/assets/4c1a5936-e1c2-49a3-a160-d8f17ec4bd80" />

Firefox
<img width="1920" height="1032" alt="Firefox" src="https://github.com/user-attachments/assets/0afe9dce-a727-4d51-ad5a-2cbe620b6139" />


I ran into an issue where the navbar layout on the About Us page was breaking on mobile, even though it worked fine everywhere else. The problem turned out to be that this page was missing the following meta tag, which was included on all the other pages
"meta name="viewport" content="width=device-width, initial-scale=1.0"

<img width="433" height="782" alt="Screenshot 2025-12-09 181830" src="https://github.com/user-attachments/assets/7c1d9313-c289-4eff-9bbc-eada6e27b74f" />
<img width="436" height="774" alt="bug 1" src="https://github.com/user-attachments/assets/a23f04cf-79de-4b85-9412-1536e18e3c9a" />

Without it, mobile browsers render the page using a large desktop-sized viewport and then scale it down, which causes responsive elements—like the navbar—to behave incorrectly. After adding the tag, the navbar displayed properly on mobile and matched the layout of the other pages.

<img width="406" height="865" alt="about us" src="https://github.com/user-attachments/assets/18198a49-ead3-42ef-ad0a-d2c6b74a0cb5" />


### Google's Lighthouse Performance
<img width="1003" height="931" alt="Screenshot 2025-12-10 005911" src="https://github.com/user-attachments/assets/b6b62550-aab2-4c20-9016-33d5ffe8f4dc" />

### Browser Compatibility
works on
Microsoft edge
Firefox
Google Chrome
Safari Mobile

### Responsiveness
<img width="1247" height="772" alt="website" src="https://github.com/user-attachments/assets/495eb11b-91e8-4656-918b-482262a05552" />

### Code Validation

HTML: Validated successfully
<img width="1920" height="1032" alt="html valid 1" src="https://github.com/user-attachments/assets/26cc1800-7bb4-491f-9f57-e6c115715004" />
<img width="1920" height="1032" alt="html vali 2" src="https://github.com/user-attachments/assets/b3e57621-8088-4682-aa40-258b4a2b2435" />
<img width="1920" height="1032" alt="html valid 3" src="https://github.com/user-attachments/assets/e6d6e8d1-a5d4-4425-ae86-5600206493c3" />

CSS: Validated successfully
<img width="1920" height="1032" alt="css valid 1" src="https://github.com/user-attachments/assets/55947723-ee79-464c-8744-aa180485bd15" />
<img width="1920" height="1032" alt="css valid 2" src="https://github.com/user-attachments/assets/d369116c-1eaa-4944-9f75-25c79897ddd4" />
<img width="1920" height="1032" alt="css valid 3" src="https://github.com/user-attachments/assets/95ab781d-f0b5-4a98-8e80-09bd973b808d" />


## Bugs
Navbar resizing: Fixed by standardizing dimensions across pages.

Navbar item spacing: Fixed accidental extra space in HTML.

## Deployment

Hosted on GitHub Pages.

## Credits
Navbar tutorial:
 https://www.youtube.com/watch?v=f3uCSh6LIY0&t=314s

Background image: 
Stomp Records
https://stomprecords.com/bands/wine-lips/

About Us Section:
Stomp Records
https://stomprecords.com/bands/wine-lips/

Logo: Screenshot from a Wine Lips music video, edited in Photoshop
https://www.youtube.com/watch?v=ZPT11C8iU-w

Code positioning and layout help: Code Institute learning platform

Additional help: ChatGPT

## Deployment

To view or run this project locally:

1. Clone the repository:  
   git clone https://github.com/dndrgstn/MS1.git

2. Navigate into the project folder:  
   cd MS1

3. Open `index.html` in a browser to view the site locally.

The project is also deployed and live on GitHub Pages:  
https://dndrgstn.github.io/MS1/

 







 

