```aura width=900 height=260
<>
  <style>{`
    @keyframes floatUp {
      0% { transform: translateY(0px); opacity: 0.85; }
      50% { transform: translateY(-10px); opacity: 1; }
      100% { transform: translateY(0px); opacity: 0.85; }
    }
    @keyframes sweep {
      0% { transform: translateX(-220px); opacity: 0; }
      20% { opacity: 0.35; }
      50% { opacity: 0.5; }
      80% { opacity: 0.2; }
      100% { transform: translateX(220px); opacity: 0; }
    }
    #orb-1 { animation: floatUp 7s ease-in-out infinite; }
    #orb-2 { animation: floatUp 9s ease-in-out infinite reverse; }
    #sweep { animation: sweep 6s linear infinite; }
  `}</style>
  <svg width="900" height="260" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stopColor="#0b1220" />
        <stop offset="100%" stopColor="#111827" />
      </linearGradient>
      <radialGradient id="orb" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#60a5fa" stopOpacity="0.7" />
        <stop offset="100%" stopColor="#1f2937" stopOpacity="0" />
      </radialGradient>
      <linearGradient id="scan" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stopColor="#22d3ee" stopOpacity="0" />
        <stop offset="50%" stopColor="#22d3ee" stopOpacity="0.35" />
        <stop offset="100%" stopColor="#22d3ee" stopOpacity="0" />
      </linearGradient>
    </defs>

    <rect width="900" height="260" rx="24" fill="url(#bg)" />

    <circle id="orb-1" cx="140" cy="90" r="120" fill="url(#orb)" />
    <circle id="orb-2" cx="760" cy="190" r="130" fill="url(#orb)" />

    <rect id="sweep" x="340" y="20" width="220" height="220" rx="24" fill="url(#scan)" />

    <text x="70" y="120" fill="#f8fafc" fontSize="40" fontWeight="700" fontFamily="Inter, Arial, sans-serif">
      Eshaan Jaiswal
    </text>
    <text x="70" y="158" fill="#94a3b8" fontSize="18" fontFamily="Inter, Arial, sans-serif">
      Computer Vision | ML | Systems
    </text>
    <text x="70" y="195" fill="#cbd5f5" fontSize="14" fontFamily="Inter, Arial, sans-serif">
      Research at CVIG Lab, IIT Gandhinagar
    </text>
  </svg>
</>
```

```aura width=160 height=44 link="https://eshaanjaiswal.github.io" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/googlechrome/ffffff"
  text="Website"
  width={160}
  height={44}
  backgroundColor="#0b4f6c"
  textColor="#ffffff"
  iconSize={20}
  gradientStrokeWidth={2}
/>
```
```aura width=150 height=44 link="https://github.com/EshaanJaiswal" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/ffffff"
  text="GitHub"
  width={150}
  height={44}
  backgroundColor="#111827"
  textColor="#ffffff"
  iconSize={20}
  gradientStrokeWidth={2}
/>
```
```aura width=160 height=44 link="https://www.linkedin.com/in/eshaanjaiswal" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/linkedin/ffffff"
  text="LinkedIn"
  width={160}
  height={44}
  backgroundColor="#0a66c2"
  textColor="#ffffff"
  iconSize={20}
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
  <svg width="900" height="160" viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg">
    <rect width="900" height="160" rx="22" fill="#0f172a" />
    <circle id="dot" cx="90" cy="80" r="8" fill="#22c55e" />
    <text x="120" y="88" fill="#e2e8f0" fontSize="20" fontWeight="600" fontFamily="Inter, Arial, sans-serif">
      Currently exploring motion dynamics in generative models
    </text>
    <text x="120" y="114" fill="#94a3b8" fontSize="14" fontFamily="Inter, Arial, sans-serif">
      Always open to research collaborations and interesting problems.
    </text>
  </svg>
</>
```
