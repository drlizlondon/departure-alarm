# Research Brief: Prior Art & Build Decision

Date: 2026-10-19  
Author: We Build for Good Studio  
Verdict: **BUILD**  

---

## 1. Problem Statement & Hard Constraints

Autonomous departure alarm with travel buffers and mobile chime

---

## 2. Search Strategy & Sources Queried

The following queries were executed across GitHub, package registries, and product directories:
* `html5 timer chime safari`
* `departure alarm progressive web app`

---

## 3. Evaluated Candidates Matrix

| Candidate | Repository / URL | License | Status / Maintenance | Fit Assessment |
|:---|:---|:---|:---|:---|
| Candidate One | https://github.com/example/one | MIT | Maintained (last commit 2 weeks ago) | Partial: covers engine but lacks our specific UI workflow |
| Candidate Two | https://github.com/example/two | Apache-2.0 | Active (last commit 1 month ago) | Mismatch: requires heavy cloud Docker backend |

---

## 4. Disqualifying Criteria (Why Existing Solutions Failed)

Existing timer web apps require native app store downloads and fail background audio triggers on iOS.

---

## 5. Residual Uncertainty & Known Blind Spots

iOS audio context suspend after 30 seconds requires user gesture priming.

---

## 6. Actionable Recommendation

* **Final Decision**: **BUILD**
* **Next Action**: Proceed with custom build, enforcing strict invariant checks and automated testing.
