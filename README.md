<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chat UI Clone</title>
</head>
<body>

  <h1>💬 Chat UI Clone</h1>
  <p>
    An open-source AI chat interface inspired by modern conversational UIs.
    Built for developers who want a clean, customizable, and scalable chat experience.
  </p>

  <div style="text-align:center;">
    <img src="./public/readme/screenshot.png" alt="Chat UI Preview" width="600"/>
  </div>

  <hr/>

  <h2>🚀 Demo</h2>
  <p>
    <a href="https://x.com/mckaywrigley/status/1738273242283151777?s=20" target="_blank">
      View Live Demo
    </a>
  </p>

  <h2>✨ Features</h2>
  <ul>
    <li>⚡ Clean and responsive chat UI</li>
    <li>🔐 Secure backend integration (Supabase)</li>
    <li>🌐 Supports multiple AI providers</li>
    <li>📱 Mobile-friendly design</li>
    <li>🧩 Easy to customize and extend</li>
  </ul>

  <h2>📢 Updates</h2>
  <p>
    We are actively working on:
  </p>
  <ul>
    <li>Simpler deployment process</li>
    <li>Better backend compatibility</li>
    <li>Improved mobile responsiveness</li>
  </ul>

  <h2>🌍 Hosted Version</h2>
  <p>
    <a href="https://chatbotui.com" target="_blank">
      Use Hosted Version
    </a>
  </p>

  <h2>❤️ Support</h2>
  <p>
    <a href="https://github.com/sponsors/mckaywrigley" target="_blank">
      Sponsor the Project
    </a>
  </p>

  <h2>🐛 Issues & Support</h2>
  <ul>
    <li>Use <b>Issues</b> only for code-related bugs</li>
    <li>Use <b>Discussions</b> for questions and help</li>
    <li>Irrelevant issues may be closed</li>
  </ul>

  <h2>💬 Discussions</h2>
  <p>
    Join discussions to ask questions, share ideas, and get help from the community.
  </p>

  <h2>🧾 Legacy Version</h2>
  <p>Version 1.0 is available in the <code>legacy</code> branch.</p>

  <h2>🔄 Updating</h2>
  <pre>
npm run update
  </pre>

  <p>For hosted version:</p>
  <pre>
npm run db-push
  </pre>

  <h2>⚡ Local Setup</h2>

  <h3>1. Clone Repository</h3>
  <pre>
git clone https://github.com/mckaywrigley/chatbot-ui.git
cd chatbot-ui
  </pre>

  <h3>2. Install Dependencies</h3>
  <pre>
npm install
  </pre>

  <h3>3. Setup Supabase</h3>
  <p>Why Supabase?</p>
  <ul>
    <li>Better security</li>
    <li>PostgreSQL database</li>
    <li>Free tier available</li>
  </ul>

  <h3>4. Install Requirements</h3>
  <p>Install Docker:</p>
  <p><a href="https://docs.docker.com/get-docker" target="_blank">Download Docker</a></p>

  <p>Install Supabase CLI:</p>

  <p><b>Mac/Linux:</b></p>
  <pre>
brew install supabase/tap/supabase
  </pre>

  <p><b>Windows:</b></p>
  <pre>
scoop bucket add supabase https://github.com/supabase/scoop-bucket.git
scoop install supabase
  </pre>

  <h3>5. Start Backend</h3>
  <pre>
supabase start
  </pre>

  <h3>6. Configure Environment</h3>
  <pre>
cp .env.local.example .env.local
supabase status
  </pre>

  <h3>7. Run App</h3>
  <pre>
npm run chat
  </pre>

  <p>App: <a href="http://localhost:3000" target="_blank">http://localhost:3000</a></p>
  <p>Backend: <a href="http://localhost:54323/project/default/editor" target="_blank">Supabase Dashboard</a></p>

  <h2>☁️ Deployment</h2>

  <h3>Backend (Supabase)</h3>
  <pre>
supabase login
supabase link --project-ref &lt;project-id&gt;
supabase db push
  </pre>

  <h3>Frontend (Vercel)</h3>
  <p>Add environment variables:</p>
  <pre>
NEXT_PUBLIC_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY
SUPABASE_SERVICE_ROLE_KEY
OPENAI_API_KEY
  </pre>

  <h2>🤝 Contributing</h2>
  <p>Contributions are welcome! Guide coming soon.</p>

  <h2>📬 Contact</h2>
  <p>
    <a href="https://twitter.com/mckaywrigley" target="_blank">
      Contact on Twitter/X
    </a>
  </p>

  <hr/>

  <p><b>⭐ If you like this project, don’t forget to star it!</b></p>

</body>
</html>
