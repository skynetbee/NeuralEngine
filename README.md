# NeuralEngine

**NeuralEngine** is a pre-compiled binary framework packaged as a Swift Package. It provides high-performance neural processing functionalities optimized for Apple platforms.

## 📦 Features

- Precompiled as `.xcframework` for easy integration
- Supports **iOS (13+)** and **macOS (11+)**
- Lightweight and fast — ideal for apps requiring efficient neural operations
- Designed for both development and production environments

## 🔧 Installation

### Swift Package Manager

Add the package to your project using Xcode:

1. Open your project in Xcode.
2. Go to `File` > `Add Packages`.
3. Enter the URL to your repository.
4. Choose the `NeuralEngine` library and click **Add Package**.

## Usage

```swift
import SwiftUI
import NeuralEngine

// 🌟 Root container showing off every mini-project
struct ContentView: View {
    var body: some View {
        DevEnvironment(
            p1: Project1View(),
            p2: Project2View(),
            p3: Project3View(),
            p4: Project4View(),
            p5: Project5View(),
            p6: Project6View(),
            p7: Project7View(),
            p8: Project8View(),
            p9: Project9View(),
            p10: Project10View(),
            workaround: WorkaroundView()
        )
    }
}

// 🔽 10 quick demo screens
struct Project1View: View  { var body: some View { Text("Hello from Project 1") } }
struct Project2View: View  { var body: some View { Text("Hello from Project 2") } }
struct Project3View: View  { var body: some View { Text("Hello from Project 3") } }
struct Project4View: View  { var body: some View { Text("Hello from Project 4") } }
struct Project5View: View  { var body: some View { Text("Hello from Project 5") } }
struct Project6View: View  { var body: some View { Text("Hello from Project 6") } }
struct Project7View: View  { var body: some View { Text("Hello from Project 7") } }
struct Project8View: View  { var body: some View { Text("Hello from Project 8") } }
struct Project9View: View  { var body: some View { Text("Hello from Project 9") } }
struct Project10View: View { var body: some View { Text("Hello from Project 10") } }

// 🛠️ Extra workaround screen
struct WorkaroundView: View { var body: some View { Text("Hello from Workaround") } }
