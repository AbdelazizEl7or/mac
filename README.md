# Starfish iOS GitHub CI Build

This project is prepared for building an iOS .ipa automatically using GitHub Actions.

## How to Use

1. Upload this folder to a GitHub repository.
2. Make sure your Xcode project is named `Starfish.xcworkspace` and your scheme is `Starfish`.
3. Commit and push to `main` branch.
4. GitHub will build the `.ipa` and give it to you under the Actions tab as an artifact.

You can also manually trigger the build using `workflow_dispatch`.
