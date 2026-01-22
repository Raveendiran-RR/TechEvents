# TechEvents 🎤

A dynamic repository for managing speaking engagements and technical events, automatically displayed on [raveendiran.com](https://raveendiran.com).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 About

This repository stores all my speaking events, talks, and workshops in a structured JSON format. The events automatically sync with my WordPress website, making it easy to keep my speaking portfolio up-to-date.

## 📂 Repository Structure

```
TechEvents/
├── events.json          # Main events data file
├── images/             # Event photos and hero banner
│   ├── hero-banner.jpg
│   ├── ai-cloud-day-2025.jpg
│   ├── devtools-day-2025.jpg
│   ├── kubetools-day-2024.jpg
│   └── neo4j-workshop-2024.jpg
├── wordpress-code.html # WordPress integration code
├── README.md           # This file
└── LICENSE            # MIT License
```

## 🎯 How It Works

1. **Edit** `events.json` to add/update/remove events
2. **Commit** changes to GitHub
3. **Automatic sync** - WordPress fetches the latest data
4. **Events appear** on the website within minutes!

## 📝 Adding a New Event

### Quick Method (GitHub Web Interface):

1. Click on `events.json`
2. Click the **pencil icon** (Edit)
3. Add your event to the `upcoming` or `past` array
4. Commit changes

### Event Template:

```json
{
  "id": "unique-event-id",
  "title": "Event Name",
  "date": "2025-MM-DD",
  "displayDate": "Month DD, YYYY",
  "year": "YYYY",
  "location": "City, Venue",
  "talk": "Your Talk Title",
  "description": "Brief description of your talk or workshop.",
  "tags": ["Tag1", "Tag2", "Tag3"],
  "organizer": "Event Organizer Name",
  "eventLink": "https://event-link.com",
  "slidesLink": "https://your-slides-link.com",
  "image": "https://raw.githubusercontent.com/Raveendiran-RR/TechEvents/main/images/event-name.jpg"
}
```

## 🖼️ Adding Event Photos

1. Upload your event photo to the `images/` folder
2. Use the filename in your event's `image` field
3. Format: `https://raw.githubusercontent.com/Raveendiran-RR/TechEvents/main/images/YOUR-FILE.jpg`

**Recommended Image Sizes:**
- Hero Banner: 1920x600px
- Event Cards: 800x600px

## 📊 Current Stats

- **Total Talks:** 10+
- **Attendees Reached:** 500+
- **Communities:** 3
- **Role:** Docker Community Leader

## 🛠️ Technologies Used

- **Storage:** GitHub Repository
- **Display:** WordPress + Custom JavaScript
- **CDN:** jsDelivr (for fast, cached delivery)
- **Format:** JSON

## 📱 WordPress Integration

Your WordPress page uses this code to fetch and display events. See `wordpress-code.html` for the complete integration code.

## 🎤 Past Speaking Events

### 2025
- **DevTools Day Bengaluru** - Generative AI 102 with Ollama and n8n
- **AI in the Cloud Day** (Upcoming) - Building AI Systems with Microsoft Autogen

### 2024
- **Kubetools Day 3.0** - Generative AI 101: A Complex World Simplified
- **Neo4j Summer Workshop** - Hands-on Neo4j Setup & Basics

## 🤝 Contributing

Found an error or want to suggest an improvement? 

1. Fork this repository
2. Create a feature branch
3. Submit a pull request

## 📧 Contact

- **Website:** [raveendiran.com](https://raveendiran.com)
- **LinkedIn:** [@raveendiranrr](https://www.linkedin.com/in/raveendiranrr/)
- **Twitter:** [@RaveendiranRR](https://twitter.com/RaveendiranRR)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Built with ❤️ by Raveendiran RR | Docker Community Leader | Gen AI Enthusiast**
