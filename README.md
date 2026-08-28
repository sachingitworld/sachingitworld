<!--
  LIQUID GLASS PROFILE
  A futuristic glass-morphism GitHub profile README
  Designed to work within GitHub's Markdown rendering restrictions
-->

<div align="center">

<!-- GLASS HERO SECTION -->
<table width="100%" style="background: transparent; border: none;">
  <tr>
    <td align="center" style="padding: 40px 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.03);
        backdrop-filter: blur(20px);
        -webkit-backdrop-filter: blur(20px);
        border: 1px solid rgba(255, 255, 255, 0.08);
        border-radius: 40px;
        padding: 60px 40px 50px;
        margin: 20px auto;
        max-width: 900px;
        position: relative;
        overflow: hidden;
        box-shadow: 
          0 8px 32px rgba(0, 0, 0, 0.4),
          inset 0 1px 0 rgba(255, 255, 255, 0.05);
      ">
        <!-- Animated gradient background -->
        <svg width="100%" height="100%" style="position: absolute; top: 0; left: 0; pointer-events: none; z-index: 0; opacity: 0.4;">
          <defs>
            <linearGradient id="heroGlow" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" style="stop-color:#6C63FF;stop-opacity:0.3">
                <animate attributeName="offset" values="0%;100%" dur="12s" repeatCount="indefinite"/>
              </stop>
              <stop offset="50%" style="stop-color:#FF6584;stop-opacity:0.15">
                <animate attributeName="offset" values="50%;150%" dur="12s" repeatCount="indefinite"/>
              </stop>
              <stop offset="100%" style="stop-color:#00D4FF;stop-opacity:0.2">
                <animate attributeName="offset" values="100%;200%" dur="12s" repeatCount="indefinite"/>
              </stop>
            </linearGradient>
            <radialGradient id="liquidBlob1" cx="30%" cy="40%" r="60%">
              <stop offset="0%" style="stop-color:#6C63FF;stop-opacity:0.15">
                <animate attributeName="cx" values="30%;70%;30%" dur="20s" repeatCount="indefinite"/>
                <animate attributeName="cy" values="40%;60%;40%" dur="20s" repeatCount="indefinite"/>
              </stop>
              <stop offset="100%" style="stop-color:#6C63FF;stop-opacity:0"/>
            </radialGradient>
            <radialGradient id="liquidBlob2" cx="70%" cy="60%" r="50%">
              <stop offset="0%" style="stop-color:#FF6584;stop-opacity:0.1">
                <animate attributeName="cx" values="70%;30%;70%" dur="25s" repeatCount="indefinite"/>
                <animate attributeName="cy" values="60%;40%;60%" dur="25s" repeatCount="indefinite"/>
              </stop>
              <stop offset="100%" style="stop-color:#FF6584;stop-opacity:0"/>
            </radialGradient>
          </defs>
          <rect width="100%" height="100%" fill="url(#heroGlow)"/>
          <circle cx="30%" cy="40%" r="300" fill="url(#liquidBlob1)"/>
          <circle cx="70%" cy="60%" r="250" fill="url(#liquidBlob2)"/>
        </svg>

        <!-- Floating particles -->
        <svg width="100%" height="100%" style="position: absolute; top: 0; left: 0; pointer-events: none; z-index: 1; opacity: 0.3;">
          <circle cx="20%" cy="30%" r="3" fill="#6C63FF">
            <animate attributeName="cy" values="30%;70%;30%" dur="15s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.3;0.8;0.3" dur="15s" repeatCount="indefinite"/>
          </circle>
          <circle cx="80%" cy="50%" r="2" fill="#00D4FF">
            <animate attributeName="cy" values="50%;20%;50%" dur="18s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.2;0.7;0.2" dur="18s" repeatCount="indefinite"/>
          </circle>
          <circle cx="50%" cy="80%" r="2.5" fill="#FF6584">
            <animate attributeName="cy" values="80%;40%;80%" dur="22s" repeatCount="indefinite"/>
            <animate attributeName="opacity" values="0.2;0.6;0.2" dur="22s" repeatCount="indefinite"/>
          </circle>
          <circle cx="10%" cy="60%" r="1.5" fill="#6C63FF">
            <animate attributeName="cy" values="60%;20%;60%" dur="16s" repeatCount="indefinite"/>
          </circle>
          <circle cx="90%" cy="20%" r="2" fill="#00D4FF">
            <animate attributeName="cy" values="20%;60%;20%" dur="19s" repeatCount="indefinite"/>
          </circle>
        </svg>

        <!-- Content -->
        <div style="position: relative; z-index: 2;">
          <!-- Typing animation using SVG -->
          <svg width="200" height="50" viewBox="0 0 200 50" style="margin: 0 auto 20px; display: block;">
            <rect x="0" y="0" width="200" height="50" fill="transparent"/>
            <text x="10" y="35" fill="rgba(255,255,255,0.15)" font-family="'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="14" font-weight="300" letter-spacing="4">
              <animate attributeName="opacity" values="0;1;1;0" dur="3s" repeatCount="indefinite" keyTimes="0;0.1;0.85;1"/>
              ◆ TERMINAL —
            </text>
          </svg>

          <h1 style="
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: clamp(2.5rem, 6vw, 4.5rem);
            font-weight: 700;
            margin: 0;
            letter-spacing: -0.02em;
            background: linear-gradient(135deg, #FFFFFF 0%, rgba(255,255,255,0.7) 50%, #FFFFFF 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-shadow: 0 0 80px rgba(108, 99, 255, 0.15);
          ">
            B.Sachin
          </h1>

          <div style="
            margin: 20px auto 0;
            padding: 12px 24px;
            display: inline-block;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.06);
            border-radius: 100px;
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
          ">
            <span style="
              font-family: 'SF Mono', 'Menlo', 'Monaco', 'Courier New', monospace;
              font-size: clamp(0.8rem, 1.2vw, 1rem);
              font-weight: 400;
              color: rgba(255, 255, 255, 0.7);
              letter-spacing: 0.15em;
            ">
              ⚡ CLOUD · INFRASTRUCTURE · LINUX · AUTOMATION
            </span>
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<!-- ANIMATED GLASS DIVIDER -->
<svg width="60" height="4" viewBox="0 0 60 4" style="margin: -10px 0 20px;">
  <rect width="60" height="4" rx="2" fill="rgba(255,255,255,0.05)"/>
  <rect width="30" height="4" rx="2" fill="rgba(108, 99, 255, 0.4)">
    <animate attributeName="width" values="10;40;10" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x" values="0;10;0" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- ABOUT ME SECTION -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.06);
        border-radius: 32px;
        padding: 40px 48px;
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.2);
      ">
        <div style="display: flex; align-items: center; gap: 14px; margin-bottom: 20px;">
          <span style="
            font-size: 20px;
            font-weight: 300;
            color: rgba(255,255,255,0.15);
            letter-spacing: 4px;
          ">◆</span>
          <h2 style="
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: 1.4rem;
            font-weight: 500;
            margin: 0;
            color: rgba(255,255,255,0.85);
            letter-spacing: -0.01em;
          ">
            ABOUT
          </h2>
          <span style="
            font-size: 12px;
            font-weight: 300;
            color: rgba(255,255,255,0.2);
            letter-spacing: 2px;
            margin-left: auto;
          ">/SYSTEM</span>
        </div>

        <div style="
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 20px 40px;
          font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
          font-size: 0.95rem;
          line-height: 1.7;
          color: rgba(255,255,255,0.7);
        ">
          <div>
            <p style="margin: 0;">
              Engineering student with a passion for <strong style="color: rgba(255,255,255,0.9); font-weight: 400;">cloud infrastructure</strong> and <strong style="color: rgba(255,255,255,0.9); font-weight: 400;">Linux systems</strong>. I build things that scale, break things to learn how they work, and automate everything in between.
            </p>
          </div>
          <div style="
            border-left: 1px solid rgba(255,255,255,0.06);
            padding-left: 40px;
          ">
            <div style="display: flex; flex-direction: column; gap: 6px;">
              <span style="color: rgba(255,255,255,0.3); font-size: 0.75rem; letter-spacing: 2px; text-transform: uppercase;">Current Focus</span>
              <span>☁ AWS · Terraform · Kubernetes</span>
              <span style="color: rgba(255,255,255,0.3); font-size: 0.75rem; letter-spacing: 2px; text-transform: uppercase; margin-top: 8px;">Philosophy</span>
              <span style="color: rgba(255,255,255,0.6);">"Learn by building. Master by breaking."</span>
            </div>
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<!-- SKILLS SECTION -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.06);
        border-radius: 32px;
        padding: 32px 36px;
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.2);
      ">
        <div style="display: flex; align-items: center; gap: 14px; margin-bottom: 28px;">
          <span style="
            font-size: 20px;
            font-weight: 300;
            color: rgba(255,255,255,0.15);
            letter-spacing: 4px;
          ">◈</span>
          <h2 style="
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: 1.4rem;
            font-weight: 500;
            margin: 0;
            color: rgba(255,255,255,0.85);
            letter-spacing: -0.01em;
          ">
            SKILLS
          </h2>
          <span style="
            font-size: 12px;
            font-weight: 300;
            color: rgba(255,255,255,0.2);
            letter-spacing: 2px;
            margin-left: auto;
          ">/KERNEL</span>
        </div>

        <!-- Skills Grid -->
        <div style="
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
          gap: 16px;
        ">
          <!-- Cloud -->
          <div style="
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 20px;
            padding: 20px 18px;
            transition: all 0.3s ease;
          ">
            <div style="font-size: 1.4rem; margin-bottom: 6px;">☁</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.65rem;
              font-weight: 500;
              color: rgba(255,255,255,0.25);
              letter-spacing: 2px;
              text-transform: uppercase;
              margin-bottom: 10px;
            ">Cloud</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.9rem;
              color: rgba(255,255,255,0.85);
              line-height: 1.8;
            ">
              AWS<br>
              Terraform<br>
              Kubernetes
            </div>
          </div>

          <!-- Systems -->
          <div style="
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 20px;
            padding: 20px 18px;
          ">
            <div style="font-size: 1.4rem; margin-bottom: 6px;">🐧</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.65rem;
              font-weight: 500;
              color: rgba(255,255,255,0.25);
              letter-spacing: 2px;
              text-transform: uppercase;
              margin-bottom: 10px;
            ">Systems</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.9rem;
              color: rgba(255,255,255,0.85);
              line-height: 1.8;
            ">
              Linux<br>
              Bash<br>
              Systemd
            </div>
          </div>

          <!-- Networking -->
          <div style="
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 20px;
            padding: 20px 18px;
          ">
            <div style="font-size: 1.4rem; margin-bottom: 6px;">🌐</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.65rem;
              font-weight: 500;
              color: rgba(255,255,255,0.25);
              letter-spacing: 2px;
              text-transform: uppercase;
              margin-bottom: 10px;
            ">Networking</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.9rem;
              color: rgba(255,255,255,0.85);
              line-height: 1.8;
            ">
              TCP/IP<br>
              DNS · HTTP<br>
              SMB · NFS
            </div>
          </div>

          <!-- Development -->
          <div style="
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.06);
            border-radius: 20px;
            padding: 20px 18px;
          ">
            <div style="font-size: 1.4rem; margin-bottom: 6px;">⚙️</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.65rem;
              font-weight: 500;
              color: rgba(255,255,255,0.25);
              letter-spacing: 2px;
              text-transform: uppercase;
              margin-bottom: 10px;
            ">Development</div>
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.9rem;
              color: rgba(255,255,255,0.85);
              line-height: 1.8;
            ">
              Python<br>
              Git<br>
              Docker
            </div>
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<!-- PROJECTS SECTION -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.06);
        border-radius: 32px;
        padding: 32px 36px;
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.2);
      ">
        <div style="display: flex; align-items: center; gap: 14px; margin-bottom: 28px;">
          <span style="
            font-size: 20px;
            font-weight: 300;
            color: rgba(255,255,255,0.15);
            letter-spacing: 4px;
          ">▣</span>
          <h2 style="
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: 1.4rem;
            font-weight: 500;
            margin: 0;
            color: rgba(255,255,255,0.85);
            letter-spacing: -0.01em;
          ">
            PROJECTS
          </h2>
          <span style="
            font-size: 12px;
            font-weight: 300;
            color: rgba(255,255,255,0.2);
            letter-spacing: 2px;
            margin-left: auto;
          ">/REPOS</span>
        </div>

        <div style="
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 18px;
        ">
          <!-- Project 1 -->
          <a href="https://github.com/sachingitworld/project1" style="text-decoration: none; display: block;">
            <div style="
              background: rgba(255,255,255,0.03);
              border: 1px solid rgba(255,255,255,0.06);
              border-radius: 20px;
              padding: 22px 24px;
              transition: all 0.3s ease;
              min-height: 130px;
            ">
              <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 10px;">
                <span style="font-size: 1.2rem;">📦</span>
                <span style="
                  font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
                  font-size: 1rem;
                  font-weight: 500;
                  color: rgba(255,255,255,0.9);
                ">Infra-as-Code</span>
              </div>
              <p style="
                font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
                font-size: 0.85rem;
                color: rgba(255,255,255,0.5);
                margin: 0 0 10px;
                line-height: 1.5;
              ">
                Terraform modules for AWS infrastructure with automated CI/CD
              </p>
              <div style="display: flex; gap: 8px; flex-wrap: wrap;">
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(108, 99, 255, 0.12);
                  color: rgba(108, 99, 255, 0.7);
                  border: 1px solid rgba(108, 99, 255, 0.08);
                  font-family: 'SF Mono', monospace;
                ">Terraform</span>
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(0, 212, 255, 0.08);
                  color: rgba(0, 212, 255, 0.6);
                  border: 1px solid rgba(0, 212, 255, 0.06);
                  font-family: 'SF Mono', monospace;
                ">AWS</span>
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(255, 101, 132, 0.08);
                  color: rgba(255, 101, 132, 0.6);
                  border: 1px solid rgba(255, 101, 132, 0.06);
                  font-family: 'SF Mono', monospace;
                ">GitHub Actions</span>
              </div>
            </div>
          </a>

          <!-- Project 2 -->
          <a href="https://github.com/sachingitworld/project2" style="text-decoration: none; display: block;">
            <div style="
              background: rgba(255,255,255,0.03);
              border: 1px solid rgba(255,255,255,0.06);
              border-radius: 20px;
              padding: 22px 24px;
              min-height: 130px;
            ">
              <div style="display: flex; align-items: center; gap: 10px; margin-bottom: 10px;">
                <span style="font-size: 1.2rem;">🖥</span>
                <span style="
                  font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
                  font-size: 1rem;
                  font-weight: 500;
                  color: rgba(255,255,255,0.9);
                ">Linux Dashboard</span>
              </div>
              <p style="
                font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
                font-size: 0.85rem;
                color: rgba(255,255,255,0.5);
                margin: 0 0 10px;
                line-height: 1.5;
              ">
                Real-time system monitoring with TUI and web interface
              </p>
              <div style="display: flex; gap: 8px; flex-wrap: wrap;">
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(108, 99, 255, 0.12);
                  color: rgba(108, 99, 255, 0.7);
                  border: 1px solid rgba(108, 99, 255, 0.08);
                  font-family: 'SF Mono', monospace;
                ">Python</span>
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(0, 212, 255, 0.08);
                  color: rgba(0, 212, 255, 0.6);
                  border: 1px solid rgba(0, 212, 255, 0.06);
                  font-family: 'SF Mono', monospace;
                ">Bash</span>
                <span style="
                  font-size: 0.65rem;
                  padding: 2px 12px;
                  border-radius: 20px;
                  background: rgba(255, 101, 132, 0.08);
                  color: rgba(255, 101, 132, 0.6);
                  border: 1px solid rgba(255, 101, 132, 0.06);
                  font-family: 'SF Mono', monospace;
                ">Docker</span>
              </div>
            </div>
          </a>
        </div>
      </div>
    </td>
  </tr>
