# Gaps — current evidence vs. target role

Target: entry-level / new-grad SDE in the US (see `profile.yml`).
Sources are linked in each row. Postings are from the 2025–2026 hiring cycles; requirements for 2027 graduates should be re-checked against live postings.

| Gap | Evidence the target demands it | What I have | Plan to close it |
|---|---|---|---|
| **My project claims can't be checked by anyone (rewritten in my own words)** | New-grad postings prefer hands-on experience from internships or personal projects ([RippleMatch new grad](https://talents.vaia.com/?p=28418926)), and this course's Step 4 check asks whether every entry is traceable. My two projects list numbers (300 TPS, 200→50 ms, 400 msg/s) with no link. | Two projects on my resume, no public repo, no dates, no team size. Right now a recruiter has to take my word for it. | Publish both projects on GitHub with a README, my role, and a load-test script that reproduces the numbers. **Closed when:** both repo links are in `resume.json` and someone else can run the benchmark and get roughly the same numbers. |
| Data structures, algorithms, and OOP fundamentals as tested in interviews | Required: "strong fundamentals in data structures, algorithms, and OOP" ([Emonics entry-level SE](https://jobright.ai/jobs/info/694c76905d7312113470db88)) | Coursework: Program Structure and Algorithms; Concepts of Object-Oriented Design. Interview practice in progress. | **Closed when:** I pass at least one online assessment or technical phone screen at a sponsoring company (confirmation email = external evidence). |
| Visible testing practice | Preferred: familiarity with software testing principles; reviewing test designs and test cases ([Visa NCG](https://www.dice.com/job-detail/ae4c6f02-9ed7-455e-819e-dcf99ae365ac)). O*NET 15-1252.00 task: develop software testing or validation procedures ([O*NET](https://www.onetonline.org/link/details/15-1252.00)). | JUnit listed in skills; 80%+ coverage claimed on gaming platform, not publicly shown. | Add CI that runs the test suite and publishes a coverage report on the public repo. **Closed when:** CI badge shows passing tests and coverage ≥ 80%. |
| Monitoring / observability | Adobe 2026 University Graduate SDE lists monitoring solutions and tools such as Prometheus/Grafana ([Adobe UG SDE](https://jobright.ai/jobs/info/695c1bcbf1f8465b79f22762)) | Alerting in a scheduler (removed entry, no longer claimed). No observability tooling on current record. | Add Prometheus metrics + a Grafana dashboard to the gaming platform repo. **Closed when:** dashboard config and screenshot are committed and linked in `resume.json`. |

## Killed row

| Gap | Evidence | What I have | Plan |
|---|---|---|---|
| ~~Bachelor's degree in Computer Science~~ | ~~Postings require a degree in CS~~ | ~~B.A./B.S. in Artificial Intelligence~~ | ~~Highlight CS coursework~~ |

**Why it was wrong:** The agent read my undergraduate major (Artificial Intelligence) as "not CS," but the postings it cited actually say "Computer Science, Software Engineering, or related field" ([Amazon Jr. SDE](https://h1bjobs.ellis.com/companies/amazon-3-60ad394d-c673-4474-9694-344b0cae748f/jobs/49293557-jr-software-development-engineer-new-york-ny), [RippleMatch](https://talents.vaia.com/?p=28418926)), and I am also completing an M.S. in Software Engineering Systems, so there is no degree-field gap.
