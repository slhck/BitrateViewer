# BitrateViewer

A small app to plot bitrate per frame, second, or GOP on macOS.

This runs under macOS. It requires `ffprobe` to be installed in `/usr/local/bin`. You can install `ffprobe` with Homebrew via `brew install ffmpeg`.

## Screenshot

![GOP](Screenshots/GOP.png)

![Frame](Screenshots/Frame.png)

## Building

- macOS 10.14.4
- Xcode 10.2
- Swift 5
- Carthage (`carthage update --platform macos`)

The following third-party libraries are used:

- [Charts](https://github.com/danielgindi/Charts)
- [SnapKit](https://github.com/SnapKit/SnapKit)
- [RxSwift](https://github.com/ReactiveX/RxSwift)

## Author/License

Author: Werner Robitza

This app is based on existing projects:

- [BitrateViewer](https://github.com/nuomi1/BitrateViewer.git)
- [BitrateViewer](https://github.com/galad87/BitrateViewer)

License: GNU GPL v3