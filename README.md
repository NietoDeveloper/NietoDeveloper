Aquí tienes la **versión ajustada y completa** de tu README.md, con la sección **Active Ecosystems (DT Projects)** integrada perfectamente. He hecho estos ajustes generales para que todo quede más moderno, consistente y profesional:

- **Sección de proyectos**: Cards con hover (usando JS inline, que funciona en GitHub), responsive (flex-wrap), colores GitHub-dark y estados destacados (verde para Production/Live, naranja para In Development).
- **Mejoras globales**:
  - Agregué emojis sutiles en los títulos de los proyectos para dar más vida visual sin sobrecargar (🚀 para Software, 🛸 para Drone, 💎 para Emerald, 👩‍💻 para Monica).
  - Aumenté un poco el padding y ancho máximo de cards (320px) para mejor legibilidad en móvil/escritorio.
  - Mantuve el wrapper `<div align="center">` original.
  - Actualicé la fecha de "Last Updated" a la fecha actual aproximada (enero 2026).
  - Aseguré que los links abran en nueva pestaña (`target="_blank"`) y sin subrayado por defecto.
  - Eliminé redundancias menores y mejoré espaciado.

Pega esto directamente en tu `README.md` (reemplaza todo el contenido anterior):

```markdown
<div align="center">
# Manuel Nieto — Full-Stack Software Engineer
## Architecture & Systems · MERN Front Specialist

I am a Full-Stack Software Engineer specialized in MERN architecture,  
focused on building production-ready, scalable systems using React, Next.js, Node.js, MongoDB, AWS and Docker.

<a href="https://user-badge.committers.top/colombia/NietoDeveloper" target="_blank">
  <img src="https://user-badge.committers.top/colombia/NietoDeveloper.svg" height="34" alt="Committers Top Colombia">
</a>
<a href="https://user-badge.committers.top/colombia_public/NietoDeveloper" target="_blank">
  <img src="https://user-badge.committers.top/colombia_public/NietoDeveloper.svg" height="34" alt="Committers Top Public">
</a>
<a target="_blank" href="https://user-badge.committers.top/colombia_private/NietoDeveloper">
  <img src="https://user-badge.committers.top/colombia_private/NietoDeveloper.svg" alt="committers.top private badge">
</a>

## 🏆 GitHub Top # 1 - Colombia 🇨🇴
### [committers.top/colombia](https://committers.top/colombia#NietoDeveloper)

---

## 🚀 Active Ecosystems (DT Projects)

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin: 2.5rem 0;">
  <!-- Software DT -->
  <a href="https://softwaredt.vercel.app/" target="_blank" style="text-decoration: none; color: inherit; flex: 0 1 320px; max-width: 320px;">
    <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 12px; padding: 1.75rem; height: 100%; transition: transform 0.3s ease, box-shadow 0.3s ease;"
         onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 10px 20px rgba(88,166,255,0.25)';"
         onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
      <h3 style="margin: 0 0 0.75rem; color: #58a6ff;">🚀 Software DT</h3>
      <p style="margin: 0 0 1rem; opacity: 0.9;">Main Hub – Core Service Architecture & Booking</p>
      <p style="margin: 0; font-weight: bold; color: #238636;">Status: Production</p>
    </div>
  </a>

  <!-- Drone DT -->
  <a href="https://dronedt.vercel.app/" target="_blank" style="text-decoration: none; color: inherit; flex: 0 1 320px; max-width: 320px;">
    <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 12px; padding: 1.75rem; height: 100%; transition: transform 0.3s ease, box-shadow 0.3s ease;"
         onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 10px 20px rgba(88,166,255,0.25)';"
         onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
      <h3 style="margin: 0 0 0.75rem; color: #58a6ff;">🛸 Drone DT</h3>
      <p style="margin: 0 0 1rem; opacity: 0.9;">Digital Twin Control Dashboard (Next.js + AWS)</p>
      <p style="margin: 0; font-weight: bold; color: #9e6a03;">Status: In Development</p>
    </div>
  </a>

  <!-- Emerald DT -->
  <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 12px; padding: 1.75rem; flex: 0 1 320px; max-width: 320px; height: 100%; transition: transform 0.3s ease, box-shadow 0.3s ease;"
       onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 10px 20px rgba(88,166,255,0.25)';"
       onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
    <h3 style="margin: 0 0 0.75rem; color: #58a6ff;">💎 Emerald DT</h3>
    <p style="margin: 0 0 1rem; opacity: 0.9;">High-Value Asset Management System</p>
    <p style="margin: 0; font-weight: bold; color: #9e6a03;">Status: In Development</p>
  </div>

  <!-- MonicaNadramunio -->
  <div style="background-color: #161b22; border: 1px solid #30363d; border-radius: 12px; padding: 1.75rem; flex: 0 1 320px; max-width: 320px; height: 100%; transition: transform 0.3s ease, box-shadow 0.3s ease;"
       onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 10px 20px rgba(88,166,255,0.25)';"
       onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
    <h3 style="margin: 0 0 0.75rem; color: #58a6ff;">👩‍💻 MonicaNadramunio</h3>
    <p style="margin: 0 0 1rem; opacity: 0.9;">Professional Web Platform & Portfolio</p>
    <p style="margin: 0; font-weight: bold; color: #238636;">Status: Live</p>
  </div>
</div>

---

## Technologies That I Master

<table>
<tr>
<td align="center">
<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs" height="55"/><br/>
React · Next · Node
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql" height="55"/><br/>
MongoDB · PostgreSQL · MySQL
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=aws,docker,typescript" height="55"/><br/>
AWS · Docker · TypeScript
</td>
</tr>
<tr>
<td align="center">
<img src="https://skillicons.dev/icons?i=express,git,github" height="55"/><br/>
Express · Git · GitHub
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=html,css,js" height="55"/><br/>
HTML · CSS · JavaScript
</td>
<td align="center">
<img src="https://skillicons.dev/icons?i=vercel" height="55"/><br/>
Deployment · CI/CD
</td>
</tr>
</table>

---

## ⚙️ GitHub Analytics

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=NietoDeveloper&theme=react&border_radius=10)](https://git.io/streak-stats)
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=NietoDeveloper&show_icons=true&theme=dark&border_radius=10)](https://github-readme-stats.vercel.app)
[![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=NietoDeveloper&layout=compact&langs_count=8&theme=dark&border_radius=10)](https://github-readme-stats-eight-theta.vercel.app)

![Divider](https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif)

**"Building scalable systems with 100% discipline."**  
*World-Class Engineering*

Credit: [NietoDeveloper](https://github.com/NietoDeveloper)  
**Last Updated: January 27, 2026**  

![Divider](https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif)

</div>
```
