# Le Modèle des Espèces Non Vues Appliqué à la Littérature Chevaleresque Ibérique

## Description
Ce dépôt contient le travail effectué dans le cadre du mémoire de Master en Humanités Numériques, intitulé "Le modèle des espèces non vues appliqué à la littérature chevaleresque dans la Péninsule Ibérique". Ce projet explore des méthodes quantitatives et computationnelles pour estimer la richesse et la diversité des textes médiévaux en utilisant des modèles statistiques.

Mon projet de recherche a été inspiré par l'article ["Forgotten Books: The Application of Unseen Species Models to the Survival of Culture"](https://github.com/mikekestemont/forgotten-books) de [Mike Kestemont](https://mikekestemont.github.io/) et [Folgert Karsdorp](https://www.karsdorp.io/) (et *al.*), publié dans la revue [Science](https://www.science.org/doi/10.1126/science.abl7655) en 2022. Cet article présente les résultats d'une vaste étude menée par une équipe de chercheurs sur la littérature épique et chevaleresque dans six langues différentes.
Les auteurs sont partis d’un constat :  parmi la richesse des artefacts culturels originellement existants, seule une infime partie d’entre eux est parvenus jusqu’à nos jours. C’est là qui réside la problématique essentielle de ce travail de recerche : comment faire donc pour estimer ce qui ne nous est pas parvenu jusqu'à aujourd'hui ? 
 C’est ainsi, afin de pourvoir estimer quantitativement les pertes subies dans le domaine de la littérature médiévale que les auteurs vont proposer l’application d’un modèle statistique à un ensemble de données.
La variété et la quantité de la production culturelle dans les civilisations du passé sont fréquemment sous-estimées, un phénomène que les auteurs définissent comme le biais de sous-estimation. C’est dans le but de corrigerce biais et d'estimer ces pertes que le modèle des espèces non observées sera appliqué.
Les auteurs reprennent ce modele statistique, emprunté de l’écologie, et plus spécifiquement du domaine de la biodiversité, et établissent une analogie très intéressante entre deux mondes, à première vue, distants.
Les auteurs considèrent, dans le cadre de ces recherches, que les œuvres littéraires peuvent être envisagées comme le sont les espèces en écologie et les copies d’un manuscrit, comme le repérage de ces mêmes espèces. De cette façon, le même modèle pourra être appliqué afin d’estimer les pertes. Pour ce faire, les auteurs utilisent l’estimateur Chao1, nommé d’après la biostatisticienne [Anne Chao](https://sites.google.com/view/chao-lab-website/brief-cv). Chao1 va estimer combien d’espèces n’ont pas été observées, tenant compte du nombre d’espèces qui n’ont été que rarement observées.

Ainsi, les espèces (ou œuvres) qui existent dans l'ensemble mais n'ont pas été observées – désignées par $f0$ – peuvent faire l'objet d'un calcul. Ce calcul se base sur le nombre d'espèces repérées une seule fois (les singletons) et le nombre d'espèces repérées deux fois (les doubletons) dans un ensemble de taille $n$. À ce calcul, on ajoute les œuvres uniques repérées dans un ensemble de $n$ documents, notées $fSobs$, afin de calculer la richesse originelle des œuvres. En utilisant cet estimateur, les auteurs pourront obtenir deux types de résultats dans leurs recherches : ils seront en mesure non seulement de calculer les espèces (ou dans ce cas, les œuvres littéraires) qui n'ont pas été observées, mais aussi de mesurer de manière significative la richesse originelle d'une population, soit ici celle des œuvres littéraires.

**Principales sources su corpus**

Voici quelques-unes des sources bibliographiques principales que nous avons utilisé pour l'élaboration de ce *corpus* : 

- [Philobiblon](https://bancroft.berkeley.edu/philobiblon/)
- [Universo de Almourol](https://parnaseo.uv.es/UniversoDeAlmourol/)
- [Iberian Books](https://iberian.ucd.ie/view/iberian:13094)
- [Catalogue of Medieval Works Printed in Castilian](https://comedic.unizar.es/)
- [SMELPS](https://smelps.wixsite.com/smelpsarturiano)
- [Corpus of Hispanic Chivalric Romances](https://textred.spanport.wisc.edu/chivalric/index.html)
- [Amadis. Base de datos de literatura caballeresca](https://clarisel.unizar.es/paginas/index.php?base=amadis&opcion=presentacion)
- [Universal Short Title Catalogue ](https://ustc.ac.uk/)
- [Bibliografía de los libros de caballerías castellanos](https://www.cervantesvirtual.com/obra/bibliografia-de-los-libros-de-caballeria-castellanos/)
- [Antología de libros de caballerías castellanos](https://www.cervantesvirtual.com/obra/antologia-de-libros-de-caballerias-castellanos/)
- [Diccionario filológico de literatura medieval española](https://dialnet.unirioja.es/servlet/libro?codigo=267414)
- [Guía para o estudo da prosa galega medieval](https://cirp.gal/publicacions/pub-0511.html)
- [Literatura caballeresca catalana: de los testimonios a la interpretación (un ensayo de crítica ecdótica) ](https://dialnet.unirioja.es/servlet/articulo?codigo=2371582)
- [Compendio bibliográfico sobre la narrativa caballeresca breve](https://www.cervantesvirtual.com/obra/compendio-bibliografico-sobre-la-narrativa-caballeresca-breve/)
- [A literatura cavaleiresca portuguesa: estado da questão](https://www.academia.edu/7984490/A_literatura_cavaleiresca_portuguesa_estado_da_arte)
- [Los libros de caballerías portugueses manuscritos](https://produccioncientifica.ucm.es/documentos/5f9e0d0f29995246493cdcc0)
- [Portal Arturiana](https://arturiana.es/inicio.html)


## Contenu
- **/report/** : Documentation et mémoire PDF.
- **/data/** : Textes médiévaux utilisés pour les analyses.
- **/notebooks/** : Scripts pour modéliser les espèces non vues.
- **/outputs/** : Résultats et visualisations.
  
## Instructions
Pour exécuter les scripts, veuillez installer les dépendances listées dans `requirements.txt`. Exécutez les notebooks dans `/notebooks/` pour répliquer les analyses.

## Contributions
Les contributions sont les bienvenues, en particulier pour l'ajout de nouveaux textes au corpus.

## Auteurs
- [Carolina Macedo](https://sorbonne.academia.edu/CarolinaMacedo)

**License**

 Creative Commons Attribution-- NonCommercial-ShareAlike 4.0 International License.


