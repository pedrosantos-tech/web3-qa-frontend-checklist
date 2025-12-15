# QA Report – Web3 Frontend

**Project:** [Nombre del proyecto]  
**Date:** [Fecha]  
**Tester:** Pedro (QA strategist)

## Summary

Brief overview of what was tested, goals, and context.

## Findings

| Category        | Issue Description                          | Severity | Suggested Fix |
|----------------|---------------------------------------------|----------|----------------|
| Routes          | `/dashboard` breaks on mobile              | Medium   | Add responsive layout |
| Assets          | `logo.png` missing in dark mode            | Low      | Add theme-aware loader |
| Network Logic   | RPC timeout not handled                    | High     | Add retry + feedback |

## Recommendations

- Implement fallback UI for wallet errors  
- Optimize asset loading strategy  
- Document route guards for future contributors

---

**Next Steps:**  
[ ] Fix critical issues  
[ ] Schedule retest  
[ ] Update onboarding docs
