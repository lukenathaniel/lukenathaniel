---
layout: project
title: John Deere
subtitle: Easy Fold™ - Embedded Display Feature for Frame Control
thumbnail: portfolio-2.jpg
logofilename: jd-logo.jpg
---
# Easy Fold™ - From Two Hands to One Tap, Unfold and Go
![image-title-here](/img/portfolio-2-A.jpg){:class="img-responsive"}
<small class="text-muted">Photo © Copyright Deere, Inc.</small>

<!--### Background-->

<div class="lead">There's no time to waste when planting season starts, but unfolding a large mechanical planter is a tricky, two-handed procedure that requires experience to do quickly and safely. John Deere's Easy Fold™ feature will make it possible to unfold and go in seconds. <br /><br /><strong>Our design challenge: create an easy to use screen to help users automate complicated frame movements using a single physical control.</strong></div>



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
<td>Stakeholder interviews (GoToMeeting, Skype), contextual inquiry, collaborative workshops, problem definition (user stories, project brief)</td>
<td>Product Manager, System Engineers, Product Owner, Product Support Specialists</td>
</tr>
<tr>
<td class="hidden-xs">Interaction Design</td>
<td>Context scenarios, wire flow (Adobe Illustrator,) dynamic prototyping (Axure RP)</td>
<td>Interaction Designer, Product Owner, System Engineer</td>
</tr>
</tbody>
</table>
</div>
</div>


## Discovery
------

<!--During my time with this UX agency, I worked almost exclusively with John Deere's Seeding group in Moline, helping them design embedded display screens for their new intelligent planting equipment. My role was to *understand and communicate user needs* and to **define the job of design** in such a way that our interaction designers were solving the right problems.-->

At outset of this project, there was no project charter, design brief, or descriptions of the business case or customer needs to work from. We knew only the feature name: "Easy Fold." So I did what I enjoy doing anyway, and I looked into it.

#### INVESTIGATION

Every project begins with *needs analysis* questions:

- Why does this Easy Fold feature exist?
- What human problem does it solve?
- What is folding, and why does it need to be easier?

I would get a chance to see for myself during some *contextual inquiry.*

In the spring of 2016 I tagged along 4 different growers in Iowa, Illinois and Wisconsin, logging about 20 hours' total time in the cab as we planted a few hundred acres with test equipment and some of the early builds of our touch user interfaces.

![image-title-here](/img/portfolio-2-D.jpg){:class="img-responsive"}

During those visits, I watched operators fold and unfold planters dozens of times as they moved in and out of field entries, buildings, refilled commodity tanks, etc, each time having to reposition the frame for transport or planting:

![image-title-here](/img/portfolio-2-C.jpg){:class="img-responsive"}

I learned that folding and unfolding was not as simple as it looks. The operator has to visually monitor the movement and ensure that latches clear parts of the frame, and if they're not paying attention, the articulating hydraulics can easily damage or destroy parts of the machine:

![image-title-here](/img/portfolio-2-E.jpg){:class="img-responsive"}

<p>One of Deere's senior engineers on this project, a veteran farmer himself, had this to tell me about folding a planter:</p>

<div class="row">
<div class="col-sm-4">
<img src="/img/portfolio-2-F-B.jpg" class="img-responsive" /><small class="text-muted">Photos © Copyright Deere, Inc.</small>
</div>
<div class="col-sm-4">
<blockquote>"It's still a 2-handed operation. Left hand on the hydraulic lever, right hand on the little black box so you direct flow to the different cylinders. <br /><br />"Hell, I can do it in my sleep now...but if you're not experienced you can easily damage something."</blockquote>
</div>
<div class="col-sm-4">
<img src="/img/portfolio-2-F-A.jpg" class="img-responsive" /><small class="text-muted">Photos © Copyright Deere, Inc.</small>
</div>
</div>



Most of our interaction designers had never sat in a tractor, so I created *Axure prototypes* to illustrate for them how and why the operators had to use the 2 controls simultaneously, using abstract representations of the different frame pieces to show cause and effect:

![image-title-here](/img/portfolio-2-H.jpg){:class="img-responsive"}

---

## Synthesis & Design
------

By the time we were asked to design this Easy Fold feature, Deere had already taken the frame control box and integrated it into the touch display as an interface:

![image-title-here](/img/portfolio-2-B.jpg){:class="img-responsive"}

We were directed to use this as our starting point for Easy Fold concepts. The rationale was that the new feature needed to be modular from a sales standpoint, but still feel completely integrated:

<blockquote><p>"Easy Fold will be a factory-installed if you pay extra, so it needs to be a seamless add-on to the frame control interface that everyone else gets right out of the box...it has to be way easier than this obviously, but it can't bee too 'different,' if that makes sense..."</p><small>Product Manager</small></blockquote>

Based on this direction, we chose to approach Easy Fold as a complement or alternative to the "Manual" screen controls we'd just imported from the black box into the touch display.

After conducting about 4 or 5 *interviews with stakeholders and subject matter experts*, I had enough material to write out some representative *use case scenarios* describing how this nonexisting feature might work:

