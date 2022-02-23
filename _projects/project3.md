---
layout: project
title: Integrated DNA Technologies
subtitle: Web-Based Ordering Tool for Gene Sequencing Products
thumbnail: portfolio-3.jpg
logofilename: idt-logo.jpg
---
# Project: Web-Based Ordering Tool for Gene Sequencing Products
![image-title-here](/img/portfolio-3-main.jpg){:class="img-responsive"}

<!--### Background-->

<!--<div class="lead">Genes are the "software" of life which is passed from parent to offspring over generations. Combined with environmental and developmental factors, they give us our physical form.</div>-->
<div class="lead text-justified"><!--Life science research often focuses on a few genes at a time, as scientists study DNA sequences to investigate phenomena such as the development of cancer.--><!--With 3+ billion base pairs in the human genome alone, <strong>targeted DNA sequencing</strong> is an efficient way for scientists to generate deep, focused data they can mine for answers to specific questions.<br /><br />-->In 2013 IDT released a new gene sequencing product, xGen® Lockdown® Probes. Making this product available for purchase online meant designing and building an ordering tool that was simple, user friendly and yet still flexible enough to support highly specific research. <!--<br /><br /><strong>Our challenge: design a simple, easy to use ordering tool that helps new users find the correct gene sequencing products while giving expert users the flexibility custom-build their own.</strong>--></div>


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
<td>Customer interviews (GoToMeeting, Skype), user testing (UserTesting.com, VerifyApp, VisualWebsiteOptimizer), click analysis (Google Analytics), user stories, hallway testing</td>
<td>Product Manager, Field Application Specialist, Bioinformaticians, Customer Care Reps, Sales Reps</td>
</tr>
<tr>
<td class="hidden-xs">Interaction Design</td>
<td>Collaborative white boarding, wireframes (Balsamiq), prototyping (Invision, HTML/JQuery)</td>
<td>Web Developers, Field Application Specialist, Staff Scientist</td>
</tr>
<tr>
<td class="hidden-xs">Illustration</td>
<td>Supporting graphics (Adobe Creative Suite)</td>
<td>Field Application Specialist, Staff Scientist, Scientific Writer</td>
</tr>
<tr>
<td class="hidden-xs">UI Engineering</td>
<td>Production UI code (Bootstrap CSS, JQuery, SiteFinity CMS), event tracking code (Google Analytics, VisualWebsiteOptimizer)</td>
<td>Web Developers</td>
</tr>
</tbody>
</table>
</div>
</div>


## Discovery
------
#### BACKGROUND

Next generation sequencing (NGS) refers to the high-throughput technologies which continue to help drive down the cost of DNA sequencing and accelerate life science research. NGS is indispensable in many areas of study, from cancer profiling and inherited diseases to zoology, food safety, agriculture and much more.

IDT entered this market in 2013 with a synthetic DNA product optimized for target capture, **an important early step** of the sequencing workflow that ultimately **turns data into answers.**
<figure>

<img src="/img/portfolio-3-E.jpg" class="img-responsive" />
<figcaption>I collaborated with staff scientists on white board illustrations like this one to help convey the customer narrative and provide goal-based context to the project team.</figcaption>
</figure>

To sell Lockdown probes on the IDT website, we'd need to **design web-based tool to help researcher isolate specific regions from sample DNA** for amplification and then sequencing. The tool would require flexible input parameters, accepting standard gene identifiers (HUGO gene symbols, NCBI gene IDs, RefSeq accession numbers), chromosomal coordinates and also raw target sequences in text (FASTA) format. The output would be a custom-designed set of Lockdown probes, available for purchase online.

#### THE CHALLENGE

When this project began, the IDT website was **built for "made to order" purchases.** Customers were designing what they needed themselves as raw DNA sequences and then having IDT synthesize that. It was not uncommon for customers to prepare orders in Excel sheets and then email them to customer care:

