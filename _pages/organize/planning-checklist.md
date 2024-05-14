---
title: Planning Checklist

---


Download the <a href="https://drive.google.com/drive/folders/1gXkvuQNRhfyOVv6XjmncFFUIK4m_yCTb">complete Step-by-Step Guide to Hosting a Mapathon</a>. 

<input type="checkbox"/> Decide if you'll do an in-person or remote event

<input type="checkbox"/> Choose a date

<input type="checkbox"/> Recruit volunteers to help plan the event

<input type="checkbox"/> Book a space

<input type="checkbox"/> Register your event <a href="/events" target="_blank">here</a>

<input type="checkbox"/> Make banners or posters using the <a href="https://drive.google.com/drive/folders/1y-PJ3MoHndFtm_Xcm_7qPMjtNYxbygCs" target="_blank">Missing Maps logo and/or the customizable community logo template</a>

<input type="checkbox"/> Recruit participants using Eventbrite or another ticketing tool

<input type="checkbox"/> Pick a task using the <a href="https://tasks.hotosm.org/" target="_blank">Tasking Manager</a> / or <a href="https://mapswipe.org" target="_blank">MapSwipe</a>

<input type="checkbox"/> Ensure strong Wi-Fi

<input type="checkbox"/> If using the <a href="https://tasks.hotosm.org/" target="_blank">Tasking Manger</a>, check that it passes your location's firewall

<input type="checkbox"/> Tables and chairs

<input type="checkbox"/> Projector & audio visual equipment

<input type="checkbox"/> Laptops for all participants if using the <a href="https://tasks.hotosm.org/" target="_blank">Tasking Manager</a> (tablets are not compatible with the Tasking Manger) or phones for each participant if using <a href="https://mapswipe.org" target="_blank">MapSwipe</a>

<input type="checkbox"/> Mice (if possible) for all participants (if using the <a href="https://tasks.hotosm.org/" target="_blank">Tasking Manager</a>)

<input type="checkbox"/> Make sure you have contact info for your event spaces tech and support staff

<input type="checkbox"/> Extra extension cords

<input type="checkbox"/> Print materials

<input type="checkbox"/> Order snacks

<input type="checkbox"/> Prepare training materials

<input type="checkbox"/> Remind participants to create their OSM profile and download a browser that is not Internet Explorer (if using the <a href="https://tasks.hotosm.org/" target="_blank">Tasking Manager</a>)

<input type="checkbox"/> If hosting remote event, test your video hosting platform including microphone and screenshare




{::nomarkdown}
{% assign subitems="" | split: ',' -%}
{% for link in page.links %}
  {% assign item=site.pages | find: "url", link.link %}
  {%- if item -%}
    {%- assign subitems=subitems | push: item -%}
  {%- endif %}
{% endfor %}
{% include item_list.html items=subitems %}
{:/nomarkdown}