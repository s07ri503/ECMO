ECMO Crisis Leader — Standalone v2.0 Physiology Engine

MAJOR VERSION
核心改變：monitor 數字不再各自硬寫，而由同一 physiology engine 推導。

Chain:
pathology
→ preload / drainage resistance / return resistance / membrane resistance / pump / gas exchange / recirculation / native circulation
→ ECMO flow + Pven + Ppre + Ppost + ΔP
→ BP / SpO2 / CVP / Hb
→ alarm / circuit animation / debrief

可辨識的 pressure-flow patterns:
- hypovolemia / drainage insufficiency: preload↓ → suction↑ → Pven more negative → chatter / flow↓
- return tubing kink: return resistance↑ → flow↓ + return-side pressure pattern
- oxygenator thrombosis: membrane resistance↑ → ΔP↑ + flow limitation
- sweep interruption: blood flow may remain, gas transfer deteriorates
- VV recirculation: displayed flow may exist but effective oxygenated systemic flow falls
- pump failure: pump capacity collapses
- VA arrest: electrical HR can be 0 while VA ECMO can preserve non-pulsatile pressure/perfusion
- VV arrest: no circulatory support → BP collapses

ELSO-aligned educational model; numeric values and deterioration timing are simulation modeling, not ELSO fixed clinical cutoffs.

Preserved:
- 23 cases
- Case-scoped mixed reasoning
- Explainable + ELSO debrief
- Cardiac Sync
- Reassessment
- Mobile Debrief fix
- Local Instructor
- No Firebase
