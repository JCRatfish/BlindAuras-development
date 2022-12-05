# BlindAuras
This is a fork of WeakAuras intended to be used by the \<Blind\> Guild.
## Converting WeakAuras to BlindAuras
### File Contents
Rename the contents of all files in the repository. For example, use the "Find in Files" feature in [Notepad++](https://notepad-plus-plus.org/). "Filters" should be set to `*.*` and "Match case" should be enabled.

1. Find `WeakAuras` and replace with `BlindAuras`
2. Find `/BlindAuras/BlindAuras` and replace with `/WeakAuras/WeakAuras`
3. Find `/BlindAuras/` and replace with `/WeakAuras/`
4. Find `The BlindAuras Team` and replace with `The WeakAuras Team`

Two files need to be modified in the `WeakAuras` folder:

1. `WeakAuras.lua`
	1. Find `"/weakauras"` and replace with `"/blindauras"`
	2. Find `/wa` and replace with `/ba`
2. `Transmission.lua`
	1. Find `weakauras` and replace with `blindauras`

### File and Folder Names
Replace `WeakAuras` with `BlindAuras`. For example, use [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/). The "Subfolders" filter and "Match case" should be enabled.
### Release
Commit changes to the "BlindAuras" repository. Ignore this "README.md" file.