<img src="/img/portfolio-3-B.jpg" class="img-responsive" />


#### AN OPPORTUNITY TO FOCUS

<p>The people who would be purchasing and using these new NGS products were doing really specific, focused work. To learn more about them I did a series of <em>needs analysis interviews</em>.</p>


They were diverse - young and old, from a dozen different countries, CEOs, lab managers at facilities, professional scientists at pharmaceuticals, research fellows in university labs studying for their GREs - but what they shared was they were doing very focused investigation requiring **highly specialized methods and tools:**


<div class="row">
<div class="col-xs-4">
<img src="/img/portfolio-3-C-1.jpg" class="img-responsive"  /><br />
</div>
<div class="col-xs-4">
<img src="/img/portfolio-3-C-2.jpg" class="img-responsive"  /><br />

</div>
<div class="col-xs-4">
<img src="/img/portfolio-3-C-3.jpg" class="img-responsive"  /><br />

</div>
</div>

<div class="row">
<div class="col-xs-4">
<p>They were <strong>studying groups of genes</strong> to do research on specific phenomena, such as the development of cancer.</p>
</div>
<div class="col-xs-4">
<p>They used <strong>specific DNA sequencing machines</strong> and compatible reagents with <strong>precise experimental protocols.</strong></p>
</div>
<div class="col-xs-4">
<p>They weren't buying products to do research. They were buying <strong>solutions</strong> to help them get <strong>answers.</strong></p>
</div>
</div>

---

Unlike IDT's custom oligo customers, this user audience needed more than just custom-made DNA, purified and shipped overnight. **They needed expertise and recommendations to support their work:**

>"Let's say it's a gene fusion, do I just give you the 120 bases on either side? I would need some recommendation on how best to do that. I just specify what I absolutely need covered?"

I collaborated with our field application specialist and inside sales reps to sketch out different parts of the *customer journey* associated with this product:

<img src="/img/portfolio-3-A.jpg" class="img-responsive" />

<p>This new product and the ordering interface we were designing were just one piece of the puzzle. <strong>For IDT to properly support our NGS customers' work, our design and ordering tool would need to fit their workflow seamlessly.</strong></p>

---

## Synthesis
------

This focus on a new set of user needs, behaviors and motivations was the first in a major shift for IDT as they transitioned from being just a **custom manufacturing** company to **product and solution** company:
<div class="row before-after">
<div class="col-xs-6 col-sm-5 text-center">
<h4>Then:</h4>
<blockquote>
<p class="before-after">"Here's what I need. <br /><strong>Build it for me."</strong></p>
</blockquote>
</div>
<div class="col-sm-2 text-center hidden-xs"><br /><br /><br /><br />
<i class="fa fa-long-arrow-right" style="font-size:4em;"></i>
</div>
<div class="col-xs-6 col-sm-5 text-center">
<h4>Now:</h4>
<blockquote>
<p class="before-after">"Here's what I am doing. <br /><strong>Tell me what I need.</strong>"</p>
</blockquote>
</div>
</div>
---

We were also splitting the difference between "make it my way" flexibility and "off the shelf" add-to-cart simplicity. The tool needed to support some expert users with advanced configuration options, but to make the first phase of the product launch simpler *we prioritized 2 customer types and use case scenarios:*

<table class="table table-condense">
<thead>
<tr>
<th style="width:20%;">Customer type</th>
<th>User Story</th>
<th>Acceptance Criteria</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Lab Manager</strong><br /><ul class="small"><li>Often placing an order for someone else</li><li>Doesn't want to play support middle-man if possible</li></ul></td>
<td><p style="font-style:italic;">"As a core lab manager ordering reagents for one of our facility's clients, I need to be able to order target capture probes at 2X coverage using the list of ~20 gene symbols they provided me."</p></td>
<td>The design tool allows for gene symbol input type, with multiple line or comma-separated symbols, minimum of 20, and provides coverage optionality including 2X coverage.</td>
</tr>
<tr>
<td><strong>Principal Investigator</strong><br /><ul class="small"><li>More advanced, DIY tinkerer, makes lots of product roadmap requests</li><li>Don't handcuff them in terms of options</li></ul></td>
<td><p style="font-style:italic;">"As a researcher studying noncoding DNA, I need to be able to target and sequence using a FASTA-formatted text as my design input, and then I need to know what percent of that is covered by the resulting probe design."</p></td>
<td>The design tool allows for raw FASTA sequence input as an option, and provides percent design coverage as an output.</td>
</tr>
</tbody>
</table>



