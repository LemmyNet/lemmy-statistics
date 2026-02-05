Lemmy Statistics
===

This repository contains statistics which are regularly collected by the [crawler](https://github.com/LemmyNet/lemmy-stats-crawler) on [join-lemmy.org](https://join-lemmy.org/). Historical data is available via git history.

## Files

- `instances/full.json.gz`: Full output from `/api/v3/site` and `/api/v3/federated_instances`
- `instances/joinlemmy.json`: Limited output for the instance list, instances with less than 5 monthly users and some data fields are filtered out ([details](https://github.com/LemmyNet/lemmy-stats-crawler/blob/main/src/aggregate.rs#L52))
- `instances/minimal.json`: Only the statistics, for use in graphs
- `communities/full.json.gz`: Full output from `/api/v3/community/list` of all crawled instances
- `communities/minimal.json`: Only the community statistics, for use in graphs
