# Android Compose Integration Guide

1. Open your existing Android Studio project.
2. Confirm the app uses Kotlin and Jetpack Compose. If it does not, ask the coding agent to migrate carefully rather than replacing project files blindly.
3. Copy `Color.kt` into your theme package and `IgniteComponents.kt` into your UI components package.
4. Update the `package` declarations to match your app's namespace.
5. Add a Material 3 theme using the supplied colors.
6. Build the Student Dashboard first using `IgniteStatCard` and `IgniteSectionTitle`.
7. Add navigation routes for each screen in `design-spec.md`.
8. Connect repositories/ViewModels to Firebase only after the static UI is approved.
9. Keep role checks in both UI navigation and Firebase Security Rules.

The component file is a starter. Add your own app-specific icons, fonts, navigation and screen state.
