# TableTap – Your Digital Menu Solution

_TableTap_ is a modern QR-based menu app designed to simplify and enhance the dining experience for both restaurants and patrons. With TableTap, customers simply scan a QR code at their table to instantly access a beautifully formatted, branded digital menu on their phones – no app download required!

## Key Features

- **Instant Access**: Scan and view the full menu instantly, whether for dine-in or takeout.
- **Professional Formatting**: Each menu is carefully designed to reflect your brand, complete with custom colors, fonts, and images.
- **Editable and Up-to-Date**: Restaurant owners have full control, with an intuitive admin panel for updating items, prices, and images at any time.
- **Seamless Branding**: Incorporate your restaurant's style with custom logos, themes, and professional layout options.
- **Environment-Friendly**: Go paperless and reduce waste, while providing customers a hygienic, touch-free menu experience.

## Getting Started

To run TableTap locally, follow these instructions:

### Prerequisites

- **Flutter SDK**
- **Firebase** project setup (authentication, Firestore, and storage)
- A **QR code generator and scanner** plugin for Flutter

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yahiyam/table_tab.git
   ```

   ```bash
   cd table_tab
   ```

2. **Install dependencies**:

   ```bash
   flutter clean
   ```

   ```bash
   flutter pub get
   ```

3. **Set up Firebase**:

   - Follow the official [Firebase documentation](https://firebase.google.com/docs) to add Firebase to the project.
   - Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files and place them in the appropriate directories.

4. **Run the App**:

   ```bash
   flutter run
   ```

## Usage

- **Admin Panel**: Restaurant owners can log in to add, update, and remove menu items, images, and prices in real-time.
- **Customer View**: Customers scan the QR code, which opens the menu in their browser or within the app (no download required).

## Technologies Used

- **Flutter** for cross-platform mobile app development
- **Firebase** for real-time data management and authentication
- **QR Code Scanner** for scanning customer-accessible menus

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, feel free to reach out to the project creator, Yahiya, via Instagram at [@_yehweh_](https://www.instagram.com/_yehweh_).
