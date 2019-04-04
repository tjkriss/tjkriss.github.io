---
layout: "page"
title: CV / Resume
permalink: "/CV"
---

<div class="wrapper">
  <section class="inner">
    <article class="resume">
      {% if site.introduction %}
      <section class="section">
        <h2 class="section__title"><span>Objective</span></h2>
        {{ site.introduction }}
      </section>
      {% endif %}

      <section class="section">
        <h2 class="section__title"><span>Education</span></h2>
        <ul>
        {% for skill in site.data.professional-strengths.skills %}
          <li>{{ skill.name }}</li>

        {% endfor %}
				  	<h3 class="section__title"><span>Kansas Academy of Mathematics and Science</span><h3>
						>Fort Hays State University, Hays, KS: May 2015
					<h3 class="section__title"><span>Bachelor of Science, Biology emphasis in Botany</span><h3>
						>Fort Hays State University, Hays, KS: May 2017
					<h3 class="section__title"><span>Master of Science, Biology emphasis in Botany</span><h3>
						>Fort Hays State University, Hays, KS: Projected - May 2019
					<h3 class="section__title"><span>Undergraduate and graduate advisor: Dr. Brian R. Maricle</span><h3>


      <section class="section">
        <h2 class="section__title"><span>Research</span></h2>

        {% for job in site.data.work-experience.jobs %}
          <p><strong>{{ job.title }} - {{ job.place }}</strong> ({{ job.years }})<br />
          {{ job.description}}</p>

          <ul>
            {% for work-item in job.work-items %}
            <li>{{ work-item }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>

      <section class="section">
        <h2 class="section__title"><span>Professional Experience</span></h2>

        {% for school in site.data.education.schools %}
          <p><strong>{{ school.name }}</strong>, {{ school.location }} - ({{ school.years }})</p>
          <ul>
            {% for degree in school.degrees %}
            <li>{{ degree }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>

         <section class="section">
        <h2 class="section__title"><span>Honors</span></h2>

        {% for school in site.data.education.schools %}
          <p><strong>{{ school.name }}</strong>, {{ school.location }} - ({{ school.years }})</p>
          <ul>
            {% for degree in school.degrees %}
            <li>{{ degree }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>
	  
	       <section class="section">
        <h2 class="section__title"><span>Presentations</span></h2>

        {% for school in site.data.education.schools %}
          <p><strong>{{ school.name }}</strong>, {{ school.location }} - ({{ school.years }})</p>
          <ul>
            {% for degree in school.degrees %}
            <li>{{ degree }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>
	  
	       <section class="section">
        <h2 class="section__title"><span>Certifications</span></h2>

        {% for school in site.data.education.schools %}
          <p><strong>{{ school.name }}</strong>, {{ school.location }} - ({{ school.years }})</p>
          <ul>
            {% for degree in school.degrees %}
            <li>{{ degree }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>

	       <section class="section">
        <h2 class="section__title"><span>College Courses Completed</span></h2>

        {% for school in site.data.education.schools %}
          <p><strong>{{ school.name }}</strong>, {{ school.location }} - ({{ school.years }})</p>
          <ul>
            {% for degree in school.degrees %}
            <li>{{ degree }}</li>
            {% endfor %}
          </ul>
        {% endfor %}
      </section>
  {% if site.phone %}
  <section class="message">
    <p>You can reach me on weekday after 5pm at <a href="tel:{{ site.phone }}">{{ site.phone }}</a>.</p>
  </section>
  {% endif %}

</div>








Tayler Kriss
Department of Biological Sciences, Fort Hays State University, Hays, KS 67601
tjkriss@mail.fhsu.edu * (620) 794-1884

Education
Kansas Academy of Mathematics and Science, Fort Hays State University, Hays, KS: May 2015
Bachelor of Science, Biology emphasis in Botany, Fort Hays State University, Hays, KS: May 2017
Master of Science, Biology, Fort Hays State University, Hays, KS:  Projected - May 2019
Undergraduate and graduate advisor: Dr. Brian R. Maricle 
Professional Experience
2017 - 2018  Graduate Work Assistant, Kansas Wetlands Education Center, Fort Hays State   	University, Great Bend and Hays, KS.
Animal care, including, prairie dogs, screech owls, big brown bats, salamanders, several turtle and snake species. 
Customer service and clerical work, greeting visitors, answering questions, giving tours of the facility and wetlands.
2018 - 2019  Graduate Teaching Assistant, Laboratory Experiences in Biology, Fort Hays State University, Hays, KS. 
Grading online lab reports and answering students questions. 
Research Experience 
Undergraduate - 2015-2016 Big Bluestem (Andropogon gerardi) stem sectioning using a 	microtome
2016 Seperation of chloroplasts from spinach leaves in sucrose solution for       spectrophotometric analysis at different light wavelengths, to determine photosynthetic activity.
2017 Photosynthetic action spectra of etiolated green beans during greening.
Graduate     --     2017-2019 Greening rates and photosynthetic development of leaves in C3 and C4 plants,          Studying how dark grown etiolated plants transition to a green state once introduced to light, using fluorescence and gas exchange measurements, by the use of an LI-6400XT Portable Photosynthesis System. Achlorophyllous leaves were measured at 0 days of light exposure, introduced to light, and measured daily for 10 days to track photosynthetic development and efficiency of photochemical processes.
Honors
        	2017 - Botanical Society of America, Li-Cor poster presentation prize, June 2017
Presentations
            2017 - Botanical Society of America - poster presentation - Tayler J. Kriss and Brian R. Maricle, Developing Chlorophyll Fluorescence in Etiolated Green Bean, Phaseolus vulgaris
                      - Kansas Academy of Science annual meeting - poster presentation -
2018 - Botanical Society of America - poster presentation - Tayler J. Kriss and Brian R. Maricle,     Developing chlorophyll fluorescence and gas exchange in etiolated green bean, Phaseolus vulgaris, and corn, Zea mays
Certifications
	2018 - FAA Small Unmanned Aircraft System Remote Pilot 
College Courses Completed
Botany - 23 credit hours
        	Botany and Lab
        	Plant Anatomy and Lab
        	Plant Physiology and Lab
        	Topics in Biology: Dendrology
        	Taxonomy of Flowering Plants and Lab
        	Range Plants and Identification Lab
Biology - 33 credit hours
        	Humans and the Environment
        	Ecology and Lab
        	General Microbiology and Lab
        	Biodiversity and Conservation Biology
        	Cellular Biology
        	Human Heredity
        	Biologic Scientific Writing
        	Rangeland Management and Techniques
Topics in Biology: Unmanned Aerial Systems
Graduate Problems in Biology: Virology
Graduate Problems in Biology: Evolution
Biostatistics and Lab
Digital informal science communication seminar
Chemistry - 10 credit hours
University Chemistry I and Lab
University Chemistry II and Lab
Undergraduate Research - 8 credit hours
Problems in Geosciences: Earth Space Science Research & Writing
        	Problems/Information: Networking/Telecommunications
        	Problems/Biology: Independent Research
Mathematics - 19 credit hours
Pre-Calculus
        	Analytic Geometry and Calculus I
        	Analytic Geometry and Calculus II
        	Computer Science I
        	Computer Science II
Physics - 10 credit hours
        	Physics for Scientists and Engineers I and Lab
        	Physics for Scientists and Engineers II and Lab
English - 6 credit hours
English Composition I
English Composition II
Communication - 3 credit hours
        	Fundamentals of Oral Communication
History - 6 credit hours
United States History to 1877
United States History Since 1877
 

