# Open Source JSON Data Collection

A comprehensive collection of open-source JSON data files for developers, testers, educators, and applications. Free to use, modify, and contribute!

## Disclaimer

This is a **sample data collection** for educational and development purposes. The content in these JSON files is compiled from various publicly available sources, manually typed, and aggregated for convenience. We are **not the original authors** of the content contained within these files.

**Credits:**
- Images sourced from [Pixabay](https://pixabay.com/) (free license)
- Avatar illustrations from [DiceBear](https://dicebear.com/) API

This project is intended as a free resource for developers and learners. If you are the rightful owner of any content and wish to have it removed, please contact us.

## Features

- **Hindi-English Tech Vocabulary** - Bilingual technical dictionary with 4000+ words
- **Tech Personalities** - Information about famous tech leaders in Hindi
- **Inspirational Quotes** - Motivational quotes in Hindi with categories
- **Blog Posts** - Technology articles with rich content

## JSON Files

| File | Description | Entries |
|------|-------------|---------|
| `tech_vocabulary.json` | Technical vocabulary with Hindi meanings | 4000+ |
| `tech_personalities.json` | Famous tech personalities data | 100+ |
| `quotes.json` | Inspirational & educational quotes | 100+ |
| `posts.json` | Technology blog posts | 10+ |
| `regions.json`| Demographic Regions | 6 |
| `subregions.json` | Demographic Sub Regions | 22 |
| `countries.json` | Demographic Countries | 250 |
| `states.json` | Country States | 5101 |
| `cities.json` | Country State Cities | 150000+ |

## Usage

### For Developers

```javascript
// Fetch vocabulary data
const response = await fetch('./tech_vocabulary.json');
const vocabulary = await response.json();

// Filter by category
const aiWords = vocabulary.filter(word => word.category === "AI/ML");
```

### For Applications

```python
import json

# Load tech personalities
with open('tech_personalities.json', 'r', encoding='utf-8') as f:
    personalities = json.load(f)

# Get all personalities from India
indian_tech = [p for p in personalities if 'भारत' in p['place']]
```

### For Testing

```json
{
  "test_vocabulary": {
    "word": "Algorithm",
    "hindi_meaning": "कलन विधि",
    "category": "AI/ML"
  }
}
```

## Data Structure

### Vocabulary Format

```json
{
  "word": "Algorithm",
  "hindi_meaning": "कलन विधि",
  "description_en": "A step-by-step procedure for solving a problem",
  "description_hi": "",
  "category": "AI/ML"
}
```

### Categories

- AI/ML
- Web Development
- Cybersecurity
- Cloud Computing
- Data Science
- General
- And more...

## Contributing

Contributions are welcome! Here's how you can help:

1. **Add New Words** - Help expand the vocabulary database
2. **Add Hindi Descriptions** - Translate descriptions to Hindi
3. **Add New Categories** - Suggest or add new tech categories
4. **Fix Errors** - Report or fix any data issues
5. **Add New JSON Files** - Create new data collections

### How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Test your changes
5. Commit your changes (`git commit -m 'Add new feature'`)
6. Push to the branch (`git push origin feature/your-feature`)
7. Create a Pull Request

## Use Cases

- **Educational Apps** - Language learning, tech tutorials
- **Translation Services** - Hindi-English tech terminology
- **Chatbots** - AI assistants with tech knowledge
- **Quiz Applications** - Tech vocabulary quizzes
- **Research** - Study tech terminology in Hindi
- **Testing** - Sample JSON data for API testing

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Support

If you find this project useful, consider supporting us:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/hinditutorpoint)

Your support helps us:
- Add more vocabulary
- Improve data quality
- Add new categories
- Maintain the project

## Share

Help others discover this resource:

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/intent/tweet?text=Check%20out%20this%20awesome%20open-source%20JSON%20data%20collection%20for%20Hindi-English%20tech%20vocabulary!)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/sharing/share-offsite/?url=)

## Contact

- **Buy Me a Coffee**: [hinditutorpoint](https://buymeacoffee.com/hinditutorpoint)

## Star History

If you like this project, please give it a star!

---

Made with ❤️ for the developer community
