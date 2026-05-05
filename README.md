<a name="top"></a>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=12,2,30,24&height=330&section=header&text=FUN%20PARTICLE&fontSize=86&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=interactive%20particles%20%2B%20live%20feedback%20experience&descAlignY=62&descSize=20" width="100%" alt="Fun Particle animated header" />

<a href="https://particle.yogender1.me">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=25&duration=2300&pause=650&color=5EEAD4&background=00000000&center=true&vCenter=true&multiline=true&width=950&height=95&lines=gesture+controlled+particle+gravity;audio+reactive+visuals+and+battle+modes;Firebase+powered+feedback+stream" alt="Animated project intro" />
</a>

<br />

<a href="https://particle.yogender1.me">
  <img src="https://img.shields.io/badge/Launch%20App-particle.yogender1.me-00d4ff?style=for-the-badge&labelColor=050816" height="40" alt="Launch app" />
</a>
&nbsp;
<a href="https://particle.yogender1.me/feedback.html">
  <img src="https://img.shields.io/badge/Live%20Feedback-Rate%20and%20Suggest-a78bfa?style=for-the-badge&labelColor=050816" height="40" alt="Open feedback page" />
</a>
&nbsp;
<a href="https://github.com/yogender-ai/Fun-Particle-feedback">
  <img src="https://img.shields.io/badge/GitHub-Fun--Particle--feedback-111111?style=for-the-badge&logo=github&logoColor=white" height="40" alt="GitHub repository" />
</a>

<br /><br />

<img src="https://img.shields.io/github/stars/yogender-ai/Fun-Particle-feedback?style=for-the-badge&logo=apachespark&color=fbbf24&labelColor=050816&logoColor=fbbf24" alt="GitHub stars" />
<img src="https://img.shields.io/github/forks/yogender-ai/Fun-Particle-feedback?style=for-the-badge&logo=git&color=a78bfa&labelColor=050816" alt="GitHub forks" />
<img src="https://img.shields.io/github/issues/yogender-ai/Fun-Particle-feedback?style=for-the-badge&logo=github&color=ef4444&labelColor=050816" alt="GitHub issues" />
<img src="https://img.shields.io/github/last-commit/yogender-ai/Fun-Particle-feedback?style=for-the-badge&logo=githubactions&color=22c55e&labelColor=050816" alt="Last commit" />

<br /><br />

<img src="https://github-readme-stats.vercel.app/api/pin/?username=yogender-ai&repo=Fun-Particle-feedback&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5eead4&icon_color=fbbf24" alt="Fun Particle Feedback GitHub card" />

</div>

---

<div align="center">

### Quick Navigation

