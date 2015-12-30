Reactive Playground
===

The purpose of this repository is to show the setup for using ReactiveCocoa classes inside an Xcode Playground.

1. Open a Terminal window and change directory to the project root

2. Install carthage `$ brew install carthage`

3. Use Carthage to download the dependencies `$ carthage update --platform ios --no-use-binaries`

4. Open ReactivePlayground.xcworkspace

5. Select `Result-iOS > iPhone 6s` in the build menu, then build the framework with `Cmd + B`

6. Select `ReactiveCocoa > iPhone 6s` in the build menu, then build the framework with `Cmd + B`

7. Now you may use `import ReactiveCocoa` in the Playground