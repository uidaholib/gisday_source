---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
#credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: https://www.lib.uidaho.edu/media/gisday/FY22_771864077_MH11_0130.jpg
# set background-position for featured image, "center", "top", "bottom"
position: center
# major heading to display over featured image
heading: GIS Day @ U of I
# paragraph text below heading in featured image
sub-heading: November 18, 2026
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 6em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## GIS Day

<a href="https://www.gisday.com/">GIS Day</a> @ University of Idaho is a free event made possible by the U of I Library, with support from <a href="#sponsors">our sponsors</a>, that brings together scholars, students, professionals, businesses, and the public to discuss geospatial technologies and demonstrate their many uses. The sessions will take place on Wednesday, Nov 18th, 2026 as a hybrid event hosted in the Idaho Student Union Building and streaming live via Zoom.

Please contact Bruce Godfrey (<a href="mailto:bgodfrey@uidaho.edu">bgodfrey@uidaho.edu</a>) with any questions.

## Schedule of Events

GIS Day @ U of I 2026 is a hybrid event taking place on November 18th in <a href="https://maps.app.goo.gl/ytTF6JsPjV36MRbJ9">Idaho Student Union Building</a> and live streaming via Zoom. Times are given in Pacific Time (PST). Please <a href="#register">register to let us know how you are attending</a>.

GIS Day will feature invited speakers, panels, and short talk sessions spread across a morning (9am - 12pm) and afternoon (1pm - 3:30pm) session, with a catered lunch in between.

TBA!

## Registration 

To participate in GIS Day 2026, please register in advance to let us know if you will be attending in person or online. Visit the event registration link and fill in the form with your details. Information about how to join the sessions will be emailed to you a day before the event. Registration is free and open to all.

*Coming soon!*

## Sponsors

Each year a variety of entities generously provide support to help make this a successful event. The list recognizes our supporters.

<div class="row mx-md-4 my-4 text-center">
    {% assign sponsors = site.data.gisday_sponsors | where: "active",true %}
    {% for s in sponsors %}
    <div class="col-6 col-md-4 p-3 p-md-5">
        <a href="{{ s.link }}" title="{{ s.sponsor }}">
            <img src="{{ s.img | prepend: '/gisday/sponsors/' | prepend: site.lib-media }}" alt="{{ s.sponsor }}" class="img-fluid">
        </a>
    </div>
    {% endfor %}
</div>

## Planning Committee Members

<ul class="list-unstyled">
    <li>Josh Conver (Library, Washington State University)</li>
    <li>Bruce Godfrey - Chair (Library, University of Idaho)</li>
    <li>Lisa Jones (Plant Science, University of Idaho)</li>
    <li>Norman Lee (Library, University of Idaho)</li>
    <li>Felix Liao (Earth and Spatial Sciences, University of Idaho)</li>
    <li>Seth Thompson (Library, University of Idaho)</li>
    <li>Evan Peter Williamson (Library, University of Idaho)</li>
</ul>