# Alcuin of York - Letters Network Visualization

An interactive network visualization exploring the correspondence of Alcuin of York (c. 735-804 CE), a central figure in the Carolingian Renaissance.

## About

This project visualizes the extensive correspondence network of Alcuin of York during his time at Charlemagne's court. The visualization includes:

- **50+ letters** from Alcuin's corpus (c. 787-804 CE)
- **Network relationships** showing direct recipients and mentioned persons
- **Carolingian court aliases** (e.g., "Flaccus" for Alcuin, "David" for Charlemagne)
- **Letter categorization** (Personal, Ecclesiastical, Courtly, Political)
- **Temporal filtering** to explore correspondence over time
- **Interactive biographies** for key figures

## Features

### Interactive Network Graph
- **Hover** over nodes to see letter citations
- **Click** info buttons (i) for biographical information
- **Drag** nodes to rearrange the layout
- **Zoom and pan** to explore the network

### Node Types
- **Gold node**: Alcuin (central figure)
- **Blue nodes**: Direct letter recipients
- **Gray nodes**: Persons mentioned in letters

### Letter Categories
Correspondence is color-coded by category:
- **Blue**: Personal letters
- **Green**: Ecclesiastical matters
- **Yellow**: Courtly correspondence
- **Red**: Political affairs

### Temporal Filter
Enable the temporal filter to:
- Explore correspondence within specific time periods
- Adjust the time window (2-8 years)
- Observe how the network evolved over time

### Carolingian Court Aliases
The visualization includes authentic court aliases used in the Carolingian Renaissance:
- Alcuin = "Flaccus" (after Horace)
- Charlemagne = "David"
- Angilbert = "Homer"
- Arno of Salzburg = "Aquila" (Eagle)
- And many more...

## Technology Stack

- **D3.js v7** - Network visualization and force-directed layout
- **Tailwind CSS** - Styling and UI components
- **Vanilla JavaScript** - Data processing and interactivity

## Running Locally

Simply open `index.html` in a modern web browser. No build process or server required.

```bash
# Clone the repository
git clone https://github.com/Chlodomer/Alcuin.git

# Open in browser
open index.html
```

Or serve with a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

## Data Sources

The letters dataset is based on Alcuin's correspondence as documented in:
- Patrologia Latina (Migne)
- Historical ecclesiastical records
- Medieval chronicles

Biographical information is sourced from:
- Eleanor Shipley Duckett, "Alcuin, Friend of Charlemagne" (1951)
- Einhard, "Vita Karoli Magni" (c. 830)
- Contemporary medieval sources

## Historical Context

Alcuin of York was a key figure in the **Carolingian Renaissance**, the revival of art, religion, and culture under Charlemagne's patronage. His correspondence network included:

- **Royalty**: Charlemagne, various Anglo-Saxon kings
- **Ecclesiastical leaders**: Popes, archbishops, abbots
- **Scholars and courtiers**: Members of Charlemagne's court academy
- **Monastic communities**: York, Lindisfarne, Tours, and more

The letters cover diverse topics:
- Theological controversies (e.g., Adoptionism)
- Educational curriculum and book requests
- Political advice and diplomacy
- Personal friendships and pastoral care
- Responses to Viking raids on monasteries

## Project Structure

```
Alcuin/
├── index.html          # Main visualization file
└── README.md          # This file
```

All code is self-contained in a single HTML file for simplicity and portability.

## Browser Compatibility

Tested and working in:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

Requires modern browser with ES6+ support.

## Contributing

Contributions are welcome! Areas for potential enhancement:

- Additional letters from Alcuin's corpus
- More detailed biographical information
- Additional filtering options (by category, person type, etc.)
- Export functionality for network data
- Timeline view alongside network visualization
- Analysis of letter themes and topics

## License

This project is open source. Historical letter content is in the public domain.

## Acknowledgments

- Alcuin's letters and the scholars who preserved them
- The Carolingian court and its intellectual legacy
- D3.js community for visualization tools
- Medieval historians and translators

## Contact

For questions or suggestions about this visualization, please open an issue on GitHub.

---

**Historical Note**: This visualization represents only a portion of Alcuin's extensive correspondence. He was one of the most prolific letter writers of his age, and his letters provide invaluable insights into Carolingian court life, early medieval education, and the intellectual culture of 8th-9th century Europe.
