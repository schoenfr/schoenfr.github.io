---
title: René Schönfelder
menu: 1
icon: home
imports:
 - iron-icon
---

Welcome to my homepage. This site is currently under construction, but feel free to take a look around. It has started as an experiment with Jekyll on Github pages and will later become my representative homepage.

# <iron-icon icon icon="account-circle" /> Personal

![René Schönfelder](img/portrait.jpg){:id="portrait"}

You can contact me in german or english via

| Email  | [schoenfelder2211@gmail.com](mailto:schoenfelder2211@gmail.com) |
| Skype  | reneschoenfelder |

or find me at

| Github | [schoenfr](http://github.com/schoenfr){:target="_blank"} |
| XING | [René Schönfelder](http://www.xing.com/profile/Rene_Schoenfelder3){:target="_blank"} |

# <iron-icon icon="social:school" /> Education

| Currently | University of Lübeck <br> Working on a PhD about Algebraic Routing for Green Navigation |
| 2014 | Certificate for University Didactics - University of Lübeck |
| 2012 | M.Sc. Computer Science - University of Lübeck <br> Thesis: [Stochastic Models and Acceleration Techniques for Green Routing in Car Navigation Systems](http://rene.odyne.net/resources/ma_schoenfelder.pdf){:target="_blank"} |
| 2009 | B.Sc. Computer Science - University of Lübeck <br> Thesis: [Structural Properties of m-Step Graphs](http://rene.odyne.net/resources/ba_schoenfelder.pdf){:target="_blank"} |
{:class="vitatable"}

# <iron-icon icon="favorite" /> Interests

- Mathematics, especially Algebra and Graph Theory
- Software Engineering and Verification
- Project Management, Agile Development
- Teaching and Mentoring
- ... and my friends and family

# <iron-icon icon="places:business-center" /> Experience

WMD Vertrieb GmbH since 08/2015
: As a software developer I assist with WMD's xSuite365.

Green Navigation since 2011
: As a doctoral student I have researched on routing algorithms for this project and supervised student projects and theses for four years.
: Core technologies used: Java, Scala, GoLang, JavaScript, jQuery, Polymer, REST (Spring), OSM, Google Maps

# <iron-icon icon="communication:forum" /> Teaching

<table class="responsive">
<thead>
  <tr>
  	<th>Term</th>
  	<th>Role</th>
  	<th>Title</th>
  	<th>Type</th>
  	<th>Lecturer</th>
  </tr>	
</thead>
<tbody>
{% for x in site.data.teachings %}
<tr>
  <td label="Term">{{x.term}}</td>
  <td label="Role">{{x.role}}</td>
  {% if x.link %}
  <td label="Title"><a href="{{x.link}}" target="_blank">{{x.name}}</a></td>
  {% else %}
  <td label="Title">{{x.name}}</td>
  {% endif %}
  <td label="Type">{{x.type}}</td>
  {% if x.lecturer %}
  <td label="Lecturer">{{x.lecturer}}</td>
  {% endif %}
</tr>
{% endfor %}
</tbody>
</table>

Furthermore, I have assisted in 27 student theses, primarily around Green Navigation.

# <iron-icon icon="maps:local-library" /> Publications

- __René Schönfelder__, Martin Leucker (2015): <br> [Abstract Routing Models and Abstractions in the Context of Vehicle Routing](http://ijcai.org/Abstract/15/374){:target="_blank"}. <br> IJCAI - International Joint Conference on Artificial Intelligence, pp 2639-2645.
- __René Schönfelder__, Martin Leucker, Sebastian Walther (2014): <br> [Efficient Profile Routing for Electric Vehicles](http://dx.doi.org/10.1007/978-3-319-11167-4_3){:target="_blank"}. <br> IOV - Internet of Vehicles, pp 21-30.
- __René Schönfelder__, Martin Leucker (2011): <br> [Stochastisches Routen für Elektrofahrzeuge](http://www.offis.de/f_e_bereiche/energie/workshops/workshop_energieinformatik/energieinformatik_2011.html){:target="_blank"}. <br> Workshop Energieinformatik, pp 45-51.

# <iron-icon icon="grade" /> Grants/Awards

- Doctoral scholarship by the [EKSH Gesellschaft für Energie und Klimaschutz Schleswig-Holstein GmbH](http://eksh.org){:target="_blank"} (2013-2016).
- Capgemini award for the best master degree in computer science at the University of Lübeck (2012).
- Erasmus scholarship for an exchange semester at the University of Oslo (2011).

# <iron-icon icon="more-horiz" /> Other Activities

- [Arbeiterkind.de](http://arbeiterkind.de){:target="_blank"}, mentoring *first-generation students* (2011-2015).
