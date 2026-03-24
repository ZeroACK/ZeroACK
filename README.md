
# Hello👋, Welcome to visit my profile! 🫡


<style>
.glass-photo-wrap {
  width: min(50%, 420px);
  margin: 0 0 1rem 1.25rem;
}

.glass-photo-wrap.align-right {
  float: right;
}

.glass-photo {
  position: relative;
  border-radius: 18px;
  padding: 10px;
  overflow: hidden;
  background:
    linear-gradient(145deg, rgba(255,255,255,0.28), rgba(255,255,255,0.08));
  border: 1px solid rgba(255,255,255,0.28);
  box-shadow:
    0 8px 24px rgba(0,0,0,0.18),
    inset 0 1px 0 rgba(255,255,255,0.35),
    inset 0 -1px 0 rgba(255,255,255,0.08);
  backdrop-filter: blur(6px) saturate(140%);
  -webkit-backdrop-filter: blur(6px) saturate(140%);
  transform: translateY(0);
  transition:
    transform 0.35s ease,
    box-shadow 0.35s ease,
    border-color 0.35s ease;
}

.glass-photo::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: inherit;
  background:
    linear-gradient(
      115deg,
      rgba(255,255,255,0) 18%,
      rgba(255,255,255,0.08) 34%,
      rgba(255,255,255,0.42) 50%,
      rgba(255,255,255,0.08) 66%,
      rgba(255,255,255,0) 82%
    );
  transform: translateX(-140%) skewX(-18deg);
  transition: transform 0.7s ease;
  pointer-events: none;
  z-index: 2;
}

.glass-photo::after {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: inherit;
  background:
    linear-gradient(to bottom, rgba(255,255,255,0.22), rgba(255,255,255,0.02) 28%, rgba(255,255,255,0) 48%);
  pointer-events: none;
  z-index: 1;
}

.glass-photo:hover {
  transform: translateY(-8px);
  border-color: rgba(255,255,255,0.4);
  box-shadow:
    0 18px 42px rgba(0,0,0,0.28),
    0 6px 14px rgba(255,255,255,0.08),
    inset 0 1px 0 rgba(255,255,255,0.48),
    inset 0 -1px 0 rgba(255,255,255,0.1);
}

.glass-photo:hover::before {
  transform: translateX(140%) skewX(-18deg);
}

.glass-photo img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 12px;
  position: relative;
  z-index: 0;
}
</style>
<div class="glass-photo-wrap align-right">
  <div class="glass-photo">
    <img
      src="https://raw.githubusercontent.com/ZeroACK/ZeroACK/main/res/DSCF0143_SRGB_Internet.jpg"
      alt="img"
    />
  </div>
</div>

### Hi there, 😉

- 🎓 I’m currently pursuing a Master’s degree in Cybersecurity
- 💻 My main programming languages are C/C++ and Python
- 🔐 My research interests include Network Security, Intrusion Detection, and Graph-based Learning
- 🌱 I’m currently exploring Cybersecurity, Machine Learning, and Intelligent Detection Systems
- 🛠️ I enjoy building projects related to security analysis, data processing, and AI
- 👯 I’m open to collaborating on open source projects in Cybersecurity, C/C++, and Python