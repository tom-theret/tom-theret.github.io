<div class="head_container">
  <img
    src="https://avatars.githubusercontent.com/u/33373907?v=4"
    class="logo_main"
  />
  <div class="head_title">
    <p class="head_title_1">
      Tom Theret - BTS SIO
    </p>
    <p class="head_title_2">
      Portfolio
    </p>
  </div>
</div>

Bonjour, je suis Tom Theret, acuellement en 2ème année de BTS SIO option SLAM. Ce site a pour but de présenter mes projets et mes compétences.

## Pourquoi le BTS SIO ?

J'ai choisi le BTS SIO car je suis passionné par l'informatique et que je souhaite en faire mon métier. J'ai choisi l'option SLAM car je suis plus intéressé par le développement que par l'administration ou le réseau même si ces domaines m'intéressent également.

## Stages et Atteliers de Professionnalisation

<div class="cards">
  <a href="/st1/intro" class="card">
    <span class="material-symbols-outlined">
      globe
    </span>
    <h3>Stage 1</h3>
    <p>
      Création d'un site internet pour une auto-école.
    </p>
  </a>
  <a href="/st2/intro" class="card">
    <span class="material-symbols-outlined">
      globe_uk
    </span>
    <h3>Stage 2</h3>
    <p>
      Recréation du site internet pour la même auto-école.
    </p>
  </a>
  <a href="/ap/intro" class="card">
    <span class="material-symbols-outlined">
    settings_account_box
    </span>
    <h3>AP</h3>
    <p>
      Réalisation de missions pour une entreprise fictive.
    </p>
  </a>
</div>

## Liens utiles

<div class="cards">
  <a href="assets/tabcomp.pdf" target="blank" class="card card_secondary">
    <span class="material-symbols-outlined">
      check_circle
    </span>
    <h3>Bilan de compétences</h3>
    <p>
      Consultez les compétences que j'ai acquises durant mon cursus.
    </p>
  </a>
  <a href="assets/cv.pdf" class="card card_secondary">
    <span class="material-symbols-outlined">
      assignment
    </span>
    <h3>Curruculum Vitae</h3>
    <p>
        Consultez mon CV.
    </p>
  </a>
</div>


<style>
  @import url('https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined');

  .material-symbols-outlined {
    font-family: 'Material Symbols Outlined';
    font-weight: normal;
    font-style: normal;
    font-size: 24px;  /* Preferred icon size */
    display: inline-block;
    line-height: 1;
    text-transform: none;
    letter-spacing: normal;
    word-wrap: normal;
    white-space: nowrap;
    direction: ltr;
  }

  #_1, h1 {
    visibility: hidden;
  }
  .head_container {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 16px;
    margin-bottom: 24px;
    margin-top: -78px;
  }
  .logo_main {
    width: 60px;
    height: 60px;
    border-radius: 50%;
  }
  .head_title {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }
  .head_title_1 {
    margin: 0;
    font-size: 1.3em;
    line-height: 1.2;
    font-weight: bold;
  }

  .head_title_2 {
    margin: 0;
    font-size: 1em;
    line-height: 1.2;
    opacity: 0.7;
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 16px;
  }

  .card {
    display: flex;
    flex-direction: column;
    gap: 0px;
    padding: 0px;
    border-radius: 8px;

    background-color: var(--md-admonition-bg-color);
    border: 1px solid var(--md-default-fg-color--lighter);

    text-decoration: none;
    color: var(--md-default-fg-color);

    overflow: hidden;

    box-shadow: 0px 1px 3px #00000055;
  }

  .card:hover {
    box-shadow: 0px 2px 6px #00000055;
    transform: translateY(-2px);
  }

  .card * {
    margin: 0;
    padding: 0;
    text-decoration: none;
    color: var(--md-default-fg-color);
  }

  .card .material-symbols-outlined {
    padding: 10px;
    background-color: var(--md-primary-fg-color);

    height: 80px;

    display: flex;
    align-items: center;
    justify-content: center;
    
    color: #fff;
    font-size: 40px;
  }

  .card_secondary .material-symbols-outlined {
    background-color: var(--md-default-fg-color--lightest);
    color: var(--md-admonition-fg-color);
  }

  .card h3 {
    font-size: 1.1em;
    font-weight: bold;
    text-align: left;
    margin: 12px 12px;
    padding: 0;
    margin-bottom: 8px;
  }

  .card p {
    font-size: 0.85em;
    opacity: 0.8;
    text-align: left;
    margin: 0 12px;
    padding: 0;
    margin-bottom: 12px;
  }
</style>