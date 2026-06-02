# anyonehub-debug-apk-and-docs
anyone-hub-alpha-releases
Bleeding-edge native Android development environment. Zero-copy architecture. Desktop-grade UI design.

Welcome to the private Alpha for Anyone-Hub. This repository hosts the pre-compiled APKs, documentation, and issue tracking for early adopters testing the platform.

Anyone-Hub is not a web wrapper. It is a fully native developer platform featuring a Kotlin Jetpack Compose frontend, a headless Rust backend daemon, and deep system-level Android Virtualization Framework (AVF) integration.

🔥 Core Architecture & Features
Advanced UI Layout Designer: A true desktop-grade drag-and-drop canvas on mobile. Features 38+ fully functional elements that anchor perfectly into place. Powered by a bi-directional JNI pipe that generates real-time XML as you move components.

Zero-Copy LSP Rendering: Our headless Rust Language Server passes text directly to the Kotlin frontend via a shared direct ByteBuffer across the memory boundary. Sub-millisecond latency.

Native Terminal & Shell Execution: Direct interaction with local compiler toolchains without cloud dependencies.

AVF Orchestration: Deep system-level execution utilizing the Android Virtualization Framework.

🚀 Installation Guide
Because Anyone-Hub utilizes local toolchains and system-level daemons, it must be sideloaded.

Download the APK: Navigate to the Releases tab in this repository and download the latest app-debug.apk or app-release.apk.

Enable Unknown Sources: On your Android device, go to Settings > Apps > Special app access > Install unknown apps and grant permission to your browser or file manager.

Install & Launch: Tap the downloaded APK to install.

Accept the EULA: Upon first launch, you will be required to read and accept the End User License Agreement due to the system-level capabilities of the terminal.

🧪 Alpha Testing Focus
For this initial alpha phase, we are highly focused on stress-testing the visual layout engine.

Your First Mission:

Open the UI Designer.

Drag, drop, and anchor the layout elements.

Observe the real-time XML generation.

Try to break the anchoring logic or the JNI layout pipe.

🐛 Bug Reports & Feedback
This is an alpha. You will encounter bumps. We want your stack traces, logcats, and brutal feedback.

Crashes: If the app crashes, capture the logcat output. Open a new issue in the Issues tab and include the raw logs.

Feature Requests: See something missing in the UI designer or the terminal? Open an issue tagged as enhancement.

If you are interested in contributing to the core Rust backend or the Jetpack Compose frontend, drop a note in your issue report or email us directly. Active alpha testers will be granted access to the main source code repository.

⚖️ Legal & Contact
By using this software, you acknowledge the inherent risks of executing shell commands and local compilers on your native OS. Anyone-Hub LLC is not responsible for local data loss. See the full EULA.md included in this repository.

Contact: anyone-hub.dev@zohomail.com
Copyright: Copyright 2024 anyone-Hub
