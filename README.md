# flutter_study_provider

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

##### Breakpoint Conditions:

```
    // Use `context.dependOnInheritedWidgetOfExactType<_InheritedProviderScope<T?>>()` to set dependencies
    InheritedElement -> void setDependencies(Element dependent, Object? value)
    this.runtimeType.toString().contains('_InheritedProviderScopeElement')

    InheritedElement -> void _updateInheritance()
    widget.runtimeType.toString().contains('_InheritedProviderScope')


```
