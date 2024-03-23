<img height='200' src="https://github.com/foodlens/FoodLens/blob/75cdec1fb3c6c459d4369cfebf3163d14cdfbf59/assets/logo.png" align="left" vspace="10"  hspace="10">

<h1 align= "top" >FoodLens - An AI Powered Food Analysis Companion Android app <br>
(Mobile Application for Food Allergen Identification and Alternative Food Suggestions)<br><br></h1>


## What is FoodLens?

FoodLens is a mobile application designed to simplify the process of identifying allergens and harmful ingredients in packaged food products. It utilizes modern technologies such as artificial intelligence and machine learning to provide users with personalized recommendations and alternative food suggestions.The project Backend is responsible for handling the REST API calls and processing data for the FoodLens application. It is implemented using Node.js with Express and MongoDB.

> ### ⚠️ ALERT
>
> To install the app, you can visit [HERE](https://play.google.com/store/apps/details?id=com.foodlens.FoodLens)
>
> To watch our business website, you can visit [HERE]()

## User flows

[Visual documentation of the App on Figma](https://www.figma.com/proto/uxg6xo07JNyTeDRCh3qjh1/FoodLens?type=design&node-id=2-122&t=zFLh34VCcQHKWw4G-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A2&mode=design)

## Features

- **User Food Profile:** Users can create their own food profile, including allergen details and dietary restrictions, to receive personalized recommendations.&nbsp;
- **Allergens Identification:** The application can identify allergens in packaged food products.&nbsp;
- **Ingredient Label Scanning:** Users can scan the ingredients label or the barcode of a packaged food product to identify allergens and artificial ingredients.&nbsp;
- **Barcode Scanning:** Users can scan the barcode of a packaged food product to retrieve its details from the database and identify allergens and artificial ingredients.&nbsp;
- **Alternative Food Suggestions:** The application suggests similar alternative packaged food products for identified harmful ingredients based on the user's food profile.&nbsp;
- **Similarity Percentage for Alternative Foods:** The application provides the similarity percentage for alternative foods, facilitating user comparisons.&nbsp;
- **Artificial Ingredients Warnings:** The application warns users about artificial ingredients in packaged food products.&nbsp;
- **Pre-suggesting Food Products:** The application pre-suggests packaged food products based on the user's food profile and previous activities.&nbsp;
- **Manual Input of Unavailable Food Details:** Users can manually input the details of unavailable packaged food products into the database.&nbsp;
- **Gamification and Rewards:** Users earn points for their contributions.&nbsp;

## Technologies Used in Front-End Development

- **Flutter:** The front-end implementation of FoodLens is built using Flutter, a mobile app development framework known for its high performance and cross-platform capabilities.&nbsp;
- **Firebase Authentication and Firestore Database:** These Firebase services are integrated into the application for user login, authentication, and seamless data storage. Its fully managed NoSQL document database provided by Firebase, used for storing user-related data and facilitating efficient data retrieval&nbsp;
- **Google MLKIT and QR_code_Scanner Package:** FoodLens utilizes Google's MLKIT and QR_code_Scanner package to scan barcodes of packaged food items.&nbsp;
- **OpenFoodFacts API:** FoodLens fetches product details from the OpenFoodFacts API.&nbsp;

## Technologies Used in Back-End Development

- **MongoDB**: The backend uses MongoDB to store information such as allergens, products, and product information.
  &nbsp;
- **OpenAI's GPT 3.5 Model:** The application utilizes OpenAI's GPT 3.5 Model to process and extract relevant information.
  &nbsp;
- **Express**: A fast and minimalist web application framework for Node.js.
  &nbsp;
- **Node.js**: A JavaScript runtime environment that allows you to run JavaScript code outside of a web browser.
  &nbsp;
- **Heroku**: A cloud platform that lets us deploy, manage, and scale applications. It's flexible, easy to use, and our application is running on it.
  &nbsp;
- **npm**: A package manager for Node.js that helps us manage project dependencies. We use it to install and manage packages that our application needs to function properly.
  &nbsp;

## Languages and Tools Used

<p align="left"> <a href="https://dart.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/> </a>&nbsp; <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a>&nbsp; <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a>&nbsp; <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>&nbsp;<a> <img src="https://developers.google.com/ml-kit/images/homepage/hero_1920.png" alt="git" width="40" height="40"/></a>&nbsp;<a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://www.dicoding.com/blog/wp-content/uploads/2022/04/logo-express-js-770x471.png" alt="express" width="40" height="40"/> </a>&nbsp; <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/810px-Npm-logo.svg.png" alt="npm" width="40" height="40"/> </a> &nbsp;<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>&nbsp;<a href="https://heroku.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a>&nbsp; <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a>&nbsp;<img src="https://static.vecteezy.com/system/resources/previews/022/227/370/original/openai-chatgpt-logo-icon-free-png.png" alt="git" width="40" height="40"/>&nbsp; <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a>&nbsp;<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>&nbsp; <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a>&nbsp; <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>

## Installation 
## 1) FoodLens Repository
>
>👉 Click [Here!](https://github.com/foodlens/FoodLens.git)

To install and run FoodLens on your device, follow these steps:

1. Clone the repository:

   - Open a terminal or command prompt.
   - Navigate to the desired directory where you want to clone the repository.
   - Run the following command:

     ```
     git clone https://github.com/foodlens/FoodLens.git
     ```

2. Install Flutter and set up your development environment:

   - Follow the official Flutter installation guide for your operating system: https://flutter.dev/docs/get-started/install

3. Install the required dependencies:

   - Open a terminal or command prompt.
   - Navigate to the project directory:

     ```
     cd FoodLens
     ```

   - Run the following command to install the dependencies:

     ```
     flutter pub get
     ```

4. Connect your device or start an emulator:

   - Connect your physical device to your computer using a USB cable.
   - Alternatively, start an emulator using Android Studio or the `flutter emulators` command.

5. Launch the application:

   - Open a terminal or command prompt.
   - Navigate to the project directory if you're not already in it.
   - Run the following command to launch the application on your connected device or emulator:

     ```
     flutter run
     ```
     
## 2) Backend Repository
>
>👉 Click [Here!](https://github.com/foodlens/backend.git)

To set up the FoodLens Backend, follow these steps:

1. Clone the repository:
   
    ```
     git clone https://github.com/your-repo.git
    ```
    
3. Install dependencies:
   
    ```
     npm install
    ```
    
5. Configure environment variables: Create a `.env` file and provide the necessary environment variables, such as database connection details and Firebase credentials.

6. Start the server:
   
    ```
     npm start
    ```
## 3) ML-model Repository
>
>👉 Click [Here!](https://github.com/foodlens/ml-model.git)

## 4) Business Website Repository
>
>👉 Click [Here!](https://github.com/foodlens/foodlensWebsite.git)

To get started with the FoodLens Business Website, follow these steps:

1. Clone the repository:
    ```
      git clone https://github.com/your-username/foodlens-website.git
    ```
    
2. Install dependencies:
    ```
      npm install
    ```
    
3. Start the development server:
    ```
       npm run dev
    ```
    
4. Open your browser and navigate to see the website in action.

## Contributors

The project was initially created by a group of second year students at the Informatics Institute of Technology, Sri Lanka.

- [Abishtakan Sivachandrathevan](https://github.com/abishtakan)
- [Mithuna Chandrasekaran](https://github.com/MithuChandran)
- [Jonathan Rajaratnam](https://github.com/JohnnyKingsman)
- [Dinuk Shivakumar](https://github.com/Dinuk002)
- [Jude Shantharaj Harishraj](https://github.com/Harish-Offcl)

## License

FoodLens is released under the MIT License.

## Contact

For any feedback or suggestions for new features, please contact the FoodLens team at teamfoodlens@gmail.com.
Enjoy exploring the FoodLens Application and discovering the power of our application!
