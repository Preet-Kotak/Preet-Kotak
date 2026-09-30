<h1 align="center">Hi 👋, I'm Preet Kotak</h1>
<p align="center">
  <a href="https://preet-kotak.vercel.app">preet-kotak.vercel.app</a>
</p>

```
BEGIN PROFILE "Preet Kotak"

    DEFINE education = "B.Tech CSE, SVNIT Surat — Batch of 2028"

    DEFINE stack = {
        languages : [Python, C, C++, JavaScript, Assembly(8086)],
        backend   : [Node.js, Express, discord.py],
        frontend  : [React, Tailwind CSS, HTML, CSS],
        ml_cv     : [YOLO, PyTorch, OpenCV, NumPy, SciPy],
        data      : [MongoDB, PostgreSQL, Redis, Supabase]
    }

    DEFINE side_quests = [
        "competitive programming, mostly in C++",
        "set up a DOSBox/TASM environment just to write x86 assembly"
    ]

    FUNCTION projects():
        RETURN {

            "BidKar": {
                what  : "real-time auction platform",
                scale : "16 concurrent Node.js workers",
                stack : "MongoDB Atlas, Redis, Cloudinary"
            },

            "ClanCapitalBot": {
                what  : "Discord bot running Clan Capital tournaments end-to-end",
                size  : "~5000 lines, Python / discord.py / PostgreSQL",
                extra : "43 slash commands across 7 cogs, 9-table relational schema, " +
                        "PIL-generated match-result images, anti-scam honeypot channel"
            },

            "8086_Assembly_Calculator": {
                what  : "multi-digit calculator written entirely in 16-bit x86 assembly",
                size  : "4059 lines of raw ASM",
                extra : "32-bit arithmetic on 16-bit hardware by chaining register pairs, " +
                        "fixed-point decimal math, custom digit-by-digit square root, " +
                        "hand-drawn 80x25 text-mode UI navigated with arrow keys",
                why   : "microprocessor coursework wasn't painful enough on its own"
            },

            "BaseFinder": {
                what  : "object detection & layout matching pipeline",
                stack : "YOLO11m, PyTorch, OpenCV, SciPy, Hungarian algorithm",
                extra : "trained YOLO11m on 468 labeled images (23 defence classes), " +
                        "0.936 mAP50 on test set, matches detected layouts against 750+ database entries, " +
                        "confidence auto-calibration, visual comparison tools"
            },

            "KissanLink": {
                what   : "WhatsApp farm marketplace for rural Gujarat",
                why    : "target users are on 2G, nobody's installing an app",
                stack  : "Twilio + Node.js/Express + MongoDB (2dsphere geo)",
                status : "Biothon 2026 finalist"
            },

            "MindSprint": {
                what      : "subscription-tracking dashboard",
                my_part   : "frontend — HTML/CSS/JS, Tailwind, Chart.js, JWT auth flow",
                built_for : "hackathon, teammate handled the backend"
            },

            "PortfolioSite": {
                what   : "personal developer portfolio, Clash of Clans-style isometric village theme",
                stack  : "React 19, Phaser 4, Vite, Tailwind CSS, EmailJS",
                extra  : "isometric village game with modal info panels, live Codeforces/LeetCode/GitHub stats, " +
                        "guided tutorial overlay, Q&A chat panel, dark/light theme toggle"
            }
        }
    END FUNCTION

    FUNCTION achievements():
        RETURN [
            "Biothon 2026 — finalist (KissanLink)",
            "4059 lines of hand-written 8086 assembly, and it actually runs"
        ]
    END FUNCTION

    FUNCTION contact():
        RETURN {
            github     : "github.com/Preet-Kotak",
            portfolio  : "preet-kotak.vercel.app",
            linkedin   : "linkedin.com/in/preet-kotak-8538b033a",
            codeforces : "codeforces.com/profile/Preet-Kotak",
            resume     : "https://docs.google.com/document/d/15jJ-j8FJX7ntpnp21Lv3mD8RdQsfIsSg/edit?usp=drive_link",
            email      : "preetdkotak@gmail.com"
        }
    END FUNCTION

    FUNCTION readme():
        # yeah, this file doubles as my GitHub profile README —
        # figured a static bio was a waste when I could just ship the source
        RETURN "you're looking at it right now."
    END FUNCTION

    FUNCTION github_stats():
        # pulled live every time this page loads — not hand-updated
        response = HTTP_GET("https://api.github.com/users/Preet-Kotak")
        RETURN {
            public_repos : response.public_repos,
            followers    : response.followers,
            following    : response.following
        }
    END FUNCTION

    ON LOAD:
        PRINT "<Preet Kotak — builds it, breaks it, fixes it, ships it>"
        PRINT projects()
        PRINT readme()
        PRINT github_stats()

END PROFILE
```

<br>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Preet-Kotak&theme=dark&hide_border=true" alt="GitHub Streak" height="170"/>
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Preet-Kotak&layout=compact&theme=dark&hide_border=true&langs_count=6" alt="Top Languages" height="170"/>
</div>

<br>

## 📈 Contribution Activity

<div align="center">
  <img src="https://ssr-contributions-svg.vercel.app/_/Preet-Kotak?chart=3dbar&gap=0.6&scale=2&flatten=2&format=svg&weeks=30&theme=native&dark=true" alt="GitHub Contribution Chart"/>
</div>

<br>

---

## 🔗 Connect With Me

<div align="center">
  
[![GitHub](https://img.shields.io/badge/GitHub-Preet--Kotak-181717?style=for-the-badge&logo=github)](https://github.com/Preet-Kotak)
[![Portfolio](https://img.shields.io/badge/Portfolio-preet--kotak.vercel.app-4a5568?style=for-the-badge&logo=vercel)](https://preet-kotak.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Preet%20Kotak-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/preet-kotak-8538b033a)
[![Codeforces](https://img.shields.io/badge/Codeforces-Preet--Kotak-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Preet-Kotak)
[![Resume](https://img.shields.io/badge/Resume-View%20Here-success?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/document/d/15jJ-j8FJX7ntpnp21Lv3mD8RdQsfIsSg/edit?usp=drive_link)
[![Email](https://img.shields.io/badge/Email-preetdkotak@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:preetdkotak@gmail.com)

</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Preet-Kotak&label=Profile%20Views&color=blueviolet&style=flat-square" alt="Profile Views"/>
</div>
