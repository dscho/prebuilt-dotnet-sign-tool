# prebuilt-dotnet-sign-tool

Pre-built [dotnet/sign](https://github.com/dotnet/sign) tool for use on
Windows/ARM64 runners. The sign tool currently lacks ARM64 support
([dotnet/sign#852](https://github.com/dotnet/sign/issues/852)), so this
provides an x64 build that runs under x64 emulation on `windows-11-arm`
GitHub-hosted runners.

Trigger the workflow manually to check for new versions and publish a release.
