# hello-world
first repo



--Users with pull access in a repository can access a combined view of commit statuses for a given ref. The ref can be a SHA, a branch name, or a tag name.

Additionally, a combined state is returned. The state is one of:

failure if any of the contexts report as error or failure
pending if there are no statuses or a context is pending
success if the latest status for all contexts is success--

curl \
  -H "Accept: application/vnd.github.v3+json" \
  https://api.github.com/repos/OWNER/REPO/commits/REF/status
