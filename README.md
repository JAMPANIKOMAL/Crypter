# Crypter

A versatile, client-side web application that allows users to encrypt and decrypt text using a variety of classical and modern cryptographic ciphers.

**Live Demo:** [jampanikomal.github.io/Crypter/](https://jampanikomal.github.io/Crypter/)

## ✨ Features

- **Multiple Ciphers:** Implements a wide range of ciphers:
    - **Classical:** Caesar, Rail Fence, Playfair, Affine, and Hill.
    - **Modern (Symmetric):** DES, 2DES, 3DES, and AES.
- **User-Friendly Interface:** Easily switch between ciphers, with controls and key inputs dynamically updating for the selected algorithm.
- **Privacy-Focused:** All encryption and decryption operations are performed locally in your browser. No data is ever sent to a server.
- **Light/Dark Theme:** Toggle between light and dark modes for user comfort.
- **Informative Modals:** An "Info" modal provides a brief overview of each available cipher.
- **Custom Alerts:** Clean, non-blocking alerts for user guidance and error messages.
- **Responsive Design:** Fully functional on both desktop and mobile devices.

## 🚀 Technologies Used

- **HTML5:** For the core structure of the application.
- **CSS3:** For modern styling, layout, and responsiveness.
- **JavaScript (with jQuery):** Powers the user interface, cipher logic, and all interactivity.
- **CryptoJS:** Used for the robust and standardized implementations of modern block ciphers (DES, 3DES, AES).

## 📦 Installation and Setup

You can run this project locally with just a few simple steps.

1.  **Clone the Repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/Crypter.git](https://github.com/YOUR_USERNAME/Crypter.git)
    cd Crypter
    ```
    *(Replace `YOUR_USERNAME` with your GitHub username)*

2.  **Run Locally:**
    Since the project uses CDN links for jQuery and CryptoJS, you don't need to install any dependencies. Simply open the `index.html` file in your favorite web browser.

    For the best experience (to avoid any potential CORS issues with local files), it's recommended to use a local server.

    **Using the VS Code Live Server Extension:**
    - Install the "Live Server" extension from the VS Code Marketplace.
    - Right-click on `index.html` in the file explorer and select "Open with Live Server."

    **Using Python's built-in HTTP server:**
    - Navigate to the project directory in your terminal and run:
      ```sh
      python -m http.server
      ```
    - Open your browser and go to `http://localhost:8000`.

## 💡 Usage

- **Select a Cipher:** Click any button in the "Select Cipher" panel to choose an algorithm.
- **Enter Text:** Type or paste the text you want to encrypt or decrypt into the "Input Text" box.
- **Provide Key(s):** Enter the required key(s) for the selected cipher in the control section.
- **Encrypt/Decrypt:** Click the "Encrypt" or "Decrypt" button to perform the operation.
- **View Output:** The result will appear in the "Output Text" box. For modern ciphers like AES/DES, the encrypted output is a Base64 string, which should be used as the input for decryption.
- **Switch Themes:** Use the toggle switch in the top-right to change between light and dark modes.
- **Get Info:** Click the "ⓘ Info" button to learn more about the ciphers.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests for new features, bug fixes, or improvements.

## 🤖 AI Assistance

This project was developed with assistance from an AI model to implement features, refine the user interface, and generate code.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
