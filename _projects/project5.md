---
layout: project
title: Integrated DNA Technologies
subtitle: Biotech E-Commerce Design Patterns
thumbnail: portfolio-5.jpg
logofilename: idt-logo.jpg
---
# Search Design Pattern for Biotech Products
![image-title-here](/img/portfolio-5-main.jpg){:class="img-responsive"}

<!--### Background-->

<!--<div class="lead">Genes are the "software" of life which is passed from parent to offspring over generations. Combined with environmental and developmental factors, they give us our physical form.</div>-->
<div class="lead text-justified">In 2015, I helped IDT's web development team establish a framework for scaffolding web development efforts in support of new product launches. <strong>The project goal: establish a generic and reusable design pattern for searching targeted genomic research products.
</strong></div>


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
<td class="hidden-xs">Needs Analysis</td>
<td>Informal interview phone calls, competitive website review</td>
<td>Product Managers, Staff Scientists, Cusotmer Care Staff</td>
</tr>
<tr>
<td class="hidden-xs">UI Design & Engineering</td>
<td>Production UI code (Bootstrap CSS, JQuery)</td>
<td>Web Developers</td>
</tr>
</tbody>
</table>
</div>
</div>


## Background
------

As IDT expanded in the 2000s to enter brand new biotech research product markets, they found themselves blazing new trails in e-commerce, selling things online that had never been sold before. Circumstances forced the organization to develop many web ordering systems from scratch, and as the company grew and expanded around the globe, this led to divergent evolution and a broken user experience.

Across an ever-expanding portfolio of products designed for genomic research, IDT web developers and customer care staff found themselves supporting multiple homegrown legacy ordering user interfaces, many of which confronted customers with 2 or more ways of searching for and ordering the same types of products.

As costs of supporting the technical debt mounted, it became clear that for us to keep up with product launch timelines, we'd have to "future proof" our web development and UX design processes a little better.

 In practice, that meant establishing a library of reusable interaction patterns.



## Needs Analysis

The effort to develop reusable work for IDT's e-commerce was being driven in part by financial planning analysts, who saw that the current costs of supporting our legacy systems were unsustainable. I conducted informal interviews with our web development director, our project manager and also customer care and scientific applications staff.


<p>Through these conversations, we wrote down 3 distinct needs the project would fulfill:
<ul class="needs-questions">
<li><strong>Customers</strong> needed 1 familiar, learnable way to search for products on our website using gene identifiers (short strings of letters like BRCA1, for example)</li>
<li><strong>Developers</strong> required a single abstraction layer that could support a breadth of different product types on the customer side while giving them a single UI codebase to maintain</strong></li>
<li><strong>Customer support & UX</strong> wanted to deliver an easy-to-use website experience that delivered on IDT's promise of excellence in service</li>
</ul>
</p>


From these conversations, I synthesized agile user stories as a way to document the identified customer problems in a format our developers and project managers were familiar with:

<img src="/img/portfolio-5-userstories.jpg" class="img-responsive" />


-----

## EXECUTION
------

I worked closely with developers, since every design decision would need to be grounded within their tech stack and development constraints. It was important that they also understood and be able to explain the design rationale to stakeholders during sprint demos.

To support the communication of a cohesive design strategy, I prepared prototype materials that showcased both the generic use case and then a product line-specific example as a use case scenario:


<br /><br />

