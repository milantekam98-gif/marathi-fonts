# 🔤 Marathi Fonts CDN

Free CDN for **1000+ Marathi AMS fonts** for web developers & designers.

## 🚀 Quick Usage

### HTML Example
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        @font-face {
            font-family: 'MarathiFont';
            src: url('https://cdn.jsdelivr.net/gh/milantekam98-gif/marathi-fonts@main/fonts/DGFont010Regular.ttf');
        }
        body {
            font-family: 'MarathiFont', sans-serif;
        }
    </style>
</head>
<body>
    <h1>मराठी फॉन्ट</h1>
</body>
</html>

### Wordpress CSS
```WordPress CSS
@font-face {
    font-family: 'MarathiCustom';
    src: url('https://cdn.jsdelivr.net/gh/milantekam98-gif/marathi-fonts@main/fonts/S0700892.TTF');
}

.marathi-text {
    font-family: 'MarathiCustom', sans-serif;
}

JavaScript Dynamic Loading
const fontUrl = 'https://cdn.jsdelivr.net/gh/milantekam98-gif/marathi-fonts@main/fonts/DGFont010Regular.ttf';
const font = new FontFace('MarathiFont', `url(${fontUrl})`);

font.load().then(function(loadedFont) {
    document.fonts.add(loadedFont);
    document.body.style.fontFamily = 'MarathiFont';
});

📦 CDN URL Format
https://cdn.jsdelivr.net/gh/milantekam98-gif/marathi-fonts@main/fonts/FONT_NAME.TTF

Replace FONT_NAME.TTF with any font file from the /fonts/ folder.

✨ Features
✅ 1000+ Fonts – Massive collection of Marathi fonts

⚡ Fast CDN – Powered by jsDelivr

🆓 Free Forever – No subscriptions, no limits

🌍 Global CDN – Fast loading worldwide

📱 Mobile Friendly – Works on all devices

📚 Available Fonts
Browse all fonts in the /fonts/ directory.

🌟 Star This Repo
If you find this useful, please ⭐ star this repository!

📧 Contact
GitHub: @milantekam98-gif

Made with ❤️ for Marathi developers & designers
