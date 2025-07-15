# github-actions
this repo is about github actions hands on lab

workflow folder has current running yml files

# For webhook events use below command lines

curl -X POST \
-H "Accept: application/vnd.github+json" \
-H "Authorization: token {PAT} \
-d '{"event_type": "webhook", "client_payload": {"key": "value"} }' \
https://api.github.com/repos/{owner}/{repo}/dispatches

## please replace {PAT}, {owner} and {repo} variables.
