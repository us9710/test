# TOPS Maths Live Tests

Student test pages for online interactions.

| Test | Link |
|---|---|
| Test 1 | https://us9710.github.io/test/1 |
| Test 2 | https://us9710.github.io/test/2 |
| Test 3 | https://us9710.github.io/test/3 |
| Test 4 | https://us9710.github.io/test/4 |
| Test 5 (adaptive) | https://us9710.github.io/test/5 |
| Test 6 (adaptive) | https://us9710.github.io/test/6 |
| TOAS O58 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O58/ |
| TOAS O59 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O59/ |
| TOAS O60 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O60/ |
| TOAS O61 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O61/ |
| TOAS O62 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O62/ |
| TOAS O63 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O63/ |
| TOAS O64 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O64/ |
| TOAS O65 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O65/ |
| TOAS O66 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O66/ |
| TOAS O67 (JEE Advanced pattern, 18 Qs) | https://us9710.github.io/test/O67/ |

- `index.html` (also in `1/`–`4/`): the test page; the folder number picks the test.
- `5/index.html`, `6/index.html`: the adaptive tests (same page). 40 minutes, 3 stages of 5 going Easy, then Medium, then Tough; the questions of each stage come from the Apps Script and depend on the stage before, so none of them are in this repo.
- Teacher preview: add `?preview` to a test link (no timer, nothing recorded).
- `tests.json`: questions only. Answer keys and grading live in a private Google Apps Script; scores go to a private Google Sheet.
- To change questions, rebuild with the private project in OneDrive `Class-Work/Interaction/LiveTests` and push the new `tests.json`.
- `O58/` … `O67/index.html`: TOAS revision tests in the JEE Advanced pattern (6 single, 6 multiple, 6 numerical; +4/−1, +4/+1 partial/−1, +3/0; max 66). The questions and keys come from the Apps Script, so none of them are in this repo. A test opens only when it is ticked in the Sheet's "TOAS Control" tab. Teacher preview: add `?preview=<key>`.
