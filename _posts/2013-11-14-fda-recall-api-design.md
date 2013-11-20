---
layout: post
title: 'FDA Recall API Design'
url: http://publicprivatesector.org/news/2013/11/14/2fda-recall-api-design.md
image: https://s3.amazonaws.com/kinlane-productions/federal-government/fda/fda-recall.jpg
---

<a href="https://github.com/si-data/smithsonian-edan"><img src="https://s3.amazonaws.com/kinlane-productions/federal-government/fda/fda-recall.jpg" align="right" width="225" /></a>
<p>I was asked to provide <a href="http://fda-data.github.io/fda-recalls/index.html">advice on the design of an upcoming FDA Recall API</a>. I couldn't think of a better way than to comment on an existing API design that by creating a Swagger definition with any refinements. This provides an interactive, functional story about one possible direction the FDA could take their recall API design.</p>

<p>The existing FDA Recall API allows you to pull weekly recalls for 5 separate product types including Food, Drugs, Vetinarian, Devices and Biologics. Using the API you can pull each week listing of recalls as well as pull detail on individual recalls.</p>

<p>The recall API and data is not pretty, but it is functional and my suggestions were minor. First they should make sure and keep all endpoints underneath a /recalls/ endpoint, and consistency in how you pull by week and product type.</p>

<p>My main advice is to just get the API launched, let developers use it and provide them with a feedback loop in which they provide comments on what the next iteration should look like. Getting live and iterating with developers is the most important thing the FDA could do.</p>

<p>The API is in pre-production and isn't generally available, but you can play with through my proxied version deployed on Github. Until it breaks at least, then I will try to keep in line with whatever they launch.</p>

<p>If you have any feedback for the FDA, make sure and leave it as an <a href="https://github.com/fda-data/developer/issues">issue on this project</a> and I'm happy to relay to them.</p>

<p>You can download the <a href="http://api.fda.publicprivatesector.org/swagger/kinlane/recalls/recalls">FDA Recall API Design</a> or stay in tune via the <a href="https://github.com/fda-data/fda-recalls">Github Repo</a>. You can leave comments or issues there, or feel free to ping @kinlane.</p>
