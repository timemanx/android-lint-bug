# android-lint-bug
Lint never completes if we use an enum class containing an enum constant named ORDER and it's used in a layout using data binding.

Steps to reproduce:
1. Add an enum class that contains an enum constant named ORDER
2. Use this enum constant in a layout with data binding
3. Run lint (./gradlew lintDebug)
