# ╔══════════════════════════════════════════════════════════════════════╗
# ║     LAVAN DEV — ULTRA-PREMIUM COSMIC AGENCY WEBSITE PROMPT v3.0     ║
# ║          COMPLETE · WORKING · NO STUBS · NO PLACEHOLDERS            ║
# ╚══════════════════════════════════════════════════════════════════════╝
#
# ⚠  This is NOT a mockup. Write a COMPLETE, PRODUCTION-READY single
#    index.html file with all CSS in <style> and all JS in <script>.
#    Every effect, animation, and interaction listed here must be
#    fully implemented. Never write placeholder comments. Never simplify.
# ─────────────────────────────────────────────────────────────────────────

═══════════════════════════════════════════
 AGENCY IDENTITY (DO NOT INVENT — USE THIS)
═══════════════════════════════════════════

  Name:         Lavan Dev
  Tagline:      "We build things that should not be possible."
  Sub-tagline:  "No bloat. No middlemen. Just focused engineers
                 building things that work."
  Stats:        15 Projects · 14 Satisfied Clients · <24H Response Time
  Location:     Tunis, Tunisia — Global Reach
  Contact:      hello@lavandev.com
  Security line: "Security is not a feature. It's a foundation."

  SERVICES:
  ├── Web Development      — Full-stack apps: React, Next.js, Node.js
  ├── Cybersecurity        — Penetration testing, secure architecture, code audits
  ├── API Engineering      — High-performance REST & GraphQL APIs built to scale
  └── Cloud & DevOps       — CI/CD pipelines, Docker, Kubernetes, AWS/GCP/Azure

  PROCESS (5 steps):
  01 Discover   — Align on goals, constraints, timeline
  02 Architect  — Design the system before writing a single line
  03 Engineer   — Build with precision, tests, and clean commits
  04 Harden     — Audit, pen-test, optimize before delivery
  05 Launch     — Deploy, monitor, support after go-live

  PROJECTS (all 7, real):
  #01  ERPNext Full Industrial Management
       Stack: ERPNext · Python · JavaScript · Industrial Management
       Desc:  Deployment & customization of a complete ERP for a factory;
              inventory management, production, accounting, HR.

  #02  Full-Stack E-Learning Platform
       Stack: React · Node.js · Express · MongoDB · Full-Stack
       Desc:  Complete web app for an online course academy — auth,
              course management, admin dashboard.

  #03  Online Abaya Shop
       Stack: React · MongoDB · REST API · Framer Motion
       Desc:  E-commerce with product listings, shopping cart,
              secure checkout.

  #04  Tirik eDisplay Architectural Revolution
       Stack: React · MySQL · UX/UI Design · Responsive Design
       Desc:  Online platform for a digital signage company showcasing
              products, services, and performance.

  #05  Bredl Skate Brand E-Commerce
       Stack: Vue.js · Security · UX/UI Design · Performance · Creativity
       Desc:  E-commerce for a skate brand: security, UX, performance.

  #06  VapeStore Manager Application (Private)
       Stack: React · Security · UX/UI Design · Performance
       Desc:  Internal UI for a vape store app. Images restricted
              due to security reasons.

  CORE COMPETENCIES (real data):
  Languages:      JS/ES6+ 90% · Python 85% · C/C++ 80% · Java 75% · Assembly/VHDL 70%
  Frameworks:     React/Redux 90% · Next.js 85% · Node.js 80% · Angular 75% · Bootstrap 90%
  Cybersecurity:  Kali Linux/Burp Suite 85% · Wireshark 80% · Network Security 85%
                  Penetration Testing 80% · Protocol Analysis 85%
  Tools:          Git 90% · Docker 85% · Kubernetes 75% · VS Code 95% · Linux 85%


═══════════════════════════════════════════
 VISUAL IDENTITY & CONCEPT
═══════════════════════════════════════════

  CORE CONCEPT: "OPERATING FROM ORBIT"
  Lavan Dev is an engineering team that operates from a vantage point
  above conventional thinking. The cosmos is their workspace. The Earth
  is their client. Every section lives in deep space. The agency's
  capabilities orbit the viewer like satellites. Code streams like
  telemetry. Gravity is a design system.

  DESIGN LANGUAGE:
  - Space opera meets terminal aesthetics
  - Cinematic dark space backgrounds with star fields
  - A real-time rotating Earth (WebGL TextureLoader) as the site's
    central visual motif — persists across sections
  - Cyan energy lines, orbital paths, satellite nodes
  - Monospaced type for data/code elements + a bold display font for headings
  - Binary/code streams as decorative texture
  - Every interaction has a "signal sent / received" micro-response

  FONTS:
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;700&family=Orbitron:wght@700;900&family=JetBrains+Mono:wght@300;400&display=swap" rel="stylesheet">

  - Display headings: "Orbitron" 700/900 — feels like a mission control font
  - Body / UI text: "Space Grotesk" 300/400 — clean, technical, readable
  - Code elements / data: "JetBrains Mono" 300/400 — terminal authenticity

  COLOR PALETTE (CSS custom properties):
  :root {
    --void:      #030a10;   /* deep space black */
    --cosmos:    #070f1c;   /* slightly lighter space navy */
    --surface:   #0a1628;   /* card / panel background */
    --pulse:     #00f0c8;   /* cyan energy — primary accent */
    --pulse-dim: rgba(0,240,200,0.12); /* glow ambient */
    --plasma:    #1a7aff;   /* electric blue — secondary */
    --warning:   #ff4d6d;   /* alert / security red */
    --text:      #c8dde8;   /* cool off-white */
    --dim:       #3a5068;   /* muted / inactive */
    --star:      #e8f4ff;   /* star white */
    --grid:      rgba(0,240,200,0.04); /* subtle grid lines */
  }

  GLOBAL TEXTURE:
  - Full-page SVG noise grain: <div class="noise-overlay"> with
    feTurbulence baseFrequency="0.65" numOctaves="3",
    opacity: 0.025, position: fixed, pointer-events: none, z-index: 9999.
  - CSS grid overlay: repeating-linear-gradient creating a subtle
    12px dot-matrix grid at opacity 0.04 — like a radar screen.
  - Persistent star field canvas behind everything (z-index 0):
    800 small dots (size 0.5–2px), randomly placed, 20% of them
    twinkle (opacity 0.3 → 1.0 on a random sine cycle).


═══════════════════════════════════════════
 REQUIRED LIBRARIES (in <head>)
═══════════════════════════════════════════

  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
  <script src="https://unpkg.com/@studio-freight/lenis@1.0.42/dist/lenis.min.js"></script>

  Earth texture: Use a procedurally generated Earth-like sphere
  (no external image URL needed — generate using ShaderMaterial with
  continental noise patterns in GLSL — see Section 1 for exact shaders).


