<template>
  <div class="container mx-auto mt-8 fade-container opacity-0 animate-fade-in">
    <h2 class="text-2xl font-semibold mb-4 text-purple-900">Contactez-moi</h2>
    <p>N'hésitez pas à me contacter si vous avez des questions, des opportunités de collaboration ou simplement pour discuter de projets intéressants.</p>
    <p>Email: leo.mandala@outlook.fr</p>
    <p>Téléphone: 06 06 90 10 54</p>

    <form
      action="https://formspree.io/f/mzblnrgb"
      method="POST"
      
    >
      <label for="name">Nom:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Envoyer</button>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@keyframes fade-in {
  to {
    opacity: 1;
  }
}

.fade-container {
  animation: fade-in 0.5s ease-in-out forwards;
}

/* Add your custom styles for the form here */
form {
  max-width: 400px;
  margin-top: 20px;
}

label {
  display: block;
  margin-bottom: 8px;
}

input,
textarea {
  width: 100%;
  padding: 8px;
  margin-bottom: 16px;
}

button {
  background-color: #4caf50;
  color: white;
  padding: 10px 15px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
</style>
