# repos-sync
need to be created at destination repository path “.github/workflows/workflow.yml”. Following changes need to be done in workflow.yml:

- Replace  [DESTINATION_ORG] with destination org name.
- Replace [DESTINATION_REPO] with destination repo name.
- Replace [SOURCE_ORG] with source org name.
- Replace [SOURCE_REPO] with source repo name.
- Replace [BRANCH_WITH_WORKFLOW] with the name of default branch where workflow kept at destination ie, main or master. Branch need to be default.
- Updated the cron schedule, eg cron: '30 06 * * *' scheduled for 06:30 AM UTC.
 

For authenticating to repo, workflow uses Personal Access Token (PAT). Create secret with PAT value named “TOKEN” in the destination repo.
