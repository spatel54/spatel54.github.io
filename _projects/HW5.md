---
name: BigFoot Exploration Dataset
tools: [Python, HTML, vega-lite, altair]
image: assets/pngs/bigfoot.jpg
description: This notebook shows two different visualizations for the bigfoot dataset!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Example including vega-lite
```
<vegachart schema-url="{{ site.baseurl }}/assets/json/cars.json" style="width: 100%"></vegachart>
```

<vegachart schema-url="{{ site.baseurl }}/assets/json/bfro_reports_fall2022.json)" style="width: 100%"></vegachart>


## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

```
<div class="left">
{% include elements/button.html link="https://github.com/spatel54/spatel54.github.io/blob/725f63d7ebc40c615a8ff2f72891eef93d7db924/assets/json/bfro_reports_fall2022.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/spatel54/spatel54.github.io/blob/725f63d7ebc40c615a8ff2f72891eef93d7db924/python_notebooks/Workbook_1.ipynb" text="The Analysis" %}
</div>
```

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/spatel54/spatel54.github.io/blob/725f63d7ebc40c615a8ff2f72891eef93d7db924/assets/json/bfro_reports_fall2022.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/spatel54/spatel54.github.io/blob/725f63d7ebc40c615a8ff2f72891eef93d7db924/python_notebooks/Workbook_1.ipynb" text="The Analysis" %}
</div>

