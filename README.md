# hangar-releases

Ready-to-install builds of Dave's apps. The source code lives in private repos in project-hangar;
only the finished APKs are published here, automatically, by each app's GitHub build.

## Apps

| App | Latest | All versions |
|---|---|---|
| Run Coach (phone + Galaxy Watch) | [`run-coach/latest.json`](run-coach/latest.json) | [Releases tagged `run-coach-v…`](https://github.com/project-hangar/hangar-releases/releases) |

## How it works

- Each app has a folder with a small `latest.json`: the newest version number and links to its APKs.
- The APKs themselves are attached to GitHub Releases (e.g. `run-coach-v22`), so every older version stays available.
- The apps read their `latest.json` from *Check for updates* and offer to install anything newer.
