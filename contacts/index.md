---
layout: page
title: Contacts
tags: [contacts]
modified: 2015-05-015T11:00:00.000000+01:00
comments: true
locations: M14 5RZ
image:
  feature: banner.png
---

* Email: secretary@greygarth.org.uk
* Postal address: Greygath Club, 1, Lower Park Road, Manchester, M14 5RS
* Phone: 0161 2242582

<img src="http://maps.googleapis.com/maps/api/staticmap?{% for location in page.locations %}{% if forloop.first %}center={{location}}&markers=color:blue%7C{{location}}{% else %}&markers=color:blue%7C{{location}}{% endif %}{% endfor %}&zoom={% if page.zoom %}{{page.zoom}}{% else %}13{% endif %}&size=300x200&scale=2&sensor=false&visual_refresh=true" alt="">