</table>

<!-- STATISTICS & CONTRIBUTIONS -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.06);
        border-radius: 32px;
        padding: 32px 36px;
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.2);
      ">
        <div style="display: flex; align-items: center; gap: 14px; margin-bottom: 28px;">
          <span style="
            font-size: 20px;
            font-weight: 300;
            color: rgba(255,255,255,0.15);
            letter-spacing: 4px;
          ">◉</span>
          <h2 style="
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: 1.4rem;
            font-weight: 500;
            margin: 0;
            color: rgba(255,255,255,0.85);
            letter-spacing: -0.01em;
          ">
            ACTIVITY
          </h2>
          <span style="
            font-size: 12px;
            font-weight: 300;
            color: rgba(255,255,255,0.2);
            letter-spacing: 2px;
            margin-left: auto;
          ">/METRICS</span>
        </div>

        <!-- Stats Grid -->
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 24px;">
          <!-- GitHub Stats -->
          <div style="
            background: rgba(255,255,255,0.02);
            border-radius: 16px;
            padding: 16px;
            border: 1px solid rgba(255,255,255,0.04);
          ">
            <img src="https://github-readme-stats.vercel.app/api?username=sachingitworld&show_icons=true&hide_title=true&hide_border=true&bg_color=0d111700&title_color=6C63FF&icon_color=6C63FF&text_color=ffffff80&count_private=true&hide=contribs" 
                 alt="GitHub Stats" 
                 style="width: 100%; max-width: 400px; height: auto;" />
          </div>

          <!-- Languages -->
          <div style="
            background: rgba(255,255,255,0.02);
            border-radius: 16px;
            padding: 16px;
            border: 1px solid rgba(255,255,255,0.04);
          ">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sachingitworld&layout=compact&hide_border=true&bg_color=0d111700&title_color=6C63FF&text_color=ffffff80&langs_count=6" 
                 alt="Top Languages" 
                 style="width: 100%; max-width: 400px; height: auto;" />
          </div>
        </div>

        <!-- Contribution Graph -->
        <div style="margin-top: 24px;">
          <div style="
            background: rgba(255,255,255,0.02);
            border-radius: 16px;
            padding: 20px 20px 10px;
            border: 1px solid rgba(255,255,255,0.04);
            text-align: center;
          ">
            <img src="https://ghchart.rshah.org/sachingitworld" 
                 alt="GitHub Contributions Chart" 
                 style="width: 100%; max-width: 800px; height: auto; border-radius: 8px;" />
            <div style="
              font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
              font-size: 0.7rem;
              color: rgba(255,255,255,0.15);
              margin-top: 8px;
              letter-spacing: 1px;
            ">
              CONTRIBUTION ACTIVITY · LAST YEAR
            </div>
          </div>
        </div>
      </div>
    </td>
  </tr>
