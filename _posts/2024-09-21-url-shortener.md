---
title: "Python - URL Shortener"
mathjax: true
layout: post
categories: media
---

<div align="center">
    <img src="../assets/images/link.gif" alt="URL Shortener GIF" />
</div>

<div style="background-color: #1a1a2e; color: #EAECEE; padding: 30px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);">
    <h2 style="margin-top: 0; font-size: 1.8em; color: #76D7C4; border-bottom: 2px solid #76D7C4; padding-bottom: 10px;">URL Shortener</h2>
    <p style="line-height: 1.6; font-size: 1.1em;">This Python web application allows users to shorten long URLs into easy-to-share links. It uses a simple interface to input URLs and generate shortened versions stored in a SQLite database.</p>

 <h3 style="color: #76D7C4; margin-top: 20px;">Key Features:</h3>
    <ul style="list-style-type: none; padding: 0;">
        <li style="color: #EAECEE; font-size: 1.1em; padding: 5px 0; position: relative;">
            <span style="color: #76D7C4;">✔️</span> Shorten any valid URL
        </li>
        <li style="color: #EAECEE; font-size: 1.1em; padding: 5px 0; position: relative;">
            <span style="color: #76D7C4;">✔️</span> User-friendly interface
        </li>
        <li style="color: #EAECEE; font-size: 1.1em; padding: 5px 0; position: relative;">
            <span style="color: #76D7C4;">✔️</span> Redirect to original URLs seamlessly
        </li>
        <li style="color: #EAECEE; font-size: 1.1em; padding: 5px 0; position: relative;">
            <span style="color: #76D7C4;">✔️</span> Easy to use and deploy
        </li>
    </ul>
</div>

```python
def generate_short_url():
    """Generate a random short URL."""
    # Implementation...

@app.route('/<short_url>')
def redirect_url(short_url):
    """Redirect to the original URL."""
    # Implementation...
```
<div style="background-color: #1a1a2e; color: #EAECEE; padding: 30px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);"> <p style="font-size: 1.1em; text-align: center;"> For the full code, please visit the repository: <a href="https://github.com/6cox9/Python-UrlShortener" target="_blank" style="color: #76D7C4; text-decoration: none; font-weight: bold;">URL Shortener</a> </p> </div>
