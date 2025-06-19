# Procurement Analytics Dashboard

A comprehensive web-based dashboard for procurement spend analysis, supplier concentration assessment, and strategic sourcing insights. This dashboard provides Pareto analysis, spend stratification, and actionable recommendations for procurement optimization.

![Dashboard Preview](assets/dashboard-preview.png)

## 🚀 Features

### Core Analytics
- **Pareto Analysis**: 80/20 rule application for supplier concentration
- **Spend Stratification**: Transaction volume vs. value analysis across spend bands
- **Multi-Threshold Analysis**: Comparative analysis at $100K and $500K thresholds
- **Category Comparison**: Side-by-side analysis of Facilities and IT & Telecoms categories

### Interactive Visualizations
- **Combined Bar & Line Charts**: Spend amounts with cumulative percentage overlays
- **Responsive Design**: Optimized for desktop, tablet, and mobile viewing
- **Dynamic Navigation**: Seamless switching between analysis sections
- **Chart.js Integration**: Professional, interactive charts with hover tooltips

### Strategic Insights
- **Supplier Concentration Metrics**: Identify consolidation opportunities
- **Process Efficiency Analysis**: Volume vs. value mismatch identification
- **Savings Opportunity Quantification**: Estimated savings potential by strategy
- **Implementation Roadmap**: Phased approach with timeline and expected ROI

### Key Metrics Tracked
- Total spend by category and threshold
- Supplier count and concentration ratios
- 80% spend achievement metrics
- Top supplier market share analysis
- Transaction volume distribution
- Strategic sourcing recommendations

## 📊 Dashboard Sections

### 1. Executive Summary
- High-level overview of procurement performance
- Key findings and strategic recommendations
- Comparative metrics across categories and thresholds

### 2. Facilities Analysis ($100K & $500K)
- Detailed supplier breakdown and concentration analysis
- Pareto charts showing spend distribution
- Supplier tables with cumulative percentages
- Category-specific insights and recommendations

### 3. IT & Telecoms Analysis ($100K & $500K)
- Technology spend concentration analysis
- Vendor performance and market share metrics
- Strategic sourcing opportunities
- Contract optimization recommendations

### 4. Spend Stratification
- Transaction volume vs. value analysis
- Spend band distribution ($0-$1K, $1K-$2K, etc.)
- Process automation opportunities
- Strategic implications by spend level

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js 4.4.0
- **Styling**: Custom CSS with responsive design
- **Icons**: Unicode emoji and custom styling
- **Data**: Static JSON data embedded in JavaScript

## 📁 Project Structure

```
procurement-dashboard/
├── README.md
├── index.html                 # Main dashboard file
├── assets/
│   ├── dashboard-preview.png  # Screenshot for README
│   └── data/
│       ├── facilities-100k.json
│       ├── facilities-500k.json
│       ├── it-telecoms-100k.json
│       ├── it-telecoms-500k.json
│       └── stratification.json
├── css/
│   └── styles.css            # Custom styles (if separated)
├── js/
│   ├── dashboard.js          # Main dashboard logic
│   ├── charts.js             # Chart configurations
│   └── data.js               # Data management
├── docs/
│   ├── insights.md           # Business insights documentation
│   ├── enhancements.md       # Enhancement recommendations
│   └── api-spec.md           # Future API specifications
└── tests/
    ├── unit/
    └── integration/
```

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Web server (for local development) or static hosting service

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bomino/VSTX-CCHMC-Tresholds.git
   cd procurement-dashboard
   ```

2. **Serve locally** (choose one method)
   
   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Using Node.js:**
   ```bash
   npx serve .
   ```
   
   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Deployment

#### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select source branch (main/master)
4. Access at `https://github.com/bomino/VSTX-CCHMC-Tresholds`

#### Netlify
1. Connect GitHub repository to Netlify
2. Deploy automatically on push
3. Custom domain support available

#### Vercel
1. Import GitHub repository
2. Zero-configuration deployment
3. Automatic HTTPS and global CDN

## 📈 Key Insights & Findings

### Supplier Concentration Analysis
- **Facilities Category**: Highly fragmented with 175+ suppliers, top supplier holds only 10-17.8% market share
- **IT & Telecoms**: Concentrated market with Encore Technologies holding 46.8-56.5% share
- **Consolidation Opportunity**: Facilities category offers significant supplier rationalization potential

