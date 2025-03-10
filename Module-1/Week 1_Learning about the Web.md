# Week 1: Learning About the Web

## Introduction to HTML5
### Evolution of HTML
- **HTML** - Hypertext Markup Language
  - Markup languages use *tags* to annotate 
  - tags indicate where headings (h1), images (img), list items (li), links (a), line breaks (br), and other components should be displayed.
  - was intended to facilitate content types
- **Mosaic** - emerged as the first graphical browser
- **Evolution of Browsers**
  - ![alt text](image.png)
  - ![alt text](image-1.png)
- **HTML 5** is a cooperation between W3C and the Web Hypertext Application Technology Working Group (WHATWG)
  - Established Guidelines
    - New features should be based on HTML, CSS, the DOM, and Javascript
    - Reduce the need for external plugins 
    - More markup to replace scripting
    - HTML 5 should be device independent
  
### Networks
 - **The Internet**
   - LAN (Local Area Network)
   - WAN (Wide Area Network)
 - **Client/Server Relationship** - happens when your computer (the client) requests a page and a server responds with the appropriate files
   - **Servers**
     - Machine that hold shared resources
     - Always connected to the network
   - **Clients**
     - Machines for personal use (laptops, phones, etc.,)
 - **URL** - Uniform Resource Locator
   - protocol - how to connect
   - domain - the server
   - (optional) document - the specific file needed
 - **Protocols**
   - **HTTP** - Hypertext Transfer Protocol
   - **HTTPS** - Secure Hypertext Transfer Protocol
   - **FTP** - File Transfer Protocol
 - **Domain Names**
   - Identifies the entity you want to connect to
   - Each has different top-level domain
   -  **IP Addresses and the Domain Name Server (DNS)**
    - **IPv6** (Internet Protocol Version 6) - the communication protocol that identifies computers on networks
    - Every computer has unique IP address:
        xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx
        where x can have 16 different values
    - Can represent over 300 trillion unique combinations
    - DNS looks up the domain and returns the IP Address
    - **DNS** (Domain Name Server)
      - With this, we don't need to remember the IP address of a domain since it will look up the IP Address based on the URL.
  - **Document**
    - URLs can specify a specific document
      - e.g.: contact.html (http://intro-webdesign.com/contact.html)
    - if no document is specified, the default document is returned
  - **The Request**
    - Once the IP Address is determined, the browser creates an HTTP request
    - Lots of hidden information in this request
      - header, cookies, form data, etc.,
  - **The Response**
    - The server returns files, not "web pages"
      - it is up to the browser to decide what to do with those files
    - If the server can't fulfill the request it will send back files with error codes: 404, 500, etc.,

### Browsers
1. **Internet Explorer** - One of the most popular browsers because it was preinstalled on Microsoft Windows
   - Platform-dependent - doesn't automatically work on Mac
2. **Microsoft Edge** - in 2015 the new Windows 10 OS included Microsoft Edge
   - Edge is meant to repleace IE
3. **Safari** - default browser on Mac devices
   - Also work on Windows
4. **Google Chrome** - Freeware browser developed by Google
   - First released in 2008, for Microsoft Windows, it was later ported to Linux, macOS, iOS, and Android Greater Security
5. **Firefox** - Free and open-source browser developed by Mozilla


## How to Use an Editor to Create an HTML File
### Creating and Editing your files
1. Decide how you will organize your files
2. Decide on a naming convention
    - dash-names, camelCase
    - No spaces, consistent capitalization
3. Decide on editor
    - Windows (Notepad, Notepad++, Sublime, VS Code)
    - Mac (TextEdit, TextWrangler, Sublime, VS Code)

### Getting Started
1. Open your editor
2. Select Save or Save Aas and name your file. You may need to create a new folder first.
3. Add Doctype, head, and body tags
4. Save File (Ctrl + S) or (Command + S)
5. Open in browser

### Troubleshooting
- My file opens in an editor instead of a browser.
  - Right click and select "Open with..."
- My Browser shows my tags
  - Check that file extension is .html
- I changed my code, but my page looks the same
  - Refresh your browser
  - Verify file name
- I get "weird" characters
  - Try typing code in by hand, not copy-and-paste

## How to Use Replit
### Online editors
1. Google Docs and Microsoft 365 are common ways to share documents.
2. Sharing code is a little different - especially when you want to share your webpage with someone
3. Use Replit

### IDEs
1. IDEs are **Integreated Development Environments**, a fancy term for software that lets you write your code, run your code, share your code, etc.,
2. Replit is an IDE for beginner programmers.

### Which editors to use?
- If want to work **locally**
  - Built-in editor
  - Sublime
  - VSCode