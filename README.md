# Shodan Dorkar

**Shodan Dorkar** is a simple and intuitive web tool designed for bug bounty hunters and security researchers. It helps you quickly generate multiple Shodan search URLs based on your target domain or keyword and selected dork types—making reconnaissance and vulnerability discovery faster and easier.

---

## Features

- Input target domain or keyword  
- Multi-select dork types grouped by categories (SSL, Web Content, Vulnerable Versions, Services, etc.)  
- Generates Shodan search URLs with your target automatically injected  
- Preview clickable links for quick access  
- Clean, responsive UI built with Tailwind CSS  
- Lightweight and easy to use — no backend needed

---

## How to Use

1. Open the `index.html` file in any modern browser.  
2. Enter your target domain or keyword in the input field.  
3. Select one or more dork types from the list (hold Ctrl/Cmd to multi-select).  
4. Click the **Search All Dorks on Shodan** button.  
5. Preview generated Shodan search URLs and click to open them in new tabs.

---

## Example

If your target is `example.com` and you select the dork `ssl.cert.subject.cn:"$"`, the tool will generate a Shodan search URL like:  
`https://www.shodan.io/search?query=ssl.cert.subject.cn:"example.com"`

---

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari)  
- Internet connection to access [Shodan](https://www.shodan.io)

---

## Notes

- Make sure you are logged in to Shodan for full search results.  
- Use Ctrl/Cmd + Click to open multiple links simultaneously.  
- This tool does not use Shodan API; it generates URLs for browser search.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contributing

Contributions and improvements are welcome! Feel free to open issues or submit pull requests.

---

## Contact

Created by Captain Nemo.  
Feel free to reach out if you have questions or suggestions.

---

Enjoy faster Shodan recon with **Shodan Dorkar**! 🚀
