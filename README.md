# BiteSavers 🍃

**Making food rescue easier, one meal at a time.**

BiteSavers is an Android mobile application designed to help reduce food waste by connecting customers with food offers from businesses. It aims to encourage sustainable consumption by making surplus food easier to discover and purchase.

The application also provides business-oriented features to help food businesses manage their listings, orders, and operations.

## ✨ Features

### 🛍️ Customer Features
- **Food Discovery** — Browse available food offers and discover participating businesses.
- **Food Details** — View food information, descriptions, prices, and availability.
- **Checkout** — Review orders and proceed through the checkout process.
- **Order Management** — View order history and order-related information.
- **Saved Offers** — Keep track of interesting food offers.
- **Payment Methods** — Manage payment methods and wallet-related options.
- **User Profile** — Access profile, privacy, security, and support information.
- **Location-Based Discovery** — Explore food offers through map-related functionality.

### 🏪 Business Features
- **Business Dashboard** — Access business-related information and activities.
- **Food Listing Management** — Add food offers and manage existing listings.
- **Order Management** — View and manage customer orders.
- **Business Profile** — Manage business information and registration details.
- **Analytics** — View business-related analytics.
- **Temperature Management** — Record and manage temperature-related information.
- **Payout Management** — Access merchant payout functionality.
- **Notifications** — View business-related notifications.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Kotlin | Main programming language |
| Jetpack Compose | Modern Android UI development |
| Material 3 | UI components and design |
| Android ViewModel | UI state and business logic management |
| Kotlin Coroutines / Flow | Asynchronous operations and reactive state |
| Navigation Compose | Navigation between application screens |
| Supabase | Backend services, authentication, database access, and storage integration |
| MapLibre | Map rendering |
| Google Play Services Location | Location-related functionality |
| Kotlin Serialization | Data serialization |
| Coil | Image loading |
| Gradle Kotlin DSL | Project configuration and dependency management |

## 🏗️ Project Architecture

The project organizes its code by application role and feature, with separate areas for UI, logic, and data models.

```text
BiteSavers/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/example/bitesavers/
│           │       ├── business/
│           │       │   ├── analytics/
│           │       │   ├── dashboard/
│           │       │   ├── inventory/
│           │       │   ├── payout/
│           │       │   ├── profile/
│           │       │   └── temperature/
│           │       ├── customer/
│           │       │   ├── checkout/
│           │       │   ├── discovery/
│           │       │   ├── orders/
│           │       │   ├── payment/
│           │       │   ├── profile/
│           │       │   └── saved/
│           │       ├── login/
│           │       └── ui/
│           │           └── theme/
│           └── AndroidManifest.xml
├── gradle/
│   └── libs.versions.toml
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Android Studio with a compatible Android Gradle Plugin.
- JDK compatible with the project's Gradle configuration.
- Android SDK Platform 37, as configured in the project.
- An Android emulator or a physical Android device.
- Supabase project credentials and any required external service configuration.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/BiteSavers.git
   ```

2. Open the project in Android Studio.

3. Allow Gradle to synchronize the project and download its dependencies.

4. Configure the required backend credentials and external services.

5. Select an Android emulator or connect a physical device.

6. Build and run the `app` module.

> **Note:** Replace `YOUR-USERNAME` with your GitHub username. The application may require additional configuration before all features can run correctly.

## 🔐 Configuration and Security

Before publishing this repository:

- Do not commit API secrets, service-role keys, passwords, or private credentials.
- Keep sensitive configuration out of version control.
- Review Supabase access policies and authentication settings.
- Check location permissions and other Android permissions.
- Remove local build outputs, temporary files, and unnecessary IDE files.

## 🌱 Project Goals

BiteSavers aims to:

- Reduce avoidable food waste.
- Encourage sustainable food consumption.
- Help customers discover food offers.
- Support businesses in managing surplus food.
- Promote environmental awareness through technology.

## 📌 Project Status

This repository contains the BiteSavers Android application source code. Feature availability, backend integration, and deployment readiness should be verified against the current implementation.


## My own part

For this project, I mainly focused on the authentication, IOT safety and merchant management features. Specifically, I worked on the Customer and business sign-in and login flows, integrated the terms and conditions agreement, and built the restaurant registration screen for the new business account. I also handled the temperature sensor setup module for adding the monitoring boxes. Moreover, I added the merchant wallet feature directly into the business profile screen and also did the function of the merchant wallet. Lastly, I also cleaned up some navigation routes, added the validation and debugging with our group members.
