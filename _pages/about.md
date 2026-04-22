---
layout: about
title: about
permalink: /
subtitle: "PhD Candidate in Economics, Brown University<br><a href='mailto:scott_lu@brown.edu'>scott_lu@brown.edu</a>"
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  # more_info: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a 4th year PhD candidate in economics at Brown University. My primary research examines the impact of urban regulation on housing supply and transportation. In addition, I am broadly interested in questions about applied econometrics, labor economics, and industrial organization.
 <!-- applying causal inference and applied econometric techniques to answer questions in urban and labor economics. -->

Previously, I worked as a Senior Research Assistant at the Federal Reserve Board in Washington, D.C., in the Trade and Quantitative Studies section.

My [CV](/cv/).

<div style="clear: both; margin-top: 2.5rem;"></div>

<h2>Working Papers</h2>
<div class="publications" style="margin-top: 1rem;">
{% bibliography --group_by none --query @*[key=lu2026drivingoutsupply]* %}
</div>

<h2>Work in Progress</h2>
<div class="publications" style="margin-top: 1rem;">
{% bibliography --group_by none --query @*[key=lu2026valueofvisaholders]* %}
</div>

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
