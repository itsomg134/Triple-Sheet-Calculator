
# 📊 Triple Sheet Calculator

A sophisticated, real-time three-way calculator that allows side-by-side calculations with independent operations and comprehensive result comparison. Perfect for comparing different calculation strategies, financial scenarios, or educational purposes.

<img width="1890" height="1057" alt="image" src="https://github.com/user-attachments/assets/92a09a25-0b36-4619-b596-620ea1ddcc29" />

## ✨ Features

### 🎯 Three Independent Sheets
- **Sheet A** (Primary) - Default addition calculator
- **Sheet B** (Secondary) - Default division calculator  
- **Sheet C** (Tertiary) - Default modulo calculator

### 🧮 Powerful Operations Per Sheet
Each sheet supports six mathematical operations:
- ➕ **Addition** (X + Y)
- ➖ **Subtraction** (X - Y)
- ✖️ **Multiplication** (X × Y)
- ➗ **Division** (X ÷ Y) with zero division protection
- ⚡ **Power** (X ^ Y) for exponential calculations
- 🧮 **Modulo** (X % Y) for remainder calculations

### 📈 Real-time Comparison Dashboard
Automatically displays across all three sheets:
- **Minimum Result** - Lowest value among all sheets
- **Maximum Result** - Highest value among all sheets  
- **Sum of Results** - Total of all valid calculations
- **Average** - Mean value of all sheet results

### 🎨 Modern UI/UX
- Glassmorphism design with smooth gradients
- Responsive layout for desktop and mobile devices
- Distinct color themes for each sheet (warm amber, cool blue, fresh green)
- Hover animations and interactive feedback
- Real-time calculation updates without page reload

### 🛠️ Control Features
- **Individual Sheet Reset** - Reset any sheet to its default values
- **Global Reset** - Reset all three sheets simultaneously
- **Error Handling** - Graceful handling of division by zero and invalid operations
- **Infinite Value Detection** - Proper display of overflow/underflow conditions

## 🚀 Live Demo

[View Live Demo](https://your-demo-link.com) - *Replace with your actual deployment link*

## 💻 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with flexbox, gradients, and animations
- **JavaScript (ES6)** - Dynamic calculations and real-time updates
- **No External Dependencies** - Pure vanilla implementation

## 📦 Installation

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/triple-sheet-calculator.git
cd triple-sheet-calculator
```

2. Open `index.html` in your browser:
```bash
# Using Python (if you want a local server)
python -m http.server 8000

# Or simply open the file directly
open index.html
```

### Quick Start

Just download the `index.html` file and open it in any modern web browser. No build process or dependencies required!

## 🎮 How to Use

1. **Enter Numbers**: Input values in the X and Y fields for each sheet
2. **Select Operation**: Choose from six mathematical operations per sheet
3. **View Results**: See instant calculations in the result area
4. **Compare**: Check the comparison dashboard for insights across all sheets
5. **Reset**: Use individual reset buttons or global reset to start fresh

### Example Use Cases

#### Financial Scenario Comparison
- **Sheet A**: Calculate compound interest (Power operation)
- **Sheet B**: Calculate simple interest (Multiplication)
- **Sheet C**: Calculate monthly payments (Division)

#### Educational Tool
- Compare different mathematical approaches to the same problem
- Demonstrate the effects of different operations on the same numbers
- Teaching order of operations and mathematical concepts

## 🧪 Testing

The calculator handles various edge cases:
- ✅ Decimal numbers
- ✅ Negative numbers  
- ✅ Division by zero (displays "⚠️ Error")
- ✅ Large exponents (displays "∞ (Infinite)" when overflow occurs)
- ✅ Empty or invalid inputs (treated as 0)

## 📱 Responsive Design

- **Desktop**: Three-column layout with spacious cards
- **Tablet**: Flexible column layout with adjusted spacing
- **Mobile**: Single-column layout for easy touch interaction

## 🔧 Customization

### Adding New Operations

To add a new operation to all sheets, modify the `computeValue` function in the JavaScript:

```javascript
case 'newOperation':
  return a * b + a; // Your custom logic
```

Then add the option to each sheet's select dropdown:

```html
<option value="newOperation">✨ New Operation (X * Y + X)</option>
```

### Changing Color Themes

Modify the gradient colors in the CSS:

```css
.sheet-A .sheet-header { 
  background: linear-gradient(120deg, #your-color-1, #your-color-2); 
  border-top: 5px solid #your-accent; 
}
```

## 🌟 Performance

- **Real-time Updates**: Instant calculation on any input change
- **Optimized Rendering**: Minimal DOM manipulation
- **No External Libraries**: Lightweight and fast loading
- **Efficient Event Handling**: Debounced updates for smooth performance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Improvement
- Add keyboard shortcuts for quick operations
- Export results to CSV/Excel
- Add chart visualization for result comparison
- Save/load calculation presets
- Dark mode toggle
- Custom operation builder

## 🐛 Known Issues

- Power operation with negative base and fractional exponents may result in complex numbers (displayed as NaN)
- Very large exponent results may display as "∞ (Infinite)"

## 📞 Support

For issues, questions, or contributions:
- Open an [issue](https://github.com/yourusername/triple-sheet-calculator/issues)
- Contact: [your-email@example.com](mailto:your-email@example.com)

## 🎯 Future Roadmap

- [ ] History tracking for each sheet
- [ ] Export/import calculation scenarios
- [ ] Chart visualization of results
- [ ] Custom operation builder interface
- [ ] Keyboard navigation support
- [ ] Dark/light theme toggle
- [ ] Save favorite calculation presets
- [ ] Mobile app version with React Native

## 🙏 Acknowledgments

- Inspired by multi-sheet spreadsheet applications
- Design influenced by modern web calculators
- Icons and emojis for enhanced user experience

---

**Made with ❤️ for efficient multi-calculation workflows**
```

This README provides comprehensive documentation covering:

1. **Project Overview** - Clear description of what the tool does
2. **Features** - Detailed breakdown of functionality
3. **Installation** - Simple setup instructions
4. **Usage Guide** - How to use the calculator with examples
5. **Technical Details** - Technologies and customization options
6. **Contributing** - How others can help improve the project
7. **Roadmap** - Future development plans

You can customize the placeholder elements like:
- Demo link URL
- Your email address
- GitHub repository URL
- Screenshot/logo placeholders

Would you like me to add any specific sections or modify the README for your particular use case?
