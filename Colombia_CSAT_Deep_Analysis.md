# 🇨🇴 Colombia Transfer Out (Bre-B) CSAT — Deep Analysis
## Wave 1 (January 2026) | GBA Research

This document provides a **deep, structured analysis** of Colombia CSAT aligned with best practices: quotes separated by **journey stage** and **segment** (satisfaction level), insights by **category and subcategory**, and **explaining text for each slide** of the Colombia CSat W1 deck.

---

# Part 1 — Taxonomy for Colombia Transfer Out CSAT

## Categories and Subcategories (Colombia-specific)

| Category | Subcategories | Description |
|----------|---------------|-------------|
| **Execution** — Streamline transfer flow | Streamline Payment, Keys & Favorites, Auth/Confirmation | Reduce effort and steps to complete a transfer; manage saved keys; confirmation friction |
| **Execution** — Status & clarity | Payment details & status, Execution failures | Clarity on whether transfer succeeded; what to do when it fails |
| **Manage** — Control & findability | Commitments/History, Assistant Findability & Onboarding, Post-transfer navigation | History, finding features, and returning to home after receipt |
| **Bugs** — Stability & failures | Instability, Falla en envío, Bloqueo de cuenta | Unexpected behavior, failed transfers, account blocks |
| **Regulatory (Colombia)** — 4x1000 | Visibility/Tracker, Exemption, Receipt/Comprobante | Tax visibility, exemption flow, 4x1000 on receipt |
| **Others** | Otros | Comments not fitting the above |

---

# Part 2 — Journey-based quote separation

Quotes are grouped by **stage of the transfer journey** to prioritize fixes by moment of impact.

## Journey stages

1. **Discovery / Entry** — Finding “Send money”, understanding the flow  
2. **Execution** — Choosing recipient, amount, source (account/cajitas), confirming  
3. **Confirmation** — Auth (password/Face ID), final confirmation  
4. **Post-transfer** — Receipt/comprobante, sharing, **going back to home**  
5. **Error / recovery** — When transfer fails or account is blocked

---

## Quotes by journey stage

### Discovery / Entry
- *"No encontraba la forma de trasladar dinero de las cajitas para mi cuenta principal... Sugiero colocar la palabra retiro en el menú al lado de la palabra enviar"* (Baja satisfacción)  
- *"Tal vez que el inicio sea más claro, a veces me confundo en vez los datos de mi cuenta"* (Alta satisfacción)

### Execution (recipient, amount, keys)
- *"a veces es un poco enredado hacer pagos a terceros por llave"* (Alta satisfacción)  
- *"me gustaría se identificara el destino cuando uso llave, no sé a qué entidad pertenece la llave sino hasta el final"* (Baja satisfacción)  
- *"poder editar los preferidos guardados para enviar el dinero, con el fin de poder personalizarlos"* (Muy alta satisfacción)  
- *"opción para eliminar cuentas de contacto"* (Alta satisfacción)  
- *"es muy largo hacer el pago, muchos pasos para poder pagar"* (Baja satisfacción)

### Confirmation (auth)
- *"Es necesario poner la contraseña en cada envío? si ya me registré con face id. tal vez que la persona pueda definir los montos minimos"* (Muy alta satisfacción)  
- *"de pronto el volver a pedir la contraseña se vuelve algo cansón"* (Muy baja satisfacción)

### Post-transfer (receipt → home)
- *"Cuando hago una transferencia, que ya se envió y estoy en la parte del comprobante, me debo devolver todos los pasos de la transferencia para llegar al inicio... debería lanzarme al inicio cuando termino"* (Muy baja satisfacción)  
- *"cuando se envía plata y está el comprobante, si necesito hacer otra o solo ver el saldo me toca dar atrás y atrás hasta llegar al inicio"* (Alta satisfacción)  
- *"Agregar una opción al finalizar las transacciones para regresar a la página inicial, ya que siempre toca devolverse"* (Alta satisfacción)  
- *"volver al menú con un clic cuando se hace el depósito o la transferencia"* (Alta satisfacción)  
- *"Sería genial que al realizar un pago automáticamente me enviara a la página de inicio"* (Muy baja satisfacción)

### Error / recovery
- *"he intentado mas de 5 veces trasladar plata de mi cuenta a Bold y no puedo"* (Muy baja satisfacción)  
- *"a veces la app falla en los envíos por Bre-B"* (Muy alta satisfacción)  
- *"persiste un bloqueo en mi cuenta de Nu contra mi cuenta de Nequi y no me dan solución"* (Muy baja satisfacción)  
- *"mientras no se caiga la plataforma todo marcha como debe ser"* (Indiferente)