═══════════════════════════════════════════
 GLOBAL SETUP
═══════════════════════════════════════════

  SMOOTH SCROLL:
  const lenis = new Lenis({ lerp: 0.065, smoothWheel: true })
  gsap.ticker.add((time) => lenis.raf(time * 1000))
  gsap.ticker.lagSmoothing(0)
  gsap.registerPlugin(ScrollTrigger)
  html { scroll-behavior: auto }

  WILL-CHANGE: Apply will-change: transform to all animated elements.
  RESIZE: Debounce all resize handlers with 150ms.

  ─────────────────────────────────────────
  CUSTOM CURSOR — "TARGETING RETICLE"
  ─────────────────────────────────────────
  Three-layer cursor system:
  #cursor-dot:   6px solid var(--pulse), follows instantly
  #cursor-ring:  44px circle, border: 1.5px solid rgba(0,240,200,0.5),
                 follows with lerp 0.10
  #cursor-scan:  Two perpendicular 1px lines (crosshair) extending
                 20px in each direction from center, opacity: 0.3,
                 always visible — gives a "targeting system" feel.

  On hover over [data-cursor="target"]:
  - #cursor-ring expands to 80px, fill: var(--pulse-dim)
  - A thin circle pulse animation radiates outward (scale: 1 → 2.5,
    opacity: 0.4 → 0, duration 0.8s, repeat while hovering)
  - Text "LOCK" appears inside the ring in JetBrains Mono 300, 8px

  On hover over links and buttons:
  - #cursor-ring morphs to a thin line (scaleY: 0.05) — like a
    targeting line sweeping across the element

  All cursor elements: position: fixed, pointer-events: none, z-index: 10000.
  Use requestAnimationFrame loop for lerp.


═══════════════════════════════════════════
 ── SECTION 0: PAGE LOADER ──
 "MISSION BOOT SEQUENCE"
═══════════════════════════════════════════

  Full-screen #void background. Three animated elements:

  1. BINARY RAIN COLUMNS (Canvas2D):
     24 columns of falling binary digits (0 and 1), randomly placed,
     falling at different speeds (3–7px/frame), cyan color,
     opacity fades as digits age (like Matrix rain but teal/cyan).
     Each column 18px wide, digits in JetBrains Mono 13px.

  2. MISSION TERMINAL (center):
     A small terminal window (400px wide, 200px tall, glass surface)
     that types out:
     > initializing lavandev systems...
     > secure_config.json — ✓ LOADED
     > ci_cd_pipeline — ✓ READY
     > threat_scan — ✓ CLEAN
     > launching in [COUNTDOWN]%
     Each line appears with a 350ms gap. The countdown goes 100 → 0
     in 2 seconds using GSAP innerHTML snap animation.
     The blinking cursor (│) at the end of the last line blinks at 0.6s intervals.

  3. PROGRESS BAR:
     Horizontal bar, 300px wide, fill: var(--pulse), fills over 2.4s.
     Below it: "LAVAN DEV" in Orbitron 900 12px, letter-spacing 8px,
     cycling through colors: --dim → --pulse → --star.

  EXIT SEQUENCE (at 100%):
     All loader elements explode outward in their respective directions:
     - Binary columns accelerate and fly off top/bottom (y: ±150vh)
     - Terminal window scales to 0 and fades
     - "LAVAN DEV" text expands to full screen then fades
     - Underlying site content fades in
     Total exit: 0.8s. GSAP timeline with stagger.


═══════════════════════════════════════════
 ── SECTION 1: HERO ──
 "COMMAND CENTER"
