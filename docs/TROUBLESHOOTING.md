# Troubleshooting

This guide provides safe first checks. Exact menu names and repair behavior
depend on the installed Axquen build.

## Launcher does not open

- Confirm that the installer came from an official Axquen distribution channel.
- Restart Windows and try opening the launcher again.
- Note any visible error message.
- Check whether security software quarantined an application file; do not
  disable protection blindly.
- Contact support with the build identifier and sanitized details.

## Java errors

- Review the Java configuration exposed by Axquen.
- Confirm that the selected runtime is suitable for the Minecraft version.
- Check that the configured Java executable still exists.
- Avoid downloading Java from unofficial bundled installers.

The exact Java version matrix for supported Axquen builds has not been supplied.
Check official release guidance.

## Minecraft startup failures

- Record the Minecraft version, loader, Java version, and memory allocation.
- Check whether the instance starts without recently added mods.
- Review the crash report and launcher log.
- Use supported diagnostics/recovery options if offered.
- Back up the instance before disabling or removing content.

## Mod incompatibilities

- Verify each mod supports the selected Minecraft version and loader.
- Check required dependencies.
- Check whether a mod is client-side, server-side, or both.
- Test changes in a duplicate instance.
- Avoid assuming a mod listed in the browser is compatible with every profile.

## Loader problems

Confirm that the selected loader matches the instance and installed mod files.
Use official loader information and Axquen release notes for version-specific
guidance. Do not mix loader-specific files without confirming compatibility.

## Missing files or installation problems

- Confirm the download completed successfully.
- Use only official distribution channels.
- Avoid deleting application or instance folders manually unless support
  explicitly guides you.
- If reinstalling, preserve backups of worlds and important instance data.

## Crash diagnostics

Axquen may detect startup crashes, identify possible faulty mods or conflicts,
and offer supported recovery options. These tools cannot guarantee a diagnosis
or repair for every crash.

## When contacting support

Provide the Axquen build, operating system, Minecraft version, loader, Java
version, reproduction steps, and sanitized logs. Remove credentials, tokens,
email addresses, session information, and private file paths before sharing.

Official support: https://discord.gg/StdYxkEXRc