---

# Part 3 — Insights by category and subcategory (reference format)

Below, each block focuses on the **most relevant subcategory** per theme, with learnings and example comments (as in the csat reference format).

---

## [Execution | Streamline Payment — Keys & process]

Customers ask to **edit and delete saved keys**, to see **which bank each key belongs to** before confirming, and to **reduce steps** (including confirmation). They also want **scheduled transfers** and **clearer entry points** (e.g. retiro/enviar). Process length and keys management are the main execution frictions.

**Keys and process:**  
Users want to edit or delete saved keys, see bank names next to each key, and have a section for frequently used contacts. Several mention that the process has too many steps and that paying by “llave” is sometimes confusing. Auth (password every time despite Face ID) is a repeated friction.

**Example comments:**  
- *"poder editar los preferidos guardados para enviar el dinero, con el fin de poder personalizarlos al gusto"* (Muy alta satisfacción)  
- *"me gustaría editar las llaves guardadas o tener algún tipo de transferencia programada"* (Alta satisfacción)  
- *"me gustaría se identificara el destino cuando uso llave, no sé a qué entidad pertenece"* (Baja satisfacción)  
- *"es muy largo hacer el pago, muchos pasos para poder pagar"* (Baja satisfacción)  
- *"Es necesario poner la contraseña en cada envío? si ya me registre con face id"* (Muy alta satisfacción)

**Opportunities:**  
- Allow editing/deleting saved keys and show bank name next to each key.  
- Add “Go to Home” after receipt; optional Face ID for confirmation with configurable amount threshold.  
- Consider scheduled transfers and clearer discovery (e.g. “Retiro” next to “Enviar”).

---

## [Bugs | Instability & execution failures]

**When transfers fail or the app is unstable, trust drops sharply.** 38.8% of negative verbatims mention instability or failures; 24.1% gave Muy baja satisfacción. Users report repeated failed attempts, not knowing if the transfer went through, app freezes, and persistent blocks (especially Nu ↔ Nequi). They feel abandoned when errors occur and there is no clear guidance.

**Example comments:**  
- *"he intentado mas de 5 veces trasladar plata de mi cuenta a Bold y no puedo"* (Muy baja satisfacción)  
- *"a veces la app falla en los envíos por Bre-B"* (Muy alta satisfacción)  
- *"persiste un bloqueo en mi cuenta de Nu contra mi cuenta de Nequi y no me dan solución"* (Muy baja satisfacción)  
- *"qr aún falla mucho"* (Muy baja satisfacción)  
- *"mientras no se caiga la plataforma todo marcha como debe ser"* (Indiferente)  
- *"a veces demora, no lo hace rápido y no se sabe si se hizo o no"* (Alta satisfacción)

**Opportunities:**  
- Maintain Bre-B reliability; real-time monitoring and proactive comms during outages.  
- Replace generic errors with contextual messages and next steps.  
- Investigate and resolve persistent Nu ↔ Nequi blocks; proactive outreach to affected users.

---

## [Regulatory — Colombia | 4x1000 visibility and control]

**The 4x1000 tax creates “surprise” friction:** users lack visibility of how much they’ve paid and when they approach the monthly cap. They also ask for exemption clarity and for the receipt not to include 4x1000 when sharing. This is a **Colombia-specific** pain and a differentiation opportunity.

**Example comments:**  
- *"quisiera poder conocer en mi cuenta cuanto he enviado en el mes para saber cuando llegaré al tope de 4x1000 mensual"* (Muy baja satisfacción)  
- *"me gustaría conocer cuánto he enviado del 4x1000 para ver lo del tope y los costos en el mes"* (Baja satisfacción)  
- *"se supone que entre cuentas de la misma persona no se cobra el 4x1000, por qué lo están cobrando?"* (Alta satisfacción)  
- *"el comprobante que se quiere compartir no debería incluir el valor del 4x1000"* (Muy alta satisfacción)  
- *"quiero marcar esta cuenta para que sea exenta del 4x1000"* (Alta satisfacción)

**Opportunities:**  
- Build a **4x1000 tracker**: accumulated amount in the month, distance to cap, optional alert near limit.  
- Clarify exemption rules in-app and in comms.  
- Option to share receipt without 4x1000 line.

---

## [Manage | Post-transfer navigation]

**After the transfer, users must go back through every step to reach home.** This appears in verbatims across satisfaction levels and is a clear UX gap: no “Go to Home” or automatic return after the receipt.

