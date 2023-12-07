<template>
  <body>
    
  
    <div class="container mx-auto mt-8 fade fade-container opacity-0 rounded-md">
      <h2 class="text-4xl font-semibold mb-4 text-purple-900 text-center">Bienvenue sur mon portfolio</h2>
      <br>
      <h1 class="text-4xl font-semibold mb-4 text-green-300 text-left">Développeur front end</h1>
      <br>
      <p class="text-lg">
Je suis Léo, un passionné de développement front-end axé sur la création d'expériences web exceptionnelles.</p>
<p class="text-lg">Mon objectif est de proposer des expériences uniques à travers des interfaces utilisateur élégantes et conviviales.</p> 
<p class="text-lg">Explorez mon portfolio pour découvrir mes projets et compétences,</p> 
<p class="text-lg">avec un penchant particulier pour les technologies web modernes telles que Vue.js, React et Tailwind CSS.</p>
        <br>
        <br>
<p class="text-lg text-right">
  J'ai 22 ans , je suis une personne joyeuse, réfléchi, passionné par la tech, peu importe le domaine : audio, jeux vidéo, réalité virtuelle, entre autres. </p>
<p class="text-lg text-right">avec le sens des priorités qui sait prendre des décisions ,toujours d’humeur égal.</p> 
<p class="text-lg text-right">Passionné par la tech, peu importe le domaine : audio, jeux vidéo, réalité virtuelle, entre autres.</p>
    </div>
  </body>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style >

    body {
  @apply bg-violet-50;
}
    

  @keyframes fade-in {
    to {
      opacity: 1;
    }
  }
  
  .fade-container {
    animation: fade-in 0.5s ease-in-out forwards;
  }
  </style>