<div id="parallax-svg">
    <lottie-player src="https://assets3.lottiefiles.com/packages/lf20_GdDzHA6nWw.json" background="transparent" speed="1" loop autoplay></lottie-player>
  </div>

  <!-- Script for Parallax Effect -->
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
  <script>
    window.addEventListener('scroll', () => {
      const scrollY = window.scrollY;
      document.getElementById('parallax-svg').style.transform = `translateY(${scrollY * 0.5}px) translateX(-50%)`;
    });
  </script>
