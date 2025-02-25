# takattoFS2-Next Mods

The official collection of Windhawk mods. The mods can be viewed and installed with [takattoFS2 Patcher](https://takattowo.github.io/takattoFS2/).

## Discussing Mods

You're welcome to participate in [GitHub Discussions](https://github.com/takattowo/takattoFS2-mods/discussions) or join [the Discord channel](https://discord.gg/yJmKf7PDzS) for a live discussion.

## Creating a New Mod

Please refer to the corresponding wiki page: [Creating a New Mod](https://github.com/takattowo/takattoFS2-mods/wiki/creating-a-new-mod).

## Submitting a New Mod

Submit a new mod by creating a pull request in this repository. The pull request must consist of a single folder, `mods/<your_mod_name>`, where `<your_mod_name>` is the folder that contains metadata and its files.

The mod's `author` metadata value must be specified, and must match the pull request author's GitHub profile.

Mods which don't specify a license are submitted under [the MIT license](https://opensource.org/licenses/MIT). It's the author's responsibility to specify the appropriate license for third-party code.

## Submitting a Mod Update

Submit a mod update by creating a pull request in this repository. The pull request must consist of changes to a single file, `mods/<your_mod_name>`, where `<your_mod_name>` is your mod folder.

The mod's `version` metadata value must be changed to a newer version.

The mod's `author` metadata value must match the pull request author's GitHub profile. This means that you can only submit an update for a mod that you originally submitted. If you'd like to update a mod that you didn't submit, you can either submit the changes to the mod author, or submit a new mod instead.

The commit message should include information about the new version. The information will be shown in the mod's changelog.
