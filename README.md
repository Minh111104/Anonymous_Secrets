# Secrets Project

This is a Node.js web application that displays a random secret and its author, fetched from the [Secrets API](https://secrets-api.appbrewery.com/).

## Features

- Fetches a random secret from an external API
- Displays the secret and username on a styled card
- Responsive and visually appealing UI using custom CSS

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed

### Installation

1. Clone this repository or download the source code.
2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the server:

    ```sh
    node index.js
    ```

4. Open your browser and go to `http://localhost:3000`

## Project Structure

```bash
    [index.js](http://_vscodecontentref_/0)
    [package.json](http://_vscodecontentref_/1)
    [README.md](http://_vscodecontentref_/2)
    public/
    images/
        whisper-img.jpg
    styles/
        [main.css](http://_vscodecontentref_/4)
    views/
    [index.ejs](http://_vscodecontentref_/5)
```

- `index.js`: Main server file
- `public/`: Static assets (CSS, images)
- `views/index.ejs`: EJS template for rendering secrets

### Dependencies

- express
- axios
- ejs

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
