---
layout: about
title: about
permalink: /
subtitle: 
# <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: IMG_1744.JPG
  image_circular: false # crops the image to make it circular
  more_info: 


selected_papers: 
  enabled: true # includes a list of papers marked as "selected={true}"
  # limit: 3 # leave blank to include all the news in the `_news` folder

social: true # includes social icons at the bottom of the page

# announcements:
#   enabled: true # includes a list of news items
#   scrollable: true # adds a vertical scroll bar if there are more than 3 news items
#   limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
#   enabled: true
#   scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#   limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. candidate at UC Berkeley advised by Prof. Kenichi Soga.
		 Prior to this, I obtained my master degree from Tsinghua University and bachelor degree from North China Electric Power University (Beijing). My research direction lies in traffic control, optimization and simulation. I did project on vehicle 
		ridesharing algorithm, fire evacuation algorithm and micro traffic simulation previously. I explore how	to use reinforcement learning to optimize the vehicle' s movement recently. 

<!-- Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically. -->
<!-- 
Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->

<div id="reviewer-map" style="height:320px;max-width:100%;margin-top:1rem;"></div>

<script>
  (function() {
    const lat = 37.8715;
    const lng = -122.2730;
    const popupText = "UC Berkeley";

    const map = L.map('reviewer-map', { scrollWheelZoom: false }).setView([lat, lng], 12);
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      attribution: '&copy; OpenStreetMap contributors'
    }).addTo(map);

    L.marker([lat, lng]).addTo(map).bindPopup(popupText).openPopup();
  })();
</script>