# Change Log

A bi-weekly log of project changes and updates, if no changes were made in a given two weeks no entry will be made.

## Catalogue

| Date | Version |
| - | - |
| [10/24/2022 - 11/06/2022](#10242022---11062022) | 0.3 |
| [10/10/2022 - 10/23/2022](#10102022---10232022) | 0.2 |
| [9/25/2022 - 10/9/2022](#9252022---1092022) | 0.1 |

## 10/24/2022 - 11/06/2022

New Features:

- Started the GitHub Pages website [#14](https://github.com/TigardHighGDC/FlappyBird/pull/14).
  - Reset the `gh-pages` branch, created `index.html` and cleaned up `.gitignore`.
- Spawning pipes [#13](https://github.com/TigardHighGDC/FlappyBird/pull/11).
  - Moving pipes across the screen.
- Bird Collision with pipes [#13](https://github.com/TigardHighGDC/FlappyBird/pull/11).
  - Bird now dies (gets deleted) when colliding with pipes.

Enhancements:

- Extra info added to `README.md` [#16](https://github.com/TigardHighGDC/FlappyBird/pull/16).
- `Flying.cs` replaced with [`Movement.cs`](https://github.com/TigardHighGDC/FlappyBird/blob/main/Assets/Scripts/Movement.cs) [#13](https://github.com/TigardHighGDC/FlappyBird/pull/11).

Bug Fixes:

- None

## 10/10/2022 - 10/23/2022

New Features:

- None

Enhancements:

- Readme updated [#10](https://github.com/TigardHighGDC/FlappyBird/pull/10).
  - Extremely basic info added, just to get away from the template readme.
- Codeowners now requests review from team members of `@ogpcleaders` respectively [#11](https://github.com/TigardHighGDC/FlappyBird/pull/11).

Bug Fixes:

- `clang-format-check.yml` now properly checks all `.cs` files [#9](https://github.com/TigardHighGDC/FlappyBird/pull/9).
  - No longer using the official `clang-format` action, now using a new python script.

## 9/25/2022 - 10/9/2022

New Features:

- Initial commit of the project.
  - Created from the [`GameDevTemplate`](https://github.com/TigardHighGDC/GameDevTemplate).
- Unity project created [#4](https://github.com/TigardHighGDC/FlappyBird/pull/4).
  - Created from the `Unity 2D Game` template.
- Rigidbody2D Bird Flying Controller [#6](https://github.com/TigardHighGDC/FlappyBird/pull/6).
  - Untested controller for the player controlled bird.

Enhancements:

- None

Bug Fixes:

- None
