# 🌲 TreeTrack Pro - Equipment Management System

A comprehensive, mobile-friendly web application designed specifically for tree service companies to track equipment, manage maintenance schedules, and get AI-powered assistance for equipment management.

![TreeTrack Pro](https://img.shields.io/badge/TreeTrack-Pro-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)
![Mobile](https://img.shields.io/badge/Mobile-Friendly-orange?style=for-the-badge)

## ✨ Features

### 📊 **Equipment Management**
- Add, edit, and remove equipment (chainsaws, chippers, stump grinders, bucket trucks, etc.)
- Track usage hours with automatic accumulation
- Monitor service intervals and maintenance schedules
- Equipment type categorization and notes

### 🔔 **Smart Maintenance Reminders**
- Intelligent alerts based on usage hours and calendar dates
- Visual status indicators (Good/Due Soon/Overdue)
- One-click maintenance completion
- Dashboard overview of all equipment status

### 📋 **Service History Tracking**
- Complete maintenance records with dates and costs
- Service type categorization
- Detailed notes and documentation
- Historical trend analysis

### 🤖 **AI-Powered Assistant**
- **Real OpenAI Integration**: Connect your API key for live AI responses
- **Demo Mode**: Smart fallback responses when offline
- **Voice Input**: Hands-free operation using Web Speech API
- Context-aware assistance for:
  - Maintenance scheduling guidance
  - Parts recommendations
  - Troubleshooting support
  - Safety reminders

### 📱 **Mobile-First Design**
- Responsive design optimized for field use
- Touch-friendly interface
- Offline functionality with local storage
- Modern glass morphism UI

## 🚀 Getting Started

### Personal/Educational Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start adding your equipment!
4. **Note**: Personal and educational use only - see license for details

### Commercial Use
For commercial use, please contact for licensing: [your-email@domain.com]

### With AI Features
1. Get an OpenAI API key from [OpenAI Platform](https://platform.openai.com/)
2. Navigate to the AI Assistant page
3. Enter your API key (stored locally only)
4. Enjoy full AI-powered assistance!

## 💻 Technical Details

### Built With
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern responsive design with animations
- **Vanilla JavaScript** - No dependencies, pure performance
- **Web Speech API** - Voice recognition capabilities
- **OpenAI API** - Advanced AI assistance (optional)

### Browser Support
- Chrome/Edge 80+
- Firefox 70+
- Safari 13+
- Mobile browsers (iOS Safari, Chrome Mobile)

### Data Storage
- **Local Storage**: All data stored in browser (no server required)
- **Offline Ready**: Works without internet connection
- **Privacy First**: No data leaves your device (except AI queries)

## 🎯 Use Cases

### For Tree Service Companies
- Track chainsaw maintenance schedules
- Monitor chipper blade sharpening intervals
- Log bucket truck hydraulic service dates
- Get AI guidance on equipment troubleshooting

### For Equipment Managers
- Centralize all equipment records
- Automate maintenance reminders
- Track service costs and history
- Access equipment data from mobile devices in the field

### For Safety Managers
- Ensure equipment is properly maintained
- Get AI-powered safety reminders
- Track compliance with service intervals
- Maintain detailed service records

## 📸 Screenshots

### Dashboard Overview
- Equipment status at a glance
- Maintenance alerts and reminders
- Quick statistics and insights

### Equipment Management
- Detailed equipment profiles
- Usage hour tracking
- Service interval monitoring

### AI Assistant
- Natural language queries
- Voice input capability
- Contextual equipment advice

## 🛠️ Customization

The application can be easily customized for different industries:

### Equipment Types
Add new equipment categories in the JavaScript:
```javascript
// In the equipment type dropdown options
<option value="Custom Equipment">Custom Equipment</option>
```

### Service Intervals
Modify default service intervals for different equipment types:
```javascript
// Customize in the maintenance calculation functions
const customIntervals = {
    'Chainsaw': 25,
    'Chipper': 100,
    'Stump Grinder': 75
};
```

### AI Responses
Enhance the demo mode responses for specific use cases:
```javascript
// Add custom demo responses in getDemoResponse function
```

## 🔐 Security & Privacy

- **Local Storage**: All equipment data stays on your device
- **API Key Security**: OpenAI keys stored locally, never transmitted to our servers
- **No Tracking**: No analytics, cookies, or user tracking
- **Proprietary Code**: Source code is proprietary and protected by copyright

## 🤝 Contributing

**Note**: This is a proprietary project. Contributions are by invitation only.

If you're interested in contributing, please:
1. **Contact** the maintainer for permission
2. **Sign** a contributor agreement if accepted
3. **Follow** the established development guidelines

### Development Guidelines (for authorized contributors)
- Maintain mobile-first responsive design
- Follow existing code style and structure
- Test across different browsers
- Update documentation for new features
- Ensure accessibility compliance

## 📊 Roadmap

### Version 2.0 (Planned)
- [ ] Multi-user support with data synchronization
- [ ] Photo upload for service records
- [ ] PDF report generation
- [ ] Integration with inventory management
- [ ] Advanced analytics and insights

### Version 2.1 (Future)
- [ ] Calendar integration
- [ ] SMS/Email reminder notifications
- [ ] Barcode/QR code scanning
- [ ] Multi-language support

## 🐛 Known Issues

- Voice recognition requires HTTPS in production
- iOS Safari may have limitations with file input
- Large datasets (1000+ equipment) may impact performance

## 💡 Tips for Best Results

1. **Regular Updates**: Log hours daily for accurate maintenance predictions
2. **Detailed Notes**: Include specific details in service records
3. **Photo Documentation**: Use the notes field to reference external photos
4. **Backup Data**: Export localStorage data regularly for safety

## 🆘 Support

### Troubleshooting
- **AI Not Working**: Check your OpenAI API key and internet connection
- **Voice Input Issues**: Ensure microphone permissions are granted
- **Data Lost**: Check if localStorage is enabled in your browser

### Getting Help
- 📖 Check our [Wiki](https://github.com/jkh2/treetrack-pro/wiki) for detailed guides
- 🐛 Report bugs via [GitHub Issues](https://github.com/jkh2/treetrack-pro/issues)
- 💬 Join discussions in [GitHub Discussions](https://github.com/jkh2/treetrack-pro/discussions)

## 📄 License

This project is licensed under a Proprietary License - see the [LICENSE](LICENSE) file for details.

**Commercial use requires a separate license agreement.**

For licensing inquiries: [your-email@domain.com]

## 🙏 Acknowledgments

- **OpenAI** for providing the GPT API that powers our AI assistant
- **Web Speech API** contributors for voice recognition capabilities
- **Tree service professionals** who provided valuable feedback during development
- **Open source community** for inspiration and best practices

## 🌟 Star History

If you find TreeTrack Pro useful, please consider giving it a star on GitHub! It helps others discover the project.

---

**Built with ❤️ for the tree service community**

*Empowering tree service professionals with intelligent equipment management*
