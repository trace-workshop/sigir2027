---
---

# Speakers & Panelists

Further keynote speakers and panelists will be announced. For the order of sessions, see the [Schedule]({{ site.baseurl }}/schedule).

{% include profile_list.html people=site.data.speakers %}

{% if site.edition.open_speaker_slots > 0 %}
<div class="container" style="margin-bottom: 30px;">
{% include profile_grid.html people=empty open_slots=site.edition.open_speaker_slots %}
</div>
{% endif %}
