# This is a GitHub Actions testing repo
### Testing the following:
- Create a github workflow
- Create dev branch and branch rules to main branch so that we can test the workflow via push and also via pull request through dev
- Create a conflict: 1 test did not pass and pull request failed, after fix, the github action triggered automatically
- Created option for running the action manually, tested also with dev branch
- Created a second job
- Make both jobs run one after the other (build then test)