<div class="row">
<div class="col-xs-6 col-sm-5 col-sm-offset-1 text-center">
<div class="lead">Persona 1: <strong>Facility Director</strong></div>
<img src="/img/portfolio-4-E-1.jpg" class="img-responsive" style="padding-right:50px;" />
</div>
<div class="col-xs-6 col-sm-5 text-center">
<div class="lead">Persona 2: <strong>Core Lab Customer</strong></div>
<img src="/img/portfolio-4-E-2.jpg" class="img-responsive" style="padding-left:50px;" />
</div>
</div>
<div class="row">
<div class="col-xs-12 col-sm-10 col-sm-offset-1 text-center">
<h4><strong>Needs, Behaviors and Motivations:</strong></h4>
</div>
</div>
<div class="row">
<div class="col-xs-6 col-sm-5 col-sm-offset-1">
<ul class="small">
<li>Accountable to university administration </li>
<li>Does not get financial support from university</li>
<li>“Tortured” relationship with school's purchasing dept.</li>
<li>Runs a business; needs the core lab to pay for itself</li>
<li>May deal with regulatory compliance</li>
<li>Wears many hats beyond research</li>
</ul>
<blockquote>
<p>"I'm trying to run a business within the university AND do research!"</p>
</blockquote>
</div>
<div class="col-xs-6 col-sm-5">
<ul class="small">
<li>Often a grad student or post-doc</li>
<li>Have deadlines so they want their IDT products ASAP</li>
<li>Understands portal advantages</li>
<li>Very busy, doesn’t always read emails or follow instructions</li>
<li>Smart; think they know it all (but has a lot to learn)</li>
<li>Not in direct contact with IDT</li>
</ul>
<blockquote>
<p>"I got an email saying my oligos have arrived...where are they?"</p>
</blockquote>
</div>
</div>


#### THE RESULT

The reusable search and browse patterns we established provided the basis for ongoing web development. Since 2015, IDT has launched new targeted products for CRISPR, qPCR, RNAi and NGS research and supported the web-based ordering of the research tools using the framework we put in place.

<div class="semihuge">1. What are some of the best opportunities for IDT to provide outstanding, best-in-class experience to Core Lab customers that is personalized, streamlined and consistent?</div>

<br />
<div class="row">
<div class="col-xs-5 col-xs-offset-1 text-center">Solution idea: <p><strong>Reporting & invoicing features</strong></p></div>
<div class="col-xs-5 text-center">Solution idea: <p><strong>Give Portal admins more control</strong></p></div>
</div>
<div class="row">
<div class="col-xs-5 col-xs-offset-1 text-center"><p>More reporting and invoicing features for Portal managers will <em>facilitate accurate, timely billing</em> and collections, help <em>prevent incorrect use of fund codes</em> and help <em>ensure regulatory compliance</em>. This may involve tighter integration with university accounting and/or Core LIMS systems.</p></div>
<div class="col-xs-5 text-center"><p>More administrative control of Portals will allow Portal managers to <em>control the flow of IDT order shipment status emails</em> and other info to Portal end users to suit the Core facility workflow, as well as control the display of pricing information which Portal end users see and <em>reduce their questions about inaccurate or confusing pricing.</em></p></div>
</div>



<div class="semihuge">2. How might Core Labs and IDT partner to provide outstanding service to our mutual customers?</div>

<br />

<div class="row">
<div class="col-xs-5 col-xs-offset-1 text-center">Solution idea: <p><strong>Prevent the IDT "Trapdoor"</strong></p></div>
<div class="col-xs-5 text-center">Solution idea: <p><strong>Provide more education support</strong></p></div>
</div>
<div class="row">
<div class="col-xs-5 col-xs-offset-1"><p>More clearly identifying the site (portal vs. punchout vs. direct) throughout the entire ordering process will help <em>prevent accidental direct orders</em> and result in less confusion and a <em>more positive first contact for Portal end users</em> creating an account for the first time. This will also save Portal managers and IDT customer care time.</p></div>
<div class="col-xs-5"><p>Allowing Portal managers to <em>integrate more support and marketing content into the Portal landing page</em>, such as how-to videos, “what’s new” promotions and application showcases will help educated end users on technologies and techniques available to them through the Core, helping Core Labs and IDT <em>more like a research partner than just a supplier.</em></p></div>
</div>

---

<div style="font-style:italic;text-align:center;">The reusable search and browse patterns we established provided the basis for ongoing web development, and since 2015 IDT has launched new targeted products for CRISPR, qPCR, RNAi and NGS research using the framework we put in place.<br /><br />To learn more about IDT's products for genomic research and discovery, visit idtdna.com. </div>

<br /><br />
