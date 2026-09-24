The latest release is available via [NuGet](https://www.nuget.org/packages/ClickableTransparentOverlayer).

# Clickable Transparent Overlay
Slightly modernized fork of CTO that utilizes ImGUI's multi-viewport feature for its functionality.

The goal of this library is providing a minimal GUI framework for desktop apps with as little bloat and boilerplate as possible.

Currently, only Windows is supported, although it should be easy to implement a portable backend using SDL & OpenGL using the [`IBackend` interface](https://github.com/Saalvage/ClickableTransparentOverlayer/blob/master/ClickableTransparentOverlay/Backends/Backend.cs).
I have not done this because I don't really expect any interest in this fork and using SDL significantly bloats the resulting executable size (which I am seeking to keep minimal).

# How to Use

Please see the sample projects ([here](https://github.com/Saalvage/ClickableTransparentOverlayer/tree/master/Examples)) which demonstrate how to use this library.

# Dependencies

* [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
* [Vortice.Windows](https://github.com/amerkoleci/Vortice.Windows)
* [Hexa.NET.ImGui](https://github.com/HexaEngine/Hexa.NET.ImGui)

# Feedback

Please open issue in github repo for feedback.
