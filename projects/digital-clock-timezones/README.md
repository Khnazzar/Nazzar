# ⏰ Digital Clock - Multi-Timezone Display

A beautiful, responsive digital clock that displays the current time in multiple time zones simultaneously. Perfect for tracking time across different regions.

## 📋 Project Overview

This project creates an interactive digital clock web application that shows:
- Real-time clock for multiple time zones
- Current date and day of the week
- 12-hour and 24-hour format toggle
- Beautiful gradient UI with smooth animations
- Responsive design for all devices

## 🎯 Features

✅ **Multiple Time Zones** - Display time for major cities worldwide  
✅ **Real-time Updates** - Clock updates every second  
✅ **Format Toggle** - Switch between 12-hour and 24-hour formats  
✅ **Beautiful UI** - Gradient backgrounds and smooth animations  
✅ **Responsive Design** - Works on desktop, tablet, and mobile  
✅ **No External Dependencies** - Pure HTML, CSS, and JavaScript  

## 📁 Project Structure

```
digital-clock-timezones/
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # Clock logic and timezone handling
├── README.md           # This file
└── screenshots/        # Project screenshots (optional)
```

## 🚀 How to Use

1. **Open the Project:**
   - Save the three files (HTML, CSS, JS) in the same folder
   - Open `index.html` in your web browser

2. **View Time Zones:**
   - The clock automatically displays major cities' times
   - Each timezone is shown in a separate card

3. **Toggle Format:**
   - Click the "Format" button to switch between 12-hour and 24-hour display

4. **Customize Time Zones:**
   - Edit the `timezones` array in `script.js` to add/remove cities

## 💻 Technical Details

**Technologies Used:**
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)

**Key JavaScript Concepts:**
- `Date` object for current time
- `toLocaleString()` for timezone conversion
- `setInterval()` for real-time updates
- DOM manipulation for dynamic updates

**Timezone Data:**
- Using `Intl.DateTimeFormat` API for accurate timezone handling
- Supports all IANA timezone identifiers

## 🎨 Customization

### Add New Time Zones
Edit the `timezones` array in `script.js`:
```javascript
const timezones = [
    'America/New_York',      // EST
    'Europe/London',         // GMT
    'Asia/Tokyo',            // JST
    'Asia/Kolkata',          // IST (Add your timezone here)
    // Add more timezones
];
```

### Change Colors
Modify the CSS gradient in `style.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/* Change these color codes */
```

### Change Update Frequency
In `script.js`, modify the interval (default: 1000ms = 1 second):
```javascript
setInterval(updateClock, 1000); // Change 1000 to desired milliseconds
```

## 🌍 Popular Timezone Identifiers

```
Americas:
- America/New_York (EST/EDT)
- America/Los_Angeles (PST/PDT)
- America/Chicago (CST/CDT)
- America/Denver (MST/MDT)

Europe:
- Europe/London (GMT/BST)
- Europe/Paris (CET/CEST)
- Europe/Berlin (CET/CEST)
- Europe/Moscow (MSK)

Asia:
- Asia/Tokyo (JST)
- Asia/Shanghai (CST)
- Asia/Hong_Kong (HKT)
- Asia/Singapore (SGT)
- Asia/Dubai (GST)
- Asia/Kolkata (IST)

Australia:
- Australia/Sydney (AEDT/AEST)
- Australia/Melbourne (AEDT/AEST)
```

## 📱 Browser Compatibility

- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers

## 🔧 Troubleshooting

| Issue | Solution |
|-------|----------|
| Clock not updating | Check if JavaScript is enabled in browser |
| Wrong timezone | Verify timezone identifier in the array |
| Styling looks broken | Clear browser cache (Ctrl+Shift+Delete) |
| Mobile layout broken | Ensure viewport meta tag is in HTML |

## 📚 Learning Resources

- [MDN - Date Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [MDN - Intl.DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat)
- [IANA Timezone Database](https://www.iana.org/time-zones)

## 🎓 Educational Value

This project demonstrates:
- Working with JavaScript Date and Time APIs
- Understanding timezone handling
- DOM manipulation and event handling
- CSS animations and responsive design
- Real-time data updates with `setInterval()`

## 📝 Future Enhancements

- [ ] Add alarm functionality
- [ ] Store favorite timezones in localStorage
- [ ] Weather information for each timezone
- [ ] Sunrise/sunset times
- [ ] World map with timezone visualization
- [ ] Sound notification at specific times

## 📄 License

This project is open source and available for educational purposes.

---

**Created:** June 2026  
**Status:** ✅ Complete and Functional

