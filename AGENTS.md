# Project instructions

This is a Flutter calendar and schedule management application.

## Platform

- Primary target: iOS.
- Keep Android compatibility unless the requested feature is iOS-specific.
- Use Flutter and Dart.
- Keep platform-specific native code to a minimum.

## Architecture

- Keep UI, models, and data logic separated.
- Do not put the entire application in main.dart.
- Keep main.dart focused on application startup and top-level configuration.
- Prefer small, reusable widgets.
- Keep the architecture understandable for a beginner.

## Dependencies

- Prefer Flutter SDK functionality where practical.
- Do not add external packages unless they provide clear value.
- Explain why a dependency is necessary before adding it.
- Do not replace an existing dependency without approval.

## Platform files

- Do not modify files under ios/ or android/ unless necessary.
- Explain any required native platform change before making it.

## Validation

- Run dart format on modified Dart files.
- Run flutter analyze after code changes.
- Run flutter test when applicable.
- Fix errors caused by the changes before finishing.

## Git safety

- Do not run git commit.
- Do not run git push.
- Do not run git reset --hard.
- Do not run git clean.
- Do not force-push.
- Leave commits and pushes to the user.
- Read-only Git commands such as git status, git diff, and git log are allowed.

## Working style

- Before substantial changes, explain the implementation plan.
- State which files will be created or modified.
- Do not modify unrelated files.
- After implementation, summarize all changes.