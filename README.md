```asm
; ScrachStack OS Boot v1.0
MOV AX,0
MOV DS,AX
LEA DX,MSG
CALL PRINT
HLT

MSG DB 'Booting ScrachStack...',0

PRINT:
    MOV AH,0x0E
.next:
    LODSB
    CMP AL,0
    JE .done
    INT 0x10
    JMP .next
.done:
    RET
```
**Languages**  
![JavaScript](https://img.shields.io/badge/-JavaScript-000?&logo=JavaScript&logoColor=F90&style=for-the-badge) 
![Lua](https://img.shields.io/badge/-lua-000?&logo=lua&style=for-the-badge)
![Python](https://img.shields.io/badge/-Python-000?&logo=python&style=for-the-badge)  
![php](https://img.shields.io/badge/-php-000?&logo=php&style=for-the-badge)  
![C#](https://img.shields.io/badge/-Csharp%20Lang-000?&logo=csharp&style=for-the-badge)  
![C](https://img.shields.io/badge/-C%20Lang-000?&logo=c&style=for-the-badge)  

**Databases**  
![MYSQL](https://img.shields.io/badge/-mysql-000?&logo=mysql&style=for-the-badge)  
![MongoDB](https://img.shields.io/badge/-MongoDB-000?&logo=mongodb&style=for-the-badge)

**Frameworks & Tools**  
![Node.js](https://img.shields.io/badge/-Node.js-000?&logo=node.js&logoColor=0F0&style=for-the-badge)  
![React](https://img.shields.io/badge/-React-000?&logo=react&style=for-the-badge)  
![vue](https://img.shields.io/badge/-vue-000?&logo=vuedotjs&style=for-the-badge)  
![Angular](https://img.shields.io/badge/-Angular-000?&logo=angular&style=for-the-badge)  
![express](https://img.shields.io/badge/-express-000?&logo=nodedotjs&style=for-the-badge)  
![Next.js](https://img.shields.io/badge/-Next-000?&logo=next.js&style=for-the-badge)  
![discord.js](https://img.shields.io/badge/-discord.js-000?&logo=discorddotjs&style=for-the-badge)  

![HTML5](https://img.shields.io/badge/-HTML5-000?&logo=html5&style=for-the-badge)  
![CSS](https://img.shields.io/badge/-CSS-000?&logo=css&style=for-the-badge)  
![Git](https://img.shields.io/badge/-Git-000?&logo=git&style=for-the-badge)  
![Docker](https://img.shields.io/badge/-Docker-000?&logo=docker&style=for-the-badge)

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ScrachStack&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" alt="ScrachStack's GitHub Stats">
</div>

---


