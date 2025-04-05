
Built by https://www.blackbox.ai

---

```markdown
# bitBalance | Bitcoin UTXO Explorer

bitBalance is a web application for exploring Bitcoin Testnet Unspent Transaction Outputs (UTXOs) in real-time. Built with a sleek UI, it allows users to easily query UTXOs associated with Bitcoin addresses and view their balance.

## Project Overview

This project is designed to provide a straightforward interface for users to input Bitcoin Testnet addresses and retrieve relevant UTXO information using the Mempool.Space API. Users can view their total balance in both Bitcoin and satoshis as well as the details of their UTXOs.

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bitBalance.git
   cd bitBalance
   ```

2. Open `index.html` in your web browser. The application does not require a separate server since all necessary files are served through a single HTML document.

## Usage

1. Enter a Bitcoin Testnet address in the input field (e.g., `tb1q...`).
2. Click on the "Scan UTXOs" button.
3. The application will display the total balance and the list of UTXOs associated with the entered address.
4. You can also copy the address to your clipboard using the copy icon next to the input field.

## Features

- User-friendly interface for querying UTXOs.
- Real-time balance display in both Bitcoin and satoshis.
- Highlighted UTXO details including transaction IDs.
- Address validation to ensure proper format for Bitcoin Testnet addresses.
- Copy address functionality for ease of use.

## Dependencies

This project uses the following libraries:

- [Tailwind CSS](https://tailwindcss.com/) - For utility-first styling.
- [Font Awesome](https://fontawesome.com/) - For icons used in the UI.

These libraries are included via CDN links in the `index.html` file.

## Project Structure

The project consists of a single HTML file:

```
bitBalance/
│
├── index.html         # Main HTML file containing all front-end code
```

### Key Components in `index.html`

- **Styles and Layout**: The application uses Tailwind CSS and custom styles for the layout and animations.
- **Form Elements**: An input field for Bitcoin addresses along with a submit button to initiate the UTXO scan.
- **Results Area**: A section to display the fetched UTXO results along with error handling and loading animations.
- **JavaScript Logic**: Handles form submissions, API interactions, and results display.

## License

This project is open-source and available under the [MIT License](LICENSE).
```