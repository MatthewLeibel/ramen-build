# ramen-build

Build runner for the Windows packages of [RAMen](https://getramenai.com), local AI with session memory.

There is no source code here. The workflow in `.github/workflows/windows.yml` fetches RAMen's private repository with
a read-only key, builds the Windows packages, tests them on a clean Windows machine the way a customer installs them,
and keeps the packages as build artifacts. Releases are published at
[MatthewLeibel/ramen-releases](https://github.com/MatthewLeibel/ramen-releases).

RAMen is proprietary software by NEOTECH Inc. Install it from https://getramenai.com.
