---
layout: pages
title: "Licences applicables"
---

<h3>Licence générale</h3>

Sauf lorsque le contraire est mentionné, le contenu est sous Licence
ouverte (voir ci-dessous).

<h4>Licence ouverte</h4>

Dans le cadre de la politique du Gouvernement en faveur de l’ouverture
des données publiques («&nbsp;Open Data»&nbsp;), Etalab a conçu
la «&nbsp;Licence Ouverte / Open Licence&nbsp;». Cette licence,
élaborée en concertation avec l’ensemble des acteurs concernés,
facilite et encourage la réutilisation des données publiques mises à
disposition gratuitement. La plateforme des données publiques gratuites
de l’Etat «&nbsp;data.gouv.fr»&nbsp; sera mise en ligne début
décembre 2011.

La «&nbsp;Licence Ouverte / Open Licence&nbsp;» présente les
caractéristiques suivantes :

* Une grande liberté de réutilisation des informations :
 1. Une licence ouverte, libre et gratuite, qui apporte la
   sécurité juridique nécessaire aux producteurs et aux
   réutilisateurs des données publiques ;
 2. Une licence qui promeut la réutilisation la plus large en
   autorisant la reproduction, la redistribution, l’adaptation et
   l’exploitation commerciale des données ;
 3. Une licence qui s’inscrit dans un contexte international
   en étant compatible avec les standards des licences Open Data
   développées à l’étranger et notamment celles du gouvernement
   britannique (Open Government Licence) ainsi que les autres standards
   internationaux (ODC-BY, CC-BY 2.0).
* Une exigence forte de transparence de la donnée et de qualité des
  sources en rendant obligatoire la mention de la paternité.
* Une opportunité de mutualisation pour les autres données publiques
  en mettant en place un standard réutilisable par les collectivités
  territoriales qui souhaiteraient se lancer dans l’ouverture des
  données publiques.

<h3>Télécharger la licence ouverte</h3>

  <ul class="posts">
    {% for licence in site.licences %}
    
  <li><span>{{ licence.langue }}</span>&nbsp;: <a href="{{ licence.pdf }}">PDF</a> <a href="{{ licence.rtf }}">RTF</a></li>

    {% endfor %}
  </ul>
