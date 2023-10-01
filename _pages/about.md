---
layout: about
title: A propos
permalink: /
subtitle: Data Scientist, Musicien, Sportif, Cinéphile, Gamer, ...
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  # address: >
  #   <p>555 your office number</p>
  #   <p>123 your address street</p>
  #   <p>Your City, State 12345</p>
  address: >
    <p>8 allée Joseph Roumanille</p>
    <p>26700 Pierrelatte, France</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
Je m'appelle Augustin BAR et j'ai <span id="age">calcul en cours...</span> ans.

Après avoir vécu une période en Espagne, je suis finalement de retour à Lyon, ville dans laquelle j'ai fait la majorité de mes études, que j'apprécie particulièrement pour son dynamisme et son efervescence. Bien que j'ai vécu principalement en Rhônes-Alpes, à l'avenir, je souhaiterai déménager temporairement ou de facon permanente dans un autre pays pour rencontrer du monde. L'Espagne n'était qu'un avant goût de ce qui m'attend autre part !

Malgré mon parcours d'ingénieur informatique et data scientist, je ne me définis pas uniquement comme un scientifique, un technique ou un manager et j'ai du mal à me restreindre à un seul domaine d'activité ou à une passion. J'ai un attrait pour les sciences et la logique mais aussi des passions diversifiées pour les arts ou le sport. J'ai souvent beaucoup (trop) de projets en même temps, mais c'est ce qui me motive à continuer à apprendre et à m'améliorer !

Je n'ai pas l'intention de révolutionner le monde mais simplement de le rendre meilleur, à mon échelle, en mettant à profit mes sensibilités et mes connaissances.

Pour moi, être curieux et ouvert d'esprit est indispensable à tout être humain complet et je pense qu'il faut savoir concilier humilité et affirmation pour se forger une personnalité, des connaissances et des avis cohérents. L'écoute et le débat sont deux éléments essentiels au changement, tant qu'ils sont faits avec une intention sincère, batie de respect et d'ouverture d'esprit.

Je ne concois pas ma vie au travail, à m'épuiser à faire des heures supplémentaires à répétition. Par contre, je donnerai le meilleur de moi-même dans des projets dans lesquels j'ai foi, qui suivent mes valeurs et savent me fournir des défis stimulants. Je ne suis pas prêt à enrichir des actionnaires et des multinationnales et je sélectionnerai minutieusement les gens avec qui je veux travailler. Je préfère une vie modeste mais épanouissante plutôt qu'un salaire généreux mais qui rentre en contradiction avec ma morale.

Je serai toujours honoré de rencontrer du monde, d'apprendre des autres et aux autres. C'est pour moi inconcevable d'avancer seul.


<script>
  // Calcul de l'âge en temps réel
  function calculateAge(birthDate) {
    var today = new Date();
    var age = today.getFullYear() - birthDate.getFullYear();
    if (today.getMonth() < birthDate.getMonth() || (today.getMonth() === birthDate.getMonth() && today.getDate() < birthDate.getDate())) {
      age--;
    }
    document.getElementById('age').textContent = age;
  }
  var birthDate = new Date('1997-12-28');

  // Appeler la fonction pour calculer et afficher l'âge
  calculateAge(birthDate);
</script>



<!-- Je vis actuellement en Espagne, à Grenade, où j'ai décidé d'aller vivre quelques mois pour suivre ma copine et découvrir la culture.
Je reviendrai beintôt à lyon, ville dans laquelle j'ai fait la majorité de mes études, que j'apprécie particulièrement pour son dynamisme et son efervescence. Malgré le fait que j'ai vécu principalement en AURA, à l'avenir, je souhaite déménager temporairement ou de facon permanente dans un autre pays pour rencontrer du monde. L'espagne n'est qu'un avant goût de ce qui m'attend autre part !

Malgré mes études d'ingénieur informatique, je ne me définis pas uniquement comme un scientifique, un technique ou un manager et j'ai du mal à me restreindre à un seul domaine d'activité ou à une passion. J'ai un attrait pour les sciences et la logique mais aussi des passions diversifiées pour les arts ou le sport. J'ai souvent beaucoup (trop) de projets en même temps, mais c'est ce qui me motive à continuer à apprendre !

Je n'ai pas l'intention de révolutionner le monde mais simplement de le rendre meilleur, à mon échelle, en mettant à profit mes sensibilités et mes connaissances.

Pour moi, être curieux et ouvert d'esprit est indispensable à tout être humain complet et je pense qu'il faut savoir concilier humilité et affirmation pour se forger une personnalité, des connaissances et des avis cohérents. L'écoute et le débat sont deux éléments essentiels au changement, tant qu'ils sont faits avec une intention sincère, batie de respect et d'ouverture d'esprit.

Je ne concois pas ma vie au travail, à me détruire durant des heures supplémentaires. Par contre, je donnerai le meilleur de moi-même dans des projets dans lesquels j'ai foi, qui suivent mes valeurs et savent me fournir des défis stimulants. Je ne suis pas prêt à enrichir des actionnaires et des multinationnales et je sélectionnerai minutieusement les gens avec qui je veux travailler. Je préfère une vie modeste mais épanouissante plutôt qu'un salaire généreux mais qui rentre en contradiction avec ma morale.

Je serai toujours honoré de rencontrer du monde, d'apprendre des autres et aux autes. C'est pour moi inconcevable d'avancer seul. -->


<!-- Je m'appelle Augustin BAR et j'ai 25 ans.

J'habite actuellement à Lyon, ville dans laquelle j'ai décidé de m'installer quelques années pour profiter de son dynamisme. J'ai vécu dans plusieurs autres villes de la région Rhônes-Alpes durant mes études, et à l'avenir, j'envisage de déménager à l'étranger pour profiter du monde.
Malgré mes études d'ingénieur informatique, je ne me définis pas uniquement comme un scientifique ou un technique et j'ai du mal à me restreindre à un seul domaine d'activité ou à une passion. J'ai un fort attrait pour les sciences et la logique mais cela ne m'empêche pas de me passionner pour le cinéma, le piano ou le sport.
Je n'ai pas l'intention de révolutionner le monde mais simplement de le rendre meilleur, à mon échelle, en mettant à profit mes sensibilités et mes connaissances.

Pour moi, être curieux et ouvert d'esprit est indispensable à tout être humain complet et je pense qu'il faut savoir concilier humilité et affirmation pour se forger une personnalité, des connaissances et des avis cohérents. L'écoute et le débat sont deux éléments essentiels au changement, tant qu'ils sont faits avec une intention sincère, batie de respect et d'ouverture d'esprit.

Je ne concois pas ma vie au travail, à me détruire durant des heures supplémentaires. Par contre, je donnerai le meilleur de moi-même dans des projets dans lesquels j'ai foi, qui suivent mes valeurs et savent me fournir des défis stimulants. Je préfère une vie modeste mais épanouissante plutôt qu'un salaire généreux mais qui rentre en contradiction avec ma morale.

Je serai toujours honoré de rencontrer du monde et de partager nos connaissances, c'est pour moi inconcevable d'avancer seul. -->

<!-- Y biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
