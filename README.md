# cron-test

Throwaway repo to check whether GitHub Actions `schedule` triggers fire for new
repositories on this account. Delete it when the test is done.

Check scheduled runs:

    gh run list -R <owner>/cron-test --event schedule
