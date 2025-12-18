# Restaurant App

A cross-platform **Restaurant Application** built using **React Native** and **React.js**, designed to support **Android, iOS, and Web** platforms from a **single shared codebase**. The project focuses on clean architecture, reusable components, and separation of business logic from platform-specific UI.

---

## 📌 Project Overview

This application demonstrates how a real-world restaurant or food-ordering platform can be built using a unified codebase. Shared logic is implemented using Redux and Redux-Saga, while UI layers are customized for mobile and web.

The project can be extended to support:
- Restaurant discovery
- Menu and category browsing
- Food ordering workflows
- Cart and checkout systems
- User authentication and profiles

---

## Setup
---

## ⚙️ Prerequisites

Before running the project, ensure the following are installed:

- Node.js (LTS recommended)
- Yarn or npm
- Android Studio (for Android builds)
- Xcode (for iOS builds, macOS only)

---

### Installation

- run `npm install` or `yarn install`

### Run on Device

- run `yarn android` or `yarn ios` to run on device or emulator

### Start the web version

- run `yarn start:web`

### Project info


Main objective of this project was to have a single code base for both 
web and mobile apps with the logic and view separated.

#### Project Structure

```
    /android                - React native android source code
    
    /app                    - React native specific code
        /base_components    - reusable react native components
        /components         - react native components
        /screens            - connected to store components
        /App.js             - App Root component
        /router.js          - route config
        
    /assets                 - contains image and fonts
    /ios                    - React native ios source code
    
    /src
        /actions            - all redux actions
        /constants          - colors and Assets
        /reducers           - all reducers
        /sagas              - all redux sagas  
        /service            - API methods
        /store              - store config
        /utils              - some utility functions

    /web                    - react js web specific code
        /screens            - connected to store components
        /components         - react components
        /base_components    - reusable react components
        /App.js             - App Root component
        /routes.js          - route config
    /webpack                - webpack config
    
```



#### ScreenShots - Native App

<img src="screenshots/1.png" data-canonical-src="screenshots/1.png" width="250" />
<img src="screenshots/2.png" data-canonical-src="screenshots/2.png" width="250" />
<img src="screenshots/3.png" data-canonical-src="screenshots/3.png" width="250" />
<img src="screenshots/4.png" data-canonical-src="screenshots/4.png" width="250" />
<img src="screenshots/5.png" data-canonical-src="screenshots/5.png" width="250" />
<img src="screenshots/6.png" data-canonical-src="screenshots/6.png" width="250" />
<img src="screenshots/7.png" data-canonical-src="./screenshots/7.png" width="250" />
<img src="screenshots/8.png" data-canonical-src="./screenshots/8.png" width="250" />


# Restaurant-app
# React-Native-Restaurant-App
# React-Native-Restaurant-App
