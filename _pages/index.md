---
title: "Reference System Python"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/sentinel/South_Georgia_Island_as_seen_by_Sentinel-2.jpg
  actions:
    - label: "Download"
      url: "https://github.com/RS-PYTHON"
  caption: "South Georgia Island as seen by Sentinel-2"
excerpt: "Reference System Python implement and maintain a new version of the RS Software compatible with the new Python-based processors, taking advantage of existing Python libraries (in particular Prefect) and novel tools to maximise the flexibility and simplify the maintainability of the solution."


intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."


feature_catalog:
  - image_path: /assets/images/architecture/stac.jpg
    alt: "RS-Server Catalog"
    title: "RS-Server Catalog"
    excerpt: "RS-Server provides a Catalog compliant with the SpatioTemporal Asset Catalog (STAC) format. "
    url: "#stac-article"
    btn_label: "Read More"
    btn_class: "btn--primary"


feature_staging:
  - image_path: /assets/images/architecture/external.jpg
    alt: "RS-Server external data sources"
    title: "RS-Server staging"
    excerpt: 'RS-Server provides staging functionality to retrieves product from ADGS, CADIP, PRIP and LTA stations'
    url: "#staging-article"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_catalog" type="left" %}
RS-Server implements the STAC API specification adding an access control per Collection and per User.
``` javascript 
 {
    "stac_version": "1.0.0",
    "type": "Collection",
    "license": "ISC",
    "id": "20201211_223832_CS2",
    "description": "A simple collection example",
    "links": [],
    "extent": {},
    "summaries": {}
}
```

{% include feature_row id="feature_staging" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

