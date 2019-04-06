---
title: "Plotter People #2"
date: 2019-03-13 18:30:00 -0800
date_label: Wednesday March 13, 2019<br/>6:30 - 9:00pm
venue: GitHub SF<br/>[88 Colin P Kelly Jr St,<br/>San Francisco, CA 94107](https://goo.gl/maps/fY73YaqfztR2)
eventbrite_id: 56689095611
categories: event-sf
---

{::options parse_block_html="true" /}

Plotter People is a meetup for creative coders and people interested in
collaborating with robots to make art. You'll get to talk to folks who make
generative art in a wide variety of programming languages and software
environments, and you'll get access to pen plotters and the people who make
them.

<div class="when-and-where">
<div class="when">
<h4>When</h4>
{{ page.date_label }}
</div>
<div class="where">
<h4>Where</h4>
{{ page.venue }}
<small>This venue is wheelchair-accessible.</small>
</div>
</div>

Plotter People is free to attend thanks to GitHub's generous donation of event
space, but please RSVP so we know how many people to expect!

{::options parse_block_html="false" /}

{% include eventbrite-button.html %}

{% include subscribe-form.html %}

<div class="squiggly">
	<h2>{{ page.title }}</h2>
</div>

{::options parse_block_html="true" /}

{:.section-header}
### Speakers

<div class="speaker">
<div class="speaker-description">
#### Chandler Abraham: 3D Rendering For Plotter Art

A common hurdle in the plotter art journey is the jump from 2D to 3D rendering. Luckily for us, plotters are an incredibly tangible and fun way to experiment with the fundamentals of computer graphics. This talk is a gentle introduction to the first principles of camera geometry and 3D rendering in the context of vector line art.

Chandler Abraham, aka [@cba](https://twitter.com/cba), is an ex-Twitter engineer, spends his days working on satellite imagery at Planet Labs.

</div>
<img src="{{ site.baseurl }}/assets/img/chandler.jpg" class="speaker-image" />
</div>


<div class="speaker">
<div class="speaker-description">
#### Geoffrey Bradway: From Monotone to Greyscale

Often when we plot we have access to one color at one pressure, and you might wonder how to broaden the range of your art to get a good light and dark tones. This talk is intended to be a guide to doing exactly that and we are going to talk about the theory behind halftones, techniques people use (stippling, hatching, dithering), algorithms you can use to plot, and some examples that showcase this.

Geoffrey Bradway, aka [@marchingcubes](https://instagram.com/marchingcubes), will also be showing what the finished piece looks like in the Plotter People gallery!

</div>
<img src="{{ site.baseurl }}/assets/img/geoffrey.jpg" class="speaker-image" />
</div>

{:.section-header}
### Schedule

| 6:30pm | Arrive at {{ page.venue }}.<br/>Make some new friends! |
| 7:00pm | **Chandler**<br/>3D Rendering For Plotter Art |
| 7:30pm | **Geoffrey**<br/>From Monotone to Greyscale |
| 8:00pm | **Gallery + Food**<br/>Grab a bite to eat, check out what folks are working on, and ask them questions! We'll have plotters running---you might even get to plot your own SVGs! |
| 9:00pm | Head home with a belly full of food and a head full of ideas! |

{% include eventbrite-button.html %}

{:.section-header}
### Code of Conduct

All attendees, speakers, sponsors, volunteers and organizers are required to
abide by the [Plotter People Code of Conduct][coc].

[coc]: /conduct.html

<script src="https://www.eventbrite.com/static/widgets/eb_widgets.js"></script>
<script type="text/javascript">
(window.rsvpIds || []).forEach(function (id) {
	window.EBWidgets.createWidget({
		widgetType: 'checkout',
		eventId: '{{ page.eventbrite_id }}',
		modal: true,
		modalTriggerElementId: id,
		onOrderComplete: function() {},
	})
})
</script>
