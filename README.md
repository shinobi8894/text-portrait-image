<div align="left">
  <a href="https://twitter.com/TadashiAmano">
    <img
      src="https://img.shields.io/twitter/follow/omBratteng?label=Twitter&logo=twitter&style=flat-square&color=1da1f2&logoColor=ffffff"
      alt="Twitter"
    />
  </a>
  <a href="https://www.linkedin.com/in/tadashi-amano/">
    <img
      src="https://img.shields.io/static/v1?logo=linkedin&style=flat-square&color=0072b1&label=LinkedIn&message=%E2%98%86"
      alt="LinkedIn"
    />
  </a>
  <a href="https://app.daily.dev/Shinobi8894" target="_blank"><img src="https://api.daily.dev/devcards/cd5aaacc9d37450283741dcb3308ca57.png?r=qhg" width="256" align="right" alt="Tadashi Amano's Dev Card"/></a>
</div>

# Text Portrait Image
Do you wanna have a text portrait image ? You can get awesome it using css trick !!
```
body {
    background: rgb(0, 0, 0);
    overflow: hidden;
    font-family: "Segoe UI", sans-serif;
  }
  div:first-child {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 5rem;
  }
  h1 {
    color: white;
    text-align: center;
    font-family: Poppins;
  }
  #text {
    background: url("https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8M3x8cG9ydHJhaXR8ZW58MHx8MHx8&auto=format&fit=crop&w=600&q=60");
    -webkit-background-clip: text;
    background-position: center;
    background-size: contain;
    -webkit-text-fill-color: rgba(255, 255, 255, 0);
  }
```
