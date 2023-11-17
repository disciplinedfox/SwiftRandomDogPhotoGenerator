# Random Dog Photo Generator

Welcome to the Random Dog Photo Generator iOS app! This simple app is built using Swift and Xcode, allowing users to generate random dog photos with just a click of a button. Whether you're a dog lover or just in need of a cute distraction, this app is perfect for you.

This app is the developer's first ever attempt at making an iOS app in Swift and Xcode. The program files contain multiple layers, the majority of which are commonly generated code for iOS use and are provided by Xcode. The viewController contains the functional code that is unique to this app. 

It contains a ViewController class which nests all of the functions and modules of this program. There is a view screen, which contains the generated image, as well as a button which were both rendered unto the main screen. Both are styalized for placement, color, and size. 

The main functions of this program include getRandomPhoto(), didTapButton(), and viewDidLoad(). The first function pulls the url code of a randomly generated photo from "placedog.net", which is a site that hosts a collection of dog photos. This site provides a url with a query to generate a dog photo with each refresh. The second function, didTapButton() utilizes the website's feature by calling for a random dog photo with each tap of the button. Lastly, viewDidLoad() renders the visual display upon loading the app.

## Features

- **Random Dog Photos:** Click the "Generate" button to fetch and display a new random dog photo.

- **User-Friendly Interface:** The app is designed with simplicity in mind, making it easy for users to generate random dog photos with a single tap.

- **Swift & Xcode:** The app is developed using Swift programming language and Xcode, ensuring a smooth and efficient user experience on iOS devices.

## Getting Started

To run the app on your local machine, follow these steps:

1. **Clone the Repository:**
   ```
   [git clone https://github.com/your-username/random-dog-photo-generator.git](https://github.com/disciplinedfox/SwiftRandomDogPhotoGenerator.git)
   ```

2. **Open in Xcode:**
   - Navigate to the project folder.
   - Open the `RandomDogPhotoGenerator.xcodeproj` file in Xcode.

3. **Build and Run:**
   - Select your target device or simulator.
   - Click the "Run" button (or press `Cmd + R`) to build and run the app.

4. **Explore the App:**
   - Interact with the app by clicking the "Generate" button to see random dog photos.

## Requirements

- Xcode 12.0 or later
- Swift 5.0 or later
- iOS 14.0 or later

## Contributing

If you'd like to contribute to the development of this app, feel free to submit a pull request. Bug reports, feature requests, and feedback are also welcome through the [GitHub Issues](https://github.com/your-username/random-dog-photo-generator/issues) page.

## License

This Random Dog Photo Generator app is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own projects.

## Contact

If you have any questions or concerns, please contact the project maintainer:

- Andrew Bloom
- drewabloom@gmail.com
- https://github.com/disciplinedfox

Thank you for using the Random Dog Photo Generator app! 🐾
