# Starbound Digital Character Sheet

A mobile-friendly digital character sheet and lightweight campaign manager for the **Starbound** homebrew tabletop RPG.

This app is built as a single-file HTML/CSS/JavaScript application. It runs entirely in the browser, saves data locally, and can be hosted for free on GitHub Pages, Netlify, or any static web host.

## Features

### Character Sheet

- Species, class, background, level, and experience tracking
- Ability scores with auto-calculated modifiers
- Saving throw proficiency tracking
- Auto-calculated skill bonuses
- Features and talents section
- Character art upload
- Character description and roleplay notes

### Class-Based Setup

The app includes class setup support for Starbound roles such as:

- Captain
- Cyber Knight
- Engineer
- Gunslinger
- Starblade
- Saboteur
- Technomancer
- Void Dancer
- Xeno Adept

Class setup can automatically suggest or apply:

- Hit die
- Saving throws
- Skill proficiencies
- Protection proficiencies
- Weapon proficiencies
- Power source / ability modifier
- Device integration slots
- Starting class features
- Power Reserve progression

### Combat Tools

- Combat Quick Panel
- Current HP, max HP, temp HP, shield, and max shield tracking
- Defense / AC
- Initiative
- Speed
- Primary weapon summary
- Damage and healing controls
- Short Rest and Long Rest recovery tools

### Abilities

- Searchable ability picker
- Ability filters by:
  - Level
  - Discipline
  - Action type
  - Damage type
  - Role tag
- Ability Level Folders
- Editable ability list
- Play-friendly Ability Card View
- Ability Save DC and Ability Attack Bonus calculations
- Power Reserve tracking

### Devices, Gear, and Inventory

- Searchable device picker
- Collapsible device search panel
- Device used / expended tracking
- Device rest recovery notes
- Weapon tracking
- Inventory / cargo tracking
- Credits tracking
- Searchable gear and feature pickers

### Mission Log

The Notes section includes structured campaign fields:

- Current Mission
- Crew / Party Members
- Contacts
- Factions
- Planets Visited
- Ships / Stations
- Active Jobs
- Debts / Obligations
- Reputation Notes
- General Campaign Notes

### Ship / Crew Tab

Track the crew's ship with:

- Ship Name
- Ship Class
- Hull / Max Hull
- Shields
- Speed
- Fuel
- Jump Charges
- Ship Weapons
- Crew Roles
- Cargo
- Upgrades
- Damage / Repairs
- Ship Notes

### GM / NPC Tools

- GM / NPC mode
- NPC Library with multiple NPCs
- NPC folders / categories
- Location, faction, and tag fields
- Searchable NPC list
- NPC duplication and deletion
- NPC HP, defense, tactics, loot, and notes

### Encounter Tracker

- Add player character to encounter
- Add blank enemies
- Add NPCs from NPC Library
- Add multiple copies of an NPC
- Initiative tracking
- Round and active turn tracking
- HP, shields, defense, speed, conditions, tactics, and notes
- Damage and healing controls
- Mark down / restore combatants

### Save System

- Local browser autosave
- Multiple save slots
- Rename save slots
- Duplicate save slots
- Delete save slots
- Export selected character as JSON
- Import JSON backups

### Display Modes

- Light Mode
- Dark Mode
- Print Mode
- Mobile-focused clean layout
- View Mode / Edit Mode toggle
- Collapsible sections for easier phone and tablet use

### Printing / PDF

The app includes a dedicated print layout for cleaner PDF export:

- Page 1: Core character and combat
- Page 2: Abilities and devices
- Page 3: Inventory, ship, notes, and mission log

## How to Use

### Open Locally

1. Download or clone this repository.
2. Make sure the main app file is named:

```text
index.html
```

3. Double-click `index.html` to open it in your browser.

No installation is required.

## Hosting for Free

This app is a static website. It does not require a server, database, or paid hosting.

### GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the root of the repository.
3. Go to **Settings > Pages**.
4. Set **Source** to **Deploy from a branch**.
5. Choose the `main` branch and `/root`.
6. Save.

Your app will be available at:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

### Netlify

1. Rename the app file to `index.html`.
2. Place it inside a folder.
3. Go to Netlify.
4. Drag and drop the folder into a new deploy.
5. Netlify will give you a free live URL.

## Updating the App

When you receive or create a new version of the app:

1. Rename the updated file to `index.html`.
2. Replace the existing `index.html` in your GitHub repository or Netlify deploy.
3. Commit or redeploy.
4. Refresh your live site.

## Data Storage

The app stores character and campaign data in the browser using local storage.

Important notes:

- Data is saved on the device/browser you are using.
- Clearing browser data may delete saved characters.
- Use **Export Selected JSON** to back up your character.
- Use **Import JSON** to restore a backup.

## Recommended Backup Workflow

Before making big changes or leveling up:

1. Open the app.
2. Choose the correct save slot.
3. Click **Export Selected JSON**.
4. Save the JSON file somewhere safe.

## File Structure

This project can work with only one file:

```text
starbound-app/
└── index.html
```

Optional GitHub project structure:

```text
starbound-app/
├── index.html
└── README.md
```

## Browser Support

Recommended browsers:

- Google Chrome
- Microsoft Edge
- Firefox
- Safari

For the best experience, use a modern browser on desktop, tablet, or mobile.

## Notes

This app is designed for the Starbound homebrew tabletop RPG and can be customized as the system grows.

Suggested future upgrades:

- More complete class progression tables
- More species traits
- More gear and device templates
- Starship combat mode
- Built-in dice log
- Campaign codex
- Import/export full campaign bundles

## License

This project is for personal tabletop RPG use.

If you plan to publish or distribute it publicly, add a license that matches how you want others to use, modify, or share it.
