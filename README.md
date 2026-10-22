# Siggy Styles — Sales & Client Analysis (2025/2026)

**Live dashboard:** https://public.tableau.com/app/profile/meadows.marrero/viz/SiggyStylesSalesClientAnalysis20252026/Dashboard1

## Introduction
- **Scenario:** one stylist in a salon needs to know how her service and
  retail sales performed between 1/25-9/25 and 1/26-9/26, how clients spend, and who visits most.
- **Real-world obstacle:** revenue looks stable, but is it actually growing?
  Are her most loyal clients also her most valuable?
- **Assumption:** analyzing only her own clients (not the whole salon) gives
  the clearest view of her individual performance.

## Problems
- **Flat services:** service revenue fell $1,110, from $136,563 to $135,453
  (–0.8%) year over year.
- **Weak retail attach:** client 27271 visited 76 times across both years and
  bought $0 retail; top spender 28049 visited 30 times and spent $396/visit.
- **How I analyzed it:**
  - Analysis was run two ways — pandas and SQL
  - Cleaned over 39,000 rows across six files.
- **Facts:** services –0.8%, retail +2.8%, spend-per-visit gap

## Solutions (with tradeoffs)
  **Option A — checkout product suggestion for frequent visitors**
  **Option B — bundle product discount with service for top spenders**
  **Option C — stock what top retail buyers actually purchase**

## Conclusion
- Services flat (–0.8%), retail up slightly (+2.8%); the real opportunity is
  retail attach.
- Key takeaway: visits ≠ value. Spend per visit and retail attach are the
  metrics to manage, not visit count.
