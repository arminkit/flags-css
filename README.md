# Flags CSS

Flags CSS is a simple CSS file that enables you to display country flags on your website by applying a specific class to an element. This is particularly useful for international websites or applications that require country-specific information.

## Features

- Easy integration with any HTML file.
- Lightweight and fast.
- No JavaScript required.
- Over 200 country flags available.

## Installation

You can include the `all-flags.css` file in your project by downloading it and linking it in your HTML file.

### Download

Clone the repository:

```bash
git clone https://github.com/arminkit/flags-css.git
```
---
## Include in HTML
```
<link rel="stylesheet" href="path/to/all-flags.css">
```
## Usage

To display a flag, add a flag class and a class with the country code (ISO 3166-1 alpha-2) to any HTML element. For example:

```
<span class="flg-16 us"></span> <!-- USA Flag 16px -->
<span class="flg-32 ca"></span> <!-- Canada Flag 32px -->
<span class="flg-64 fr"></span> <!-- France Flag 64px -->
<span class="flg-128 ir"></span> <!-- Iran Flag 128px -->
```

## Example

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flags CSS Example</title>
    <link rel="stylesheet" href="all-flags.css">
</head>
<body>
    <h1>Country Flags</h1>
    <span class="flg-32 us"></span> United States<br>
    <span class="flg-32 ca"></span> Canada<br>
    <span class="flg-32 fr"></span> France<br>
    <span class="flg-32 de"></span> Germany<br>
    <span class="flg-32 jp"></span> Japan<br>
</body>
</html>
```
## 

Thank you for using Flags CSS! We hope it helps you create amazing international websites.

**Designed by ArminKiT**
