Java 25 modified to work with Windows Vista. This build will work on unmodified Vista and networking works now.

Suggested build command (or you will get missing function errors):

```bash configure --with-target-bits=64 --with-toolchain-version=2019 --with-extra-cflags="-DPSAPI_VERSION=1" --with-extra-cxxflags="/DPSAPI_VERSION=1"```

You can also download a pre-compiled release in the releases section.

Another thing, this is targetting unmodified Windows Vista. the Vista extended kernel could cause issues with this that would otherwise not happen on a stock Vista system. 
Compatibility is not guaranteed with the extended kernel installed.

If you need to contact me for any reason, my Discord server is your best bet.

- **My website**: https://win-games.uk/
- **My Discord**: https://discord.gg/xZyz6WTfaT
- **My email**: windvd@win-games.uk
