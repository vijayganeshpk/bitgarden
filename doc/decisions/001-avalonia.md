# Selection of Avalonia UI Framework for Bitgarden

Date: 2024-09-06

Status: proposed

## Context

The Bitgarden project aims to create an enhanced, user-friendly GUI for Bitwarden, addressing several limitations in the current official GUI. As a cross-platform application, we need a framework that can support multiple operating systems while providing a rich, native-like user interface. The chosen framework should also be compatible with .NET, as Bitwarden's core is built with C#.

Key requirements for the UI framework:

1. Cross-platform support (Windows, macOS, Linux)
2. .NET compatibility
3. Rich UI capabilities
4. Active community and ongoing development
5. Open-source licensing

## Decision

We have decided to use the Avalonia UI framework for developing the Bitgarden GUI.

Avalonia UI is a cross-platform XAML-based UI framework for .NET applications. It allows developers to create desktop applications that can run on Windows, macOS, and Linux using a single codebase.

Reasons for selecting Avalonia UI:

1. **Cross-platform compatibility**: Avalonia supports Windows, macOS, and Linux, aligning with our goal of creating a widely accessible application.

2. **.NET integration**: As a .NET-based framework, Avalonia integrates seamlessly with C# and other .NET technologies, making it compatible with Bitwarden's existing codebase.

3. **XAML-based**: Avalonia uses XAML for defining user interfaces, which is familiar to developers with WPF or UWP experience, potentially easing the learning curve and development process.

4. **Rich UI capabilities**: Avalonia provides a comprehensive set of UI controls and supports custom styling, enabling us to create a modern and intuitive interface.

5. **Active development and community**: Avalonia has an active development community, regular updates, and growing adoption, suggesting long-term viability and support.

6. **Open-source**: Avalonia is open-source and released under the MIT license, aligning with our project's open-source nature.

7. **Performance**: Avalonia is designed to be lightweight and performant, which is crucial for a security-focused application like a password manager.

## Consequences

Positive consequences:

- Ability to target multiple platforms with a single codebase, reducing development and maintenance efforts.
- Modern UI capabilities that will allow us to address the shortcomings of the current Bitwarden GUI.
- Potential for good performance across different operating systems.
- Alignment with .NET ecosystem, facilitating integration with Bitwarden's core functionality.

Potential challenges:

- Learning curve for developers not familiar with Avalonia or XAML-based frameworks.
- Smaller community compared to more established frameworks like Electron, which may result in fewer resources and third-party libraries.
- Potential limitations in platform-specific features, which may require additional work to implement.

Next steps:

- Set up a proof-of-concept to validate Avalonia's capabilities in the context of our specific requirements.
- Develop a small prototype to assess the learning curve and identify any potential roadblocks.
- Establish coding standards and best practices for Avalonia development within the team.
