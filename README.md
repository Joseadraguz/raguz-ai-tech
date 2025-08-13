<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Raguz AI</title>
<style>
  body {
    margin: 0;
    font-family: 'Orbitron', sans-serif;
    background-color: #0a0a0a;
    color: #fff;
    overflow-x: hidden;
  }
  .hero {
    position: relative;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    background: url('IMAGE_URL_HERE') no-repeat center/cover;
  }
  .overlay {
    position: absolute;
    inset: 0;
    background: rgba(0,0,0,0.5);
  }
  .content {
    position: relative;
    z-index: 1;
    max-width: 80%;
  }
  h1 {
    font-size: 3rem;
    text-shadow: 0 0 20px #0ff, 0 0 40px #0ff;
    animation: glow 2s infinite alternate;
  }
  @keyframes glow {
    from { text-shadow: 0 0 20px #0ff, 0 0 40px #0ff; }
    to { text-shadow: 0 0 30px #ff00ff, 0 0 60px #ff00ff; }
  }
  p {
    font-size: 1.2rem;
    color: #ccc;
    margin-top: 1rem;
  }
</style>
</head>
<body>

<div class="hero">
  <div class="overlay"></div>
  <div class="content">
    <h1>Raguz AI — Where Code Breathes & The Future Listens</h1>
    <p>Step into the neon future of intelligence.</p>
  </div>
</div>

</body>
</html>