[![Overview](https://img.shields.io/badge/Overview-0d1117?style=for-the-badge&labelColor=0d1117&color=5eead4)](#overview)
[![Highlights](https://img.shields.io/badge/Highlights-0d1117?style=for-the-badge&labelColor=0d1117&color=a78bfa)](#highlights)
[![Flow](https://img.shields.io/badge/Flow-0d1117?style=for-the-badge&labelColor=0d1117&color=fbbf24)](#feedback-flow)
[![Stack](https://img.shields.io/badge/Stack-0d1117?style=for-the-badge&labelColor=0d1117&color=22c55e)](#tech-stack)
[![Support](https://img.shields.io/badge/Support-0d1117?style=for-the-badge&labelColor=0d1117&color=ef4444)](#support)

</div>

---

## Overview

**Fun Particle Feedback** is the presentation and feedback hub for **Fun Particle**, an interactive browser experience where particle gravity responds to hand gestures, music, and game-like modes.

The feedback page gives visitors a simple way to rate the project, report bugs, share ideas, and help shape the next version.

<div align="center">

| Live App | Feedback Page | Repository |
| --- | --- | --- |
| [particle.yogender1.me](https://particle.yogender1.me) | [Send Feedback](https://particle.yogender1.me/feedback.html) | [Fun-Particle-feedback](https://github.com/yogender-ai/Fun-Particle-feedback) |

</div>

---

## Highlights

<div align="center">

| Area | What it adds |
| --- | --- |
| Interactive particles | A browser-based particle playground controlled by hand motion. |
| Gesture tracking | Webcam input turns finger movement into gravity and visual effects. |
| Visual modes | Swarm, Heart, Saturn, Flower, Fireworks, Duel, Battle, and Survival. |
| Audio reaction | Particles can react to uploaded audio, direct audio URLs, or microphone input. |
| Feedback system | Users can rate the app, choose categories, and write suggestions. |
| Live stream | Feedback appears in a live feed so the project feels active and community-driven. |
| Firebase support | Google sign-in and Firestore keep feedback organized and protected. |
| Creator-ready README | Animated banners, badges, diagrams, and clear project links for GitHub visitors. |

</div>

---

## Experience Map

```mermaid
flowchart LR
    A[Visitor opens Fun Particle] --> B[Allows camera]
    B --> C[Controls particles with hand gestures]
    C --> D[Tries modes and audio reaction]
    D --> E[Opens feedback page]
    E --> F[Signs in with Google]
    F --> G[Sends rating, category, and message]
    G --> H[Feedback appears in live stream]
    H --> I[Creator improves next version]
```

---

## Feedback Flow

```mermaid
sequenceDiagram
    participant User
    participant Page as Feedback Page
    participant Auth as Google Sign-In
    participant API as Feedback API
    participant DB as Firestore

    User->>Page: Opens feedback experience
    User->>Auth: Signs in with Google
    Auth-->>Page: Returns verified user
    User->>Page: Adds rating and message
    Page->>API: Sends feedback payload
    API->>DB: Saves feedback
    DB-->>API: Returns latest feedback list
    API-->>Page: Sends stats and stream
    Page-->>User: Shows confirmation
```

---

## Tech Stack

<div align="center">

| Layer | Tools |
| --- | --- |
| Frontend | HTML, CSS, JavaScript |
| Visual Engine | Three.js, WebGL |
| Tracking | MediaPipe Hands |
| Audio | Web Audio API |
| Auth | Firebase Authentication |
| Data | Firebase Firestore |
| Hosting | Vercel, Render, or static hosting |

</div>

---

## Project Links

<div align="center">

| Link | URL |
| --- | --- |
| Live project | https://particle.yogender1.me |
| Feedback page | https://particle.yogender1.me/feedback.html |
| GitHub repo | https://github.com/yogender-ai/Fun-Particle-feedback |
| Creator GitHub | https://github.com/yogender-ai |
| Creator LinkedIn | https://www.linkedin.com/in/yogender1/ |

</div>

---

## Roadmap Ideas

- Add more feedback categories.
- Add public feature voting.
- Show recent ratings in a cleaner dashboard.
- Add admin moderation for feedback entries.
- Add shareable mode links for Fun Particle.
- Add a short demo video or GIF preview to the README.
- Add screenshots for desktop and mobile views.

---

## Creator

<div align="center">

Built by **Yogender**

<br />

<a href="https://www.linkedin.com/in/yogender1/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="https://github.com/yogender-ai">
  <img src="https://img.shields.io/badge/GitHub-yogender--ai-111111?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

## Support

<div align="center">

If Fun Particle made you smile, star the repository and send feedback from the live app.

<br /><br />

<a href="https://github.com/yogender-ai/Fun-Particle-feedback">
  <img src="https://img.shields.io/badge/Star%20the%20Repo-Thank%20You-FFD700?style=for-the-badge&logo=github&logoColor=000&labelColor=050816" alt="Star the repository" />
</a>

<br /><br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,30,24&height=150&section=footer&animation=twinkling" width="100%" alt="Animated footer" />

<a href="#top">Back to top</a>

</div>