</table>

<!-- CONTACT / LINKS -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.06);
        border-radius: 32px;
        padding: 28px 36px;
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.2);
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 40px;
        flex-wrap: wrap;
      ">
        <a href="https://github.com/sachingitworld" style="
          font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
          font-size: 0.9rem;
          color: rgba(255,255,255,0.6);
          text-decoration: none;
          transition: color 0.3s ease;
          display: flex;
          align-items: center;
          gap: 8px;
        ">
          <span style="font-size: 1.2rem;">⌨</span> GitHub
        </a>
        <a href="https://linkedin.com/in/yourusername" style="
          font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
          font-size: 0.9rem;
          color: rgba(255,255,255,0.6);
          text-decoration: none;
          transition: color 0.3s ease;
          display: flex;
          align-items: center;
          gap: 8px;
        ">
          <span style="font-size: 1.2rem;">🔗</span> LinkedIn
        </a>
        <a href="mailto:your.email@example.com" style="
          font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
          font-size: 0.9rem;
          color: rgba(255,255,255,0.6);
          text-decoration: none;
          transition: color 0.3s ease;
          display: flex;
          align-items: center;
          gap: 8px;
        ">
          <span style="font-size: 1.2rem;">✉</span> Email
        </a>
        <a href="https://yourportfolio.com" style="
          font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
          font-size: 0.9rem;
          color: rgba(255,255,255,0.6);
          text-decoration: none;
          transition: color 0.3s ease;
          display: flex;
          align-items: center;
          gap: 8px;
        ">
          <span style="font-size: 1.2rem;">▣</span> Portfolio
        </a>
      </div>
    </td>
  </tr>
