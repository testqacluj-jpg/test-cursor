# AGENTS.md

## Cursor Cloud specific instructions

This is a bare repository with no application code, build system, or dependencies. It contains only `README.md` and `test.txt`.

### Environment

- No package manager, build tool, or framework is configured.
- No services, databases, or external dependencies are required.
- The update script is a no-op (`echo "No dependencies to install"`).

### If application code is added later

When source code is added to this repository, update:
1. The update script (via `SetupVmEnvironment`) to install the relevant dependencies.
2. This file with lint/test/build/run instructions and any non-obvious caveats.
