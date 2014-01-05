---
layout: pages
title: "Licences applicables"
---

<h3>Licence générale</h3>

Sauf lorsque le contraire est mentionné, le contenu est sous licence
CC-BY ou sous licence ouverte, lorsqu'il s'agit de données.

<hr />

<h3>Licence CC-BY</h3>

<h4>Vous êtes autorisé à :</h4>

- _Partager_ —  copier, distribuer et communiquer le  matériel par tous
  moyens et sous tous formats
- _Adapter_ — remixer, transformer et créer à partir du matériel pour
  toute utilisation, y compris commerciale.

L'Offrant ne peut retirer les autorisations concédées par la licence
tant que vous appliquez les termes de cette licence.

<h4>Selon les conditions suivantes :</h4>

_Attribution_ — Vous devez créditer l'Oeuvre, intégrer un lien
vers la licence et indiquer si des modifications ont été effectuées
à l'Oeuvre. Vous devez indiquer ces informations par tous les moyens
possibles mais vous ne pouvez pas suggérer que l'Offrant vous soutient
ou soutient la façon dont vous avez utilisé son Oeuvre.

_Aucune contrainte supplémentaire_ — Vous n'êtes pas autorisé
à appliquer des conditions légales ou des mesures techniques qui
restreindraient légalement autrui à utiliser l'Oeuvre dans les
conditions décrites par la licence.

<h4>Notes&nbsp;:</h4>

Vous n'êtes pas dans l'obligation de respecter la licence pour les
éléments ou matériel appartenant au domaine public ou dans le cas où
l'utilisation que vous souhaitez faire est couverte par une exception.

Aucune garantie n'est donnée. Il se peut que la licence ne vous
donne pas toutes les permissions nécessaires pour votre utilisation.
Par exemple, certains droits comme les droits moraux, le droit des
données personnelles et le droit à l'image sont susceptibles de
limiter votre utilisation.

<h4>Télécharger la licence CC-BY</h4>

Le texte intégral se trouve <a
href="http://creativecommons.org/licenses/by/2.0/fr/legalcode">ici</a>.

<hr />

<h3>Licence ouverte</h3>

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

<h4>Télécharger la licence ouverte</h4>

  <ul class="posts">
    {% for licence in site.licences %}
    
  <li><span>{{ licence.langue }}</span>&nbsp;: <a href="{{ licence.pdf }}">PDF</a> <a href="{{ licence.rtf }}">RTF</a></li>

    {% endfor %}
  </ul>