**Example comments:**  
- *"Cuando hago una transferencia... estoy en la parte del comprobante, me debo devolver todos los pasos... debería lanzarme al inicio cuando termino"* (Muy baja satisfacción)  
- *"cuando se envía plata y está el comprobante... me toca dar atrás y atrás hasta llegar al inicio"* (Alta satisfacción)  
- *"Agregar una opción al finalizar las transacciones para regresar a la página inicial"* (Alta satisfacción)  
- *"volver al menú con un clic cuando se hace el depósito o la transferencia"* (Alta satisfacción)

**Opportunities:**  
- Add “Ir al inicio” / “Go to Home” on receipt screen or auto-navigate after closing/sharing receipt.  
- Low effort, high impact.

---

## [Execution | Speed & efficiency — what works]

**When Bre-B works, speed and simplicity drive satisfaction.** 53.9% gave Muy alta satisfacción; positive verbatims highlight “rápido”, “sencillo”, “ágil”, “fácil”. Efficiency and reliability are the main positive themes.

**Example comments:**  
- *"Proceso rápido y sencillo"* (Muy alta satisfacción)  
- *"la verdad 10/10 el bre-b"* (Muy alta satisfacción)  
- *"todo es fácil y rápido y la app es amigable"* (Muy alta satisfacción)  
- *"es muy fácil y ágil el proceso"* (Muy alta satisfacción)  
- *"me encanta el reconocimiento facial"* (Muy alta satisfacción)

**Opportunities:**  
- Preserve and communicate speed and simplicity; avoid adding steps.  
- QR is a bright spot; improve discoverability if awareness is low.

---

# Part 4 — Sentiment by segment (satisfaction levels)

| Segment | Definition | Sentiment summary |
|--------|------------|--------------------|
| **Group A (Detractors)** | Muy baja + Baja satisfacción (25.3%) | Dominated by failures, blocks, and lack of clarity. Feel loss of control; many cite December incidents. |
| **Group B (Passives)** | Alta satisfacción (17.9%) | Satisfied but want improvements: keys management, 4x1000 visibility, post-transfer navigation, Face ID. |
| **Group C (Promoters)** | Muy alta satisfacción (53.9%) | Speed and simplicity drive satisfaction; some still ask for keys editing, 4x1000 tracker, and receipt/UX tweaks. |

**Most common issues by group:**  
- **Group A:** Instability/failures (38.8%), 4x1000 (~15%), account blocks (~5%), long/confusing process (~10%).  
- **Group B:** Simplify process (195 verbatims), 4x1000 visibility, keys management, post-transfer navigation, Face ID.  
- **Group C:** Same themes as opportunities (keys, 4x1000, receipt, auth), plus positive reinforcement of speed and ease.

---

# Part 5 — Actionable recommendations (summary)

**High priority**  
1. **Maintain Bre-B reliability** — Monitoring, proactive comms, post-mortems.  
2. **Build 4x1000 tracker** — Accumulated amount, cap, alerts; differentiator.  
3. **Contextual error messages** — Replace generic errors with explanation + next steps.  
4. **Resolve Nu ↔ Nequi blocks** — Identify and unblock users stuck since December.

**Quick wins**  
5. **Post-transfer flow** — “Go to Home” or auto-return after receipt.  
6. **Keys management** — Edit/delete keys; show bank name next to key.  
7. **Face ID for confirmation** — Optional biometrics with amount threshold.  
8. **QR from gallery** — Scan from saved images if feasible.

---

# Part 6 — Explaining text for each slide (Colombia CSat W1 deck)

Use these as **speaker notes or narrative text** for each slide when presenting.

---

## Slide 1 — Overall CSAT score (71.8%)

**Explaining text:**  
“This is the first wave of Colombia Transfer Out CSAT. We have almost 4,000 responses from January 2026. The overall score is 71.8%, with 71.8% satisfied (Alta + Muy alta satisfacción) and 25.3% detractors (Muy baja + Baja satisfacción). This slide sets the baseline we’ll use to track improvement in future waves.”

---

## Slide 2 — Key findings at a glance

**Explaining text:**  
“Four findings summarize the story: First, **speed equals trust** — when Bre-B is instant, users give Muy alta satisfacción. Second, **instability destroys trust** — December incidents pushed the detractor rate up. Third, **4x1000** is a unique friction in Colombia; people want visibility and control. Fourth, **small UX fixes** — like post-transfer navigation and keys management — can have a big impact. We’ll go deeper into each in the next slides.”

---

## Slide 3 — Context: first wave

