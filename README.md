# my_new_ci_cd_pipeline

> goal: develop ci/cd support for trunk based development 

desired qualities:

- as simple as possible
  - makes use of extant GH actions as much as possible
- runs fast qa tests when feature branches are created or change
  - linting, unit-tests, formatting
- runs slower qa tests prior to merge to main
  - e2e tests, security scans


using:

- github workflows/actions
- github environments
- github releases/deployments
- github merge-queues