### Transaction Volume vs. Value
- **Process Inefficiency**: 97% of Facilities transactions under $5K represent only 46% of spend
- **Automation Opportunity**: 70,000+ small transactions ideal for P-card automation
- **Resource Optimization**: Focus procurement resources on $25K+ transactions (60-70% of spend)

### Savings Potential
- **Total Opportunity**: $4M - $6M annually (8.7-13% of total spend)
- **Quick Wins**: $1.5M - $2.0M in first 3 months
- **Strategic Impact**: 90% reduction in transaction volume through process automation

## 🔧 Configuration

### Data Updates
To update the dashboard with new data:

1. **Modify data in JavaScript arrays** (current implementation)
2. **Replace with API calls** (recommended for production)
3. **Update chart configurations** if data structure changes

### Customization Options
- **Thresholds**: Modify spend thresholds in chart configurations
- **Categories**: Add/remove procurement categories
- **Styling**: Customize colors, fonts, and layout in CSS
- **Metrics**: Add new KPIs and calculations

## 🔮 Roadmap & Enhancements

### Phase 1: Core Improvements (0-3 months)
- [ ] Interactive drill-down capabilities
- [ ] Data export functionality (CSV/Excel)
- [ ] Enhanced mobile responsiveness
- [ ] Search and filter capabilities

### Phase 2: Advanced Features (3-6 months)
- [ ] Real-time data integration
- [ ] Predictive analytics and forecasting
- [ ] Advanced visualizations (Sankey, treemap)
- [ ] Automated reporting and alerts

### Phase 3: Enterprise Features (6-12 months)
- [ ] User authentication and role-based access
- [ ] API development for data integration
- [ ] Collaboration features and annotations
- [ ] Compliance and audit reporting

See [Enhancement Recommendations](docs/enhancements.md) for detailed specifications.

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines:

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit changes (`git commit -m 'Add amazing feature'`)
6. Push to branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Code Standards
- Use semantic HTML5 elements
- Follow CSS BEM methodology for styling
- Write clean, commented JavaScript
- Ensure cross-browser compatibility
- Test on multiple screen sizes

### Reporting Issues
- Use GitHub Issues for bug reports and feature requests
- Provide detailed reproduction steps
- Include browser and version information
- Attach screenshots if applicable

## 📊 Data Sources & Methodology

### Data Collection
- Procurement transaction data from ERP systems
- Supplier master data and categorization
- Contract and spend classification
- UNSPSC category mapping

### Analysis Methodology
- **Pareto Analysis**: 80/20 rule application for supplier concentration
- **ABC Analysis**: Spend stratification by transaction value
- **Threshold Comparison**: Multi-level analysis for strategic insights
- **Trend Analysis**: Historical pattern identification

### Data Quality
- Automated data validation and cleansing
- Duplicate detection and removal
- Supplier name standardization
- Category classification verification

## 🔒 Security & Privacy

### Data Protection
- No sensitive data stored in repository
- Anonymized supplier and transaction data
- Client-side processing only
- No external data transmission

### Best Practices
- Regular security updates
- Input validation and sanitization
- XSS protection measures
- HTTPS deployment recommended

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Chart.js** for excellent charting capabilities
- **Procurement Analytics Community** for methodology insights
- **Open Source Contributors** for inspiration and best practices

## 📞 Support & Contact

### Documentation
- [Business Insights](docs/insights.md)
- [Enhancement Roadmap](docs/enhancements.md)
- [API Specifications](docs/api-spec.md)

### Getting Help
- 📧 Email: [mlawali@versatexmsp.com]
- 💬 Issues: [GitHub Issues](https://github.com/yourusername/procurement-dashboard/issues)
- 📖 Wiki: [Project Wiki](https://github.com/yourusername/procurement-dashboard/wiki)

### Version History
- **v1.0.0** - Initial release with core analytics
- **v1.1.0** - Enhanced navigation and mobile support
- **v1.2.0** - Interactive charts and data export

---

**Built with ❤️ for procurement professionals seeking data-driven insights**

*Last updated: December 2024*

