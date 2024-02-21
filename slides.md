---
theme: default
background: false
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## VueDsfr
  Bibliothèque de composants pour les applications Vue qui doivent respecter le DSFR.

  Plus d’info à [vue-ds.fr](https://vue-ds.fr)
drawings:
  persist: false
defaults:
  foo: true
transition: slide-up
title: Welcome to Slidev
mdc: true
---

<MetallicTitle>
  VueDsfr Origins
</MetallicTitle>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/dnum-mi/vue-dsfr" target="_blank" alt="VueDsfr sur GitHub" title="VueDsfr sur GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
Les origines de VueDsfr
-->

---
transition: slide-up

---

<style>
.slidev-layout h1 {
  font-size: 1.25em;
  font-weight: bold;
  color: #fefefe !important;
}
</style>

<div class="flex  flex-col  items-center  h-full">

# Problèmes
  
  <div class="h-full">
    <ul class="h-full flex  flex-col  justify-center">
        <li v-click>Référentiels pas ou peu appliqués</li>
        <li v-click>+20 000 sites -> la qualité se diluait</li>
    </ul>
  </div>
</div>

<!--
Le développement d’applications au ministère posait quelques problèmes.

Jusqu’ici, les référentiels administratifs concernant le développement de sites web n’étaient pas ou peu appliqués.

Avec plus de 20 000 sites gérés par l’Etat, la qualité visée lors du développement d’un site Internet se diluait.
-->

---
transition: slide-up

---

<style>
.slidev-layout h1 {
  font-size: 1.25em;
  font-weight: bold;
  color: #fefefe !important;
}
</style>

<div class="flex  flex-col  items-center  h-full">

# Le DSFR
  
  <div class="h-full  flex  flex-col  space-between">
    <ul class="flex-grow  flex  flex-col  justify-center">
        <li v-click> = 2e étape de MEP de la marque État (2020)</li>
        <li v-click>composants réutilisables</li>
        <li v-click>standard obligatoire pour sites de l’État</li>
    </ul>
    <p v-click>
      Est une première partie de la solution
    </p>
  </div>
</div>

<!-- 
En tant que Système de design, le DSFR est un ensemble de composants réutilisables guidé par des standards
pouvant être assemblés pour construire des sites et applications web.

Ce système de design français ou DSFR est un standard obligatoire pour les sites de l’Etat depuis 2023.

Il marque la seconde étape de la mise en place de la marque Etat créée en 2020.
 -->

---
layout: default

---

<style>
.slidev-layout h1 {
  font-size: 1.25em;
  font-weight: bold;
  color: #fefefe !important;
}
</style>

<div class="flex  flex-col  items-center  h-full">

# Framework ?
  
  <div class="h-full  flex  flex-col  justify-center">
    <ul>
        <li v-click>structure logicielle prédéfinie et réutilisable</li>
        <li v-click>fournit une base standard</li>
        <li v-click>
          facilite le développement :
        </li>
    </ul>
    <ul class="ml-8" style="list-style: disc;">
      <li v-click>
        propose une architecture logicielle
      </li>
      <li v-click>
        propose (ou impose) des conventions
      </li>
      <li v-click>
        évite de « réinventer la roue »
      </li>
    </ul>
    <p v-click>
      +55% développeurs utilisent un framework
    </p>
  </div>
</div>

---
transition: slide-up

---

<style>
.slidev-layout h1 {
  font-size: 1.25em;
  font-weight: bold;
  color: #fefefe !important;
}
</style>

<div class="flex  flex-col  items-center  h-full">

# Vue.js
  
  <div class="h-full  flex  flex-col  justify-center">
    <ul>
        <li v-click>framework orienté composants</li>
        <li v-click>Très utilisé</li>
    </ul>
    <ul class="ml-8" style="list-style: disc;">
      <li v-click>
        Alibaba
      </li>
      <li v-click>
        Expedia
      </li>
      <li v-click>
        Netlify
      </li>
      <li v-click>
        Gitlab
      </li>
      <li v-click>
        Behance (Adobe)
      </li>
      <li v-click>
        Bien d’autres...
      </li>
    </ul>
    <p v-click>
      +43k stars
    </p>
    <p v-click>
      Très activement maintenu
    </p>
  </div>
</div>

<!-- 
Vue.js est très utilisé, depuis de nombreuses années (il existe depuis 2013)

Il est très activement maitenu.

43k stars sur GitHub, il s’agit de la v3, car le dépôt a changé entre la v2 et la v3. la v2 étant plus agée, elle avait beaucoup plus de stars. La v3 finale a été publiée en septembre 2020
 -->

---
transition: slide-up

---

<style>
.slidev-layout h1 {
  font-size: 1.25em;
  font-weight: bold;
  color: #fefefe !important;
}
</style>

<div class="flex  flex-col  items-center  h-full">

# VueDsfr
  
  <div class="h-full  flex  flex-col  justify-center">
    <ul>
        <li v-click>contient le HTML des composants DSFR</li>
        <li v-click>contient le comportement (JS) associé</li>
        <li v-click>utilise CSS du DSFR</li>
    </ul>
    <h2 v-click>
      Investissement très rentable
    </h2>
    <p v-click class="text-center">
      bibliothèque très activement maintenue
      <br>
      (50 stars, 1218 dl/semaine) :
    </p>
    <ul>
      <li v-click>
        retours utilisateurs (dont nous)
      </li>
      <li v-click>
        contributeurs
      </li>
      <li v-click>
        suit évolutions du DSFR
      </li>
      <li v-click>
        totale maîtrise par BRR
      </li>
      <li v-click>
        documentation à jour
      </li>
    </ul>
  </div>
</div>

<!-- 
VueDsfr est une bibliothèque dont le but est le portage des composants du DSFR en Vue 3.

Elle reproduit fidèlement les composants du DSFR.

Elle a été initiée par la FDR sous l’impulsion de Stanislas Ormières (qui est encore le mainteneur principal, parfois pendant son temps de travail au ministère, et souvent dans son temps libre), tout comme moi (Clément Debroize).
-->