═══════════════════════════════════════════

  Layout: Full viewport. The WebGL Earth occupies the right 55% of the
  viewport, slightly outside frame (bleeding off the right edge by 15%).
  Hero text is left-aligned on the left 50%.

  ─────────────────────────────────────────
  WEBGL EARTH (Three.js — the site's hero element)
  ─────────────────────────────────────────
  Canvas: #earth-canvas, position: absolute, covers entire hero.
  This Earth persists (fixed or re-rendered) as a background motif
  throughout multiple sections by fading/scaling it between them.

  Earth construction (pure GLSL — no external textures):
  const earthGeo = new THREE.SphereGeometry(2.4, 128, 128)

  Shader uniforms:
  - uTime: float (increments 0.004/frame)
  - uRotation: float (increments 0.0012/frame — realistic slow rotation)
  - uCloudTime: float (increments 0.0006/frame — slower cloud drift)
  - uAtmosphere: float (1.0)

  vertexShader:
    uniform float uTime;
    varying vec2 vUv;
    varying vec3 vNormal;
    varying vec3 vPosition;
    void main() {
      vUv = uv;
      vNormal = normalize(normalMatrix * normal);
      vPosition = (modelMatrix * vec4(position, 1.0)).xyz;
      gl_Position = projectionMatrix * modelViewMatrix * vec4(position, 1.0);
    }

  fragmentShader (Earth surface — noise-based continents):
    uniform float uTime;
    uniform float uRotation;
    uniform float uCloudTime;
    varying vec2 vUv;
    varying vec3 vNormal;
    varying vec3 vPosition;

    // ── Include full 3D simplex noise (snoise3) implementation here ──
    // Source: Ashima Arts snoise — include ALL helper functions:
    // vec3 mod289(vec3), vec4 mod289(vec4), vec4 permute(vec4),
    // vec4 taylorInvSqrt(vec4), float snoise(vec3)

    float fbm(vec3 p, int octaves) {
      float value = 0.0;
      float amplitude = 0.5;
      for (int i = 0; i < 6; i++) {
        if (i >= octaves) break;
        value += amplitude * snoise(p);
        p *= 2.1;
        amplitude *= 0.5;
      }
      return value;
    }

    void main() {
      // Scrolling UV for rotation
      vec2 scrollUv = vec2(vUv.x + uRotation, vUv.y);

      // Continent noise — fbm gives natural landmass shapes
      vec3 noiseCoord = vec3(scrollUv * 3.5, uTime * 0.01);
      float continent = fbm(noiseCoord, 5);

      // Ocean vs land threshold
      float land = smoothstep(0.05, 0.18, continent);

      // Ocean color — deep blue with shimmer
      vec3 ocean = mix(
        vec3(0.01, 0.07, 0.18),
        vec3(0.03, 0.15, 0.35),
        fbm(noiseCoord * 2.0, 3) * 0.5 + 0.5
      );
      // Add specular-like shimmer on ocean
      float shimmer = pow(max(0.0, snoise(noiseCoord * 8.0 + uTime * 0.2)), 3.0);
      ocean += vec3(0.0, 0.12, 0.25) * shimmer * 0.4;

      // Land color — varied terrain
      float terrain = fbm(noiseCoord * 5.0 + vec3(10.0), 4);
      vec3 lowland  = vec3(0.08, 0.22, 0.06);
      vec3 highland = vec3(0.28, 0.22, 0.12);
      vec3 snow     = vec3(0.85, 0.88, 0.92);
      float elev = smoothstep(0.3, 0.8, terrain);
      vec3 landColor = mix(lowland, highland, elev);
      // Polar snow caps
      float polar = smoothstep(0.65, 0.85, abs(vUv.y - 0.5) * 2.0);
      landColor = mix(landColor, snow, polar);

      vec3 surface = mix(ocean, landColor, land);

      // Night side — city lights on dark side (orange dots noise)
      vec3 lightDir = normalize(vec3(-1.2, 0.4, 1.8));
      float NdotL = dot(vNormal, lightDir);
      float dayMix = smoothstep(-0.25, 0.4, NdotL);
      float cityLights = pow(max(0.0, fbm(noiseCoord * 12.0, 4) * 0.5 + 0.5), 6.0);
      cityLights *= (1.0 - land) * (1.0 - dayMix); // only on ocean/night
      vec3 nightColor = surface * 0.04 + vec3(1.0, 0.6, 0.1) * cityLights * 0.8;
      surface = mix(nightColor, surface, dayMix);

      // Cloud layer
      float cloud = smoothstep(0.55, 0.75,
        fbm(vec3(scrollUv * 2.8 + uCloudTime, uTime * 0.005), 4) * 0.5 + 0.5
      );
      surface = mix(surface, vec3(0.82, 0.88, 0.9), cloud * 0.85 * dayMix);

      // Atmospheric rim glow (cyan to match brand)
      float rim = pow(1.0 - max(0.0, dot(vNormal, normalize(vec3(0.0, 0.0, 1.0)))), 3.5);
      vec3 atmosphere = vec3(0.0, 0.6, 0.9) * rim * 1.2;
      surface += atmosphere;

      // Specular highlight
      vec3 viewDir = normalize(-vPosition);
      vec3 halfVec = normalize(lightDir + viewDir);
      float spec = pow(max(0.0, dot(vNormal, halfVec)), 60.0);
      surface += vec3(0.7, 0.9, 1.0) * spec * 0.5 * dayMix;

      gl_FragColor = vec4(surface, 1.0);
    }

  Atmosphere shell: A second SphereGeometry(2.52, 64, 64) around the Earth:
    - MeshPhongMaterial, transparent: true, opacity: 0.12
    - color: 0x00aaff, side: THREE.BackSide
    - Pulsing: opacity oscillates 0.08 → 0.18 with Math.sin(time * 0.5)

  Orbital rings (3 rings around Earth):
    - TorusGeometry(3.2, 0.003, 8, 200), wireframe: false
    - Material: MeshBasicMaterial, color: 0x00f0c8, opacity: 0.2, transparent
    - Tilts: (Math.PI/4, 0, 0), (0, Math.PI/6, Math.PI/3), (Math.PI/2, 0.3, 0)
    - Each rotates at a different speed each frame (0.001, -0.0015, 0.0008)

  3 satellite nodes orbiting on ring paths:
    - Each is a tiny SphereGeometry(0.035), MeshBasicMaterial color: 0x00f0c8
    - Positioned as: x = ring_radius * cos(angle), y = ring_radius * sin(angle) * tilt_factor
    - They orbit at different speeds; create small glow halo with SpriteMaterial

  Mouse parallax:
    earth.rotation.y += (targetRY - earth.rotation.y) * 0.03
    earth.position.x += (mouseNX * 0.3 - earth.position.x) * 0.04
    earth.position.y += (-mouseNY * 0.2 - earth.position.y) * 0.04

  ─────────────────────────────────────────
  HERO TEXT (left side overlay)
  ─────────────────────────────────────────
  Structure:
    [eyebrow]   WE BUILD THINGS THAT          (JetBrains Mono 400, 1rem,
                                               var(--pulse), letter-spacing 3px)
    [H1 line1]  SHOULD                         (Orbitron 900, 11vw, var(--star))
    [H1 line2]  NOT BE                         (Orbitron 900, 11vw, var(--star))
    [H1 line3]  POSSIBLE.                      (Orbitron 900, 11vw, var(--pulse))
    [divider]   ──── [ thin cyan line, 120px ] ────
    [body]      No bloat. No middlemen. Just focused engineers
                building things that work.     (Space Grotesk 300, 1.1rem)
    [CTA row]   [ Start a Project → ]  [ View Work ↓ ]

  Load animation (GSAP timeline, delay 2.5s — after loader exits):
    - Eyebrow: clips in from left (clipPath: inset(0 100% 0 0) → inset(0 0% 0 0))
    - Each H1 line: rises from y:80 to y:0, staggered 0.15s, ease: power4.out
    - "POSSIBLE." shakes once horizontally (x: ±4px, 3 cycles) after landing —
      like a signal lock snapping into place
    - Divider line draws itself (scaleX: 0 → 1, transformOrigin: left)
    - Body text fades in, y: 20 → 0
    - CTA buttons slide in from y: 30

  Floating animation (loop, after load complete):
    gsap.to(".hero-headline", {
      y: -8, duration: 4, yoyo: true, repeat: -1, ease: "sine.inOut"
    })

  CTA buttons styling:
  Primary: border: 1.5px solid var(--pulse), background transparent.
    Hover: liquid fill — ::before pseudo-element with background var(--pulse),
    scaleX: 0 → 1 origin center, 0.4s ease; text color → var(--void).
  Secondary: plain text link with underline drawn on hover (::after scaleX 0→1).

  ─────────────────────────────────────────
  TELEMETRY DATA STRIP (bottom of hero)
  ─────────────────────────────────────────
  A fixed-width horizontal bar at the very bottom of the hero section.
  Background: rgba(0,240,200,0.04). Border-top: 1px solid rgba(0,240,200,0.12).
  Contains live-updating mock data in JetBrains Mono 11px, var(--dim):

  [●] STATUS: OPERATIONAL   |   LAT: 36.8°N   LONG: 10.2°E   |
  UPTIME: 99.97%   |   LAST DEPLOY: 14h ago   |   THREAT LEVEL: MINIMAL

  The status dot blinks (opacity 1 ↔ 0, 1.2s interval).
  The numbers subtly randomize every 8s to feel "live".


═══════════════════════════════════════════
 ── SECTION 2: STATS ──
 "SIGNAL CONFIRMATION"
═══════════════════════════════════════════

  Dark section (#cosmos), the Earth visible in the background at 15% opacity
  (CSS background-attachment: fixed effect — Earth parallaxes behind).

  Three stat panels in a row, separated by 1px vertical lines (var(--dim)).
  Each panel:
    [Large Number]   [Label]
    15               PROJECTS
    14               SATISFIED CLIENTS
    <24H             MAX RESPONSE TIME

  Large numbers: Orbitron 900, 9vw, var(--pulse).
  Labels: Space Grotesk 300, 0.8rem, letter-spacing 4px, uppercase, var(--dim).

  Entry animation (GSAP, ScrollTrigger):
  Numbers count UP from 0. But with a twist — each digit passes through
  all values (0→9 rapidly) before settling on the real value.
  Implementation:
    function cyberCount(el, target, duration) {
      let current = 0
      const chars = "0123456789"
      const interval = setInterval(() => {
        el.textContent = chars[Math.floor(Math.random() * chars.length)]
        current += target / (duration / 30)
        if (current >= target) {
          el.textContent = el.dataset.prefix
            ? el.dataset.prefix + target
            : target + (el.dataset.suffix || "")
          clearInterval(interval)
        }
      }, 30)
    }

  Below the stats: a full-width "terminal echo" line:
    > system_check: all_nodes_operational — 0 vulnerabilities detected
  Typed out using a typewriter effect when this section scrolls into view.
  Color: var(--pulse), JetBrains Mono 300, 0.85rem.


═══════════════════════════════════════════
 ── SECTION 3: WHAT WE BUILD (SERVICES) ──
 "ORBITAL CAPABILITY MAP"
═══════════════════════════════════════════
  (Inspired by the original site's 4-service grid but elevated 10×)

  ─────────────────────────────────────────
  CONCEPT: SATELLITE DEPLOYMENT ANIMATION
  ─────────────────────────────────────────
  When this section scrolls into view, 4 "satellite cards" deploy
  from the center (0,0) and animate outward to their grid positions —
  as if being launched into orbit. Each card "locks into" its orbit slot
  with a brief shake/vibration.

  gsap.from(".service-card", {
    x: 0, y: 0, scale: 0.3, opacity: 0,
    stagger: { amount: 0.8, from: "center" },
    duration: 1.2,
    ease: "back.out(1.7)",
    scrollTrigger: { trigger: "#services", start: "top 60%" }
  })

  HTML structure:
  <section id="services">
    <div class="section-label">// ORBITAL CAPABILITIES</div>
    <h2>What we build</h2>
    <div class="services-grid">
      <div class="service-card" data-cursor="target">...</div> × 4
    </div>
  </section>

  Each service card:
  - Background: var(--surface), border: 1px solid rgba(0,240,200,0.12)
  - Top accent: a 2px horizontal line at top, full width, var(--pulse)
  - Icon: SVG icon in var(--pulse) — </> for Web Dev, shield for Security,
          server-rack for API, cloud for DevOps
  - Service name: Orbitron 700, 1.3rem, var(--star)
  - Description: Space Grotesk 300, 0.95rem, var(--text)
  - Tag badges: small pills, border: 1px solid rgba(0,240,200,0.3),
                JetBrains Mono, 0.7rem

  Service card hover interaction:
  - Border glows: box-shadow: 0 0 0 1px var(--pulse), 0 0 20px var(--pulse-dim)
  - A diagonal "scan line" sweeps across the card surface from top-left
    to bottom-right (::before pseudo, background: linear-gradient,
    transform: skewX(-10deg) translateX(-120%) → translateX(200%), 0.5s)
  - Service icon scales to 1.2 and rotates 10° with spring ease
  - A small "ACTIVE" label appears top-right (JetBrains Mono, 0.65rem, --pulse)

  SERVICES DATA:
  1. </> Web Development
     Full-stack web apps built with modern frameworks — React, Next.js, Node.js
     Tags: React · Next.js · Node.js · Full-Stack

  2. [shield] Cybersecurity
     Penetration testing, secure architecture, and code audits to keep your systems bulletproof.
     Tags: Pen Testing · Kali Linux · Burp Suite · Audits

  3. [server] API Engineering
     High-performance, well-documented REST and GraphQL APIs designed to scale under pressure.
     Tags: REST · GraphQL · Node.js · Performance

  4. [cloud] Cloud & DevOps
     CI/CD pipelines, containerization, and cloud infrastructure on AWS, GCP, or Azure.
     Tags: Docker · Kubernetes · AWS · CI/CD


═══════════════════════════════════════════
 ── SECTION 4: WHO WE ARE ──
 "MISSION BRIEFING"
═══════════════════════════════════════════

  Split layout: left 45% text, right 55% interactive terminal.

  LEFT — Text:
    SECTION LABEL: // WHO WE ARE   (JetBrains Mono, var(--pulse))
    H2: "A small team of engineers who care deeply about the craft."
        (Orbitron 700, 3.5vw, var(--star))
    P1: "No bloat, no middlemen. Just focused people building things that work."
    P2: "We believe security is not a feature, it's a foundation. Every system
         we ship is designed to perform under load and resist attack from day one."
    Stat strip: "est. 2019 · Tunis, TN · Available globally"
                (JetBrains Mono, var(--dim), letter-spacing 2px)

  Each paragraph appears with a scroll-triggered clipPath reveal:
    gsap.from(para, {
      clipPath: "inset(0 0 100% 0)", opacity: 0, y: 30,
      scrollTrigger: { trigger: para, start: "top 80%", end: "top 40%", scrub: 1.5 }
    })

  RIGHT — Interactive Terminal (data-cursor="target"):
    A realistic terminal window UI:
    - Window chrome: 3 dots (red/yellow/green), title bar "bash — lavandev@server"
    - Background: #060f18, border: 1px solid rgba(0,240,200,0.2)
    - Border-radius: 12px, box-shadow: 0 25px 60px rgba(0,0,0,0.5)

    Content types out on scroll enter (150ms per character):
    Line 1: $ lavandev --init your-project        (--pulse)
    Line 2:   ✓ Secure config loaded              (green #00e07a)
    Line 3:   ✓ CI/CD pipeline ready              (green)
    Line 4:   ✓ Threat scan complete — 0 vulns    (green)
    Line 5:   ✓ Performance audit — 97/100        (green)
    Line 6:   ✓ Ready to ship                     (green, bold)
    Line 7:   _  (blinking cursor)

    After all lines type: a brief pause, then an animation where all
    "✓" checkmarks pulse outward (scale 1 → 1.5 → 1 with cyan glow) in sequence.

  Background: the Earth globe, blurred (filter: blur(40px)), at 20% opacity,
  slowly rotating in the background behind both columns.


═══════════════════════════════════════════
 ── SECTION 5: HOW WE WORK ──
 "MISSION PROTOCOL — ORBITAL TIMELINE"
═══════════════════════════════════════════
  (Inspired by the original 5-step horizontal process)

  LAYOUT: Full-width section. The 5 steps are arranged on a horizontal
  dashed line (exactly like the original, but dramatically animated).

  Background: deep space with the Earth in center background (opacity 0.25).

  HTML:
  <section id="process">
    <h2>How we work</h2>
    <p class="section-sub">No surprises. Just clean code and clear communication.</p>
    <div class="timeline-track">
      <div class="timeline-line"></div>  <!-- the dashed --pulse line -->
      <div class="timeline-step" data-step="01" data-label="Discover">...</div>
      × 5 steps
    </div>
  </section>

  The dashed line: border-top: 2px dashed var(--pulse) at 40%.
  Drawn left-to-right by ScrollTrigger (starts at width: 0, animates to 100%
  using a clip-path mask or a pseudo-element scaleX).

  Each step node is a circle (50px diameter):
  - Background: var(--void), border: 2px solid var(--pulse)
  - Inside: "01" in Orbitron 700, 0.8rem, var(--pulse)
  - When the line "reaches" each node: the node pulses (box-shadow glow expands),
    the step content below fades in with y: 20 → 0

  Animation sequence is scroll-scrubbed:
    const tl = gsap.timeline({
      scrollTrigger: {
        trigger: "#process",
        start: "top 60%",
        end: "bottom 60%",
        scrub: 1.5
      }
    })
    tl.to(".timeline-line", { scaleX: 1, transformOrigin: "left center" })
    tl.from(".timeline-step", { opacity: 0, y: 20, stagger: 0.15 }, "<0.1")

  Step nodes: when hovered, a small tooltip floats above with the
  full description. Tooltip has a small arrow pointer down, background
  var(--surface), border var(--pulse-dim).

  STEPS DATA:
  01 Discover  — We align on your goals, constraints, and timeline.
  02 Architect — We design the system before writing a single line.
  03 Engineer  — We build with precision, tests, and clean commits.
  04 Harden    — We audit, pen-test, and optimize before delivery.
  05 Launch    — We deploy, monitor, and support after go-live.


═══════════════════════════════════════════
 ── SECTION 6: PROJECTS ──
 "MISSION LOG — HORIZONTAL SCROLL"
═══════════════════════════════════════════

  GSAP horizontal pin (exactly as specified in original prompt):
  gsap.to(".projects-track", {
    x: () => -(document.querySelector(".projects-track").scrollWidth - window.innerWidth),
    ease: "none",
    scrollTrigger: {
      trigger: "#projects",
      pin: ".projects-pin",
      scrub: 0.9,
      end: () => "+=" + document.querySelector(".projects-track").scrollWidth
    }
  })

  Section label (sticky, outside the horizontal scroll):
    { // Featured Projects }   (JetBrains Mono, var(--pulse))

  Track contains all 6 project cards, each 100vw × 100vh, display: flex.

  Each project card design:
  - Background: var(--surface), subtle gradient overlay
  - Top: binary code string decoration (random 0/1 characters, JetBrains Mono,
         8px, var(--dim), overflow hidden — unique per card)
  - Project number: "#01" → "#06", Orbitron 700, 1rem, var(--pulse), top-left
  - GitHub icon button (SVG), top-right, styled as a terminal icon
  - A ">" caret prefix before the project title (JetBrains Mono, var(--pulse))
  - Title: Orbitron 700, 2.8vw, var(--star)
  - Description: Space Grotesk 300, 1rem, var(--text), max-width 380px
  - Stack tags: pill badges with border: 1px solid var(--pulse), JetBrains Mono,
                0.75rem, var(--pulse). Each tag has "</>" icon before the label.
  - Left border accent: 2px solid var(--pulse) or var(--plasma), varies per card

  Card interaction:
  3D tilt on mousemove (identical to original prompt):
    card.addEventListener('mousemove', e => {
      const rect = card.getBoundingClientRect()
      const rx = ((e.clientY - rect.top) / rect.height - 0.5) * -14
      const ry = ((e.clientX - rect.left) / rect.width - 0.5) * 14
      gsap.to(card, { rotateX: rx, rotateY: ry, transformPerspective: 1200,
                      duration: 0.4, ease: "power2.out" })
    })
    card.addEventListener('mouseleave', () => {
      gsap.to(card, { rotateX: 0, rotateY: 0, duration: 0.8,
                      ease: "elastic.out(1, 0.4)" })
    })

  Hover: scan-line sweep (same as service cards), plus the title
  glitches for 0.4s:
    function glitch(el) {
      const glitchChars = "!@#$%^&*<>/\\"
      const original = el.textContent
      let i = 0
      const id = setInterval(() => {
        el.textContent = original.split("").map((c, idx) =>
          idx < i ? original[idx]
          : Math.random() > 0.7 ? glitchChars[Math.floor(Math.random()*glitchChars.length)]
          : c
        ).join("")
        if (i++ >= original.length) { el.textContent = original; clearInterval(id) }
      }, 35)
    }

  PROJECT DATA:
  #01  ERPNext Full Industrial Management
       ERPNext · Python · JavaScript · Industrial Management
       "Deployment & customization of a complete ERP for a factory —
        inventory management, production, accounting, and HR."

  #02  Full-Stack E-Learning Platform
       React · Node.js · Express · MongoDB · Full-Stack
       "Complete web app for an online course academy — authentication,
        course management, and an admin dashboard."

  #03  Online Abaya Shop
       React · MongoDB · REST API · Framer Motion
       "E-commerce with product listings, shopping cart, and secure checkout."

  #04  Tirik eDisplay Architectural Revolution
       React · MySQL · UX/UI Design · Responsive Design
       "Online platform for a digital signage company showcasing products,
        services, and performance."

  #05  Bredl Skate Brand E-Commerce
       Vue.js · Security · UX/UI Design · Performance · Creativity
       "E-commerce for a skate brand: security-first, high performance, strong UX."

  #06  VapeStore Manager Application (Private)
       React · Security · UX/UI Design · Performance
       "Internal UI for a vape store app. Images restricted for security reasons."

  SCROLL PROGRESS INDICATOR:
  A thin var(--pulse) bar at the top of the section, width grows
  from 0% → 100% as user scrolls through all cards.
  A small glowing dot tracks the leading edge.


═══════════════════════════════════════════
 ── SECTION 7: CORE COMPETENCIES ──
 "SYSTEM DIAGNOSTICS — SKILL CONSTELLATION"
═══════════════════════════════════════════
  (Inspired by original but replaced progress bars with a constellation map)

  ─────────────────────────────────────────
  CONCEPT: STAR CONSTELLATION SKILL MAP
  (This is the award-winning original section — no progress bars)
  ─────────────────────────────────────────
  A Canvas2D element (full section width, 500px tall) renders all skills
  as star nodes in a constellation. Each skill is a dot. Related skills
  are connected by thin lines (like a star map). The whole constellation
  rotates slowly.

  Implementation:
  const skills = [
    // [label, x_pct, y_pct, category, percentage, size_px]
    ["JS/ES6+", 0.18, 0.3, "lang", 90, 8],
    ["Python",  0.32, 0.5, "lang", 85, 7.5],
    ["C/C++",   0.22, 0.7, "lang", 80, 7],
    ["Java",    0.10, 0.55, "lang", 75, 6.5],
    ["Assembly",0.06, 0.35, "lang", 70, 6],

    ["React",   0.48, 0.25, "fw", 90, 8],
    ["Next.js", 0.60, 0.40, "fw", 85, 7.5],
    ["Node.js", 0.52, 0.60, "fw", 80, 7],
    ["Angular", 0.68, 0.65, "fw", 75, 6.5],
    ["Bootstrap",0.72, 0.30,"fw", 90, 8],

    ["Kali/Burp",0.82, 0.45,"sec", 85, 7.5],
    ["Wireshark",0.90, 0.28,"sec", 80, 7],
    ["Pen Testing",0.88,0.65,"sec",80, 7],
    ["Net Security",0.78,0.70,"sec",85, 7.5],

    ["Git",     0.40, 0.80, "tools", 90, 8],
    ["Docker",  0.50, 0.85, "tools", 85, 7.5],
    ["K8s",     0.60, 0.78, "tools", 75, 6.5],
    ["Linux",   0.35, 0.70, "tools", 85, 7.5],
    ["VS Code", 0.45, 0.60, "tools", 95, 8.5],
  ]

  Category colors:
  lang:   var(--pulse)   — #00f0c8
  fw:     #1a7aff        — plasma blue
  sec:    #ff4d6d        — warning red
  tools:  #f0c800        — gold

  Connections drawn between nodes in the same category:
  ctx.strokeStyle = rgba(color, 0.2)
  ctx.lineWidth = 0.8

  Per-frame:
  - Entire constellation slowly rotates around its center (angle += 0.0002/frame)
  - Each star twinkles (radius oscillates ± 0.5px on a sin cycle)
  - Stars near mouse glow brighter and grow (within 80px radius)

  Hover on a star node:
  - Tooltip shows: label, percentage bar, category
  - Connection lines to that node's category brighten to 0.7 opacity
  - Other category lines dim to 0.05

  BELOW the constellation: a classic 2×2 competency grid
  (for accessibility / readability) with the actual progress bars
  from the original site, but styled with the new palette:
    - Progress bar fill: linear-gradient(90deg, var(--pulse), var(--plasma))
    - Animated: scaleX 0 → actual% on scroll, ease: power2.out
    - Label and percentage: Space Grotesk 300, var(--text)

  Quadrant headers: Orbitron 700, 1rem, var(--pulse) with SVG icons.
  Languages · Frameworks & Libraries · Cybersecurity & Networks · Tools & Environments


═══════════════════════════════════════════
 ── SECTION 8: DUAL MARQUEE ──
 "ESCAPE VELOCITY BROADCAST"
═══════════════════════════════════════════

  Full-width strip, 2 rows, background var(--pulse), text var(--void).
  Font: Orbitron 900, 10vw, uppercase.

  Row 1 → (forward):
  " LAVANDEV — WEB DEV — SECURITY — API — CLOUD — DEVOPS — LAVANDEV — "
  Row 2 ← (reverse):
  " POSSIBLE — SHIP — SECURE — FAST — CLEAN — PRECISE — POSSIBLE — "

  Each row is duplicated (×2 content) for seamless loop:
  gsap.to(".mq-fwd",  { xPercent: -50, duration: 16, ease: "none", repeat: -1 })
  gsap.to(".mq-rev",  { xPercent: +50, duration: 20, ease: "none", repeat: -1 })
  // .mq-rev starts at xPercent: -50 so the first content is the starting visible half

  Scroll velocity effect:
  ScrollTrigger.create({
    onUpdate: self => {
      const v = self.getVelocity() / 400
      gsap.to([fwdTween, revTween], { timeScale: 1 + Math.abs(v) * 0.8,
                                       duration: 0.5, overwrite: true })
    }
  })

  Separator between the two rows: 1px solid var(--void) at 40% opacity.


═══════════════════════════════════════════
 ── SECTION 9: KINETIC TYPOGRAPHY ──
 "CORE PRINCIPLES — SIGNAL BURST"
═══════════════════════════════════════════
  (Award-winning original concept)

  Full viewport section, background var(--void).
  4 massive principle statements, revealed one by one on scroll,
  each with a unique entrance animation:

  Statement 1: "SECURITY IS FOUNDATION."
    - Each letter has a random initial position scattered across the viewport
    - On trigger: letters fly to their correct positions with collision physics
      (simulated: random x/y → 0, varied durations 0.4–1.0s, ease: power3.out)

  Statement 2: "ZERO MIDDLEMEN."
    - Text starts opacity 0, sliced into horizontal strips (10 strips)
    - Each strip reveals in sequence (clipPath: inset(0 0 100% 0) → inset(0 0 0% 0))
    - Stagger: 0.05s per strip, bottom strip first (reversed order)
    - Creates a "venetian blind" up-reveal

  Statement 3: "SHIP. DON'T PERFECT."
    - Text enters from left side, character by character
    - But the period after each word: drops from above with bounce

  Statement 4: "WE BUILD WHAT OTHERS CAN'T."
    - Outlined text (-webkit-text-stroke: 2px var(--pulse), fill: transparent)
    - On scroll reach: fills in from left (clip-path or SVG fill animation)
    - The apostrophe in "CAN'T" blinks on/off 3× before settling

  Font: Orbitron 900, 8vw each. Each on its own full-height panel.
  Left-aligned, vertically centered.


═══════════════════════════════════════════
 ── SECTION 10: PARTICLE FIELD (Three.js) ──
 "DEEP FIELD — AMBIENT SECTION"
═══════════════════════════════════════════

  Canvas: #particles-canvas behind a minimal "philosophy" section.
  2500 particles in a sphere of radius 6.

  UNIQUE CONCEPT — PACKET TRANSMISSION:
  Every 3 seconds, 5 particles simultaneously "fire" from one side of
  the sphere to the opposite (representing data packets). These particles
  move 20× faster than normal, leave a trail (rendered as a thin line
  from old to new position), and pulse bright white on arrival.
  This represents Lavan Dev's "secure, high-performance API engineering."

  ```js
  const count = 2500
  const positions = new Float32Array(count * 3)
  const velocities = new Float32Array(count * 3)
  // Initialize in sphere (Box-Muller / rejection sampling)
  for (let i = 0; i < count; i++) {
    const theta = Math.random() * Math.PI * 2
    const phi = Math.acos(2 * Math.random() - 1)
    const r = 6 * Math.cbrt(Math.random())
    positions[i*3]   = r * Math.sin(phi) * Math.cos(theta)
    positions[i*3+1] = r * Math.sin(phi) * Math.sin(theta)
    positions[i*3+2] = r * Math.cos(phi)
    // Gentle drift: small random velocity
    velocities[i*3]   = (Math.random() - 0.5) * 0.002
    velocities[i*3+1] = (Math.random() - 0.5) * 0.002
    velocities[i*3+2] = (Math.random() - 0.5) * 0.002
  }
  geometry.setAttribute('position', new THREE.BufferAttribute(positions, 3))
  const mat = new THREE.PointsMaterial({
    color: 0x00f0c8, size: 0.018,
    transparent: true, opacity: 0.65, sizeAttenuation: true
  })
  const points = new THREE.Points(geometry, mat)
  ```

  Per-frame:
  - points.rotation.y += 0.0004
  - All particle positions += velocities
  - Boundary: if distance from origin > 6.5, reflect velocity inward
  - geometry.attributes.position.needsUpdate = true

  IntersectionObserver: when section enters view, particles rush
  toward center (multiply velocities by -3 for 2s then ease back).

  Text overlay (centered):
    [section label] // PHILOSOPHY
    "We believe the best systems are the ones nobody notices.
     They just work. Every time. Under any load. Against any threat."
     (Space Grotesk 300, 1.2rem, max-width 600px, centered)


═══════════════════════════════════════════
 ── SECTION 11: NAVBAR ──
 "MISSION CONTROL — PERSISTENT"
═══════════════════════════════════════════

  Position: fixed top, full width, z-index: 100.

  Initial state (over hero):
  - background: transparent
  - backdrop-filter: none

  After first scroll (50px):
  - background: rgba(3,10,16,0.85)
  - backdrop-filter: blur(20px) saturate(180%)
  - border-bottom: 1px solid rgba(0,240,200,0.08)
  - transition: all 0.4s

  Left: "LAVAN" in Orbitron 900, "DEV" in Orbitron 900 var(--pulse).
        Below: a blinking "(●) AVAILABLE" in JetBrains Mono 9px var(--pulse).

  Right: nav links (Space Grotesk 400, 0.9rem):
         Work · Services · About · Contact
  Each link hover: letter scramble effect (fast, 0.4s, settles to original).

  CTA button: "Start a Project" — outlined var(--pulse), same liquid fill hover.


═══════════════════════════════════════════
 ── SECTION 12: FOOTER ──
 "TRANSMISSION COMPLETE"
═══════════════════════════════════════════

  Background: #020810 (near void). Subtle star field visible.

  HERO FOOTER TEXT:
  Huge stacked text, center-aligned:
    LET'S
    BUILD
    SOMETHING
    IMPOSSIBLE.
  Font: Orbitron 900, 13vw. Color: var(--star).
  "IMPOSSIBLE." in var(--pulse).

  Each line enters from below (y: +100 → 0) on scroll enter, stagger 0.12s.

  LETTER SCRAMBLE on hover over any line:
    const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%"
    el.addEventListener("mouseover", () => {
      let iter = 0
      clearInterval(el._si)
      el._si = setInterval(() => {
        el.textContent = el.dataset.value.split("").map((c, i) => {
          if (c === " ") return " "
          if (i < iter) return el.dataset.value[i]
          return chars[Math.floor(Math.random() * chars.length)]
        }).join("")
        if (iter >= el.dataset.value.length) clearInterval(el._si)
        iter += 0.5
      }, 25)
    })

  CTA EMAIL:
    hello@lavandev.com  (scramble on hover, JetBrains Mono 400, var(--pulse))
    [ Start a Project → ] button (same scramble on hover)

  COLUMNS GRID (3 col, below CTA):
  ┌─────────────────┬─────────────────┬──────────────────┐
  │ LAVAN DEV       │ WORK            │ CONNECT          │
  │ est. 2019       │ Web Dev         │ hello@lavandev   │
  │ Tunis, TN       │ Cybersecurity   │ GitHub           │
  │ Available global│ API Engineering │ LinkedIn         │
  │                 │ Cloud & DevOps  │ Twitter / X      │
  └─────────────────┴─────────────────┴──────────────────┘
  All in Space Grotesk 300, var(--dim). Headers in JetBrains Mono, var(--pulse).
  Social link hover: underline drawn (::after scaleX 0→1, origin: left).

  BOTTOM BAR:
  Left:  © 2025 Lavan Dev — All rights reserved
  Right: Crafted in deep space · Tunis, TN
  Both: JetBrains Mono 300, 0.75rem, var(--dim).
  A thin 1px border-top: rgba(0,240,200,0.06).

  AMBIENT FOOTER CANVAS:
  A subtle Canvas2D behind the footer draws slowly drifting horizontal
  scan lines (like an oscilloscope at rest) — thin var(--pulse) lines,
  opacity 0.03, moving top-to-bottom at 0.2px/frame. Feels like idle
  radar signal. Adds cinematic depth without distraction.


═══════════════════════════════════════════
 ── AWARD-WINNING BONUS CONCEPTS ──
 (All must be implemented — these are the differentiators)
═══════════════════════════════════════════

  ─────────────────────────────────────────
  BONUS A: GRAVITY CURSOR DISTORTION FIELD
  ─────────────────────────────────────────
  Apply a real-time SVG feTurbulence displacement filter to the
  entire page. The displacement center follows the cursor position.
  Intensity: VERY subtle (scale: 3–5px) — just enough to feel like
  space is slightly warped around the cursor. Imperceptible from static
  screenshots but unmistakable during interaction.

  ```html
  <svg class="cursor-warp-svg" style="position:fixed;top:0;left:0;
    width:0;height:0;pointer-events:none">
    <filter id="warp-filter">
      <feTurbulence type="fractalNoise" baseFrequency="0.015"
        numOctaves="2" result="noise" seed="2"/>
      <feDisplacementMap in="SourceGraphic" in2="noise"
        scale="4" xChannelSelector="R" yChannelSelector="G"/>
    </filter>
  </svg>
  ```

  Apply to: certain hero elements only (not the whole page — for perf).
  The turbulence `seed` value changes based on mouse proximity to elements,
  creating a subtle ripple effect as the cursor approaches.

  ─────────────────────────────────────────
  BONUS B: SIGNAL TRANSMISSION EASTER EGG
  ─────────────────────────────────────────
  When the user types "LAVAN" anywhere on the page (keyboard):
  1. A full-screen terminal flash: "SECURE_CHANNEL_ESTABLISHED" in Orbitron,
     white text on var(--pulse) background, 0.4s then fades.
  2. All the particle systems accelerate for 2s then settle.
  3. A toast notification appears bottom-right:
     "[ SYS ] Welcome, operator. Connection secured." in JetBrains Mono.

  Track keypresses globally:
  let typed = ""
  document.addEventListener("keypress", e => {
    typed += e.key.toUpperCase()
    if (typed.includes("LAVAN")) { triggerEasterEgg(); typed = "" }
    if (typed.length > 10) typed = typed.slice(-10)
  })

  ─────────────────────────────────────────
  BONUS C: SECTION TRANSITION SWEEP
  ─────────────────────────────────────────
  Between each major section: a thin var(--pulse) horizontal line
  sweeps the full viewport width (scaleX: 0 → 1 → 0, origin left then right).
  Duration: 0.5s. Triggered as the section boundary passes the viewport center.
  This acts as a "wipe" signal — like a radar sweep marking each new area.

  ScrollTrigger on each section start:
    onEnter: () => triggerSweep(),
    onEnterBack: () => triggerSweep()

  ─────────────────────────────────────────
  BONUS D: SCROLL PROGRESS TELEMETRY BAR
  ─────────────────────────────────────────
  At the very top of the viewport: a 2px height bar.
  Left portion: var(--pulse), grows 0% → 100% as page scrolls.
  Right portion: var(--void).
  A small blinking triangle/cursor at the leading edge.
  At 100%: bar flashes 3× then stays full.

  ─────────────────────────────────────────
  BONUS E: MOBILE TERMINAL EXPERIENCE
  ─────────────────────────────────────────
  On mobile (< 768px):
  - Disable all Three.js canvases → replace hero with CSS-only space gradient:
    background: radial-gradient(ellipse at 60% 40%, #0a2040 0%, #030a10 70%)
    + static star dots using box-shadow on a tiny ::before element.
  - Simplify particles: 200 CSS-only animated dots via @keyframes float.
  - Keep: marquee, terminal, kinetic typography, scroll reveals.
  - Constellation: show as a simple list with colored dot indicators instead.
  - All text sizes: max 12vw for headings (clamp(2rem, 10vw, 7rem)).

  ─────────────────────────────────────────
  BONUS F: "WORMHOLE" PROJECT TRANSITION
  ─────────────────────────────────────────
  When clicking "View →" on a project card (before navigating),
  play a 0.6s wormhole animation:
  A circular mask expands from the click point, revealing a deep space
  vortex (Canvas2D spinning spiral, drawn with arc() calls, radiating
  outward). This replaces the standard page transition feel.

  Implementation (if SPA-style navigation between cards):
  canvas.style.display = "block"
  let angle = 0, radius = 0
  const id = requestAnimationFrame(function draw() {
    ctx.clearRect(0,0,W,H)
    ctx.strokeStyle = `rgba(0,240,200,${0.8 - radius/maxR * 0.8})`
    ctx.lineWidth = 2
    ctx.beginPath()
    ctx.arc(clickX, clickY, radius, 0, Math.PI * 2)
    ctx.stroke()
    // Draw spiral arms
    for (let a = 0; a < Math.PI * 6; a += 0.1) {
      const r = (a / (Math.PI * 6)) * radius
      ctx.fillStyle = `rgba(0,240,200,${0.3 - a/(Math.PI*6)*0.3})`
      ctx.fillRect(clickX + r*Math.cos(a+angle), clickY + r*Math.sin(a+angle), 1.5, 1.5)
    }
    radius += 8; angle += 0.1
    if (radius < maxR) requestAnimationFrame(draw)
    else { canvas.style.display = "none" }
  })

  ─────────────────────────────────────────
  BONUS G: NOISE GRAIN OVERLAY
  ─────────────────────────────────────────
  A full-screen fixed <div class="grain"> with:
  - SVG filter: feTurbulence baseFrequency="0.65" numOctaves="3"
  - CSS: opacity: 0.028, mix-blend-mode: overlay
  - Animated: every 200ms re-render turbulence seed changes by 1
    (via JS: turbulence.setAttribute("seed", Math.random()*100))
  - This creates living film grain — organic cinematic texture.
  - pointer-events: none, z-index: 9998.


═══════════════════════════════════════════
 PERFORMANCE & ACCESSIBILITY
═══════════════════════════════════════════

  - All Three.js renderers: setPixelRatio(Math.min(devicePixelRatio, 2))
  - IntersectionObserver to pause/resume Three.js animation loops
    when canvases are off-screen.
  - prefers-reduced-motion: disable all GSAP animations, play once only,
    disable Three.js distortion and particles. Keep static layout.
  - Focus states: outline: 2px solid var(--pulse), offset: 4px.
  - All images/icons have alt attributes.
  - ARIA labels on all icon buttons.
  - Debounce resize handlers at 150ms.
  - Three.js geometries: .dispose() on scene rebuild.

  MOBILE BREAKPOINTS:
  < 768px:  Disable WebGL. Simplified CSS animations. Single-column layout.
  768–1024: Reduce particle count to 800. Keep all GSAP.
  > 1024px: Full experience.


═══════════════════════════════════════════
 OUTPUT SPECIFICATION
═══════════════════════════════════════════

  Deliver a SINGLE index.html file.
  - All CSS inside <style> in <head>
  - All JavaScript inside <script> at end of <body>
  - No external files, no imports beyond CDN links in <head>
  - No placeholder comments — write actual, working code
  - No simplified stubs — every listed feature fully implemented
  - Sections in order: Loader → Nav → Hero → Stats → Services →
    Who We Are → Process → Projects → Competencies → Marquee →
    Kinetic Type → Particles → Footer
  - All real Lavan Dev data must be present, exactly as specified above
  - Do not invent fake testimonials or client names not listed above