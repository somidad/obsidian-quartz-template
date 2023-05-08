---
draft: true
---
# Obsidian Quartz template

This is a template repository of Obsidian vault for publishing into GitHub pages using Quartz

## Quartz

https://quartz.jzhao.xyz

## Settings

Following settgins are enabled by default:

- Automatically update internal links
- New link format: absolute path in vault

See guidelines: https://quartz.jzhao.xyz/notes/obsidian/#settings

### Templates

Following templates are defined by default:

- `post`: includes basic frontmatters, title, tags and draft (set to `true`)

### Recommended plugins

Following plugins are installed by default:

- Templater: Obsidian Quartz template is already configured to insert a template `post` when creating a new note

## How to publish

- Edit `config.toml`, `data/config.yaml` and `data/graphConfig.yaml`
- Edit `.github/workflows/publish.yml`
  - If you prefer to use Hugo template other than official Quarta, edit `Clone Quartz` step
  - If you need to include files other than `_index.md`, edit `Move content` step
  - Edit `cname` in `Publish` step

## Sponsor

If you think this is useful, please consider to support me

<a href="https://www.buymeacoffee.com/somidad" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-green.png" alt="Buy Me A Coffee" width="217" height="60" style="height: 60px !important;width: 217px !important;" ></a>
