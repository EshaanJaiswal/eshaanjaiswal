```aura width=900 height=260
<>
  <style>{`
    @keyframes floatUp {
      0% { transform: translateY(0px); opacity: 0.75; }
      50% { transform: translateY(-14px); opacity: 1; }
      100% { transform: translateY(0px); opacity: 0.75; }
    }
    @keyframes drift {
      0% { transform: translateX(0px) translateY(0px); opacity: 0.5; }
      50% { transform: translateX(18px) translateY(-8px); opacity: 0.9; }
      100% { transform: translateX(0px) translateY(0px); opacity: 0.5; }
    }
    @keyframes scan {
      0% { transform: translateX(-260px); opacity: 0; }
      20% { opacity: 0.4; }
      50% { opacity: 0.6; }
      80% { opacity: 0.2; }
      100% { transform: translateX(260px); opacity: 0; }
    }
    @keyframes shimmer {
      0% { opacity: 0.15; }
      50% { opacity: 0.45; }
      100% { opacity: 0.15; }
    }
    #orb-1 { animation: floatUp 7s ease-in-out infinite; }
    #orb-2 { animation: floatUp 9s ease-in-out infinite reverse; }
    #orb-3 { animation: drift 8s ease-in-out infinite; }
    #scan { animation: scan 6s linear infinite; }
    #shimmer { animation: shimmer 4s ease-in-out infinite; }
  `}</style>
  <div
    style={{
      width: 900,
      height: 260,
      borderRadius: 24,
      overflow: 'hidden',
      position: 'relative',
      display: 'flex',
      background: 'radial-gradient(circle at 15% 20%, #1e3a8a 0%, #0b1220 38%, #0b1220 100%)',
      fontFamily: 'Inter, Arial, sans-serif',
    }}
  >
    <svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <radialGradient id="orb" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="#60a5fa" stopOpacity="0.7" />
          <stop offset="100%" stopColor="#1f2937" stopOpacity="0" />
        </radialGradient>
        <radialGradient id="orb-warm" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="#f59e0b" stopOpacity="0.5" />
          <stop offset="100%" stopColor="#111827" stopOpacity="0" />
        </radialGradient>
        <linearGradient id="scan" x1="0" y1="0" x2="1" y2="0">
          <stop offset="0%" stopColor="#22d3ee" stopOpacity="0" />
          <stop offset="50%" stopColor="#22d3ee" stopOpacity="0.35" />
          <stop offset="100%" stopColor="#22d3ee" stopOpacity="0" />
        </linearGradient>
        <linearGradient id="glow" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0%" stopColor="#38bdf8" stopOpacity="0" />
          <stop offset="45%" stopColor="#38bdf8" stopOpacity="0.25" />
          <stop offset="100%" stopColor="#a5b4fc" stopOpacity="0" />
        </linearGradient>
      </defs>

      <circle id="orb-1" cx="140" cy="90" r="120" fill="url(#orb)" />
      <circle id="orb-2" cx="760" cy="190" r="130" fill="url(#orb)" />
      <circle id="orb-3" cx="520" cy="70" r="90" fill="url(#orb-warm)" />

      <rect id="shimmer" x="0" y="0" width="900" height="260" fill="url(#glow)" />

      <rect id="scan" x="320" y="18" width="260" height="224" rx="28" fill="url(#scan)" />
    </svg>

    <div
      style={{
        position: 'absolute',
        left: 70,
        top: 78,
        display: 'flex',
        flexDirection: 'column',
      }}
    >
      <div style={{ color: '#f8fafc', fontSize: 40, fontWeight: 700, lineHeight: 1.1 }}>
        Eshaan Jaiswal
      </div>
      <div style={{ color: '#94a3b8', fontSize: 18, marginTop: 10 }}>
        Computer Vision | ML | Systems
      </div>
      <div style={{ color: '#cbd5f5', fontSize: 14, marginTop: 10 }}>
        Research at CVIG Lab, IIT Gandhinagar
      </div>
    </div>
  </div>
</>
```

```aura width=160 height=44 link="https://eshaanjaiswal.github.io" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/googlechrome/0b1220"
  text="Website"
  width={160}
  height={44}
  backgroundColor="#e2e8f0"
  textColor="#0b1220"
  iconSize={22}
  borderColor="#cbd5f5"
  gradientStrokeWidth={2}
/>
```
```aura width=150 height=44 link="https://github.com/EshaanJaiswal" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/0b1220"
  text="GitHub"
  width={150}
  height={44}
  backgroundColor="#e2e8f0"
  textColor="#0b1220"
  iconSize={22}
  borderColor="#cbd5f5"
  gradientStrokeWidth={2}
/>
```
```aura width=160 height=44 link="https://www.linkedin.com/in/eshaanjaiswal" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/linkedin/0b1220"
  text="LinkedIn"
  width={160}
  height={44}
  backgroundColor="#e2e8f0"
  textColor="#0b1220"
  iconSize={22}
  borderColor="#cbd5f5"
  gradientStrokeWidth={2}
/>
```

---

## About
- 2nd Year undergraduate in Computer Science and Engineering at IIT Gandhinagar.
- Interests: Computer Vision, Deep Learning, Machine Learning, Computer Architecture, Systems, and Algorithmic Research.
- I focus on strong theory backed by practical experimentation.

## Research
- Working under Prof. Shanmuganathan at the CVIG Lab, IIT Gandhinagar.
- Focus: Motion Dynamics in Generative Models for motion and visual synthesis.

## Experience
- Delivery Data Scientist Intern, Turing (May 2025 - July 2025).

## Skills
- Languages: C, C++, Python, SQL, HTML, CSS, JavaScript, Verilog.
- Core Interests: Computer Vision, Deep Learning, Machine Learning, Computer Architecture, Systems, Competitive Programming, Web Development.
- Foundations: Data Structures and Algorithms.

---

```aura width=900 height=160
<>
  <style>{`
    @keyframes pulse {
      0% { opacity: 0.55; }
      50% { opacity: 1; }
      100% { opacity: 0.55; }
    }
    #dot { animation: pulse 2.5s ease-in-out infinite; }
  `}</style>
  <div
    style={{
      width: 900,
      height: 160,
      borderRadius: 22,
      overflow: 'hidden',
      position: 'relative',
      display: 'flex',
      background: '#0f172a',
      fontFamily: 'Inter, Arial, sans-serif',
    }}
  >
    <svg width="900" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg">
      <circle id="dot" cx="90" cy="80" r="8" fill="#22c55e" />
    </svg>
    <div
      style={{
        position: 'absolute',
        left: 120,
        top: 56,
        display: 'flex',
        flexDirection: 'column',
      }}
    >
      <div style={{ color: '#e2e8f0', fontSize: 20, fontWeight: 600 }}>
        Currently exploring motion dynamics in generative models
      </div>
      <div style={{ color: '#94a3b8', fontSize: 14, marginTop: 8 }}>
        Always open to research collaborations and interesting problems.
      </div>
    </div>
  </div>
</>
```
