# 🌿 Oliver – Professional Olive Press Management System

<div align="center">

<p align="center">
  <img src="https://github.com/user-attachments/assets/436f38f7-b9fe-4dc3-85aa-e9783d1ed7ce" alt="Oliver Logo" width="200"/>
</p>
**A comprehensive desktop application for managing olive presses, financial operations, inventory, and personnel**

[![Flutter](https://img.shields.io/badge/Flutter-3.7+-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.7+-0175C2?logo=dart)](https://dart.dev)
[![License](https://img.shields.io/badge/License-Proprietary-blue)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20|%20Linux%20|%20macOS-blue)](https://flutter.dev/docs/development/platform-integration/windows-desktop)

</div>

---
<p align="center">
<img width="600" alt="Cover" src="https://github.com/user-attachments/assets/0fb6480d-93e5-4293-bc97-0919430cb2f7" />
</p>

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Architecture](#project-architecture)
- [Prerequisites & Environment Requirements](#prerequisites--environment-requirements)
- [Installation & Setup](#installation--setup)
- [Configuration](#configuration)
- [Build & Run Commands](#build--run-commands)
- [Folder Structure](#folder-structure)
- [Core Modules & Features](#core-modules--features)
- [API Integration](#api-integration)
- [Usage Guidelines](#usage-guidelines)
- [Development Workflow](#development-workflow)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)

---

## Overview

**Oliver** is a professional-grade desktop application designed specifically for managing olive press operations (معاصر الزيتون) in agricultural and commercial settings. Built with **Flutter** for cross-platform desktop support, Oliver provides a comprehensive suite of tools for financial management, inventory tracking, personnel management, and operational reporting.

The application supports **4 languages**: Arabic (العربية), English, Turkish (Türkçe), and French (Français), making it accessible to diverse user bases across the Mediterranean and Middle East regions.

### Target Users
- Olive press operators and managers
- Agricultural business administrators
- Financial accountants and bookkeepers
- Inventory and warehouse managers
- HR and payroll administrators

---

<h2>📸 Screenshots</h2>

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/849b8a6c-1741-46ea-8740-612a37300f07" width="400"><br>
<b>Login Screen</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/16bded50-432f-4c15-b087-2f8f5b67fac8" width="400"><br>
<b>Dashboard</b>
</td>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/b8fb1ecd-0852-43d7-b094-6d3030e6ade0" width="400"><br>
<b>Navigation Menu</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/eba91347-bc7b-4253-afc2-14d269119f7e" width="400"><br>
<b>Client Management</b>
</td>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/1b1e232f-b468-4f7d-b737-b32e47f48941" width="400"><br>
<b>Reservation Form</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/d7c382e8-81d3-43b7-9ce2-d61fbd8e8a1a" width="400"><br>
<b>Settings</b>
</td>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/a77a2b0c-886b-40ef-8a1e-7ac7a62a2e87" width="400"><br>
<b>Dark Theme</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/69733b0a-05f0-46e6-a005-3eec5ded3fa8" width="400"><br>
<b>Data Synchronization</b>
</td>
</tr>
</table>


---

## Key Features

### 📱 **Client & Customer Management**
- Add, update, and manage customer profiles
- Store comprehensive customer details (name, address, phone, email, contact person)
- Customer profile images and documentation
- Search and filtering capabilities
- Customer account history and transactions

### 🤝 **Supplier & Partner Management**
- Supplier profile creation and management
- Trader relationship tracking
- Purchase order and payment management
- Supplier performance metrics
- Transaction history and reconciliation

### 🌿 **Olive & Oil Operations**
- Olive purchase and sale transaction recording
- Batch tracking and identification
- Oil extraction and conversion management
- Olive-to-oil ratio calculations
- By-product management (التلت - Tilt, الجفت - Jift)
- Production capacity planning
- Quality control documentation

### 💰 **Financial & Accounting System**
- Complete accounting module (الحسابات)
- Sales management (olive, oil, and by-product sales)
- Expense tracking and categorization
- Salary and payroll management
- Treasury and cash flow management
- Account receivables and payables
- Financial reporting and reconciliation
- Daily accountant reports
- Account statements and ledgers

### 👥 **Human Resources & Personnel**
- Employee profile management
- Salary and compensation tracking
- Bonus and deduction management
- Employee service tracking
- HR document management

### 📦 **Inventory & Asset Management**
- Equipment purchase and depreciation tracking
- Press and machinery inventory management
- Warehouse and tank management
- Full tank and damaged tank tracking
- Asset utilization reports

### 📊 **Reporting & Analytics**
- Dashboard statistics and KPIs
- Daily reports and summaries
- Financial statements
- Inventory reports
- Operational efficiency metrics
- Custom report generation
- PDF export capabilities

### 🌍 **Multi-Language Support**
- Arabic (العربية) - RTL language support
- English (EN) - LTR
- Turkish (Türkçe) - LTR
- French (Français) - LTR
- Easy language switching without restart

### 🎨 **User Experience Features**
- Responsive desktop UI
- Dark and light theme support
- Intuitive navigation
- Keyboard shortcuts and accessibility
- Real-time data validation
- Toast notifications
- Loading indicators and animations

### 🔗 **Additional Features**
- Genetics and breeding information management
- Line queue and production scheduling
- Loyalty and customer tier management
- Price list management
- Loans and credit management
- Friendships and gifts tracking
- Statistical regions and area management
- Service officer assignment and tracking

---

## Technology Stack

### **Framework & Language**
- **Flutter**: ^3.7.0 - Cross-platform UI framework
- **Dart**: ^3.7.0 - Programming language

### **Architecture & Design Patterns**
- **Clean Architecture**: Separation of concerns with clear layers
- **BLoC Pattern**: State management and business logic
- **Repository Pattern**: Data access abstraction
- **Dependency Injection**: Using GetIt and Injectable

### **State Management**
- **flutter_bloc**: ^9.1.0 - BLoC implementation
- **bloc_test**: ^10.0.0 - Testing support
- **formz**: ^0.8.0 - Form state management

### **Local Database**
- **isar**: ^3.1.0+1 - Lightweight embedded database
- **isar_flutter_libs**: ^3.1.0+1 - Platform support
- **isar_generator**: ^3.1.0+1 - Code generation

### **Networking & API**
- **dio**: ^5.8.0+1 - HTTP client
- **pretty_dio_logger**: ^1.4.0 - Network debugging
- **internet_connection_checker**: ^3.0.1 - Connectivity detection
- **connectivity_plus**: ^6.1.4 - Network status monitoring

### **UI & Presentation**
- **flutter_screenutil**: ^5.9.3 - Responsive design adaptation
- **flutter_svg**: ^2.0.17 - SVG support
- **google_fonts**: ^6.2.1 - Web font integration
- **animate_do**: ^4.2.0 - Animation library
- **flutter_animate**: ^4.5.2 - Advanced animations
- **lottie**: ^3.3.1 - Lottie animations
- **fl_chart**: ^0.69.0 - Charts and graphs
- **dropdown_button2**: ^2.3.9 - Enhanced dropdowns
- **animated_custom_dropdown**: ^3.1.1 - Custom animated dropdowns
- **dotted_border**: ^2.1.0 - Custom borders
- **expandable_page_view**: ^1.0.17 - Expandable page views
- **loading_animation_widget**: ^1.3.0 - Loading animations

### **Localization & Internationalization**
- **easy_localization**: ^3.0.7+1 - i18n support
- **intl**: - Internationalization utilities
- **JSON-based language files**: Arabic, English, Turkish, French

### **Desktop & Window Management**
- **bitsdojo_window**: ^0.1.6 - Window customization
- **window_manager**: ^0.4.3 - Window lifecycle management
- **adaptive_layout**: ^0.1.7 - Adaptive UI layouts

### **File & Document Handling**
- **file_picker**: ^10.1.2 - File selection
- **pdf**: ^3.11.3 - PDF generation
- **printing**: ^5.14.2 - Printing support
- **open_file**: ^3.5.10 - File opening utilities
- **path_provider**: ^2.1.5 - Path resolution
- **path_provider_windows**: ^2.3.0 - Windows-specific paths
- **screenshot**: ^3.0.0 - Screenshot capture
- **qr_flutter**: ^4.1.0 - QR code generation

### **Hardware Integration**
- **blue_thermal_printer**: ^1.2.3 - Thermal printer support
- **flutter_esc_pos_utils**: ^1.0.1 - POS printer utilities

### **Utilities & Helpers**
- **json_annotation**: ^4.9.0 - JSON serialization
- **json_serializable**: - JSON code generation
- **logger**: ^2.6.2 - Structured logging
- **shared_preferences**: ^2.5.3 - Local preferences
- **dartz**: ^0.10.1 - Functional programming utilities
- **equatable**: ^2.0.7 - Value equality
- **get_it**: ^8.0.3 - Service locator
- **injectable**: ^2.5.0 - DI code generation
- **injectable_generator**: - DI generator
- **cached_network_image**: ^3.4.1 - Image caching
- **carousel_slider**: ^5.0.0 - Image carousels

### **Code Generation & Build Tools**
- **build_runner**: ^2.4.15 - Code generation
- **flutter_launcher_icons**: ^0.14.3 - App icons
- **flutter_native_splash**: ^2.4.5 - Native splash screens

### **Testing**
- **flutter_test**: SDK integrated
- **mockito**: ^5.4.5 - Mocking library
- **pinput**: ^5.0.1 - PIN input widget

### **Linting & Analysis**
- **flutter_lints**: ^5.0.0 - Recommended lints
- **analyzer**: ^6.0.0 - Static analysis

---

## Project Architecture

Oliver follows **Clean Architecture** principles with clear separation of concerns:

```
lib/
├── features/                    # Feature-based modules
│   ├── auth/                   # Authentication module
│   ├── clients/                # Client management
│   ├── suppliers/              # Supplier management
│   ├── sales/                  # Sales operations
│   ├── accounting/             # Financial accounting
│   ├── employees/              # HR & payroll
│   ├── inventory/              # Inventory management
│   ├── reports/                # Reporting & analytics
│   ├── dashboard/              # Dashboard & statistics
│   ├── [other features]/       # Additional domain modules
│   └── shared/                 # Shared feature components
│
├── core/                        # Core application layer
│   ├── base/                   # Base classes and abstractions
│   ├── constants/              # Application constants
│   ├── cubit/                  # Global state management
│   │   ├── connectivity/       # Network status
│   │   ├── locale/             # Language management
│   │   ├── theme/              # Theme management
│   │   └── [other cubits]/     # Global state
│   ├── di/                     # Dependency injection
│   ├── enums/                  # Application enums
│   ├── errors/                 # Error handling
│   ├── extensions/             # Dart extensions
│   ├── helper/                 # Helper utilities
│   ├── injection/              # Service locator setup
│   ├── isar/                   # Database configuration
│   ├── models/                 # Core data models
│   ├── network/                # API client configuration
│   ├── pdf_printing/           # PDF & printing utilities
│   ├── report_generator/       # Report generation logic
│   ├── routing/                # Navigation and routing
│   ├── services/               # Core services (theme, etc)
│   ├── shared/                 # Shared utilities
│   ├── sync/                   # Data synchronization
│   ├── translations/           # Localization setup
│   ├── utils/                  # General utilities
│   └── widgets/                # Reusable widgets
│
├── main.dart                    # Application entry point
├── app.dart                     # Main app widget
└── app_bloc_observer.dart      # BLoC logging & monitoring
```

### Architecture Layers

#### 1. **Presentation Layer**
- Widgets and UI components
- BLoC state management
- User interaction handling
- Navigation routing

#### 2. **Domain Layer**
- Business logic and use cases
- Entity definitions
- Repository abstractions
- Exception definitions

#### 3. **Data Layer**
- Data models and DTOs
- Repository implementations
- Data sources (local, remote)
- API clients and services

#### 4. **Core Layer**
- Shared utilities and extensions
- Service locator and DI
- Theme and localization management
- Network and database configuration

---

## Prerequisites & Environment Requirements

### **System Requirements**

#### Windows
- **OS**: Windows 10 or later (64-bit)
- **RAM**: Minimum 4 GB (8 GB recommended)
- **Disk Space**: 2 GB for development, 500 MB for runtime
- **CPU**: Intel/AMD 64-bit processor

#### Linux
- **OS**: Ubuntu 18.04+ or equivalent distribution
- **RAM**: Minimum 4 GB (8 GB recommended)
- **Disk Space**: 2 GB for development
- **Package Manager**: apt, pacman, or equivalent

#### macOS
- **OS**: macOS 10.13 or later
- **RAM**: Minimum 4 GB (8 GB recommended)
- **Disk Space**: 3 GB for development

### **Software Requirements**

#### Essential
- **Flutter SDK**: ^3.7.0 or later
- **Dart SDK**: ^3.7.0 or later (bundled with Flutter)
- **Git**: Latest version

#### Platform-Specific

**Windows:**
- Visual Studio Build Tools 2019+ or Visual Studio Community 2019+
  - Desktop development with C++ workload
  - Windows 10 SDK (any recent version)

**Linux:**
```bash
# Core requirements
sudo apt-get install -y \
  build-essential \
  cmake \
  git \
  pkg-config \
  libgtk-3-dev \
  libclipboard-dev \
  libxkbcommon0
```

**macOS:**
- Xcode 12.0+
- Xcode Command Line Tools
- CocoaPods

#### Optional but Recommended
- **Android Studio** or **VS Code** - IDE with Flutter/Dart plugins
- **DevTools** - Flutter's development tools
- **Git GUI** - For version control (GitHub Desktop, GitKraken, etc.)

---

## Installation & Setup

### **Step 1: Verify Flutter Installation**

```bash
# Check Flutter version
flutter --version

# Verify all dependencies
flutter doctor

# Expected output: "No issues found!" ✓
```

### **Step 2: Clone Repository**

```bash
# Clone the repository
git clone https://github.com/your-organization/oliver.git
cd oliver

# Navigate to project directory
cd oliver-desktop
```

### **Step 3: Get Flutter Dependencies**

```bash
# Update Flutter packages
flutter pub get

# Alternative with verbose output
flutter pub get -v
```

### **Step 4: Run Code Generation**

```bash
# Generate code for models, DI, and JSON serialization
flutter pub run build_runner build --delete-conflicting-outputs

# Watch mode for development (auto-regenerate on changes)
flutter pub run build_runner watch
```

### **Step 5: Setup Database (Isar)**

```bash
# Dependencies are installed with pub get
# Isar will initialize on first app launch
# Database location:
# - Windows: %APPDATA%\com.abdalluh\oliver
# - Linux: ~/.local/share/com.abdalluh/oliver
# - macOS: ~/Library/Application Support/com.abdalluh/oliver
```

### **Step 6: Verify Setup**

```bash
# List available platforms
flutter devices

# Should show at least one desktop platform:
# - Windows (windows)
# - Linux (linux)
# - macOS (macos)
```

---

## Configuration

### **Environment-Specific Setup**

#### **Windows Desktop**

```bash
# Configure for Windows desktop
flutter config --enable-windows-desktop

# Enable Windows development
flutter create --template=app --platforms=windows .
```

#### **Linux Desktop**

```bash
# Configure for Linux desktop
flutter config --enable-linux-desktop

# Check CMake version (required >= 3.10)
cmake --version
```

#### **macOS Desktop**

```bash
# Configure for macOS desktop
flutter config --enable-macos-desktop

# Install CocoaPods dependencies
cd macos && pod install && cd ..
```

### **Application Configuration**

#### **Localization Setup**
The app uses `easy_localization` for multi-language support. Language files are located in `assets/lang/`:

```
assets/lang/
├── ar.json    # Arabic (العربية)
├── en.json    # English
├── fr.json    # French (Français)
└── tr.json    # Turkish (Türkçe)
```

To add a new language:
1. Create `assets/lang/xx.json` (where xx is the locale code)
2. Copy structure from existing language file
3. Translate all strings
4. Update `easy_localization` configuration in `main.dart`

#### **Theme Configuration**
Theme colors and styles are managed in `core/services/theme_service.dart`:

```dart
// Access current theme
final theme = Theme.of(context);

// Switch themes
context.read<ThemeCubit>().toggleTheme();
```

#### **Local Storage Preferences**
User preferences are stored via `shared_preferences`:

```dart
// Location:
// - Windows: Registry HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\...
// - Linux: ~/.config/com.abdalluh.oliver/
// - macOS: ~/Library/Preferences/com.abdalluh.oliver.plist
```

#### **Database Configuration**
Isar database is configured in `core/isar/isar_setup.dart`:

```dart
// Database file location:
// Windows: C:\Users\[Username]\AppData\Roaming\com.abdalluh\oliver
// Linux: ~/.local/share/com.abdalluh/oliver
// macOS: ~/Library/Application Support/com.abdalluh/oliver
```

### **API Configuration**

If the app integrates with backend services, configure API endpoints in `core/network/`:

```dart
// api_client.dart
const String apiBaseUrl = 'https://api.example.com'; // Set your API base URL

// Network timeout configurations
const Duration apiTimeout = Duration(seconds: 30);
```

---

## Build & Run Commands

### **Development Mode**

```bash
# Run on default connected device
flutter run

# Run with verbose logging (useful for debugging)
flutter run -v

# Run with specific device
flutter run -d windows    # Windows desktop
flutter run -d linux      # Linux desktop
flutter run -d macos      # macOS desktop

# Run with profile mode (performance analysis)
flutter run --profile

# Run with release mode
flutter run --release
```

### **Build Commands**

#### **Build Desktop Applications**

```bash
# Windows Desktop Build
flutter build windows --release

# Linux Desktop Build
flutter build linux --release

# macOS Desktop Build
flutter build macos --release

# Build artifacts location:
# Windows: build/windows/runner/Release
# Linux: build/linux/x64/release/bundle
# macOS: build/macos/Build/Products/Release
```

#### **Build with Code Generation**

```bash
# Regenerate code and rebuild
flutter pub run build_runner build --delete-conflicting-outputs && flutter run

# Watch mode (auto-rebuild on code changes)
flutter pub run build_runner watch
```

### **Web Build** (if supported)

```bash
# Enable web support
flutter config --enable-web

# Build web
flutter build web --release

# Run web
flutter run -d chrome  # Requires Chrome installed
```

### **Debugging & Analysis**

```bash
# Analyze code for issues
flutter analyze

# Format code according to Dart conventions
dart format lib/

# Run Dart linter
dart lint lib/

# Check for unused imports and code
flutter pub run build_runner build

# Run DevTools for debugging
flutter pub global activate devtools
devtools
```

### **Testing Commands**

```bash
# Run all tests
flutter test

# Run tests with coverage
flutter test --coverage

# Run specific test file
flutter test test/widget_test.dart

# Run tests in watch mode
dart run test --watch
```

### **Clean Build**

```bash
# Clean build artifacts
flutter clean

# Clean and rebuild
flutter clean && flutter pub get && flutter pub run build_runner build --delete-conflicting-outputs && flutter run
```

---

## Folder Structure

### **Detailed Directory Layout**

```
oliver-desktop/
│
├── android/                         # Android platform code
│   ├── app/                        # Android app module
│   └── gradle/                     # Gradle build configuration
│
├── ios/                            # iOS platform code
│   ├── Runner/                     # iOS app target
│   └── Podfile                     # CocoaPods dependencies
│
├── linux/                          # Linux platform code
│   ├── CMakeLists.txt             # CMake build configuration
│   ├── flutter/                   # Flutter engine
│   └── runner/                    # Linux app runner
│
├── macos/                          # macOS platform code
│   ├── Runner/                    # macOS app target
│   └── Podfile                    # CocoaPods dependencies
│
├── windows/                        # Windows platform code
│   ├── CMakeLists.txt            # CMake build configuration
│   ├── flutter/                  # Flutter engine
│   └── runner/                   # Windows app runner
│
├── web/                           # Web platform (if enabled)
│   ├── index.html                # HTML entry point
│   ├── manifest.json             # Web app manifest
│   └── icons/                    # Favicon and PWA icons
│
├── lib/                           # Main application code
│   ├── features/                 # Feature modules (domain-specific)
│   │   ├── account_statement/
│   │   ├── all_accounting/
│   │   ├── auth/
│   │   ├── clients/
│   │   ├── dashboard_statistics/
│   │   ├── employees/
│   │   ├── expense/
│   │   ├── financial_year/
│   │   ├── home/
│   │   ├── reports/
│   │   ├── sales/
│   │   ├── suppliers/
│   │   ├── [50+ additional features]/
│   │   └── shared/               # Shared UI components for features
│   │
│   ├── core/                     # Core application layer
│   │   ├── base/                # Base classes (BaseBloc, BaseRepository, etc)
│   │   ├── constants/           # App constants, strings, sizes
│   │   ├── cubit/               # Global state management
│   │   │   ├── connectivity/    # Network connectivity state
│   │   │   ├── locale/          # Language/locale state
│   │   │   ├── theme/           # Theme state management
│   │   │   └── [other global states]/
│   │   ├── di/                  # Dependency injection setup
│   │   ├── docs/                # Documentation and guides
│   │   ├── enums/               # Enum definitions
│   │   ├── errors/              # Custom exceptions and error handling
│   │   ├── examples/            # Code examples and templates
│   │   ├── extensions/          # Dart extensions (String, DateTime, etc)
│   │   ├── helper/              # Helper functions and utilities
│   │   ├── injection/           # Service locator configuration
│   │   ├── isar/                # Local database setup
│   │   ├── mixins/              # Reusable behavior mixins
│   │   ├── models/              # Core data models
│   │   ├── network/             # API client and interceptors
│   │   │   ├── dio_client.dart
│   │   │   ├── interceptors/
│   │   │   └── [API setup]/
│   │   ├── pdf_printing/        # PDF generation utilities
│   │   ├── report_generator/    # Report generation logic
│   │   ├── routing/             # App routing with GoRouter
│   │   ├── services/            # Core services (theme, logging, etc)
│   │   ├── shared/              # Shared utilities and helpers
│   │   ├── sync/                # Data synchronization logic
│   │   ├── translations/        # Localization setup
│   │   ├── utils/               # General utility functions
│   │   └── widgets/             # Reusable UI widgets
│   │
│   ├── main.dart                # Application entry point
│   ├── app.dart                 # Main App widget
│   └── app_bloc_observer.dart   # BLoC observer for logging
│
├── test/                         # Unit and widget tests
│   ├── widget_test.dart         # Example widget test
│   ├── core/                    # Core layer tests
│   └── features/                # Feature tests
│
├── assets/                       # Static assets
│   ├── images/                  # Images and icons
│   │   └── app_icon.png        # App icon
│   ├── svgs/                    # SVG graphics
│   │   ├── icons/               # Icon SVGs
│   │   └── images/              # Image SVGs
│   ├── lang/                    # Localization files
│   │   ├── ar.json              # Arabic translations
│   │   ├── en.json              # English translations
│   │   ├── fr.json              # French translations
│   │   └── tr.json              # Turkish translations
│   └── fonts/                   # Custom fonts
│       └── Switzer/             # Switzer font family
│           ├── *.otf, *.ttf     # Font files
│           └── NotoNaskhArabic/ # Arabic font support
│
├── tool/                        # Development tools
│   ├── generate_feature.dart    # Feature scaffold generator
│   └── generate_project.dart    # Project generator
│
├── .github/                     # GitHub configuration
│   └── copilot-instructions.md # Flutter/Dart guidelines
│
├── pubspec.yaml                 # Flutter dependencies
├── analysis_options.yaml        # Linting rules
├── devtools_options.yaml        # DevTools configuration
├── README.md                    # This file
└── LICENSE                      # Project license
```

### **Feature Module Structure** (Example: `features/clients/`)

Each feature module follows this structure for consistency:

```
features/[feature_name]/
├── data/                    # Data layer
│   ├── datasources/        # Remote and local data sources
│   │   ├── remote/
│   │   └── local/
│   ├── models/             # Data Transfer Objects (DTOs)
│   └── repositories/       # Repository implementations
│
├── domain/                 # Domain layer (business logic)
│   ├── entities/          # Core domain entities
│   ├── repositories/      # Repository abstractions
│   └── usecases/          # Use cases and business logic
│
└── presentation/          # Presentation layer (UI)
    ├── bloc/              # BLoCs for state management
    ├── cubit/             # Cubits for local state
    ├── pages/             # Full-screen pages
    ├── widgets/           # Reusable widgets
    └── [feature]_routes.dart  # Feature routing
```

---

## Core Modules & Features

### **Feature Breakdown**

#### **Authentication (`features/auth/`)**
- User login and registration
- Session management
- User credentials validation
- Password reset

#### **Financial Management (`features/accounting/`, `features/expense/`, etc.)**
- General ledger and accounts
- Income and expense tracking
- Financial reporting
- Cash flow management

#### **Operations (`features/sales/`, `features/purchases/`, etc.)**
- Sales transaction recording
- Purchase order management
- Olive and oil tracking
- Inventory movements

#### **HR & Payroll (`features/employees/`)**
- Employee records
- Salary management
- Attendance tracking
- Benefits and deductions

#### **Reporting (`features/reports/`, `features/dashboard_statistics/`)**
- Financial reports
- Operational dashboards
- Custom report generation
- Export to PDF

---

## API Integration

### **Network Layer Architecture**

The app uses **Dio** for HTTP requests with a layered architecture:

```
core/network/
├── api_client.dart          # Dio HTTP client instance
├── interceptors/
│   ├── logging_interceptor.dart
│   ├── error_handler_interceptor.dart
│   └── auth_interceptor.dart
└── api_endpoints.dart       # API endpoint constants
```

### **API Configuration**

```dart
// core/network/api_client.dart
const String apiBaseUrl = 'https://api.example.com';
const Duration apiTimeout = Duration(seconds: 30);

// API endpoints
const String loginEndpoint = '/auth/login';
const String clientsEndpoint = '/clients';
const String salesEndpoint = '/sales';
// ... more endpoints
```

### **Making API Calls**

Example in repository layer:

```dart
// data/repositories/client_repository.dart
class ClientRepository {
  final ApiClient _apiClient;
  
  Future<List<ClientModel>> getClients() async {
    try {
      final response = await _apiClient.get('/clients');
      return (response.data as List)
          .map((client) => ClientModel.fromJson(client))
          .toList();
    } catch (e) {
      throw ServerException(e.toString());
    }
  }
}
```

### **Network Error Handling**

The app includes automatic error handling for:
- Network timeout
- Server errors (5xx)
- Client errors (4xx)
- Connection failures
- SSL/Certificate errors

---

## Usage Guidelines

### **For End Users**

#### **First-Time Setup**
1. Launch the Oliver application
2. Select preferred language (Arabic, English, Turkish, French)
3. Complete user authentication
4. Configure company/business information
5. Set financial year and accounting period

#### **Common Workflows**

**Recording a Sale:**
1. Navigate to Sales > New Sale
2. Select client and products
3. Enter quantity and pricing
4. Verify total and tax calculations
5. Confirm and print receipt (optional)

**Managing Inventory:**
1. Go to Inventory > Warehouse Management
2. View current stock levels
3. Record incoming purchases
4. Document outgoing sales
5. Generate inventory reports

**Generating Reports:**
1. Select Reports from main menu
2. Choose report type (financial, operational, etc.)
3. Specify date range
4. Review and export as PDF

### **For Developers**

#### **Adding a New Feature**

1. **Generate Feature Scaffold**
   ```bash
   dart tool/generate_feature.dart feature_name
   ```

2. **Implement Domain Layer**
   - Create entities
   - Define repository abstractions
   - Implement use cases

3. **Implement Data Layer**
   - Create DTOs/models
   - Implement data sources (local/remote)
   - Implement repository

4. **Implement Presentation Layer**
   - Create BLoC for state management
   - Build UI widgets and pages
   - Integrate with routing

5. **Add Tests**
   - Unit tests for business logic
   - Widget tests for UI
   - Integration tests for workflows

#### **Extending the App**

**Adding API Integration:**
1. Define API endpoint in `core/network/api_endpoints.dart`
2. Create data models in `data/models/`
3. Implement data source in `data/datasources/`
4. Add repository method
5. Create use case and BLoC

**Adding New Language:**
1. Add `assets/lang/[locale].json`
2. Copy keys from existing language file
3. Translate all values
4. Update `EasyLocalization` configuration

**Modifying UI Theme:**
1. Edit `core/services/theme_service.dart`
2. Update colors and typography
3. Rebuild app: `flutter run`

---

## Development Workflow

### **Git Workflow**

```bash
# Create feature branch
git checkout -b feature/your-feature-name

# Make changes and commit
git add .
git commit -m "feat: describe your changes"

# Push to remote
git push origin feature/your-feature-name

# Create Pull Request
# (via GitHub web interface)
```

### **Code Quality Standards**

#### **Formatting**
```bash
# Format code
dart format lib/

# Check formatting
dart format --output=none --set-exit-if-changed lib/
```

#### **Linting**
```bash
# Run linter
dart lint lib/

# Fix common issues
dart fix --apply
```

#### **Code Analysis**
```bash
# Analyze code
flutter analyze

# Get detailed output
flutter analyze --verbose
```

#### **Testing**
```bash
# Run all tests
flutter test

# Run specific test
flutter test test/widget_test.dart

# Generate coverage report
flutter test --coverage
```

### **Debugging**

#### **Using DevTools**
```bash
# Launch DevTools
flutter pub global activate devtools
devtools

# Connect to running app via DevTools URL
```

#### **Verbose Logging**
```bash
# Run with verbose output
flutter run -v

# View device logs
flutter logs
```

#### **IDE Debugging**
- Set breakpoints in VS Code / Android Studio
- Run with debugging: `flutter run`
- Step through code and inspect variables

---

## Troubleshooting

### **Common Issues & Solutions**

#### **Build Errors**

| Issue | Solution |
|-------|----------|
| "Unable to find CMake" | Install CMake or update PATH |
| "Gradle sync failed" | Run `flutter clean && flutter pub get` |
| "Pod install failed" (macOS) | Run `cd macos && pod install --repo-update && cd ..` |
| "Visual Studio Build Tools not found" | Install Visual Studio Build Tools with C++ workload |

#### **Runtime Errors**

| Issue | Solution |
|-------|----------|
| "MissingPluginException" | Run `flutter clean` and rebuild |
| "FileSystemException" | Check file permissions and database location |
| "DioException" | Verify API endpoint and network connection |
| "Isar database locked" | Close other app instances and restart |

#### **Development Issues**

| Issue | Solution |
|-------|----------|
| "Unsupported operation: Platform.isIOS" | Build for supported platform (Windows, Linux, macOS) |
| "Localization not working" | Run `flutter pub get` and rebuild |
| "Code generation not updating" | Run `flutter pub run build_runner build --delete-conflicting-outputs` |
| "Hot reload not working" | Use `flutter run` instead of previous session |

### **Performance Optimization**

- Use `ListView.builder()` for long lists
- Implement `const` constructors for widgets
- Use `ScreenUtilInit` for responsive layouts
- Minimize rebuilds with proper BLoC scoping
- Defer heavy operations to background isolates

### **Getting Help**

- Check [Flutter Documentation](https://flutter.dev/docs)
- Review [Dart Documentation](https://dart.dev/guides)
- Consult [Issue Tracker](https://github.com/flutter/flutter/issues)
- Run `flutter doctor` to diagnose environment issues

---

## Contributing

### **How to Contribute**

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### **Code Style**

- Follow [Effective Dart](https://dart.dev/guides/language/effective-dart) guidelines
- Use meaningful variable and function names
- Add documentation comments to public APIs
- Keep functions focused and under 20 lines when possible
- Use 80-character line length limit

### **Commit Message Format**

```
<type>: <subject>

<body>

<footer>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Example:
```
feat: add client filtering in list view

Implemented search and filter functionality for client list
- Added text search by name
- Added status filter (active/inactive)
- Performance optimized with debouncing
```

---

## License

This project is proprietary and confidential. Unauthorized copying, modification, or distribution is strictly prohibited.

---

## Support & Contact

For issues, questions, or feature requests:
- **Email**: support@oliver-app.com
- **Issues**: [GitHub Issues](https://github.com/your-org/oliver/issues)
- **Documentation**: [Wiki](https://github.com/your-org/oliver/wiki)

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history and updates.

---

**Made with ❤️ for olive press operators worldwide**



   
