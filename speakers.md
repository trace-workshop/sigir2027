---
---

# Speakers & Panelists

Speakers are listed in alphabetical order by last name. For the actual order and sessions, please see the [Schedule]({{ site.baseurl }}/schedule) tab.

{% include profile_list.html people=site.data.speakers %}

{% if site.edition.open_speaker_slots > 0 %}
<div class="container" style="margin-bottom: 30px;">
{% include profile_grid.html people=empty open_slots=site.edition.open_speaker_slots %}
</div>
{% endif %}
