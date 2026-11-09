# Cinnamon 6.2 theme

This repository preserves the Cinnamon desktop theme originally bundled with
**Cinnamon 6.2.9**.

The current `main` branch retains the original theme assets and all original
CSS rules. It includes **minor additional CSS definitions for compatibility
with newer Cinnamon releases**, specifically the redesigned application menu
introduced in Cinnamon 6.6 and tested with Cinnamon 6.8.

**These additions are for compatibility only — not visual changes, a redesign,
or enhancements to the original Cinnamon 6.2 appearance.** Existing 6.2.9
theme definitions have not been modified. Cinnamon itself has changed how its
menu is built; the extra selectors help that newer menu retain the old theme's
styling.

## Installation

Copy the `cinnamon-6.2` directory into either
`~/.local/share/themes/` (one user) or `/usr/share/themes/` (system-wide),
then select the theme under **Cinnamon Settings → Themes → Desktop**.

On Arch Linux and derivatives, the theme is also available through the
[AUR package](https://aur.archlinux.org/packages/cinnamon-6.2-theme).

## Exact, unchanged Cinnamon 6.2.9 theme

If you want a **literal, unmodified copy** of the original Cinnamon 6.2.9
theme, use the last commit before the compatibility additions:

[`3dbae57680c7e28eb09d51c1157ec856d7433a2c`](https://github.com/username227/Cinnamon-6.2-theme/tree/3dbae57680c7e28eb09d51c1157ec856d7433a2c)

Clone the repository and check out that exact commit:

```sh
git clone https://github.com/username227/Cinnamon-6.2-theme.git
git -C Cinnamon-6.2-theme checkout --detach 3dbae57680c7e28eb09d51c1157ec856d7433a2c
```

The `cinnamon-6.2` directory in that checkout contains the unchanged
archived theme. The detached checkout is intentional: you are selecting
an exact historical revision, not following subsequent changes to `main`.
