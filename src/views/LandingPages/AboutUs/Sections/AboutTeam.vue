<script setup>
// example component
import HorizontalTeamCard from "@/examples/cards/teamCards/HorizontalTeamCard.vue";

// images
import emma from "@/assets/img/team-5.jpg";
import william from "@/assets/img/bruce-mars.jpg";
import ivana from "@/assets/img/ivana-squares.jpg";
import marquez from "@/assets/img/ivana-square.jpg";
</script>

<template>
  <section class="pb-5 position-relative mx-n3">
    <div class="container">
      <div class="related-articles-text"><div class="user-content" dir="auto"><h2 class="display-5">Nos principales catégories</h2>
<p class="lead">Trouvez ce qu'il vous faut chez nous</p>
</div></div>
      <div class="related-articles-content">
        <div class="article">
          <div class="article-container"><img
              src="//images.ctfassets.net/n6bd9fnkwjgt/4jTN2hEJvUALsyQEIVhTEy/d55a1f392794d452f8e27120c20434c9/spacejoy-q3Qd86sfaoU-unsplash.jpg?fit=fill&amp;w=530&amp;h=530&amp;q=85"
              loading="lazy" class="article-img">
            <div class="article-text">
              <h3 class="heading" dir="auto">Guide du premier achat immobilier</h3><a class="link stretched-link"
              href="/guides-et-conseils-immobiliers/guide-du-premier-achat-immobilier"></a>
          </div>
        </div>
      </div>
      <div class="article">
        <div class="article-container"><img
            src="//images.ctfassets.net/n6bd9fnkwjgt/HIJju1jK7d2Ss9UY8NeY9/5a1b1e8fc99cee2a599e6a2b124b6475/Guide_Vendeur_-_Background.png?fit=fill&amp;w=530&amp;h=530&amp;q=85"
            loading="lazy" class="article-img">
          <div class="article-text">
            <h3 class="heading" dir="auto">Le guide du vendeur</h3><a class="link stretched-link"
              href="/guides-et-conseils-immobiliers/guide-vendeur"></a>
          </div>
        </div>
      </div>
      <div class="article">
        <div class="article-container"><img
            src="//images.ctfassets.net/n6bd9fnkwjgt/4YE2sYUJEwut7IaqE0QhxH/f023c63f3230e6dfc3b755b5b8abd621/Guide_de_l-investissement_locatif.jpg?fit=fill&amp;w=530&amp;h=530&amp;q=85"
            loading="lazy" class="article-img">
          <div class="article-text">
            <h3 class="heading" dir="auto">Guide de l'investissement locatif</h3><a class="link stretched-link"
              href="/guides-et-conseils-immobiliers/guide-de-l-investissement-locatif"></a>
          </div>
        </div>
      </div>
      <div class="article">
        <div class="article-container"><img
            src="//images.ctfassets.net/n6bd9fnkwjgt/1NnUPK7yPKcpZA7vNHQkpb/c8fca4a8068c877bfc6c084c425d756c/Untitled_design.png?fit=fill&amp;w=530&amp;h=530&amp;q=85"
            loading="lazy" class="article-img">
          <div class="article-text">
            <h3 class="heading" dir="auto">Le guide de la rénovation immobilière</h3><a class="link stretched-link"
              href="/guides-et-conseils-immobiliers/guide-de-la-renovation-immobiliere"></a>
          </div>
        </div>
      </div>
    </div>

  </div>
</section></template>
<style>
.related-articles-content {
  flex-direction: row;
    flex-wrap: wrap;
    display: flex;
}
.related-articles-content .article{
  width: 25%;
  padding: 0 20px;
}
.article-container{
  max-height: 100%;
  height: 100%;
}
.article-container img{
  width: 100%;
  border-radius: 20px;
}
</style>