<template>
  <div class="card">
    <img src="./assets/images/image-qr-code.png">
    <h3>Improve your front-end skills by building projects</h3>
    <h4>Scan the QR code to visit Frontend Mentor and take your coding skils to the next level</h4>
  </div>

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Steven Park</a>.
  </div>
</template>

<style lang="scss">
@use "~/assets/scss/main";

$text-header: hsl(218, 44%, 22%);
$text-accent: hsl(220, 15%, 55%);
$card-bg: hsl(0, 0%, 100%);

h3, h4 {
  text-align: center;
}

h3 {
  font-weight: 700;
  color: $text-header;
  margin-top: 25px;
  margin-bottom: 15px;
}

h4 {
  font-weight: 400;
  color: $text-accent;
  margin-bottom: 25px;
}

.card {
  background-color: $card-bg;
  width: 325px;
  margin: 15vh auto;
  padding: 15px;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  img {
    width: 100%;
    border-radius: inherit;
  }
}
</style>