![image-title-here](/img/portfolio-2-L.jpg){:class="img-responsive"}


I drafted a hybrid *context scenario/wireframe flow* describing the hypothetical narrative of a corn grower unfolding his new Easy Fold-enabled planter. We envisioned a simple user interface, more of a "mode" the user would place the machine in. As soon as the machine was in Easy Fold mode, the operator would then move the hydraulic control lever and the UI screen that would update dynamically as the movements progressed:

![image-title-here](/img/portfolio-2-G.jpg){:class="img-responsive"}

The project's program manager, an experienced grower himself, didn't respond well to this direction:

> "No. This is supposed to feel easy, not some wizard of screens. I don't like the stepwise thing...I just want to see the 'Mission accomplished' feedback at the end.""

It was easy to understand his vision, which the Deere stakeholders agreed with, and so we took a second pass at it in *higher fidelity mockups* using this "mission accomplished" idea as our new true north:

![image-title-here](/img/portfolio-2-I.jpg){:class="img-responsive"}


The team responded positively to this direction, but then the lead system engineers pointed out a *missing requirement,* a wrinkle we hadn't yet accounted for.

This feature was possible because of position sensors installed on the frame. The first time an operator runs the procedure, they have to visually monitor progress and take snapshots of the frame in certain states. Essentially, the operator has to "teach" Easy Fold which sensor positions correspond to which physical frame fold states. Only then can the automated sequence result in a properly folded or unfolded frame.

To brainstorm this issue, I made some 1-on-1 phone calls and did a lot of *virtual white boarding* with 2 of Deere's seeding engineers to conceive of an overlay screen to let operators capture these snapshots:

![image-title-here](/img/portfolio-2-K.jpg){:class="img-responsive"}


Eventually we came up with a clear *problem statement* to characterize this last UI design hurdle for Easy Fold:

<div class="row well">
<div class="col-sm-4">
<p><strong>Need:</strong> For Easy Fold to control the hitch during automated folding/unfolding, the system needs to know 3 different hitch height values ("Fold", "Plant", "Transport".)</p>
</div>
<div class="col-sm-4">
<p><strong>Challenge:</strong> Each of the height height values should be captured independently at the appropriate point during an actual fold procedure.</p>
</div>
<div class="col-sm-4">
<p><strong>Resolution:</strong> To facilitate capture of these “snapshots” at the appropriate points in the sequence, we would only allow the user to capture them within specific sensor state ranges.
</p>
</div>
</div>

Below is an excerpt from the PowerPoint the lead engineer and I collaborated on in order to *tell this story* for the rest of the core team and solicit the sanity feedback we needed to make sure we got it right:

![image-title-here](/img/portfolio-2-J.jpg){:class="img-responsive"}

It was agreed that Easy Fold would be developed with this initial setup in mind. The first time an operator ran the automatic fold sequence, they'd be prompted to set up their hitch height settings using this interface. Each time they used Easy Fold thereafter, it would "remember" the captured frame states and **let them fold or unfold the planter by using a single switch.**

---

## Testing
-----

Because our agency's statement of work included design only, we did not participate in any usability evaluations for the work we completed for this feature. Instead, I authored a *proposal for usability testing* our Easy Fold designs with Deere customers using goal-based scenarios, and provided that to Deere with our deliverables:

<table class="table table-condensed">
<thead>
<tr>
<th style="width:40%;">Research Question</th><th style="width:40%;">Task</th><th>Metric</th>
</tr>
</thead>
<tbody>
<tr>
<td>Is the Easy Fold touch UI learnable and efficient?</td><td><em>"Imagine you've arrived and entered the field and are ready to plant. Using the touch display, how would you unfold the planter with the automated fold feature?"</em></td><td>Pass/Fail, SEM, Completion Time</td>
</tr>
<tr>
<td>Is the first-time initial setup of Easy Fold hitch height settings likely to be understood by both experienced and novice machine operators?</td><td><em>"You've purchased the new Easy Fold option, and your dealer has instructed you that the first time you use it, you'll need to set up the hitch height set points. Once your display powers up, where would you go to access those settings and do that?"</em></td><td>Pass/Fail, SEM, Completion Time (Segment by experience level)</td>
</tr>
</tbody>
</table>

---

<div class="row">
<div class="col-md-6">
<p>The Easy Fold feature was developed largely as-designed, and then extensively field-tested with cooperators and product validation engineers in 2017. <strong>It is now available as an option with model year 2018+ planters.</strong></p>

<p>It's too soon to know just how easy Easy Fold really is, but the market always speaks and John Deere, as they have always done, will pay attention to customer feedback and take the time to get it right.</p>
</div>
<div class="col-md-6">
<img src="/img/portfolio-2-M.jpg" class="img-responsive" /><div style="font-style:italic;text-align:center;margin-top:5px;">You can see Easy Fold in action on Youtube as part of the SeedStar 4 package, now available with John Deere planters.</div>
</div>
</div>


---



<br /><br />
