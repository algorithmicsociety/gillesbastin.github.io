---
layout: page
title: Publications
permalink: /publications/
categories: publications
---

Merci de consulter [le serveur HAL](https://cv.archives-ouvertes.fr/gilles-bastin) pour télécharger les PDF des publications disponibles en open access.
<br><br>

---

<h3>Nouvelles publications</h3>
  <table style="width:100%;border:none;">
  {% for post in site.categories[page.categories] %}
    <tr>
      <td style="width:15%;border:none;">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      <span>{{ post.date | date: date_format }}</span>
      </td>
      <td style="border:none;">
        <a href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </td>
    </tr>
    <tr>
      <td style="width:15%;border:none;">
      </td>
      <td style="border:none;">
      {%- if site.show_excerpts -%}
        <i>{{ post.excerpt | strip_html | truncatewords:75 }}</i>
      {%- endif -%}
      </td>
    </tr>
    {% endfor %}
  </table>
<br>

---

### Liste des Publications

#### Thèses | Academic Thesis

Gilles Bastin, _Le paradoxe du paria Morphologie des mondes de l’information et _persona_ des journalistes_, Habilitation à Diriger des Recherches, garant : Pierre-Michel Menger, Ecole des Hautes Etudes en Sciences Sociales, novembre 2015.

Gilles Bastin, _Les professionnels de l’information européenne à Bruxelles. Sociologie d’un monde de l’information (territoires, carrières, dispositifs)_, Thèse de doctorat en sociologie, dir. : Catherine Paradeise, Ecole Normale Supérieure de Cachan, novembre 2003 ([tel-01385480](https://hal.archives-ouvertes.fr/tel-01385480)).

#### Livres | Books

Gilles Bastin, _Petit lexique du journalisme_, Presses Universitaires de Grenoble, 2018.

Gilles Bastin, _Grands débats des sciences économiques et sociales_, Presses Universitaires de France, 1998.

#### Articles dans des revues scientifiques | Articles

[23] Gilles Bastin et Paola Tubaro, « Le moment big data des sciences sociales ». _Revue française de sociologie_, Centre National de la Recherche Scientifique, 2018, Big data, sociétés et sciences sociales, 59 (3), pp.375-394 ([hal-01885416](https://hal.archives-ouvertes.fr/hal-01885416/)).

[22] Gilles Bastin, « Le journalisme et les sciences sociales : trouble ou problème ? », _Sur le Journalisme / On Journalism / Sobre Jornalismo_, 5(2), 2016, p. 44-63 ([hal-01525594](https://halshs.archives-ouvertes.fr/halshs-01525594v1) ; [http://surlejournalisme.com/rev/index.php/slj/article/view/256](http://surlejournalisme.com/rev/index.php/slj/article/view/256)).

[21] Gilles Bastin et Jean-Marc Francony, « L’inscription, le masque et la donnée. Datafication du web et conflits d’interprétation autour des données dans un laboratoire invisible des sciences sociales », _Revue d’Anthropologie des connaissances_, 10(4), 2016, p. 505-530 ([hal-01490598](https://halshs.archives-ouvertes.fr/halshs-01490598) ; [https://www.cairn.info/revue-anthropologie-des-connaissances-2016-4-page-505.htm](https://www.cairn.info/revue-anthropologie-des-connaissances-2016-4-page-505.htm)).

[20] Gilles Bastin, « L’approche morphologique des mondes de l’information : modèles et données pour l’analyse séquentielle de la personnalité des journalistes », _Recherches en communication_, 43, 2016 ([hal-01393518](https://halshs.archives-ouvertes.fr/halshs-01393518) ; [http://sites.uclouvain.be/rec/index.php/rec/article/view/10363/7713](http://sites.uclouvain.be/rec/index.php/rec/article/view/10363/7713)).

[19] Gilles Bastin et Antoine Machut, « Gravitation et dispersion dans les carrières des journalistes passés par la presse quotidienne nationale », _Temporalités_, 23, 2016, mis en ligne le 12 octobre 2016 ([hal-01382317](https://hal.archives-ouvertes.fr/hal-01382317v1) ; [http://temporalites.revues.org/3403](#)).

[18] Gilles Bastin, « La niche fiscale des journalistes et la morphologie des mondes de l'information », _Sur le Journalisme / On Journalism / Sobre Jornalismo_, 3(2), 2014, p. 102-115 ([hal-01330132](https://hal.archives-ouvertes.fr/halshs-01330132v1) ; [http://surlejournalisme.com/rev/index.php/slj/article/view/186/75 ](http://surlejournalisme.com/rev/index.php/slj/article/view/186/75)).

[17] Gilles Bastin et Milan Bouchet-Valat, « Media Corpora, Text Mining, and the Sociological Imagination – A Free Software Text Mining Approach to the Framing of Julian Assange by three news agencies using R.TeMiS », _Bulletin of Sociological Methodology_, 122, 2014, p. 5-25 ([hal-00969513](https://hal.archives-ouvertes.fr/halshs-00969513v1) ; [http://bms.sagepub.com/content/122/1/5.full.pdf+html](http://bms.sagepub.com/content/122/1/5.full.pdf+html)).

[16] Gilles Bastin, « Paradox of the Pariah : Toward a Weberian Understanding of Modern Journalism », _Max Weber Studies_, 13 (2), 2013, p. 216-236 ([hal-00969557](https://hal.archives-ouvertes.fr/halshs-00969557v1) ; [https://doi.org/10.15543/MWS/2013/2/6](https://doi.org/10.15543/MWS/2013/2/6)).

[15] Gilles Bastin, « The Press in the Light of Modern Capitalism : A planned survey by Max Weber on newspapers and journalism », _Max Weber Studies_, 13 (2), 2013, p. 151-175 (traduction anglaise de « La presse au miroir du capitalisme moderne », _Réseaux,_ 2001) ([hal-00969518](https://hal.archives-ouvertes.fr/halshs-00969518v1) ; [https://doi.org/10.15543/MWS/2013/2/3](https://doi.org/10.15543/MWS/2013/2/3)).

[14] Milan Bouchet-Valat & Gilles Bastin, « RcmdrPlugin.temis, a Graphical Integrated Text Mining Solution in R », _The R Journal_, 5 (1), 2013, p. 188-196 ([hal-00939504](http://hal.univ-grenoble-alpes.fr/hal-00939504) ; [https://journal.r-project.org/archive/2013-1/bouchetvalat-bastin.pdf](https://journal.r-project.org/archive/2013-1/bouchetvalat-bastin.pdf)).

[13] Gilles Bastin, « Newsworkers and their gendered careers. Findings of a longitudinal analysis of 1,171 LinkedIn profiles of French journalists », _Textual and Visual Media_, 5, p. 17-30 ([hal-00945257](https://hal.archives-ouvertes.fr/halshs-00945257v1) ; [http://textualvisualmedia.com/images/revistas/05/articles/Newsworkers.pdf](http://textualvisualmedia.com/images/revistas/05/articles/Newsworkers.pdf)).

[12] Gilles Bastin, « Le cas Mathieu ou l’entretien renversé », _Sur le Journalisme / On Journalism / Sobre Jornalismo_, 1, 2012, p. 40-51 ([hal-00738468](https://hal.archives-ouvertes.fr/halshs-00738468v1) ; [http://surlejournalisme.com/rev/index.php/slj/article/download/3/1](http://surlejournalisme.com/rev/index.php/slj/article/view/3/1)).

[11] Gilles Bastin, « The Mediatisation and Anonymisation of the World in the Work of Max Weber », _Max Weber Studies_ , vol. 9, n° 1 & 2, 2010, p. 123-141 (traduction anglaise de « Médiatisation et anonymisation du monde chez Max Weber », in H. Bruhns et P. Duran (dir.), _Max Weber et le politique_, LGDJ, 2009) ([hal-00485156](https://hal.archives-ouvertes.fr/halshs-00485156v1) ; [http://mws.quotus.org/article/MWS/2009/1-2/7](http://mws.quotus.org/article/MWS/2009/1-2/7)).

[10] Gilles Bastin, « Codes et codages professionnels dans les mondes de l’information », _Réseaux_ , 157-158, 2009, p. 192-211 ([hal-00450206](https://hal.archives-ouvertes.fr/halshs-00450206v1) ; [http://www.cairn.info/revue-reseaux-2009-5-page-191.htm](http://www.cairn.info/revue-reseaux-2009-5-page-191.htm)).

[9] Gilles Bastin, « Une exception d’irresponsabilité ? Médias et journalistes dans l’affaire d’Outreau », _Questions de communication_, 13, 2008, p. 80-107 ([hal-00332412](https://halshs.archives-ouvertes.fr/halshs-00332412v2) ; [https://questionsdecommunication.revues.org/1703](https://questionsdecommunication.revues.org/1703)).

[8] Gilles Bastin, « Weber dépasse Weber. À propos d’une nouvelle traduction de l’Ethique protestante et l’esprit du capitalisme », _Sociologie du travail_, 47(1), 2005, pp.115-124. ([hal-00008618](https://hal.archives-ouvertes.fr/halshs-00008618v1) ; [http://www.sciencedirect.com/science/article/pii/S003802960400161X](http://www.sciencedirect.com/science/article/pii/S003802960400161X)).

[7] Gilles Bastin, « Les professionnels de l’information en travailleurs de la gouvernance. Éléments d’économie politique de l’information européenne à Bruxelles depuis les années 1960 », _Regards Sociologiques_, 27-28, 2004, pp. 138-148 ([http://www.regards-sociologiques.com/index.php/2004-27-28](http://www.regards-sociologiques.com/index.php/2004-27-28)).

[6] Gilles Bastin & Pierre-Paul Zalio, « Sociologie économique début de siècle : l’impossible troisième voie entre histoire et théorie économique », _terrains & travaux_, 4, 2003([hal-01384438](https://halshs.archives-ouvertes.fr/halshs-01384438v1) ; [http://www.cairn.info/revue-terrains-et-travaux-2003-1-page-6.htm](http://www.cairn.info/revue-terrains-et-travaux-2003-1-page-6.htm)).

[5] Gilles Bastin, « Der Journalismus in der Bourdieuschen Soziologie : Ein Gegenstand, der Widerstand leistet. Einige Bemerkungen über das Feld des Journalismus » (« Le journalisme dans la sociologie bourdieusienne : un objet qui résiste. Quelques remarques sur le champ du journalisme »), _Publizistik_, 48(3), 2003 ([hal-00101367](https://halshs.archives-ouvertes.fr/halshs-00101367v1) ; [http://link.springer.com/article/10.1007/s11616-003-0075-8](http://link.springer.com/article/10.1007/s11616-003-0075-8)).

[4] Gilles Bastin, « L’Europe saisie par l’information (1952-2001) : des professionnels du journalisme engagé aux _content coordinators_. Sociologie du monde de production de l’information européenne à Bruxelles. », _Cahiers Politiques_, mai 2003 ([hal-00104213](https://halshs.archives-ouvertes.fr/halshs-00104213)).

[3] Gilles Bastin, « Traduire le travail de l’information », _terrains & travaux_, 3, 2002 ([https://www.cairn.info/revue-terrains-et-travaux-2002-1-page-92.htm](https://www.cairn.info/revue-terrains-et-travaux-2002-1-page-92.htm)).

[2] Gilles Bastin, « La presse au miroir du capitalisme moderne. Une enquête de Max Weber sur les journaux et le journalisme », _Réseaux_, 109, 2001 ([https://www.cairn.info/revue-reseaux1-2001-5-page-172.htm](https://www.cairn.info/revue-reseaux1-2001-5-page-172.htm)).

[1] Gilles Bastin et Pierre-Paul Zalio, « La sexualité, objet sociologique ordinaire ? », _terrains & travaux_, 2, 2001 ([https://www.cairn.info/revue-terrains-et-travaux-2001-1-page-3.htm](https://www.cairn.info/revue-terrains-et-travaux-2001-1-page-3.htm)).

#### Contributions | Book chapters

[12] Gilles Bastin, « Gravitation, aléa, séquence. Variations sociologiques autour du concept de carrière », in D. Demazière et M. Jouvenet (dir.), _La sociologie d’Andrew Abbott_, Presses de l’EHESS, 2016, vol. 2, pp. 195-216 ([hal-01385699](https://hal.archives-ouvertes.fr/hal-01385699v1)).

[11] Gilles Bastin, « Analyser les carrières de journalistes dans les mondes de l’information : propositions pour une enquête indirecte sur le réseau LinkedIn », in Christine Leteinturier et Cégolène Frisque (dir.), _Les espaces professionnels des journalistes. Des corpus quantitatifs aux analyses qualitatives_, Editions Panthéon-Assas, 2015, pp. 203-228 ([hal-01386990](https://hal.archives-ouvertes.fr/hal-01386990v1)).

[10] Gilles Bastin & Roselyne Ringoot, « Os livros de jornalistas : uma virada autoral no jornalismo ? » in D. Oliveira Moura et al., _Mudança e permanências do jornalismo_, Insular, 2015.

[9] Gilles Bastin, « L’entrepreneur chez Max Weber », in Pierre-Marie Chauvin, Michel Grossetti et Pierre-Paul Zalio (dir.), _Dictionnaire sociologique de l’entrepreneuriat_, Presses de Sciences Po, 2015 ([hal-01386991](https://hal.archives-ouvertes.fr/hal-01386991v1)).

[8] Gilles Bastin & Roselyne Ringoot, « Les livres de journalistes. Un tournant auctorial en journalisme ? », in Florence Le Cam et Denis Ruellan (dir.), _Changements et permanences du journalisme_, L'Harmattan, 2014, pp. 139-156 ([hal-01386352](https://hal.archives-ouvertes.fr/hal-01386352)).

[7] Gilles Bastin, « Note sur l’usage des réseaux dans les sciences sociales », in C. Bonnet, V. Krings et C. Valenti, _Connaître l’Antiquité. Individus, réseaux et stratégies du XVIIIème au XXIème siècle_, Presses Universitaires de Rennes, 2010, p. 13-27.

[6] Gilles Bastin, « Médiatisation et anonymisation du monde chez Max Weber », in H. Bruhns et P. Duran (dir.), _Max Weber et le politique_, LGDJ, 2009, p. 129-142.

[5] Gilles Bastin, « Comment on fait un ‘quote’. Coproduction et revendications de juridiction dans les mondes de l’information », in J.-B. Legavre et P. Dauvin (dir.), _Les publics des journalistes_, La Dispute, 2008, pp. 65-83 ([hal-00350120](https://hal.archives-ouvertes.fr/hal-00350120)).

[4] Gilles Bastin, « Une politique de l’information ? Le ‘système Olivi’ ou l’invention des relations de presse à la Commission européenne », in _La communication sur l’Europe, regards croisés_, CEES, 2007, pp. 125-136.

[3] Gilles Bastin, « Comment les mots viennent à Margot Wallström. Problèmes d’intermédiation de l'action publique européenne à Bruxelles dans les années 2000 », in G. de Terssac et D. Filâtre (dir.), _Les dynamiques intermédiaires au coeur de l'action publique_, Toulouse, Octarès, 2005, pp. 213-223.

[2] Gilles Bastin, « Les journalistes accrédités auprès des institutions européennes. Quelques signes du changement dans un monde de travail », in D. Georgakakis (dir.), _Les métiers de l'Europe politique. Acteurs et professionnalisations de l'Union européenne_, Strasbourg, Presses Universitaires de Strasbourg, 2002.

[1] Gilles Bastin, « Bruxelles, correspondance. Géographie économique de l’information européenne à Bruxelles », in M. Dumoulin (dir.), _Bruxelles l’européenne, regards croisés sur une région capitale_, UCL-Tempora, Bruxelles, 2001.

#### Articles dans des revues sans comité de lecture | Other articles

[3] Gilles Bastin, « Vidéogazette ou le studio magnétique de la Villeneuve », _La furia humana_, 34 (http://www.lafuriaumana.it/index.php/67-archive/lfu-34/784-gilles-bastin-videogazette-ou-le-studio-magnetique-de-la-villeneuve)


[2] Gilles Bastin, « Les deux visages du journalisme européen. Quelques remarques depuis le monde de l'information européenne à Bruxelles », _Médiamorphoses_, 12, 2004.

[1] Gilles Bastin, « Die Abrechnung », _Message_, 1, 2004.

#### Traductions | Translations

[2] Max Weber, « Rapport préliminaire pour une proposition d’enquête sur la sociologie de la presse », trad. de « Vorbericht über eine vorgeschlagene Erhebung über die Soziologie des Zeitungswesens »), _Réseaux_, 109, 2002.

[1] Hanno Hardt et Bonnie Brennen, « Travail de l’information, histoire et matériau photographique : analyse visuelle d’une salle de rédaction dans les années 1930 », trad. de « Newswork, History and Photographic Evidence : A Visual Analysis of a 1930s Newsroom », in Brennen, B. & H. Hardt (eds.), Picturing the Past : Media, History and Photography, Champaign, University of Illinois Press, 1999, 263p.], _terrains & travaux_, 3, 2002.