## Design & Prototyping
------

#### Design principle: match the user's reality

<div class="row">
<div class="col-md-8">
<p>While the cost of DNA sequencing has gone down, it's not yet like copy machines in the office that get used for company picnic flyers. Every sequencing run costs hundreds or thousands of dollars in reagents and expert skilled labor. Thus, researchers need to sequence ONLY what they are studying, and that's what makes target capture such an important step.</p>

<p>We needed to reconcile a <strong>tension between what most people understand to be "easy" ordering experiences with what is still very technical, specific work that is easy to screw up</strong> by ordering the wrong target capture probes:</p>

<blockquote><p>"I'm not sure how easy can make placing an order for $20,000 reagents. We don't want to get into a situation where we're delaying production and verifying these huge orders manually just because the ordering tool makes it too easy to buy the wrong thing..."</p><small>Customer care representative</small></blockquote>

<p>For this reason, <strong>we placed the design tool functionality behind the login.</strong> This also had the benefit of folding the product pricing and purchasing into existing customer pricing models for universities, core labs and internal customers.</p>

<p>(This also forced users of the tool to identify themselves in order to get access to designs which, theoretically, could be downloaded and synthesized by a competitor of IDT.)</p>
</div>
<div class="col-md-4">
<figure>
<img src="/img/portfolio-3-F.jpg" class="img-responsive" />
<figcaption>This flow diagram is some of the pre-design modeling I used to help reach team consensus on how the tool should work (before we decided how it looked.)</figcaption></figure>
</div>
</div>

#### Design principle: explain proprietary terminology

<div class="row">
<div class="col-sm-6">
<p>The xGen Lockdown probe design and ordering tool would save customers some trouble by baking expertise into the software, empirically-informed opinions about design strategies that yield good results for most people. The flip side of that, however, is that while this satisfies most "design it for me" it provides little context into the strategy behind the design.</p>

<p>For this reason <strong>we made a point of providing help context to explain what terms like "target definition" and "tiling density" meant.</strong> We couldn't really omit these terms or simplify them with suitable synonyms because it was new territory altogether. Instead, we would provide helpful explanations in context, and we'd use modal dialog windows so that the customer with doubts about a certain word could investigate it without leaving their work in progress:</p>
</div>
<div class="col-sm-6">
<figure>
<img src="/img/portfolio-3-H.png" class="img-responsive" />
<figcaption>I collaborated with IDT product scientists to design supporting illustrations like this to reduce ambiguity about product terminology.</figcaption>
</figure>
</div>
</div>

#### Strategy: What's good for the codebase is good for UX

I worked very closely with developers from the outset of this project. The volume of IDT's business had outgrown their hand-coded desktop website, and as business units became more autonomous the development groups had begun to diverge into what was now a fragmented user experience. That fragmentation was costing us needless development time from duplicated UI code, and also the inevitable design churn that results from questions about the "correct" design pattern to use for a given interaction problem.

We had a plan: we would take this as an opportunity to *put a responsive CSS framework in place.* We'd kill 2 birds with one stone:

- **We would scaffold future development with reusable interface components and patterns**
- **We would keep the visual design tighter and maintainable within a centralized framework**

#### Strategy: Use prototypes to tell stories, drive decisions

