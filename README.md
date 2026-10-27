<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Matias%20Vagliviello&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Matias Vagliviello" />

<a href="https://github.com/matiasvagli">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=A78BFA&center=true&vCenter=true&width=620&height=40&lines=Backend+developer;Sistemas+distribuidos+%26+DDD;IA+aplicada+y+MCP+servers;Menos+c%C3%B3digo%2C+m%C3%A1s+criterio" alt="Backend developer · Sistemas distribuidos · IA aplicada" />
</a>

<br/><br/>

![Backend](https://img.shields.io/badge/backend-first-7c6ff7?style=for-the-badge)
![Arquitectura](https://img.shields.io/badge/DDD-%C2%B7_Saga_%C2%B7_Outbox-0ea5e9?style=for-the-badge)
![IA](https://img.shields.io/badge/MCP-%C2%B7_RAG-10b981?style=for-the-badge)

</div>

---

## 🧠 Quién soy

Soy **backend developer** y me especializo en lo que no se ve, pero se nota cuando falla:

- 💸 que **el dinero no se pierda** cuando un servicio se cae a mitad de una transferencia;
- 🛡️ que un **agente de IA no pueda robar credenciales** ni filtrar datos sin que nadie se entere;
- ⚡ que un listado **no se vuelva lento** cuando la base crece.

Diseño con **DDD**, pruebo la lógica donde importa y construyo **de punta a punta**:
del modelo de dominio a la API, y de ahí a la pantalla. Además me meto de lleno en
**IA aplicada**: MCP servers, RAG y herramientas para que los equipos trabajen mejor con LLMs.

## 🛠️ Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,django,fastapi,ts,nextjs,nestjs,go,postgres,prisma,docker&perline=10" alt="Python, Django, FastAPI, TypeScript, Next.js, NestJS, Go, PostgreSQL, Prisma, Docker" />

</div>

## 🌍 Abiertos a la comunidad

Código abierto: usalo, rompelo, abrí un issue o mandá un PR.

| Proyecto | Qué es |
|---|---|
| 💸 [**Microservicios**](https://github.com/matiasvagli/Microservicios) | Billetera digital en microservicios: gateway + 4 servicios, **Saga Pattern** con compensaciones, eventos e idempotencia. |
| 🔍 [**SkillAudit**](https://github.com/matiasvagli/skillaudit) | Un MCP server que **audita otros MCP servers**: los corre en Docker aislado y observa su comportamiento real, en vez de confiar en el código. |
| 🧩 [**ragkit**](https://github.com/matiasvagli/ragkit) | Pipeline de ingesta RAG autoconfigurable para NestJS: elegís el proveedor de IA y el resto se configura solo. |
| 🤝 [**Team Context MCP Server**](https://github.com/matiasvagli/Team-Context-MCP-Server) | Contexto compartido y persistente para equipos que trabajan con LLMs: que el conocimiento no se evapore cuando alguien se va. |
| ⚡ [**CRUDFULL**](https://github.com/matiasvagli/crudfull) | Generador de CRUDs para FastAPI con tres motores: sin base, SQLAlchemy async o MongoDB. |

## 🧭 Cómo trabajo

| Principio | Cómo se ve en la práctica |
|---|---|
| 🧱 **Dominio antes que código** | Modelo el dominio con DDD. Las reglas de negocio viven fuera del framework y se prueban sin levantar un servidor. |
| 🔁 **Consistencia bajo fallos** | Saga, outbox transaccional e idempotencia: si un paso falla, el sistema compensa en vez de quedar a medias. |
| 🔐 **Seguridad por defecto** | Secretos solo por entorno, todo input externo validado, queries parametrizadas y autenticación explícita en cada endpoint. |
| 📉 **Performance con guardas, no con reportes** | Todo listado va paginado y con un test automático que falla si la cantidad de queries crece con N. Los N+1 se cazan en el review, no en producción. |
| 🎯 **Simple antes que ingenioso** | La solución más simple que resuelva el problema, ordenada y sin capas "por si acaso". |
| ✅ **Tests donde importan** | Lógica de negocio, cálculos y casos borde. Sin perseguir cobertura por cobertura. |

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" alt="" />

</div>
