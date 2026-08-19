# 🔓 UnlockTool – Complete Admin System (Login + Dashboard)
https://unlocktool-system-managment.vercel.app/index.html
**Author:** Adam Salhi (Adam Der SEO)  
**Tech stack:** HTML5, CSS3, JavaScript, Chart.js, SheetJS  
**Features:**  
- Neon cyberpunk admin login with validation  
- Full‑featured dashboard: sales, accounts, bugs, problems, issues  
- CRUD operations (add/edit/delete) on all tables  
- Data persistence using localStorage  
- Export to Excel  
- Dark/Light theme toggle  
- Fully responsive sidebar navigation  
screenshots :
<img width="1436" height="856" alt="image" src="https://github.com/user-attachments/assets/558f5de9-347a-46b1-adab-2d11c0c54316" />

## Hinweis zum Sicherheitskonzept

Dies ist eine **reine Frontend-Demo**. Die Zugangsdaten stehen im JavaScript und die
Sitzung wird nur im `localStorage` markiert. Das ist **keine echte Absicherung**: Jede
Person kann den Quelltext lesen oder den Wert im Browser selbst setzen.

Fuer einen produktiven Einsatz muesste die Anmeldung serverseitig geprueft werden
(Passwort-Hash in einer Datenbank, Sitzung ueber ein HttpOnly-Cookie oder ein signiertes
Token), und der Server duerfte die Dashboard-Daten erst nach erfolgreicher Pruefung
ausliefern.
