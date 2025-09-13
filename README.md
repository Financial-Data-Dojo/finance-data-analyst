# Finance Data Analyst

## YouTube Guides

### [Financial Data Dojo YouTube Channel](https://www.youtube.com/@Dojo.FinancialData)

        > New YouTube Channel launched!
    	> Focus will be on practical guides to becoming a Data Analyst in Finance with real-world skills.
    	> Instructions also included on how to configure the Settings below

> [User Settings tutorial](https://www.youtube.com/watch?v=9B9I6Bolxt8&t=380s)

> [The Ultimate Data Analyst Toolkit for Finance](https://www.youtube.com/watch?v=9B9I6Bolxt8)

> [Your First Python Project as a Finance Data Analyst in under 40 mins!](https://www.youtube.com/watch?v=DINIzZ4EO6I)

## What?

This is a selection of VS Code extensions that has been curated after real-world usage by data analysts in the financial industry. This set is focussed around useful Data and Python extensions as well as being visually pleasing.

## Why?

We would often get asked on the most best extensions to get started with as a data analyst in finance. So we created this extension pack to make it easier for new users to get up and running as soon as possible!

# Information on each extension

## Coding related

> Helpful packages that are core to enabling Python coding within VS-Code, or add key functionaility.

| Name                                                | Description | Why it's useful |
| --------------------------------------------------- | ----------- | -----------     |
| ms-python.debugpy                                   | Python debugger engine for VS Code.       | Essential for stepping through and fixing complex code issues.           |
| ms-python.python                                    | Core Python extension for VS Code.       | Provides linting, IntelliSense, debugging, and environment management.           |
| ms-python.vscode-pylance                            | Language server for Python offering fast IntelliSense.       | Improves code completion, error checking, and performance.           |
| ms-toolsai.jupyter                                  | Support for running and editing Jupyter Notebooks.       | Allows working with data analysis workflows inside VS Code.           |
| ms-toolsai.jupyter-keymap                           | Keymaps for Jupyter-like shortcuts in VS Code.       | Provides familiar notebook-style keyboard shortcuts.           |
| ms-toolsai.jupyter-renderers                        | Rich rendering support (plots, tables, HTML) in Jupyter cells.       | Enhances visualization directly inside VS Code notebooks.           |
| ms-toolsai.vscode-jupyter-cell-tags                 | Adds cell tagging in Jupyter notebooks.       | Useful for parameterization and exporting specific cells.           |
| ms-toolsai.vscode-jupyter-slideshow                 | Turns Jupyter notebooks into slide presentations.       | Great for teaching or presenting analysis directly from notebooks.           |
| ms-vscode.powershell                                | PowerShell language support with IntelliSense and debugging.       | Enables automation and scripting within VS Code.           |
| visualstudioexptteam.intellicode-api-usage-examples | Provides sample projects showing AI-assisted IntelliCode suggestions.       | Helps understand and get started with IntelliCode.           |
| visualstudioexptteam.vscodeintellicode              | AI-assisted code completions based on best practices.       | Speeds up coding with smarter auto-completion.           |

## Data related

> Since we're focussed on working with data, these extensions are crucial to our workflow in making it easier to read and interact with the various common datasets and types we use.

| Name                                                | Description | Why it's useful |
| --------------------------------------------------- | ----------- | -----------     |
| alturos.vscjsontableeditor     | JSON editor with a spreadsheet-like table view.       | Makes large JSON files easier to read and edit.       |
| grapecity.gc-excelviewer       | Preview Excel and CSV files directly in VS Code.       | Saves time by avoiding external Excel tools.       |
| ms-mssql.data-workspace-vscode | Manage SQL Server data workspaces.       | Organizes SQL projects and connections in one place.       |
| ms-toolsai.datawrangler        | Visual data cleaning and transformation tool.       | Super useful when viewing dataframes for preview.       |
| nickdemayo.vscode-json-editor  | Rich JSON editor with validation and formatting.       | Prevents JSON syntax errors and improves readability.       |
| redhat.vscode-yaml             | YAML language support with validation and IntelliSense.       | Crucial for working with config files like Kubernetes or CI/CD.       |
| mechatroner.rainbow-csv               | Highlights CSV columns in different colors.       | Makes CSV files much easier to navigate.       |

## Organisational

> Keeping your code structured and organised is half the battle. These extensions try to make it easier to look after the more adminstrative side of coding, so you can just focus on building!

| Name                                  | Description | Why it's useful |
| --------------------------------------| ----------- | -----------     |
| davidanson.vscode-markdownlint        | Lints and enforces Markdown style rules.       | Ensures clean, consistent markdown documentation.       |
| ms-python.black-formatter             | Automatically formats Python code using Black.       | Enforces consistent and PEP 8–compliant style. Easier for teams to read/be consistent.       |
| gruntfuggly.todo-tree                 | Displays TODO/FIXME comments in a tree view.       | Keeps track of tasks and reminders inside projects. Super useful!       |
| inferrinizzard.prettier-sql-vscode    | Formats SQL queries for readability.       | Saves time by auto-formatting complex queries.       |
| jeff-hykin.polacode-2019              | Generates screenshots of code snippets.       | Useful for sharing styled code in slides or docs/documentation.       |
| kevinrose.vsc-python-indent           | Fixes Python indentation issues automatically.       | Prevents syntax errors caused by misaligned code.       |
| oderwat.indent-rainbow                | Colors indentation levels in code.       | Quickly spot alignment and indentation errors.       |
| streetsidesoftware.code-spell-checker | Checks spelling in source code and documentation.       | Prevents typos in comments, strings, and docs.       |
| yzhang.markdown-all-in-one            | Provides Markdown shortcuts, TOC, and preview features.       | Streamlines writing and formatting documentation.       |

## Themes

> When you're spending hours in a coding session, you want your environment to look sleek and exciting. These themes have been tested and hand picked to provide a nice experience whilst you build.

| Name                          | Description | Why it's useful |
| ------------------------------| ----------- | -----------     |
| zanza00.random-theme-switcher | Automatically switches VS Code theme randomly.       | Keeps coding experience fresh and varied.       |

| Theme Name |
| ---------- |
|akamud.vscode-theme-onedark   |
| daylerees.rainglow           |
| eliverlara.andromeda         |
| enkia.tokyo-night            |
| pkief.material-icon-theme    |
| robbowen.synthwave-vscode    |
| sallar.vscode-duotone-dark   |

# Useful Settings Config

To quickly customise your VS Code environment, try our Settings JSON config details below. (Ctrl/Cmd + Shift + P > Search for Preferences: Open User Settings (JSON))

```json
{
  "workbench.colorTheme": "Solarized Dark",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.settings.applyToAllProfiles": [],
  "editor.fontSize": 12,
  "editor.cursorBlinking": "expand",
  "editor.minimap.enabled": false,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "ms-python.black-formatter",
  "[Python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.formatOnSave": true
  },
  "[SQL]": {
    "editor.defaultFormatter": "inferrinizzard.prettier-sql-vscode"
  },
  "files.defaultLanguage": "python",
  "indentRainbow.indicatorStyle": "light",
  "jupyter.interactiveWindow.textEditor.executeSelection": true,
  "jupyter.interactiveWindow.creationMode": "perFile",
  "cSpell.language": "en-GB",
  "randomThemeSwitcher.switchMode": "interval",
  "randomThemeSwitcher.switchInterval": 15,
  "randomThemeSwitcher.themeList": [
    "Andromeda Italic Bordered",
    "Atom One Dark",
    "Codecourse (rainglow)",
    "Friction (rainglow)",
    "Heroku (rainglow)",
    "Isotope (rainglow)",
    "Kiwi Contrast (rainglow)",
    "Laracasts (rainglow)",
    "Legacy (rainglow)",
    "Lichen (rainglow)",
    "Overflow (rainglow)",
    "Pleasure Contrast (rainglow)",
    "Prime (rainglow)",
    "Rainbow (rainglow)",
    "Solarized Dark",
    "Storm (rainglow)",
    "SynthWave '84",
    "Tokyo Night Storm"
  ],
  "randomThemeSwitcher.excludeThemes": [
    "Abyss",
    "Default Dark+",
    "Default Dark Modern",
    "Visual Studio Dark",
    "Kimbie Dark",
    "Monokai",
    "Monokai Dimmed",
    "Red",
    "Solarized Dark",
    "Tomorrow Night Blue",
    "Atom One Dark",
    "Absent Contrast (rainglow)",
    "Absent (rainglow)",
    "Allure Contrast (rainglow)",
    "Allure (rainglow)",
    "Arstotzka Contrast (rainglow)",
    "Arstotzka (rainglow)",
    "Azure Contrast (rainglow)",
    "Azure (rainglow)",
    "Banner Contrast (rainglow)",
    "Banner (rainglow)",
    "Blink Contrast (rainglow)",
    "Blink (rainglow)",
    "Bold Contrast (rainglow)",
    "Bold (rainglow)",
    "Box UK Contrast (rainglow)",
    "Box UK (rainglow)",
    "Brave Contrast (rainglow)",
    "Brave (rainglow)",
    "Carbonight Contrast (rainglow)",
    "Carbonight (rainglow)",
    "Chocolate Contrast (rainglow)",
    "Chocolate (rainglow)",
    "Codecourse Contrast (rainglow)",
    "Codecourse (rainglow)",
    "Coffee Contrast (rainglow)",
    "Coffee (rainglow)",
    "Comrade Contrast (rainglow)",
    "Comrade (rainglow)",
    "Crackpot Contrast (rainglow)",
    "Crackpot (rainglow)",
    "Crisp Contrast (rainglow)",
    "Crisp (rainglow)",
    "Dare Contrast (rainglow)",
    "Dare (rainglow)",
    "Darkside Contrast (rainglow)",
    "Darkside (rainglow)",
    "Downpour Contrast (rainglow)",
    "Downpour (rainglow)",
    "Earthsong Contrast (rainglow)",
    "Earthsong (rainglow)",
    "Fodder Contrast (rainglow)",
    "Fodder (rainglow)",
    "Frantic Contrast (rainglow)",
    "Frantic (rainglow)",
    "Freshcut Contrast (rainglow)",
    "Freshcut (rainglow)",
    "Friction Contrast (rainglow)",
    "Friction (rainglow)",
    "Frontier Contrast (rainglow)",
    "Frontier (rainglow)",
    "Github Contrast (rainglow)",
    "Github (rainglow)",
    "Glance Contrast (rainglow)",
    "Glance (rainglow)",
    "Gloom Contrast (rainglow)",
    "Gloom (rainglow)",
    "Glowfish Contrast (rainglow)",
    "Glowfish (rainglow)",
    "Goldfish (rainglow)",
    "Grunge Contrast (rainglow)",
    "Grunge (rainglow)",
    "Halflife Contrast (rainglow)",
    "Halflife (rainglow)",
    "Hawaii Contrast (rainglow)",
    "Hawaii (rainglow)",
    "Heroku Contrast (rainglow)",
    "Heroku (rainglow)",
    "Hive Contrast (rainglow)",
    "Hive (rainglow)",
    "Horizon Contrast (rainglow)",
    "Horizon (rainglow)",
    "Hub Contrast (rainglow)",
    "Hub (rainglow)",
    "Hyrule Contrast (rainglow)",
    "Hyrule (rainglow)",
    "Iceberg Contrast (rainglow)",
    "Iceberg (rainglow)",
    "Isotope Contrast (rainglow)",
    "Isotope (rainglow)",
    "Jewel Contrast (rainglow)",
    "Jewel (rainglow)",
    "Jingle Contrast (rainglow)",
    "Jingle (rainglow)",
    "Joker Contrast (rainglow)",
    "Joker (rainglow)",
    "Juicy Contrast (rainglow)",
    "Juicy (rainglow)",
    "Jumper Contrast (rainglow)",
    "Jumper (rainglow)",
    "Keen Contrast (rainglow)",
    "Keen (rainglow)",
    "Kiwi Contrast (rainglow)",
    "Kiwi (rainglow)",
    "Laracasts Contrast (rainglow)",
    "Laracasts (rainglow)",
    "Laravel Contrast (rainglow)",
    "Laravel (rainglow)",
    "Lavender Contrast (rainglow)",
    "Lavender (rainglow)",
    "Legacy Contrast (rainglow)",
    "Legacy (rainglow)",
    "Lichen Contrast (rainglow)",
    "Lichen (rainglow)",
    "Loyal Contrast (rainglow)",
    "Loyal (rainglow)",
    "Mauve Contrast (rainglow)",
    "Mauve (rainglow)",
    "Mellow Contrast (rainglow)",
    "Mellow (rainglow)",
    "Mintchoc Contrast (rainglow)",
    "Mintchoc (rainglow)",
    "Monzo Contrast (rainglow)",
    "Monzo (rainglow)",
    "Morass Contrast (rainglow)",
    "Morass (rainglow)",
    "Mud Contrast (rainglow)",
    "Mud (rainglow)",
    "Newton Contrast (rainglow)",
    "Newton (rainglow)",
    "Otakon Contrast (rainglow)",
    "Otakon (rainglow)",
    "Overflow Contrast (rainglow)",
    "Overflow (rainglow)",
    "Pastel Contrast (rainglow)",
    "Pastel (rainglow)",
    "Patriot Contrast (rainglow)",
    "Patriot (rainglow)",
    "Peacock Contrast (rainglow)",
    "Peacock (rainglow)",
    "Peacocks In Space Contrast (rainglow)",
    "Peacocks In Space (rainglow)",
    "Peel Contrast (rainglow)",
    "Peel (rainglow)",
    "Penitent Contrast (rainglow)",
    "Penitent (rainglow)",
    "Piggy Contrast (rainglow)",
    "Piggy (rainglow)",
    "Pleasure Contrast (rainglow)",
    "Pleasure (rainglow)",
    "Potpourri Contrast (rainglow)",
    "Potpourri (rainglow)",
    "Prime Contrast (rainglow)",
    "Prime (rainglow)",
    "Rainbow Contrast (rainglow)",
    "Rainbow (rainglow)",
    "Rebellion Contrast (rainglow)",
    "Rebellion (rainglow)",
    "Revelation Contrast (rainglow)",
    "Revelation (rainglow)",
    "Scorch Contrast (rainglow)",
    "Scorch (rainglow)",
    "Service Contrast (rainglow)",
    "Service (rainglow)",
    "Shrek Contrast (rainglow)",
    "Shrek (rainglow)",
    "Slate Contrast (rainglow)",
    "Slate (rainglow)",
    "Slime Contrast (rainglow)",
    "Slime (rainglow)",
    "Snappy Contrast (rainglow)",
    "Snappy (rainglow)",
    "Solarflare Contrast (rainglow)",
    "Solarflare (rainglow)",
    "Soup Contrast (rainglow)",
    "Soup (rainglow)",
    "Sourlick Contrast (rainglow)",
    "Sourlick (rainglow)",
    "Spearmint Contrast (rainglow)",
    "Spearmint (rainglow)",
    "Spitfire Contrast (rainglow)",
    "Spitfire (rainglow)",
    "Stark Contrast (rainglow)",
    "Stark (rainglow)",
    "Stasis Contrast (rainglow)",
    "Stasis (rainglow)",
    "Stealth Contrast (rainglow)",
    "Stealth (rainglow)",
    "Storm Contrast (rainglow)",
    "Storm (rainglow)",
    "Super Contrast (rainglow)",
    "Super (rainglow)",
    "Tame Contrast (rainglow)",
    "Tame (rainglow)",
    "Tetra Contrast (rainglow)",
    "Tetra (rainglow)",
    "Tickle Contrast (rainglow)",
    "Tickle (rainglow)",
    "Tonic Contrast (rainglow)",
    "Tonic (rainglow)",
    "Tribal Contrast (rainglow)",
    "Tribal (rainglow)",
    "Tron Contrast (rainglow)",
    "Tron (rainglow)",
    "Turnip Contrast (rainglow)",
    "Turnip (rainglow)",
    "Tweed Contrast (rainglow)",
    "Tweed (rainglow)",
    "Violaceous Contrast (rainglow)",
    "Violaceous (rainglow)",
    "Vision (colorblind) (rainglow)",
    "Volatile Contrast (rainglow)",
    "Volatile (rainglow)",
    "Warlock Contrast (rainglow)",
    "Warlock (rainglow)",
    "Waste Contrast (rainglow)",
    "Waste (rainglow)",
    "Yitzchok Contrast (rainglow)",
    "Yitzchok (rainglow)",
    "Userscape Contrast (rainglow)",
    "Userscape (rainglow)",
    "Vegetable Contrast (rainglow)",
    "Vegetable (rainglow)",
    "Yule Contrast (rainglow)",
    "Yule (rainglow)",
    "Zacks Contrast (rainglow)",
    "Zacks (rainglow)",
    "Andromeda",
    "Andromeda Bordered",
    "Andromeda Italic Bordered",
    "Andromeda Italic",
    "Andromeda Colorizer",
    "Tokyo Night",
    "Tokyo Night Storm",
    "SynthWave '84",
    "DuoTone Dark Sea",
    "DuoTone Dark Space",
    "DuoTone Dark Forest",
    "DuoTone Dark Sky",
    "DuoTone Dark Earth"
  ]
}
```
