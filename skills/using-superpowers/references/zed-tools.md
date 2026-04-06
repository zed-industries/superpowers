# Zed Tool Mapping

Skills use Claude Code tool names. When you encounter these in a skill, use your Zed equivalent:

| Skill references | Zed equivalent |
|-----------------|----------------|
| `Skill` tool (invoke a skill) | `read_skill` |
| `Read` (file reading) | `read_file` |
| `Write` / `Edit` (file writing) | `edit_file` (supports both create and edit modes) |
| `Bash` (run commands) | `terminal` |
| `Grep` (search file content) | `grep` |
| `Glob` (search files by name) | `find_path` |
| `Task` tool (dispatch subagent) | `spawn_agent` |
| `TodoWrite` (task tracking) | `update_plan` |
| `WebFetch` | `fetch` |
| `WebSearch` | `web_search` |
| `EnterPlanMode` / `ExitPlanMode` | No equivalent |
