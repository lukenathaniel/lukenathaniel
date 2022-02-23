---
layout: project
title: John Deere
subtitle: ActiveCal™ - Embedded Display Feature for Field Calibration
thumbnail: portfolio-1.jpg
logofilename: jd-logo.jpg
---
# ActiveCal™ - Recalibrating User Expectations for Accuracy
![image-title-here](/img/portfolio-1-A.jpg){:class="img-responsive"}
<small class="text-muted">Photo © Copyright Deere, Inc.</small>

<!--### Background-->

<div class="lead">The most important part of the crop cycle is putting seed in the ground. John Deere aims to give growers more accuracy and confidence in their seeding rates with new on-the-go calibration feature, ActiveCal™. <br /><br /><strong>Our challenge: transform a tedious but critical setup procedure into an easy-to-use touch display feature that can be used while seeding.</strong></div>



<div class="myrole">
<h4 class="mycontributions">My contributions to this project:</h4>
<div>
<table class="table table-condensed">
<thead>
<tr>
<th class="hidden-xs">Task</th>
<th style="width:40%;">Activities</th>
<th style="width:40%;">Collaborators</th>
</tr>
</thead>
<tbody>
<tr>
<td class="hidden-xs">User Research</td>
<td>Focus groups (North Dakota, Montana), contextual inquiry, problem definition (user stories, project brief)</td>
<td>Product Manager, System Engineers, Product Owner, Product Support Specialists, Territory Sales Manager, Product Planner</td>
</tr>
<tr>
<td class="hidden-xs">Interaction Design</td>
<td>Context scenarios, wire frames (Balsamiq, Powerpoint,) wire flow diagram (Adobe Illustrator,) dynamic prototyping (Axure RP)</td>
<td>Product Manager, Interaction Designer, Product Owner, System Engineer</td>
</tr>
</tbody>
</table>
</div>
</div>



## Discovery
------

Before we could design this solution, we needed to understand the problem:

- Why does an air cart operator need to calibrate their air cart in the first place?
- What challenges exist with how they do this today?

When we kicked off this project, very little context was provided aside from the legacy display screens for the manual meter calibration procedure, whose interface was described by Deere as "hard to use:"

![image-title-here](/img/portfolio-1-E.jpg){:class="img-responsive"}

I wanted to unpack the business case a bit more, but as a supplier to Deere we didn't have direct ad hoc access to customers to conduct research interviews yet, so instead I browsed some topic-specific forums looking for *stories in the wild*. A few keyword searches yielded a wealth of insightful anecdotes related to this meter calibration:

<blockquote>
<p>"When I first got my drill, I had accidentally entered something wrong on the [display] setup, I went through calibration for fertilizer and seed, then seeded about 1/2 acre. Then I found out that I was dropping double rate on the seed and half rate on the fertilizer.</p>
<small>AgTalk Forum User</small>
</blockquote>

<blockquote>
<p>"I'm guessing we could cheat and tell the monitor to apply 112 lb/ac (knowing that its over-applying 7-10%) so that we can get an actual 120 lb/ac. But surely there's a way to get it to apply what the monitor is saying it is, isn't there?"</p>
<small>AgTalk Forum User</small>
</blockquote>


<!--
> "...if you fill the tank, and right away do a calibration, the seed isn't as dense as it will be once you've sown for a round or two. **I've quite often seen calibration factors change an easy 10% because of this.**"

  > "Did you calibrate using the [default value] or did you use the display? Using the display calibration always put [too much] of everything on."
-->
I supplemented that by looking at Deere product literature and dealer websites, and synthesizing that into a problem statement:

<div class="row well">
<div class="col-sm-7">
<p><strong>Need:</strong> Air cart operators need to apply product at the rates they enter in the display. Too little seed costs them yield, and too much fertilizer kills the crop.</p>
<p><strong>Challenge:</strong> Differences in shape, density, particle size consistency and moisture content all impact how much product is displaced with each turn of the meter.</p>
<p><strong>Resolution:</strong> For this reason, operators must recalibrate their meters every time they refill their commodity tanks, and then manually verify their rate by metering out commodity into a bag, weighing it, and comparing to the expected value.</p>
</div>
<div class="col-sm-5">
<img src="/img/portfolio-1-H.jpg" class="img-responsive img-thumbnail" /><small class="text-muted">Photo © Copyright Deere, Inc.</small>
</div>
</div>

