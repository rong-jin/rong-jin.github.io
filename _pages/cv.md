---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mechanical Engineering, University of Kentucky, 2027 (expected)
* M.S. in Mechanical Engineering Design, University of Manchester, 2019
* B.E. in Mechanical Design, Manufacturing and Automation, Shanghai Maritime University, 2018

Work experience
======
* Jan 2023 – Current: Graduate Research Assistant, University of Kentucky
  * Advisor: Dr. Xingsheng Sun  
  * Duties included: Conducting high-velocity impact simulations on Mg alloy specimens using the SPH method in LS-DYNA and developing an automated data assimilation framework with LS-DYNA and Python for material parameter calibration.  


* Oct 2019 – Dec 2022: Mechanical Engineer, Zhenhua Port Machinery Company Limited (ZPMC)  
  * Duties included: Conceptualizing and drafting detailed construction schematics for port machinery, performing static structural analysis with FEM in ANSYS, and creating 3D models and animations using SolidWorks Motion to support product visualization and promotion.  

  
Skills
======
* Programming Languages
  * Python
  * MATLAB
* CAD Tools
  * AutoCAD
  * SolidWorks
* CAE Tools
  * ANSYS Workbench
  * ANSYS Mechanical APDL
  * LS-DYNA

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

<!--Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!--Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams-->
