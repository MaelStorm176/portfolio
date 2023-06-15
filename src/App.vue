<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <main class="items-center" style="width: 100%">
    <section title="About me" style="width:25%">
      <div class="window">
        <div class="title-bar">
          <button aria-label="Close" class="close"></button>
          <h1 class="title">Maël JAMIN</h1>
          <button aria-label="Resize" class="resize"></button>
        </div>
        <div class="details-bar">
          <span>Fullstack</span>
          <span>Web</span>
          <span>Developer</span>
        </div>


        <div class="window-pane">
          <div class="items-center">
            <img
                src="/profile-picture.jpg"
                alt="Maël JAMIN"
                class="window-image profile-picture"
            />
          </div>
          <div class="window-pane-title">About me</div>
          <div class="window-pane-content">
            <p>
              I'm a 20 years old student in computer science at the University of Nantes.
              I'm currently looking for an internship in web development.
            </p>
            <p>
              I'm passionate about web development and I'm always looking for new technologies to learn.
              I'm also interested in new technologies in general.
            </p>
          </div>
        </div>
        <div class="separator"></div>
        <div class="window-pane">
          <div class="window-pane-title">Social Networks</div>
          <div class="window-pane-content flex gap-10">
            <a href="https://www.linkedin.com/in/mael-jamin-0b1b0b1b0/" target="_blank">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" height="48" width="48"><title>logo-linkedin</title><g><rect x="30.47" y="3.05" width="1.53" height="25.9" fill="#000000"></rect><rect x="28.95" y="28.95" width="1.52" height="1.53" fill="#000000"></rect><rect x="28.95" y="1.52" width="1.52" height="1.53" fill="#000000"></rect><rect x="27.42" y="4.57" width="1.53" height="22.86" fill="#000000"></rect><rect x="3.04" y="30.48" width="25.91" height="1.52" fill="#000000"></rect><rect x="4.57" y="27.43" width="22.85" height="1.52" fill="#000000"></rect><polygon points="22.85 15.24 21.33 15.24 21.33 13.71 18.28 13.71 18.28 15.24 16.76 15.24 16.76 13.71 13.71 13.71 13.71 22.86 16.76 22.86 16.76 18.29 18.28 18.29 18.28 16.76 19.81 16.76 19.81 18.29 21.33 18.29 21.33 22.86 24.38 22.86 24.38 16.76 22.85 16.76 22.85 15.24" fill="#000000"></polygon><rect x="7.61" y="13.71" width="3.05" height="9.15" fill="#000000"></rect><rect x="7.61" y="9.14" width="3.05" height="3.05" fill="#000000"></rect><rect x="4.57" y="3.05" width="22.85" height="1.52" fill="#000000"></rect><rect x="3.04" width="25.91" height="1.52" fill="#000000"></rect><rect x="3.04" y="4.57" width="1.53" height="22.86" fill="#000000"></rect><rect x="1.52" y="28.95" width="1.52" height="1.53" fill="#000000"></rect><rect x="1.52" y="1.52" width="1.52" height="1.53" fill="#000000"></rect><rect y="3.05" width="1.52" height="25.9" fill="#000000"></rect></g></svg>
            </a>
            <a href="">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" height="48" width="48"><title>logo-social-media-old-instagram</title><g><polygon points="30.47 3.05 30.47 10.67 19.81 10.67 19.81 12.19 21.33 12.19 21.33 13.71 22.85 13.71 22.85 12.19 30.47 12.19 30.47 28.95 32 28.95 32 3.05 30.47 3.05" fill="#000000"></polygon><rect x="28.95" y="28.95" width="1.52" height="1.53" fill="#000000"></rect><rect x="28.95" y="1.52" width="1.52" height="1.53" fill="#000000"></rect><rect x="3.04" y="30.48" width="25.91" height="1.52" fill="#000000"></rect><rect x="25.9" y="4.57" width="1.52" height="3.05" fill="#000000"></rect><rect x="22.85" y="3.05" width="3.05" height="1.52" fill="#000000"></rect><rect x="22.85" y="13.71" width="1.53" height="7.62" fill="#000000"></rect><rect x="22.85" y="7.62" width="3.05" height="1.52" fill="#000000"></rect><rect x="21.33" y="21.33" width="1.52" height="1.53" fill="#000000"></rect><rect x="21.33" y="4.57" width="1.52" height="3.05" fill="#000000"></rect><rect x="19.81" y="22.86" width="1.52" height="1.52" fill="#000000"></rect><path d="M12.19,15.24H10.66v4.57h1.53v1.52h1.52v1.53h4.57V21.33h1.53V19.81h1.52V15.24H19.81V13.71H18.28V12.19H13.71v1.52H12.19Zm3.04,0h3.05v3.05H16.76V16.76H15.23Z" fill="#000000"></path><rect x="12.19" y="9.14" width="7.62" height="1.53" fill="#000000"></rect><rect x="12.19" y="24.38" width="7.62" height="1.52" fill="#000000"></rect><rect x="10.66" y="22.86" width="1.53" height="1.52" fill="#000000"></rect><rect x="9.14" y="21.33" width="1.52" height="1.53" fill="#000000"></rect><rect x="7.61" y="13.71" width="1.53" height="7.62" fill="#000000"></rect><rect x="1.52" y="28.95" width="1.52" height="1.53" fill="#000000"></rect><path d="M1.52,12.19H3.04v1.52H7.61V12.19H9.14v1.52h1.52V12.19h1.53V10.67H10.66V1.52H28.95V0H3.04V1.52H1.52V3.05H3.04v7.62H1.52V3.05H0v25.9H1.52ZM7.61,1.52H9.14v9.15H7.61Zm-3.04,0H6.09v9.15H4.57Z" fill="#000000"></path></g></svg>
            </a>
            <a href="">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" height="48" width="48"><title>logo-social-media-facebook-circle</title><polygon points="30.47 9.905 28.95 9.905 28.95 6.855 27.42 6.855 27.42 5.335 25.9 5.335 25.9 3.805 22.85 3.805 22.85 2.285 19.81 2.285 19.81 0.765 12.19 0.765 12.19 2.285 9.14 2.285 9.14 3.805 6.09 3.805 6.09 5.335 4.57 5.335 4.57 6.855 3.04 6.855 3.04 9.905 1.52 9.905 1.52 12.955 0 12.955 0 20.565 1.52 20.565 1.52 23.615 3.04 23.615 3.04 26.665 4.57 26.665 4.57 28.185 6.09 28.185 6.09 29.715 9.14 29.715 9.14 31.235 13.71 31.235 13.71 20.565 9.14 20.565 9.14 15.995 13.71 15.995 13.71 9.905 15.23 9.905 15.23 8.375 22.85 8.375 22.85 12.955 18.28 12.955 18.28 15.995 24.38 15.995 24.38 17.525 22.85 17.525 22.85 19.045 21.33 19.045 21.33 20.565 18.28 20.565 18.28 31.235 22.85 31.235 22.85 29.715 25.9 29.715 25.9 28.185 27.42 28.185 27.42 26.665 28.95 26.665 28.95 23.615 30.47 23.615 30.47 20.565 32 20.565 32 12.955 30.47 12.955 30.47 9.905" fill="#000000"></polygon></svg>
            </a>
          </div>
        </div>
        <div class="separator"></div>
      </div>


      <div class="window">
        <div class="title-bar">
          <button aria-label="Close" class="close"></button>
          <h1 class="title">Search</h1>
          <button aria-label="Resize" disabled class="hidden"></button>
        </div>
        <div class="separator"></div>

        <div class="modeless-dialog">
          <section class="field-row" style="justify-content: flex-start">
            <label for="text_find" class="modeless-text">Find:</label>
            <input id="text_find" type="text" style="width:100%;" placeholder="">
          </section>
          <section class="field-row" style="justify-content: flex-end">
            <button class="btn">Cancel</button>
            <button class="btn" style="width:95px;">Find</button>
          </section>
        </div>
      </div>


    </section>

    <section title="Details" style="width: 75%">
      <div class="standard-dialog">
        <p class="heading center">Maël Jamin</p>
        <p class="desc center">I design and code beautifully simple things and i love what i do. Just simple like that!</p>
        <div class="separator"></div>
        <div>
          <h2 class="subheading">Intro</h2>
          <p>I'm a 20 years old student in computer science at the University of Nantes. I'm currently looking for an internship in web development.</p>
          <p>I'm passionate about web development and I'm always looking for new technologies to learn. I'm also interested in new technologies in general.</p>
        </div>
        <div>
          <h2 class="subheading">Education & Experience</h2>
          
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped>

</style>
