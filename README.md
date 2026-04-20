<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Edmar Magbanua | Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <style>
    /* Reset and base styles */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { line-height: 1.6; color: #333; background: #f9f9f9; scroll-behavior: smooth; }
    a { text-decoration: none; color: #0077ff; }
    a:hover { text-decoration: underline; }

    /* Header / Nav */
    header { background: #1a1a1a; color: #fff; padding: 1rem 0; position: sticky; top: 0; z-index: 1000; }
    nav { display: flex; justify-content: space-between; align-items: center; width: 90%; margin: auto; }
    nav h1 { font-size: 1.8rem; letter-spacing: 1px; }
    nav ul { list-style: none; display: flex; gap: 2rem; }
    nav ul li a { color: #fff; font-weight: 500; transition: 0.3s; }
    nav ul li a:hover { color: #00d1ff; }

    /* Sections */
    .section { padding: 4rem 1rem; text-align: center; }
    h2 { font-size: 2rem; margin-bottom: 1rem; color: #1a1a1a; }

    /* About */
    .profile { width: 150px; height: 150px; border-radius: 50%; object-fit: cover; margin-bottom: 1rem; border: 3px solid #0077ff; }

    /* Video */
    .video iframe { border-radius: 10px; }

    /* Projects */
    .cards { display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin-top: 2rem; }
    .card { background: #fff; padding: 1.5rem; width: 250px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s; }
    .card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.15); }
    .card h3 { margin-bottom: 0.5rem; color: #0077ff; }

    /* Contact */
    #contact a { color: #0077ff; font-weight: 500; }

    /* Footer */
    footer { background: #1a1a1a; color: #fff; padding: 1rem 0; text-align: center; font-size: 0.9rem; }

    /* Responsive */
    @media (max-width: 768px) {
      .cards { flex-direction: column; align-items: center; }
      nav ul { flex-direction: column; gap: 1rem; margin-top: 1rem; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <nav>
      <h1>Edmar Magbanua</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- About -->
  <section id="about" class="section">
    <img src="/Gemini_Generated_Image_rlrctrlrctrlrctr.png" alt="Edmar Photo" class="profile">
    <h2>Hello, I'm Edmar 👋</h2>
    <p>BSIT Student passionate about web development, UI/UX design, and emerging technologies. I love creating clean and functional digital experiences.</p>
  </section>

<!-- Video Section -->
<section class="section">
  <h2>My Mood 🎬</h2>

  <div class="video-container">
    <iframe 
      src="https://www.youtube.com/embed/MGRm4IzK1SQ"
      title="YouTube video"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>

</section>

<style>
.video-container {
  position: relative;
  width: 100%;
  max-width: 800px;
  margin: auto;
  aspect-ratio: 16 / 9;
}

.video-container iframe {
  width: 100%;
  height: 100%;
  border: none;
  border-radius: 12px;
}
</style>
    </div>
  </section>

  <!-- Projects -->
<!-- Projects -->
<!-- Projects -->
<section id="projects" class="section">
  <h2>My Projects 💻</h2>
  <div class="cards">

    <!-- UI Design (Figma) -->
    <div class="card">
      <h3>UI Design Project</h3>
      <p>
        Crafted sleek user interfaces and interactive prototypes using 
        <a href="https://www.figma.com/proto/DnWfcQfuA3DE6at1UtmNZ9/edmar" target="_blank">
          Figma
        </a>.
      </p>
      <a href="https://www.figma.com/proto/DnWfcQfuA3DE6at1UtmNZ9/edmar" target="_blank" class="btn">
        View Project
      </a>
    </div>

    <!-- Canva Design -->
    <div class="card">
      <h3>Graphic Design (Canva)</h3>
      <p>
        Designed creative social media graphics, posters, and branding materials using Canva.
      </p>
      <a href="https://www.canva.com/design/DAFxxxxxxx/view" target="_blank" class="btn">
        View Designs
      </a>
    </div>

    <!-- Resume -->
    <div class="card">
      <h3>Resume</h3>
      <p>
        Created a modern and professional resume showcasing skills, education, and experience.
      </p>
      <a href="https://sg.docworkspace.com/d/sbCaii4zdr5Vknzb_2bwp6zk1a3stufktuz?sa=601.1074" target="_blank" class="btn">
        View Resume
      </a>
    </div>
    <!-- Resume -->
    <div class="card">
      <h3>Portfolio</h3>
      <p>
        Created a modern and professional resume showcasing skills, education, and experience.
      </p>
      <a href="https://canva.link/a9dayfjxw7mj06n" target="_blank" class="btn">
        View Portfolio
      </a>
    </div>
  </div>
</section>
<
  </p>
</div>
  </div>
</section>
</script>
<!-- CHATBOT -->
<div id="chat-toggle">💬</div>

<div id="chatbot">
  <div id="chat-header">Edmar Bot 🤖</div>
  <div id="chat-box"></div>

  <div id="chat-input">
    <input type="text" id="userInput" placeholder="Ask about me..." onkeypress="handleKey(event)">
    <button onclick="sendMessage()">Send</button>
  </div>
</div>

<style>
#chat-toggle {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #0077ff;
  color: white;
  padding: 15px;
  border-radius: 50%;
  cursor: pointer;
}

#chatbot {
  position: fixed;
  bottom: 80px;
  right: 20px;
  width: 300px;
  background: white;
  border-radius: 10px;
  box-shadow: 0 5px 20px rgba(0,0,0,0.3);
  display: none;
  flex-direction: column;
}

#chat-header {
  background: #0077ff;
  color: white;
  padding: 10px;
  text-align: center;
}

#chat-box {
  height: 250px;
  overflow-y: auto;
  padding: 10px;
}

.msg {
  margin: 5px;
  padding: 8px;
  border-radius: 8px;
}

.user {
  background: #0077ff;
  color: white;
  text-align: right;
}

.bot {
  background: #eee;
}

#chat-input {
  display: flex;
}

#chat-input input {
  flex: 1;
  padding: 10px;
  border: none;
}

#chat-input button {
  padding: 10px;
  background: #0077ff;
  color: white;
  border: none;
}
</style>

<script>
// Toggle chatbot
document.getElementById("chat-toggle").onclick = () => {
  let bot = document.getElementById("chatbot");
  bot.style.display = bot.style.display === "flex" ? "none" : "flex";
};

// Enter key
function handleKey(e) {
  if (e.key === "Enter") sendMessage();
}

// Send message
function sendMessage() {
  let input = document.getElementById("userInput");
  let text = input.value.trim();
  if (!text) return;

  addMessage(text, "user");
  input.value = "";

  setTimeout(() => {
    addMessage(getReply(text), "bot");
  }, 500);
}

// Add message
function addMessage(text, sender) {
  let box = document.getElementById("chat-box");
  let msg = document.createElement("div");
  msg.className = "msg " + sender;
  msg.innerText = text;
  box.appendChild(msg);
  box.scrollTop = box.scrollHeight;
}

// Custom replies (ABOUT YOU)
function getReply(input) {
  input = input.toLowerCase();

  if (input.includes("hello") || input.includes("hi"))
    return "Hi! Welcome to Edmar's portfolio 👋";

  if (input.includes("who are you"))
    return "I'm Edmar's chatbot assistant 🤖";

  if (input.includes("about"))
    return "Edmar is a BSIT student passionate about web development and design.";

  if (input.includes("projects"))
    return "You can check Edmar's projects above in the Projects section 💻";

  if (input.includes("contact"))
    return "Check the Contact section to reach Edmar 📩";

  if (input.includes("skills"))
    return "Skills: HTML, CSS, JavaScript, UI/UX Design.";

  if (input.includes("bye"))
    return "Thanks for visiting! 👋";

  return "Try asking about Edmar, his projects, or contact info 😊";
}
</script>
</body>
</html>

<!-- Contact -->
<section id="contact" class="section">
  <h2>Contact Me 📩</h2>

  <p>Gmail: 
    <a href="mailto:magbanuaedmar240@gmail.com">
      magbanuaedmar240@gmail.com
    </a>
  </p>

  <p>Contact No.: 
    <a href="tel:+6397979940">
      +6397979940
    </a>
  </p>

  <p>Facebook: 
    <a href="https://facebook.com/edmar.pasquil.magbanua" target="_blank">
      My Profile
    </a>
  </p>

  <p>Instagram: 
    <a href="https://instagram.com/@Edmar12" target="_blank">
      @Edmar12
    </a>
  </p>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 Edmar Magbanua | All Rights Reserved</p>
</footer>

</body>
</html>
  
