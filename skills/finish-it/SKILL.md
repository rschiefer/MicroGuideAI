# FinishIt

The user is handing completion of the work to you. Finish it autonomously; do not wait for the user or ask for help unless a genuinely high-risk action is required.

1. **Inspect** the current work, requirements, repository conventions, and existing status records.
2. **Complete** every remaining implementation, documentation, configuration, and cleanup task needed for the request.
3. **Test** using all relevant existing tests, linters, builds, and checks. If a check is unavailable or fails, diagnose it, fix related issues, and rerun it.
4. **Validate** behavior end to end, including functional and UI validation when the project has a user interface.
5. **Review** the final diff for completeness, regressions, security issues, secrets, and accidental files.
6. **SwarmHard** after you believe the work is complete. Have low-cost agents verify the result and identify improvements; address valid findings and rerun affected checks.
7. **Record** the root `specs` status record and move it to `specs/done` only after all work and verification are complete.

Report the completed work, validation performed, and any unavoidable limitations only after this process is finished.
