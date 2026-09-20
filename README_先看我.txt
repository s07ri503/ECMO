ECMO Crisis Leader — Standalone v1.5 Case-Scoped Reasoning

修正 v1.4.1 截圖發現的 cross-case management pollution：
- 干擾項現在有獨立 selected state，不再借用原 case treatment state。
- 換 case 時額外 Assessment / Diagnosis / Management state 會清空。
- 綠色 ✓ 只代表 learner 真的點過。
- DPC / distal perfusion / vascular limb-rescue procedures 不再作為一般 case 的 generic distractor。
- Cannula migration-specific refixation/reposition procedures只在 migration case 的 native treatment 中保留。
- VA-KINK 不會再莫名出現整排已完成的 DPC management。

仍保留：
- 23 cases
- Mixed clinical reasoning
- Explainable Debrief
- Reassessment / stabilization
- Cardiac Sync
- Mobile Debrief button fix
- 本機 Instructor
- 無 Firebase / Room / Live
