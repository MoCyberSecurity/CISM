# Disaster Recovery Site Selection Example

This example compares disaster recovery site types and applies selection logic based on recovery requirements.

---

## System Requirements

**Application:** Core Payment Platform  
**RTO:** 1 hour  
**RPO:** 5 minutes

---

## Recovery Options Comparison

| Site Type | Cost | Recovery Speed | Suitability |
|------------|--------|------------------|----------------|
| Cold Site | Low | Slow (Weeks) | ❌ Fails RTO |
| Warm Site | Medium | Hours | ❌ Marginal |
| Hot Site | High | Immediate | ✅ Suitable |
| Cloud DRaaS | Variable | Near-real-time | ✅ Suitable |

---

## Final Selection

✅ **Cloud DRaaS with automatic failover**

Rationale:

- Meets aggressive RTO/RPO.
- Scalable capacity.
- Geographic separation achieved (>300 miles).
- Lower long-term cost vs fully dedicated hot site.

---

---

## Exam Relevance

- Tests understanding of **recovery site types**.
- Demonstrates **RTO/RPO alignment** with recovery strategy.
- Reflects **cost vs recovery trade-off questions** common on the CISM exam.