</table>

<!-- FOOTER -->
<table width="100%" style="background: transparent; border: none; max-width: 900px; margin: 0 auto 40px;">
  <tr>
    <td style="padding: 20px; background: transparent; border: none;">
      <div style="
        text-align: center;
        padding: 30px 20px 10px;
        border-top: 1px solid rgba(255,255,255,0.03);
      ">
        <svg width="100%" height="2" style="display: block; max-width: 200px; margin: 0 auto 20px;">
          <rect width="100%" height="2" rx="1" fill="rgba(255,255,255,0.02)"/>
          <rect width="60" height="2" rx="1" fill="rgba(108, 99, 255, 0.15)">
            <animate attributeName="width" values="20;80;20" dur="6s" repeatCount="indefinite"/>
            <animate attributeName="x" values="0;20;0" dur="6s" repeatCount="indefinite"/>
          </rect>
        </svg>

        <span style="
          font-family: 'SF Mono', 'Menlo', 'Monaco', 'Courier New', monospace;
          font-size: clamp(0.7rem, 0.9vw, 0.85rem);
          color: rgba(255,255,255,0.15);
          letter-spacing: 0.15em;
          line-height: 2;
        ">
          ⚡ BUILDING SYSTEMS · BREAKING THINGS · LEARNING HOW THEY WORK
        </span>

        <div style="margin-top: 8px;">
          <span style="
            font-family: 'SF Pro Text', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            font-size: 0.6rem;
            color: rgba(255,255,255,0.05);
            letter-spacing: 1px;
          ">
            LIQUID GLASS · v1.0
          </span>
        </div>
      </div>
    </td>
  </tr>
</table>

</div>
