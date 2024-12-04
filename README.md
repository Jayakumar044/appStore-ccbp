*****let's build an App Store*****


* Functionality to be added :

The app must have the following functionalities

- Initially, the **Social** tab should be active and the apps with **Social** as their category should be displayed
- When a value is provided in the search input
  - The apps in the active category, that include search input value in their name should be displayed
  - When another tab is clicked, the apps in the corresponding category, that include search input value in their name should be displayed
  - The search should be case insensitive
- When the search input is empty,
  - All the apps in the active category should be displayed
  - When another tab is clicked, the apps in the corresponding category should be displayed
- The `AppStore` component is provided with `tabsList`. It consists of a list of tabItem objects with the following properties in each tabItem object

  |     Key     | Data Type |
  | :---------: | :-------: |
  |    tabId    |  String   |
  | displayText |  String   |

- The `AppStore` component is provided with `appsList`. It consists of a list of app objects with the following properties in each app object

  |   Key    | Data Type |
  | :------: | :-------: |
  |  appId   |  Number   |
  | appName  |  String   |
  | imageUrl |  String   |
  | category |  String   |

