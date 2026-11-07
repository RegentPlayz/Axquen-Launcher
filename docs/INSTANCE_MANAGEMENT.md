# Instance Management

Axquen's instance library is designed to keep different Minecraft setups
organized and separate.

## Why use separate instances?

Separate instances can maintain distinct Minecraft versions, loaders, mods,
worlds, and configuration. This reduces accidental cross-contamination between
a lightweight PvP setup, an SMP profile, and a larger modpack.

## Create an instance

Use the **New** action in the Instances view and follow the options presented
by your installed Axquen build. Exact fields and defaults may vary by version.
Choose a Minecraft version and loader combination compatible with the mods you
intend to use.

## Launch an instance

Select the intended instance and use its **Play** action. If launch fails,
record the Axquen build, Minecraft version, loader, Java version, and relevant
sanitized logs.

## Edit and duplicate

Use **Edit** to adjust the instance configuration exposed by the application.
Use **Duplicate** when you want a separate copy to experiment with while
preserving the original setup. Verify the destination and content before
deleting or replacing anything.

## Content and folders

The library exposes **Content** and **Open Folder** actions. Use them to
inspect or manage instance content through the supported interface and local
folder. Avoid manually deleting unfamiliar files.

## Search and sorting

The instance view includes a search field and sorting/filter controls. These
help locate a profile in a library containing multiple versions or modpacks.

## Importing existing profiles

The import interface lists Modrinth, CurseForge, Prism Launcher, MultiMC,
GDLauncher, ATLauncher, Dawn (Feather), Lunar Client, and TLauncher. The
application may show whether a launcher is detected. Detection depends on
local installation paths and supported profile formats; not every installation
will be detected or importable.

## Delete carefully

Before deleting an instance, back up any worlds, screenshots, resource packs,
configurations, or other data you want to keep. Confirm which instance is
selected before using **Delete**.
