# Run log
## 2026-11-06
- Web searches returned only aggregator results with stale/unclear dates; direct fetches to employer/aggregator hosts failed (hosts not in session network allowlist: statsskuld.se, paconsulting.com, climatetechlist.com).
- No posting could be verified as posted within the last 30 days. Six leads logged as UNVERIFIED in jobs_repository.csv; none reported as "new".
- Fix: allow job-board/employer domains in the environment network settings (or connect a job-search connector).
