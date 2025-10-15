# DSRelativeTimeFormatter

A tiny, dependency‑free Swift utility for producing concise, human‑friendly relative time strings like `"3hr 15min ago"`, `"1.5 hr ago"`, or `"45s"`. The formatter is immutable and thread‑safe, suitable for apps and packages.

## Features

- Compact, readable relative time output
- Two styles: subunits (e.g., `"1d 3hr"`) and decimal most‑significant (e.g., `"1.5 hr"`)
- Abbreviations: `s`, `min`, `hr`, `d`, `wk`, `mo`, `yr`
- Stateless and thread‑safe
- No dependencies beyond Foundation
- See Tests for a few usage examples.

## Supported Platforms

This package targets Apple platforms that support Swift 5.9+ and Foundation:

- iOS 15+
- iPadOS 15+
- macOS 12+
- tvOS 15+
- watchOS 8+

(Adjust the exact versions in your Package.swift if your project requires different minimums.)

## Installation

Add DSRelativeTimeFormatter to your Swift Package dependencies:

```swift
// In Package.swift
.dependencies: [
  .package(url: "https://github.com/your-org/DSRelativeTimeFormatter.git", from: "1.0.0")
]


