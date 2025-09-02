## Sa <img src="https://media.giphy.com/media/Q7LHmoFwVP6Yc1swZs/giphy.gif" height="20px"></h2>

### Ben Furkan Kaya çok bi bot deneyimim yok kendi çapımda takılıyorum kullandığım botları burada paylaşıcam.

<h1 align="center"><img src="https://readme-typing-svg.herokuapp.com?font=Pacifico&pause=1000&color=ff3235&background=69FF2000&center=true&vCenter=true&repeat=false&width=435&lines=+Connect+With+Me" alt="Typing SVG" /></h1>

<div align="left">
  <a target="_blank" rel="noopener noreferrer" href="https://discord.com/users/1397270331970027530">
    <img alt="Discord" align="center" src="https://discord.com/assets/cb48d2a8d4991281d7a6a95d2f58195e.svg" style="height:50px; width:50px;" />
  </a>
</div>

<h1 align="center"><img src="https://readme-typing-svg.herokuapp.com?font=Pacifico&pause=1000&color=326EFF&background=69FF2000&center=true&vCenter=true&repeat=false&width=435&lines=+My+Discord+Account's" alt="Typing SVG" /></h1>

[![Discord Profilim](https://lanyard.cnrad.dev/api/1397270331970027530)](https://discord.com/users/1397270331970027530)

<div align="center">
  <h3><b>📍 Profilime Kaç Kişi Baktı</b></h3>
</div>
<p align="center">    
  <img src="https://kayaaaq-counter.vercel.app/api/count" alt="Visitor Counter" />
</p>

/api
  └── count.js

export default async function handler(req, res) {
  const count = Math.floor(Math.random() * 1000) + 100; // Geçici
  
  res.setHeader('Content-Type', 'image/svg+xml');
  res.status(200).send(`
    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="20">
      <rect width="120" height="20" fill="#0066cc"/>
      <text x="60" y="15" font-family="Arial" font-size="12" fill="white" text-anchor="middle">
        Visitors: ${count}
      </text>
    </svg>
  `);
}
