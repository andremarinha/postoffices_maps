---
layout: default
title: Post office maps
description: Interactive maps of post offices in Portugal, Spain, Italy, and Greece, with methods and sources.
permalink: /
---

# Post office maps

These interactive maps support my thesis. Each page shows the post offices collected for a given country. See **Methods** and **Sources** below for notes on data collection and processing.

## Interactive maps
- 🇵🇹 **Portugal** — [Open map]({{ '/maps/portugal_postoffices_map.html' | relative_url }})
- 🇪🇸 **Spain** — [Open map]({{ '/maps/spain_postoffices_map.html' | relative_url }})
- 🇮🇹 **Italy** — [Open map]({{ '/maps/italy_postoffices_map.html' | relative_url }})
- 🇬🇷 **Greece** — [Open map]({{ '/maps/greece_postoffices_map.html' | relative_url }})

> Tip for citations/footnotes in the thesis: link the specific page, e.g.  
> `https://andremarinha.github.io/postoffices_maps/maps/portugal_postoffices_map.html`

## Methods (short)

**Collection.** <!-- Replace with your notes: e.g., official operator lists, public datasets, web scraping from postal websites, manual validation. -->  
**Processing.** <!-- Outline cleaning/deduping, geocoding, CRS used, and QA checks. -->  
**Visualization.** <!-- Library and choices: Leaflet/folium, marker styling, clustering, basemap provider. -->  
**Limitations.** <!-- Coverage gaps, update cadence, known biases or uncertainties. -->

## Sources

<details open>
<summary><strong>Basemap/tiles</strong></summary>
<p>© OpenStreetMap contributors — see <a href="https://www.openstreetmap.org/copyright">copyright &amp; attribution</a>.</p>
</details>

<details>
<summary><strong>Country datasets</strong></summary>
<ul>
  <li><strong>Portugal:</strong> <!-- Add source + URL --></li>
  <li><strong>Spain:</strong> <!-- Add source + URL --></li>
  <li><strong>Italy:</strong> <!-- Add source + URL --></li>
  <li><strong>Greece:</strong> <!-- Add source + URL --></li>
</ul>
</details>

## How to cite

> André Marinha ({{ 'now' | date: '%Y' }}). “Post office locations — &lt;country&gt; (interactive map).”  
> <code>{{ site.url }}{{ site.baseurl }}/maps/&lt;country&gt;_postoffices_map.html</code> (accessed {{ 'now' | date: '%Y-%m-%d' }}).

<small>Last updated: {{ 'now' | date: '%Y-%m-%d' }}</small>
