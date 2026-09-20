ECMO Crisis Leader — Standalone v1.4 Explainable Debrief

新增：
1. Debrief 不再只顯示「錯」：
   - Diagnosis reasoning：說明為什麼是合理 differential、為什麼本案證據不支持它為主因
   - Management reasoning：說明處置適用的 physiology，以及為什麼本案不適當/非 definitive
   - Case discrimination：直接比較本案關鍵線索與相似 ECMO emergency

2. Definitive critical action 完成後：
   - 狀態切換為 Reassessment / stabilization
   - 停止 Instructor pathology override
   - Timeline 明確記錄進入 reassessment
   - Debrief 顯示 definitive action completed

範例：Return tubing kink
- Crystalloid 在 hypovolemia/drainage insufficiency 可能合理
- 但 return-side kink 是 mechanical obstruction，volume 無法解除 obstruction
- Sweep gas failure 主要是 gas-exchange/CO2 removal 問題，不解釋突然 blood-flow collapse
- Tamponade 是合理 differential，但需 CVP/POCUS/filling/pulse pressure 等支持

保留：
- 23 cases
- Mixed Clinical Reasoning
- Cardiac Sync
- 本機 Instructor
- 無 Firebase / Room / Live
- JS syntax PASS
