[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18121545&assignment_repo_type=AssignmentRepo)
## Parsing yaml

You need to find out what user has admin permissions and return the **full name** of the user.

File structure information is available:
```
- username
  - name
  - permission
```
use ```text``` method for ```requests.get``` to obtain file content before parsing.

The number of users and their properties may vary (theoretically), so **do not use numerical indexes** for them, but cycles instead.\
```['users'][1]['permission']``` will probably return the correct answer, but is not considered a correct solution.
