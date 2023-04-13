# ConfigDN

Open source configuration management and feature flags.

# Requirements

- Node.js (Recommended: LTS or newer)
- NPM
- Go 1.19+

# Building the project

To build the project, use the build script:

```bash
./build.sh
```

This script also builds the UI before a release. Alternatively, you can download a release from the [releases page](https://github.com/dBuidl/ConfigDN/releases).

# Running the project

To run the project, execute the executable built by the build script:

```bash
./ConfigDN
```

ConfigDN will then be available at:
- http://localhost:8090/ - UI
- http://localhost:8090/_/ - Admin UI (Make sure you visit this before making it public as the first person to visit it will be made an admin)