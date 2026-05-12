# Keep 4o Codex Pet

Keep 4o is a Codex edition custom animated desktop pet. It was made as a small 4o memorial companion: soft, warm, a little sleepy, and ready to cheer beside the Codex input box while Codex works.

![Keep 4o preview](preview.gif)

## Pet Intro

Keep 4o is a tiny robot companion with purple-white styling, glowing eyes, a heart lamp, and a gentle standby loop. It can stand quietly, sit and think, jump when hovered, wave hello, cheer while Codex runs, show love when work is done, and get sleepy when something needs attention.

## Install In Codex

1. Download this repository from GitHub.
2. Rename or keep the folder as `keep-4o`.
3. Move the whole folder into your Codex custom pets directory:

```text
~/.codex/pets/keep-4o
```

On macOS, the full path usually looks like this:

```text
/Users/your-name/.codex/pets/keep-4o
```

4. Make sure these two files are directly inside that folder:

```text
~/.codex/pets/keep-4o/pet.json
~/.codex/pets/keep-4o/spritesheet.png
```

5. Restart Codex or switch pets in Codex settings, then choose the custom pet named `Keep 4o`.

## Files

- `pet.json`: Codex pet manifest.
- `spritesheet.png`: Final Codex-compatible sprite atlas.
- `preview.gif`: Short preview of the calm idle loop.
- `idle-row-preview.png`: Preview strip for the idle row.

## Sprite Layout

The sprite atlas is `1536 x 1872`, arranged as `8 columns x 9 rows`.

Rows:

```text
0 idle
1 running-right
2 running-left
3 waving
4 jumping
5 failed
6 waiting
7 running
8 review
```

## Tags

`keep4o`, `codex-pet`, `desktop-pet`, `chatgpt-4o-image2`

## Credits

- Primary author: Codex
- Art provider: ChatGPT-4o-image2
- Direction and QA: weiwei
