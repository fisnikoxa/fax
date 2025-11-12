# Rregulla zgjidhjeje për përbërësit e forcës (sq)

Përdor këtë shabllon për çdo problem me një forcë F dhe një kënd të dhënë.

## Shablloni i zgjidhjes (kopjo dhe plotëso)

- Formula për përbërësit
  - Këndi i matur nga +[boshti] drejt −[boshti] do të thotë se këndi nga boshti +x është θ = [...].
  - Prandaj
    - Fx = F cos θ, Fy = F sin θ  (nëse këndi matet nga +x)
    - ose Fy = F cos θ, Fx = F sin θ (nëse këndi matet nga +y)
  - Shenjat: kuadranti [I/II/III/IV] ⇒ (Fx, Fy) = ([+/−], [+/−]).

- Fletë‑shpëtimi: pse përdoret F·sin apo F·cos?
  - Ideja kryesore: Përbërësi është projekcioni i vektorit mbi boshtin. Në trekëndëshin kënd‑drejtë, projekcioni = hipotenuza F × (ana përkatëse / hipotenuza). Ngjitur → cos, Përballë → sin.
  - Këndi matin nga +x: Fx = F cos θ (ngjitur), Fy = F sin θ (përballë). Shenjat varen nga kuadranti.
  - Këndi matin nga +y: Fy = F cos θ, Fx = F sin θ (kujdes shenjat).
  - Shenjat sipas kuadrantit: I (+,+), II (−,+), III (−,−), IV (+,−).
  - Shembull i shpejtë: 35° nga +y drejt −x ⇒ përbërësi ngjitur me +y është Fy = F cos 35°; përbërësi përballë është Fx = −F sin 35°.

## Hapat praktikë
1) Lexo madhësinë F dhe si matet këndi (nga +x apo +y, dhe drejt cilit bosht).
2) Ktheje në kënd nga +x nëse të duhet: θx = 90° ± θy.
3) Zgjidh sin/cos sipas ngjitur/përballë.
4) Vendos shenjat sipas kuadrantit.
5) Llogarit numerikisht (me njësi) dhe jep:
   - Formën vektoriale: F = Fx i + Fy j
   - Komponentët skalarë: (Fx, Fy)

---

## Problem 3 — F = 6.5 kN, pjerrësia 5/12 (kuadranti III)

<div style="max-width:460px">
<svg viewBox="0 0 420 160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="F 6.5 kN me pjerrësi 5-12, drejtimi majtas-poshtë">
  <defs>
    <marker id="arr" viewBox="0 0 10 10" refX="10" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#111827" />
    </marker>
  </defs>
  <rect x="0" y="0" width="100%" height="100%" fill="#ffffff"/>
  <g transform="translate(210,100)">
    <line x1="-190" y1="0" x2="190" y2="0" stroke="#9ca3af" stroke-dasharray="6 6" stroke-width="1.2" />
    <line x1="0" y1="50" x2="0" y2="-120" stroke="#9ca3af" stroke-dasharray="6 6" stroke-width="1.2" />
    <text x="192" y="-6">x</text>
    <text x="6" y="-124">y</text>
    <line x1="0" y1="0" x2="-180" y2="60" stroke="#ef4444" stroke-width="3" marker-end="url(#arr)" />
    <text x="-160" y="70">F = 6.5 kN</text>
    <!-- mini slope triangle 12-5 -->
    <g transform="translate(40,-30) rotate(20)">
      <polygon points="0,0 60,0 60,-25" fill="#ffffff" stroke="#ef4444" />
      <text x="28" y="12" font-size="12">12</text>
      <text x="66" y="-12" font-size="12">5</text>
    </g>
  </g>
</svg>
</div>

- Formula për përbërësit
  - Nga trekëndëshi 5–12–13: cos θ = 12/13, sin θ = 5/13.
  - Prandaj (shenja të kuadrantit III):
    - Fx = −F cos θ = −6.5·12/13 = −6.0 kN
    - Fy = −F sin θ = −6.5·5/13 = −2.5 kN
  - Shenjat: kuadranti III ⇒ (Fx, Fy) = (−, −).

- Fletë‑shpëtimi (zbatuar):
  - Projekcioni: ngjitur → cos, përballë → sin.
  - Këndi nga +x: Fx = F cos θ, Fy = F sin θ; nga +y: Fy = F cos θ, Fx = F sin θ.
  - Këtu: drejtim majtas‑poshtë ⇒ përdor vlerat 12/13 (horizontalja) dhe 5/13 (vertikalja) me shenjat −.

- Përfundimi
  - Formë vektoriale: F = −6.0 i − 2.5 j kN
  - Komponentët skalarë: (Fx, Fy) = (−6.0, −2.5) kN
