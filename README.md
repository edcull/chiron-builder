# Chiron Character Creator

A web-based character creator for the Chiron tabletop RPG system, set in the Alpha Centauri universe. Create colonist characters with faction affiliations, ideologies, proficiencies, advantages, and drawbacks.

## Features

- **Seven Factions**: Gaians, Hive, University, Morgan Industries, Spartans, Believers, and Peacekeepers - each with unique bonuses and starting proficiencies
- **Ideology System**: Choose Faction, Role, Belief, and Aversion ideologies that shape your character's worldview and proficiency costs
- **Proficiency Selection**: 100+ proficiencies organized by ideology, with dynamic XP costing based on your ideology alignment
- **Advantages & Drawbacks**: Customize your character with benefits and flaws that affect XP balance
- **Resource Tracking**: Automatic calculation of Energy, Nutrients, Minerals, Breakthroughs, and Facilities income
- **PDF Export**: Generate a professional character sheet PDF with all selections
- **JSON Import/Export**: Save and load characters for later editing

## How to Use

1. **Open the HTML file** in any modern web browser (Chrome, Firefox, Safari, Edge)
2. **Select a faction** - this determines your starting bonuses and faction ideology
3. **Choose ideologies** - Role, Belief, and Aversion shape proficiency costs
4. **Select proficiencies** - pick skills from the grid, noting XP costs by ideology alignment
5. **Add advantages/drawbacks** - balance XP by taking flaws for benefits
6. **Export** - generate a PDF character sheet or save as JSON

## Technical Details

- **Single HTML file** - no build process or dependencies required
- **Uses jsPDF** for PDF generation (loaded from CDN)
- **Responsive design** - works on desktop and mobile
- **Local storage** - character data stays in your browser

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

This project is designed for personal use with the Chiron RPG system.

## Version

Current version: 0.21

### Changelog

- **0.21**: Updated Morgan Industries faction bonus
- **0.2**: Fixed some issues with resources and added facility managment and breakthrough as resources
- **0.1**: Initial release
