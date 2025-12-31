# SkyVPN-App
SkyVPN is a SwiftUI-based VPN registration app with login, signup, logout, and password reset features. Clean MVVM architecture and modern design for iOS and macOS.
🌐 SkyVPN – SwiftUI VPN Registration App

 

 

 

SkyVPN is a sleek VPN registration app built entirely with SwiftUI. Effortlessly manage user accounts with login, signup, logout, and password reset features, all wrapped in a modern, responsive interface.

🚀 Features

	•	✅ User Login
	•	✅ User Registration
	•	✅ Logout Functionality
	•	✅ Password Reset

🛠 Requirements

	•	iOS 14.0+ / macOS 10.14.4+
	•	Xcode 12+
	•	Swift 5+

🏗 Architecture

Built with MVVM (Model–View–ViewModel) for clean separation between UI and business logic.
	•	Makes code maintainable, testable, and scalable
	•	Decouples View from data handling
	•	Simplifies integration with SwiftUI’s declarative UI

🎨 Why SwiftUI?

	•	Declarative syntax for clear, concise code
	•	Automatic support for Dark Mode, Dynamic Type, localization, and accessibility
	•	Works seamlessly with Xcode design tools
	•	One codebase for all Apple platforms

⚙️ Components

Views

	•	Login – Handles authentication
	•	Router – Controls navigation and app flow
	•	Home – Main screen after login
	•	SignUp – Handles new user registration

ViewModel

	•	AuthVM – Connects Views with API and data services

	Fully decoupled from UI for clean architecture

Network Layer

	•	NetworkService – Centralized API request manager

Third-Party Libraries

	•	Alamofire
	•	Licenses available in Utils/License.txt

💻 Installation

	1.	Clone the repository:

git clone 最新文本1：[skyvpn.me](https://skyvpn.me/register?referral=k0041s8rmu)

	2.	Enter the project directory
	3.	Install dependencies with CocoaPods:

pod install

	4.	Open .xcworkspace and run the app in Xcode

🔧 Code Management

	•	Uses Gitflow workflow for structured branching
	•	Ideal for large projects and continuous development

🎯 Screenshots

(Add your app screenshots here for a visual appeal)

🌟 Contributions

Feel free to open issues, submit pull requests, or suggest new features!