**Explaining text:**  
“This is our baseline. Future waves will be compared to this. It’s important to remember that January 2026 data was collected right after significant Bre-B instability in December 2025, so part of what we see may reflect that context.”

---

## Slide 4 — Sentiment distribution by satisfaction level

**Explaining text:**  
“Understanding what users write at each rating helps us prioritize. Muy baja satisfacción with negative sentiment needs root-cause fixes — stability and errors. Alta satisfacción with improvement requests points to quick UX wins — navigation, keys, 4x1000 visibility. So we use sentiment by satisfaction level to decide where to act first.”

---

## Slide 5 — Verbatim analysis (2,439 of 3,932)

**Explaining text:**  
“We analyzed 2,439 verbatims — a 62% response rate. This gives us a solid qualitative base to separate themes by journey and segment, and to pull representative quotes for each finding.”

---

## Slide 6 — Learning #1: Failures destroy trust

**Explaining text:**  
“When transfers fail or the system is unstable, users don’t tolerate uncertainty. A single bad experience can turn a promoter into a detractor. In the data, 38.8% of negative verbatims mention instability or failures, and 24.1% gave Muy baja satisfacción — unusually high. During the December incident, Bre-B success rate dropped to 22.5%. So reliability isn’t just one factor — it’s the foundation: when it breaks, satisfaction collapses.”

---

## Slide 7 — Learning #2: The tax creates ‘surprise’ friction

**Explaining text:**  
“4x1000 is unique to Colombia. Users get frustrated because they don’t see how much they’ve paid or how close they are to the monthly cap. We see around 107 verbatims about 4x1000 — about 4.5% of improvement requests. No major bank in Colombia offers a real-time tracker today, so building one could be a strong differentiator and turn a regulatory pain into trust.”

---

## Slide 8 — Learning #3: Speed drives satisfaction (53.9% Muy alta satisfacción)

**Explaining text:**  
“When transfers are instant, users feel confident. Efficiency is the number-one driver of trust. So the core experience — when it works — is already strong. The challenge is keeping it consistent and fixing what happens when it doesn’t work.”

---

## Slide 9 — Learning #4: Small UX frictions (quick wins)

**Explaining text:**  
“From the user’s point of view, several small frictions add up: **Navigation** — after the receipt, they have to go back through every step to get home. **Keys** — they can’t edit or delete saved keys, and bank names appear only at the end. **Auth** — they’re asked for password even when they use Face ID. **QR** — some want to scan from gallery, not only live camera. These are mostly low-effort, high-impact fixes.”

---

## Slide 10 — Detractor pain categories

**Explaining text:**  
“Detractors cluster around four pains: **Transfer failures** — about 38.8%; repeated failures and uncertainty about status. **4x1000** — about 15%; surprise deductions and no visibility of limits. **Long process** — about 10%; too many taps, confusing keys, and the receipt-to-home loop. **Account blocks** — about 5%; especially Nu–Nequi, feeling trapped. The common thread is **loss of control**: they don’t understand what’s happening and can’t fix it themselves.”

---

## Slide 11 — Actionables (priority)

**Explaining text:**  
“Priorities in order: **One**, maintain Bre-B reliability — monitoring and proactive comms. **Two**, build the 4x1000 tracker — show accumulated tax and distance to cap. **Three**, contextual error messages — replace generic errors with clear guidance. **Four**, resolve Nu–Nequi blocks — identify and unblock users stuck since December. These address the main causes of detraction and loss of control.”

---

## Slide 12 — UX quick wins & structural items

**Explaining text:**  
“Beyond the top four, we have quick wins: post-transfer ‘Go to Home’, keys management 2.0, Face ID for confirmation, and QR from gallery. We recommend doing the navigation and keys improvements first — they’re low effort and directly address verbatim demand.”

---

## Slide 13 — Market pattern comparison

**Explaining text:** **“Across Brazil, Mexico, and Colombia we see the same patterns: speed equals trust, instability destroys it, and error handling is a major gap. Colombia adds a specific factor — 4x1000 — which is both a challenge and an opportunity to differentiate with visibility and control.”**

---

## Slide 14 — Closing

**Explaining text:**  
“To close: the foundation is solid — when Bre-B works, users love it. The path to higher CSAT is clear — maintain stability, add 4x1000 visibility, and improve error handling and small UX frictions. This deck and the deep analysis document give us the structure to track progress in the next waves.”

---

**Document:** Colombia CSAT Deep Analysis  
**Team:** GBA Research  
**Date:** February 2026  
**Scope:** Transfer Out (Bre-B) | Cuenta Colombia | Wave 1 baseline
