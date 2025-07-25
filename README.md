# Budgify 💰 - Ultimate Expense Tracker & Wallet Manager

<p align="center">
  <img src="https://i.imgur.com/8a5nO32.jpg" alt="Budgify Logo" width="150" style="border-radius: 24px;"/>
  <h1 align="center">Budgify - Smart Finance Management</h1>
  <p align="center">
    <b>Track. Analyze. Optimize.</b> Your all-in-one financial companion with stunning visuals and powerful insights.
  </p>
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.budgifydev.budgify" target="_blank">
    <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" width="200"/>
  </a>
</p>

<p align="center">
  <a href="https://flutter.dev" target="_blank"><img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"></a>
  <a href="https://dart.dev" target="_blank"><img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"></a>
  <a href="https://riverpod.dev/" target="_blank"><img src="https://img.shields.io/badge/Riverpod-4A98E8?style=for-the-badge&logo=riverpod&logoColor=white" alt="Riverpod"></a>
  <a href="https://pub.dev/packages/get" target="_blank"><img src="https://img.shields.io/badge/GetX-00A9E0?style=for-the-badge&logo=getx&logoColor=white" alt="GetX"></a>
  <a href="https://pub.dev/packages/hive" target="_blank"><img src="https://img.shields.io/badge/Hive-FFC107?style=for-the-badge&logo=hive&logoColor=black" alt="Hive"></a>
  <a href="https://pub.dev/packages/lottie" target="_blank"><img src="https://img.shields.io/badge/Lottie-000000?style=for-the-badge&logo=lottie&logoColor=white" alt="Lottie"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/Version-2.1.3-green.svg" alt="Version">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <!-- Replace with your GitHub username and repo name -->
  <img src="https://img.shields.io/github/stars/your-username/budgify-app?style=social" alt="GitHub Stars">
</p>

## ✨ Key Features

### 📊 Dynamic Financial Dashboard
- **Real-time Overview**: Instantly see your monthly savings, top spending categories, and budget progress.
- **Interactive Cards**: Beautifully designed cards provide key financial insights at a glance.
- **Lottie Animations**: Engaging animations make the financial experience more enjoyable.

### 💰 Smart Transaction Management
- **Effortless Tracking**: Log expenses and incomes with custom titles, amounts, notes, and dates.
- **Intelligent Categorization**: Assign transactions to default or custom-created categories, each with a unique icon and color.
- **Multiple Views**: View your transaction history in a clean list, a detailed table, or a visual grid.

### 👛 Multi-Wallet System
- **Unlimited Wallets**: Create and manage multiple wallets for Cash, Bank, and Digital funds.
- **Seamless Transfers**: Easily transfer funds between your wallets with a dedicated interface.
- **Wallet-Specific Insights**: Track the balance and progress of each wallet individually.

### 🌈 Immersive & Customizable UI
- **8 Stunning Themes**: Personalize your app with a variety of color themes including Dark, Purple, Blue, Green, Red, and more.
- **Responsive Design**: A fluid and adaptive layout that looks great on both phones and tablets.
- **Customizable Views**: Switch between list, grid, and table views for your expenses to see data your way.

### 🌍 Global Accessibility
- **Multi-Language Support**: Fully translated into 7 languages:
  - English | العربية (Arabic) | Español (Spanish)
  - Deutsch (German) | Français (French)
  - 中文 (Chinese) | Português (Portuguese)
- **Currency Customization**: Supports a wide range of global currency symbols.

### 📈 Advanced Analytics & Reports
- **Visual Charts**: Analyze your finances with interactive Pie, Bar, and Line charts.
- **Flexible Filtering**: View data by day, month, or year to understand spending trends over time.
- **Detailed Reports**: Generate comprehensive tables summarizing your daily, monthly, and yearly financial activity.

## 🎥 App Showcase

<table>
  <tr>
    <td align="center"><b>Homepage</b></td>
    <td align="center"><b>Wallets & Categories</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/fb947537-0bff-4d87-ae8f-5f4e7d8a7e32" width="250"></td>
    <td><img src="https://github.com/user-attachments/assets/913dcd63-3cea-42f5-8b76-7ecddb608b1e" width="250"></td>
  </tr>
  <tr>
    <td align="center"><b>Charts & Analytics (Pie)</b></td>
    <td align="center"><b>Charts & Analytics (Line)</b></td>
  </tr>
    <tr>
    <td><img src="https://github.com/user-attachments/assets/cabef679-2eea-4081-a1dc-50a914797800" width="250"></td>
    <td><img src="https://github.com/user-attachments/assets/099c6d74-1ba9-46f0-b087-846840daf68e" width="250"></td>
  </tr>
   <tr>
    <td align="center"><b>Detailed Expenses</b></td>
    <td align="center"><b>Calendar View</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ef921814-8575-431f-82d0-21c59a624a97" width="250"></td>
    <td><img src="https://github.com/user-attachments/assets/302141bc-cdea-4032-a235-83289dd2f525" width="250"></td>
  </tr>
</table>

## 🛠️ Tech Stack & Architecture

Budgify is built with a modern, scalable architecture designed for performance and maintainability.

```mermaid
graph TD
    A[UI Layer - Flutter] --> B[State Management];
    A --> C[Navigation];
    A --> D[Local Database];

    subgraph B [State Management]
        B1[Riverpod]
        B2[StateNotifierProvider]
    end

    subgraph C [Navigation & Services]
        C1[GetX]
    end

    subgraph D [Local Database]
        D1[Hive]
        D2[Type Adapters]
    end

    E[App Features] --> F[UI Components];
    F --> F1[Lottie Animations];
    F --> F2[FL Chart];
    F --> F3[Responsive UI];

    E --> G[Core Logic];
    G --> G1[Multi-Language Support];
    G --> G2[Custom Themes];
    G --> G3[Data Reports];
