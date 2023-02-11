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
![Annotation 2023-02-10 211330](https://user-images.githubusercontent.com/92864027/218241619-00bcb7f9-e4c6-4235-b422-a902191a55b5.png)
