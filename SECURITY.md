# Security Policy / Política de seguridad

[English](#english) · [Español](#espanol)

---

<a id="english"></a>
## English

Anti-UAC affects how selected trusted applications are launched on Windows, so security reports are taken seriously.

### Please do not open a public Issue for

- vulnerabilities that could enable unintended privilege changes;
- ways to make Anti-UAC act on arbitrary or untrusted executables without clear user intent;
- paths that allow modification of unrelated system files or programs;
- credential, token or private-system-information exposure;
- other issues where publishing reproduction details could put users at risk.

Use GitHub's **Private vulnerability reporting** for this repository when available. If that option is not visible, do not post sensitive reproduction details publicly; open a minimal public Issue stating that you need a private security contact, without including exploit details or private data.

### Include

- affected Anti-UAC version;
- Windows version;
- clear impact description;
- minimum steps needed to reproduce;
- whether administrator privileges are already required;
- any relevant mitigations you identified.

Do not include real passwords, authentication tokens, private keys or unnecessary personal information.

### Scope

Reports about Anti-UAC's own behaviour are welcome. General Windows UAC bypass techniques, malware development, evasion techniques or vulnerabilities unrelated to Anti-UAC are outside the scope of this repository.

No response-time or remediation-time guarantee is provided because this is a personal hobby project maintained in free time.

---

<a id="espanol"></a>
## Español

Anti-UAC afecta a la forma en que se inician determinadas aplicaciones de confianza en Windows, por lo que los informes de seguridad se consideran importantes.

### No abras un Issue público para

- vulnerabilidades que permitan cambios de privilegios no previstos;
- formas de hacer que Anti-UAC actúe sobre ejecutables arbitrarios o no fiables sin una intención clara del usuario;
- rutas que permitan modificar archivos del sistema o programas ajenos;
- exposición de credenciales, tokens o información privada del sistema;
- otros problemas en los que publicar los pasos de reproducción pueda poner a usuarios en riesgo.

Utiliza **Private vulnerability reporting** de GitHub para este repositorio cuando esté disponible. Si no aparece esa opción, no publiques detalles sensibles: abre como máximo un Issue público mínimo indicando que necesitas un canal privado de seguridad, sin incluir detalles de explotación ni datos privados.

### Incluye

- versión afectada de Anti-UAC;
- versión de Windows;
- descripción clara del impacto;
- pasos mínimos para reproducirlo;
- si ya se requieren privilegios de administrador;
- mitigaciones relevantes que hayas identificado.

No incluyas contraseñas reales, tokens de autenticación, claves privadas ni información personal innecesaria.

### Alcance

Se aceptan informes sobre el comportamiento propio de Anti-UAC. Técnicas generales para eludir UAC, desarrollo de malware, técnicas de evasión o vulnerabilidades ajenas a Anti-UAC quedan fuera del alcance de este repositorio.

No se garantiza un plazo de respuesta o corrección porque se trata de un proyecto personal mantenido como hobby en el tiempo libre.

---

**Anti-UAC — IMC93Labs**
