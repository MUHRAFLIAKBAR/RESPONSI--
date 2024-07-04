<template>
  <section class="about">
    <div class="container">
      <h2>CONTACT ME</h2> 
      <div class="content">
        <p>NOTING TO SEE</p>
      </div>
      <div class="social-icons">
        <a href="#" class="icon">
          <i class="fab fa-facebook"></i>
        </a>
        <a href="#" class="icon">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="#" class="icon">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 50px 0;
  background: linear-gradient(360deg, #191919, #0019f7);
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
  text-align: center;
}

h2 {
  font-size: 2.5em;
  margin-bottom: 20px;
  color: #d6d6d6;
  font-family: 'Roboto', Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; /* Mengubah jenis font */

}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

.profile-pic {
  width: 300px;
  height: 150px;
  border-radius: 15px; /* Mengatur sudut melengkung */
  object-fit: cover;
  margin-bottom: 20px;
}
p {
  font-size: 1.2em;
  line-height: 1.6;
  color: #000000;
}

.social-icons {
  margin-top: 20px;
}

.icon {
  margin: 0 10px;
  font-size: 1.5em;
  color: #faf8f8;
}

.icon:hover {
  color: #007bff;
}
</style>

<!-- Tambahkan Font Awesome untuk ikon media sosial -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