Once I had a better grasp of the problem domain and knew what kind of questions ask, I conducted 1-on-1 *stakeholder interviews* with the Deere team. My goal was to understand from a product marketing and support perspective how they were managing customer expectations for this procedure:

![image-title-here](/img/portfolio-1-I.jpg){:class="img-responsive img-thumbnail"}

#### IN THE FIELD

Conversations with Deere's test engineers provided an opportunity for some *contextual inquiry*, getting us out of the office and into the cab for ride-alongs at test sites where we could not only talk about the calibration but actually try doing it ourselves:

 ![image-title-here](/img/portfolio-1-C.jpg){:class="img-responsive img-thumbnail"}

As I learned more about setting up air carts, I began to sketch out a customer narrative for the manual version of this calibration procedure:

 ![image-title-here](/img/portfolio-1-F.jpg){:class="img-responsive img-thumbnail"}

 My storyboard blew up fairly quickly, as quickly identified no fewer than 17 individual steps in the manual version of this calibration.

<figure>
<img src="/img/portfolio-1-N.jpg" class="img-responsive img-thumbnail" />
<figcaption>With a tow-between setup like this pictures here, an operator has to walk about a hundred feet from the tractor to the cart, and then back - 3 times. </figcaption>
</figure>

#### LISTENING TO CUSTOMERS

We also made this topic part of our agenda at a *customer focus group* in North Dakota, using the *critical incident* questions to direct conversations towards actual events. We visited with 10 experienced growers that day, and heard in their own words some of the frustrations they encountered with the existing touch displays:

<div class="row">
<div class="col-sm-5"><img src="/img/portfolio-1-D.jpg" class="img-responsive img-thumbnail" /></div>
<div class="col-sm-7"><br /><blockquote><p>"We've had days where we can't get it calibrated, and they'll sit out there and fight that all day and not get ANYTHING done...It'd be nice to have it where you punched that (calibration value) in, and you could just trust that."</p></blockquote></div>
</div>
<br />From the secondary research, stakeholder interviews and customer focus group feedback, we had a clearer picture of the human narrative this feature would be a small part of.

#### PATTERN ANALYSIS

To get a feel for some appropriate patterns, studied *competitive products* in the market, analyzing them at a "boxes-and-arrows" level of abstraction.

![image-title-here](/img/portfolio-1-G.jpg){:class="img-responsive"}

<!--<ul>
  <li>How are their screens the same or different?</li>
  <li>What terminology is proprietary vs. just lingo?</li>
  <li>What UI heuristics do they fail to hit?</li>
  <li>What mental models do they set up?</li>
  <li>What are the system inputs and outputs?</li>
  <li>How much "guidance" do the designs include?</li>
</ul>-->
<!--
It was clear that the few in-field air cart calibration products out there shared the same general theory of operation:

-  Air carts use a **calibration value** that tells the meters how much product to dispense per unit distance in order to achieve a certain rate of application.
- This calibration value can be entered by the operator, or calculated automatically based on a mass of seed dispensed over a known distance.
- The systems' tank scales compare the tank weights before and after seeding a known distance, producing a % difference and allowing the operator to make a judgement about accuracy.
- If they like what they see, they can update their calibration factor immediately.
- If they're not confident in it, they can just continue seeding and gather more data.

At an abstract level, we confirmed the Deere air cart was wired up to work more or less by the same principles.

We also knew that we didn't want to make this like other calibrations or setup features, buried in a menu and tucked out of the way behind 3 or 4 screen taps. **This would heavily inform our approach to ActiveCal as more of a performance optimization feature than a setup procedure.**
-->
---

## Synthesis
------
Deere's product manager, an experienced farmer himself and former service technician, shared with me his vision for ActiveCal as a "switch" operators would just turn on as they worked:

<blockquote><p>"So you'll stop the cart, take a picture of the scale readings, and then you'll go seed a few passes, then stop. You take another snapshot of the tank weight, and then the display...it knows your tool width, it knows your target rate...so it just compares what went out of the tank and tells you how close you are. Then you hit accept and keep on seeding...I think once you put the technology in the customer's hands, most of them are going to auto-cal and never look back."</p><small>Product Manager</small></blockquote>

To help tell that story visually, I drafted a *context scenario* to help the project team picture how using this feature might feel:

![image-title-here](/img/portfolio-1-J.jpg){:class="img-responsive img-thumbnail"}

As a customer-focused narrative, the context scenario is meant to elicit feedback on our understanding of the customer need, and also describe a specific solution - but without any design details just yet.

<!--
- How do we see this feature working? How would it feel?
- What is the operator doing, thinking before during and after?
- What is the full context of machine states the operator is also managing?

The goal was to converge on a *design target.* We'd paint a picture of a human outcome we wanted to realize, and execute our interaction design against that. -->

---

## Design
------

I kicked off the screen designs for ActiveCal in *wireframe* fidelity to help keep our ideas from getting too precious too soon. We didn't want to put finished-looking work in front of the client and bias them before they'd had a chance to react and course-correct any assumptions.

![image-title-here](/img/portfolio-1-K.jpg){:class="img-responsive img-thumbnail"}


Once we had agreement on the flow described in rough strokes, our production designers added graphic fidelity working within a predetermined set of UI conventions.

#### PROTOTYPING

After a few iterations in low-fidelity, our interaction and production designers had finalized our individual screen designs. We still had not yet demonstrated a dynamic, interactive version of the proposed design, however.

<div class="row">
<div class="col-sm-5"><p>To give Deere stakeholders a more realistic sense of how the proposed designs would play out interactively, I prototyped a series of "happy path" demos using Axure RP and Quicktime.</p><p>Deere's UI developers used similar short videos at sprint demos every 2 weeks, so <strong>the format was very familiar and easily evaluated by their team.</strong></p><p>Using a series of short, story-specific happy path videos like this one, we were able to secure a final approval of the UI design from the Deere project team.</p></div>
<div class="col-sm-7"><script src="https://fast.wistia.com/embed/medias/ps93m9gssi.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:75.0% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_ps93m9gssi seo=false videoFoam=true" style="height:100%;width:100%">&nbsp;</div></div></div></div>
</div>

---

## Testing
-----

Although any official usability testing for the interfaces will be conducted internally by Deere, we were able to solicit customer reactions to our design concepts at a follow-up focus group in Montana later the same year. I helped plan and lead the event, collaborating with Deere's air seeding product manager and the UI development product owner.

![image-title-here](/img/portfolio-1-L.jpg){:class="img-responsive img-thumbnail"}

Getting validation at a focus group was problematic, however. Our team wasn't budgeted to bring an interactive prototype and materials for 1-on-1 usability testing, and **the group dynamics and cognitive biases of 17 people in the same room would have introduced too much experimental noise.**

So we took a slightly different approach:

<div class="row">
<div class="col-md-6"><br />
<p><strong>Need:</strong> The project charter called for customer feedback on completed work, to be taken via System Usability Scale (SUS) indication (at the time this was Deere's standard UX metric intended for uniform comparison across platforms.)</p>
<p><strong>Challenge:</strong> Due to the focus group format, characterizing our non-interactive screen review as validation would be problematic for longitudinal comparison with any SUS scores that were taken during actual 1-on-1 usability testing. </p>
<p><strong>Resolution:</strong> Following a 90-minute group review of screens covering 10 topics, including ActiveCal, we collected individual SUS scores whose average we then reported as a <em>concept review.</em> Not the ideal application of the SUS method, but qualifying our customer feedback as a concept review positioned it honestly and provided a basis for future comparison for any conceptual screen feedback we might collect in a similar focus group setting.
</p>
</div>
<div class="col-md-6">
<img src="/img/portfolio-1-M.jpg" class="img-responsive" />
</div>
</div>

---

<div style="font-style:italic;text-align:center;">The John Deere C850 is now in production, marketed around faster, more accurate rate calibration with ActiveCal. Beginning in model year 2019, the C850 will be available with the Generation 4 Command Center touch display, where you'll see this interface design brought to life.</div>

<br /><br />