My early HTML prototypes, built on Bootstrap CSS and JQuery, captured "happy path" interactions as video clips. These clips were meant to *demonstrate intent without turning stakeholders loose* to kick the tires on a half-baked prototype. **I prioritized the 2 main use case scenarios for these video proofs:**

<script src="https://fast.wistia.com/embed/medias/yxninjv4i7.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:56.25% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_yxninjv4i7 seo=false videoFoam=true" style="height:100%;width:100%">&nbsp;</div></div></div>
----


## Testing
-----

#### Strategy: Sometimes, your best guess is good enough

Prior to unleashing our ordering solution on the paying public, we recruited customer support to solicit their feedback as *proxy users*.

 - All of them had a biology and/or chemistry education.
 - Some had lab experience as researchers using NGS.
 - Most importantly, all of them had the **deep customer understanding** to be able to talk at length about common pain points associated with ordering and using gene sequencing products.

They weren't customers, but for our needs they were close enough.

And we weren't aiming for perfection in this first phase anyway. We weren't trying to measure statistically significant performance gains between a legacy and redesigned experience. This was all very new for IDT and the market, both the product and the way people were going to be ordering it. *We just needed to know if we were in the ballpark on a few important heuristics:*

- **Match of system to real world** - Did the sequence of interactions and labels and text align with the reality of the research workflow?
- **Help and documentation** - Were the pieces in place for users to easily self-service questions or doubts about what certain things meant?
- **Consistency and standards** - After years of using maker-centric jargon, IDT had grown a little numb to our use of synonyms and scientific shorthand. We were we consistent in referring to the same thing with the same words?

With these goals in mind, we reviewed a beta version of the tool with at least 8 customer care representatives, as well as 4 of IDT's collaborator customers. Using the goal-based scenarios described below, **all 12 participants were able to complete the tasks successfully:**

<table class="table table-condensed">
<thead>
<tr>
<th style="width:70%;">Task Description</th>
<th>Pass/Fail</th>
<th>SEQ (Avg)</th>
</tr>
</thead>
<tbody>
<tr>
<td>"Imagine you are working as a core facility staff member and are provided this list of 12 genes to order target capture reagents for. Can you show me how you would do that, using this screen in front of you? "</td>
<td>12/12</td>
<td>4.58</td>
</tr>
<tr>
<td>"Imagine your research focuses on noncoding regions of genes, and you want to sequence an entire region that you have described as FASTA text. If you wanted to design a probe set to capture and sequence that region and do so at 2X coverage, how would you do that with this tool?"</td>
<td>12/12</td>
<td>4.75</td>
</tr>
</tbody>
</table>

<div class="text-center small">(SEQ = Single Ease Question: "How would you rate that task overall on a scale of 1 to 7, where 1 = Very Difficult and 7 = Very Easy?")</div>

---

We also captured participant comments, which at least for customers focused less on the user interface and more on the product support resources:

<blockquote>
<p>"For someone who is not competent in bioinformatics, the site was intuitive and easy to use.  Maybe some info, once people order, for compatible protocols for preparing libraries, etc. We used Agilent Sure Select with good results, so maybe some links to compatible protocols would be nice."</p>
<small>Customer participant feedback</small>
</blockquote>

This comment and others like it *underscored our need to consider the broader customer experience beyond the user interface.* Without product knowledge reflected in all touch points before and after the customers' use of the design tool, it would be difficult to support successful research outcomes for the people using the product.

#### The Result

Our team successfully launched this tool in late 2013. In the following 18 months, the tool's volume exceeded original 3-year sales targets, making the project a commercial success. With the recent addition of features such as predesigned capture sets for thousands of human gene targets, the tool today continues to serve the life science research community.

<img src="/img/portfolio-3-I.jpg" class="img-responsive" />

---

<div style="font-style:italic;text-align:center;">Visit IDTDNA.com to learn more about applications of next-generation sequencing.</div>

<br /><br />
