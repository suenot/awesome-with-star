# Information comes from [uraimo/Awesome-Swift-Playgrounds](https://github.com/uraimo/Awesome-Swift-Playgrounds)
# Awesome Swift Playgrounds [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![147 playgrounds](https://img.shields.io/badge/Playgrounds:-147-orange.svg) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=A%20List%20of%20more%20than%20150%20Awesome%20Swift%20Playgrounds&url=https://github.com/uraimo/Awesome-Swift-Playgrounds&via=uraimo)

> A curated list of awesome Swift playgrounds.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/uraimo/awesome-swift-playgrounds/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/uraimo/awesome-swift-playgrounds/graphs/contributors); you rock!

If you see a playground here that does not work anymore with the current release of Xcode or is not a good fit, please submit a pull request to improve this file or consider updating it, thank you!

### Downloading all the playgrounds

Unless otherwise indicated, all playgrounds are compatible with Swift 3.

All the playgrounds are available as submodules in the `playgrounds/` directory, to download them all in one go, just clone this repository with `git clone --recursive https://github.com/uraimo/Awesome-Swift-Playgrounds.git` or execute `git submodule update --init` after you have cloned the repository the usual way. 

Apple's playgrounds distributed as zip archives have to be downloaded manually.

### Tags

🌟 = My personal favorites

🍁 = Swift 4+ Playground

⏳ = Pre-Swift 3 Playground

### Contents

- [PlaygroundBooks](#playgroundbooks)
- [Learning Swift](#learning-swift)
- [Learning Swift: Advanced Topics](#learning-swift-advanced-topics)
  - [Design Patterns](#design-patterns)
  - [Protocol Oriented Programming](#protocol-oriented-programming)
  - [Functional Reactive Programming](#functional-reactive-programming)
- [Apple's Playgrounds](#apples-playgrounds)
- [Playgrounds about Playgrounds](#playgrounds-about-playgrounds)
- [Playgrounds from Playgroundbooks](#playgrounds-from-playgroundbooks)
- [Theoretical Computer Science](#theoretical-computer-science)
    - [Algorithms and Data Structures](#algorithms-and-data-structures)
    - [Languages](#languages)
    - [Machine Learning](#machine-learning)
- [UIKit And Graphics](#uikit-and-graphics)
  - [Core Image](#core-image)
  - [Metal](#metal)
  - [Animations](#animations)
  - [SpriteKit](#spritekit)
- [Audio](#audio)
- [Mathematics](#mathematics)
- [Libraries and APIs](#libraries-and-apis)
- [Playground sets](#playground-sets)
- [Miscellaneous](#miscellaneous)


## PlaygroundBooks
*Playgrounds that can be run on your iPad*

* [Tree Trouble Playbook](https://github.com/joelrorseth/Tree-Trouble) - An interactive Swift Playground Book about Binary Search Trees. :star:17
* [Auto Pong](https://github.com/cardoso/AutoPong) - A tutorial to implement a pong based on a simple AI. :star:2
* [Neural Network Playground](https://github.com/hetelek/Neural-Network-Playground) - A neural network Swift playground, with no third party dependencies. :star:360
* [Window Manager Playground](https://github.com/steventroughtonsmith/windowmanager-playgroundbook) - Playground for an experimental window manager. :star:37
* [AudioKit Playground Book](https://github.com/audiokit/AudioKitPlaygroundBook) - A set of playgrounds using AudioKit designed for the iOS10 Playgrounds app. :star:74
* [Numsw](https://github.com/sonsongithub/numsw) - A swift playground book that mimics some of the features of numpy and jupyter notebook. :star:107
* [File Browser Playground](https://github.com/steventroughtonsmith/files-playgroundbook) - Simple File Browser for Swift Playgrounds on iOS. :star:191
* [Geometry with Swift](https://github.com/dbbudd/Geometry-Swift-PlaygroundBook) - In this course your students will learn the fundamentals of Swift 3 programming, using geometry as their context for learning.  :star:3
* [Image Filtering](https://github.com/lennet/image-filtering) - A Swift playgroundbook about Image Filtering. 🌟 :star:48
* [Spacetime Rhapsody](https://github.com/hollisliu/Spacetime-Rhapsody) - A Swift Playground visualizing gravity based on Einstein's Theory of General Relativity. 🌟 :star:11
* [Guilloche Pattern Playground Book](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁 :star:7
* [Accessibility](https://github.com/xReee/wwdc2018) - Accessibility for iOS developers. 🍁  :star:2

## Learning Swift
*Some interesting playgrounds to learn Swift*

* [The Swift Programming Language Playgrounds](https://github.com/danielpi/Swift-Playgrounds) - 40+ playgrounds, one for each chapter of Apple's Swift book. 🌟 :star:176
* [Swift Hack Pack](https://github.com/GuildSA/swift-hack-pack) - Collection of playgrounds that teaches Swift. :star:11
* [The Swift Summary Book](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language. 🌟 :star:1675
* [Swifter Tips](https://github.com/swifter-tips/Playground) - Examples for every feature of the Swift language. :star:113
* [About Swift](https://github.com/NicolaLancellotti-About/About-Swift) - A playground about Swift language. :star:38
* [MPCS51032 UChicago iOS Course](https://github.com/uchicago-mobi/mcps51032-2017-spring-playground) - Playgrounds from the 2017 Spring iOS course of the University of Chicago. :star:4
* [What's new in Swift 4](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showing off the new features in Swift 4.0. 🍁 🌟  :star:1954
* [Codable Playground](https://github.com/filip-zielinski/CodablePlayground) - Playground that demonstrates advanced uses of Codable 🍁 :star:10

## Learning Swift: Advanced Topics
*Advanced topics, useful once you have mastered the basics of the language*

* [A Swift Introduction to Core Data](https://github.com/andyshep/CoreDataPlaygrounds) - Learn Core Data experimenting directly in this playground. 🌟 :star:128
* [TDDSwiftPlayground](https://github.com/sshrpe/TDDSwiftPlayground) - Demonstration of using Swift Playgrounds in Test Driven Development with XCTest. :star:42
* [Concurrency on iOS](https://github.com/sammyd/2017AtSwift_Concurrency) - Concurrency and Parallelism in iOS. :star:33
* [Modern Core Data](https://github.com/dfreniche/modern-core-data-playground) - An introduction to Core Data. :star:24
* [Swift DSL Example](https://github.com/cfdrake/swift-dsl-example) - Implementation of a DSL in Swift. :star:16
* [Katan](https://github.com/marciok/katan) - A micro web server that replies "Hello world!" to every request, an example of how to use sockets in Swift. :star:14
* [Swift Regular Expressions](https://github.com/ogulcan/SwiftRegEx) - A playground to learn regular expressions with Swift. :star:3
* [Network Stack](https://github.com/AndrejKolar/NetworkStack) - Clean & simple Swift networking stack playground. :star:8
* [Swiftly Typed Resources](https://github.com/jstart/Swiftly-Typed-Resources) - A playground showing how Swift makes Strings, Colors, Fonts, Images, etc easier to deal with. ⏳ :star:73
* [Swift KVO Closures](https://github.com/rectalogic/KVOPlayground) - Swift KVO playground. ⏳  :star:10
* [Swift Date Tutorial](https://github.com/liuyubobobo/Swift-NSDate-Tutorial) - Learn everythig about NSDate. ⏳  :star:7
* [Swift And C](https://github.com/MacMark/SwiftAndC) - Examples about using C with Swift. ⏳  :star:5
* [Swift Memory Management](https://github.com/ndethore/swift-memory-management) - How to avoid retain cycles, from [this post](http://detho.re/2016/01/21/writing-memory-efficient-swift-code/). ⏳ :star:2

### Design Patterns

* [Design Patterns Playground](https://github.com/edopelawi/DesignPatternsPlayground) - Learning GoF's Design Patterns in Swift 3. :star:24
* [iOS Design Patterns](https://github.com/haxpor/ios-design-patterns) - Sample projects for MVC, MVP, MVVM, and VIPER. :star:58
* [Design Patterns in Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design patterns in Swift 3. :star:10009
* [GOF Swift](https://github.com/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) - Learn all 23 Gang of Four patterns using Swift. :star:38
* [The Principles of OOD in Swift 4](https://github.com/ochococo/OOD-Principles-In-Swift) - The Principles of OOD based on Uncle Bob articles.🍁 :star:1409

### Protocol Oriented Programming

* [Swift Diagram Playgrounds](https://github.com/alskipp/Swift-Diagram-Playgrounds) - Adaptation of the Protocol-Oriented Programming in Swift talk from WWDC 2015. :star:249
* [Swift Protocol Extensions](https://github.com/davidahouse/SwiftProtocolExtensions) - A playground to explore Protocol Extensions. ⏳  :star:19
* [Battleship Example](https://github.com/vichudson1/Battleship-POP-Example) - An example of how to use Protocol Oriented Programming with the battleship game. ⏳  :star:9

### Functional Reactive Programming

* [ReactiveCocoa Playground](https://github.com/nikita-leonov/ReactiveCocoaPlayground) - The easiest way to get a taste of ReactiveCocoa. ⏳  :star:96
* [Swift Reactive Playground](https://github.com/ColinEberhardt/SwiftReactivePlayground) - Companion to the article: ReactiveCocoa made Simple With Swift. ⏳  :star:26


## Apple's Playgrounds
*Playgrounds from Apple, usually presented at some WWDC*

* [Apple's Mandelbrot Playground](https://github.com/palmerc/Mandelbrot-Swift-Playground) - A playground with the mandelbrot fractal (updated to Swift 3 by @palmerc, @kemalenver). :star:12
* [Interactive Newton's Cradle](https://github.com/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) - Apple's interactive playground of a Newton's Cradle where collisions and gravity are applyed with UIKit dynamics. 🌟 (updated to Swift 3 by @p-sun)  :star:5
* [Apple's Balloons Playground](https://developer.apple.com/swift/blog/downloads/Balloons.zip) - The balloons playground showed at WWDC14. ⏳ 
* [Apple's Crustacean Playground](https://developer.apple.com/sample-code/wwdc/2015/downloads/Crustacean.zip) - Protocol-Oriented Programming with Value Types. ⏳ 
* [Apple's Swift Standard Library Playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) - experiment with Swift standard library types and high-level concepts using visualizations and practical examples. ⏳ 

## Playgrounds about Playgrounds
*Playgrounds that describe what you can do with playgrounds*

* [XCTest Playground](https://github.com/Liquidsoul/XCTestPlayground) - Better looking tests for playgrounds. :star:45
* [Interactive Playground](https://github.com/dasdom/InteractivePlayground) - Exploring interactivity in Playgrounds. :star:50
* [Mondrian](https://github.com/timbellay/Mondrian) - Make iOS app mockups in Swift 2.x playgrounds. ⏳  :star:3

## Playgrounds from Playgroundbooks
*Playgrounds derived from iPad Swift Playgroundbooks*

* [iPad Swift Playgrounds](https://github.com/kushtaneja/iPad_Swift_Playgrounds) - The sample playgroundbooks converted to playgrounds. :star:16

## Theoretical Computer Science

* [Logician](https://github.com/mdiep/Logician) - Logic programming in Swift. 🌟 :star:130
* [Function Composition in Swift](https://github.com/ijoshsmith/function-composition-in-swift) - Exploration of function composition in Swift. 🌟 :star:51
* [Functional Debug View](https://github.com/tomquist/DebugView) - Playground to visualize functional programming with graphical sequences. 🍁 🌟 :star:30
* [Swift Adventures in Monad Land](https://github.com/alskipp/Swift-Adventures-In-Monad-Land) - Learn about monads. :star:164
* [Functional Design Patterns](https://github.com/cmvicentehe/FunctionalProgrammingDesignPatterns) - A few functional programming concept and patterns. :star:4
* [OOP with Functions in Swift](https://github.com/iamleeg/OOPInFPInSwift) - Object-Oriented Programming in Functional Programming in Swift. 🍁 :star:57
* [Learn about transducers](https://github.com/mbrandonw/learn-transducers-playground) - A little tutorial that explains transducers. ⏳  :star:79
* [Swift Functors, Applicatives, and Monads in Pictures](https://github.com/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) - Companion to the article: Swift Functors, Applicatves, and Monads in Pictures. ⏳  :star:58
* [Functors in Swift](https://github.com/mokagio/Swift-Functor-Introduction-Playground) - A playground to introduce Functors in Swift, and their practical usage. ⏳  :star:7

### Algorithms and Data Structures
*Algorithms and data structures implemented in Swift*

* [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift with explanations. 🌟 :star:18593
* [Sorting Experiments](https://github.com/adrfer/Sort) - Alluring experiments with sorting algorithms in Swift, sort of. :star:5
* [Visual Binary Trees](https://github.com/akpw/VisualBinaryTrees) - Effortless visualization of arbitrary Binary Trees, along with their pluggable traversal implementations. 🌟 :star:46
* [Julia Fractal Playground](https://github.com/gongzhang/julia-set-playground#julia-set-playground) - A Swift playground that generates beautiful Julia set fractal images.  :star:209
* [A Star](https://github.com/Dev1an/A-Star) - Protocol oriented A* pathfinding algorithm implementation in Swift 4.🍁 :star:14
* [Sorting Algorithms](https://github.com/bwide/Sorting-Algorithms-Playground) - Live Visualization of some famous sorting algorithms and your experiments. :star:1
* [Animated Sorting Algorithms](https://github.com/p-sun/Animated-Sorting-Algorithms) - Swift 4 playgrounds to view and manipulate sorting algorithms.🍁 :star:3
* [Expressions](https://github.com/mpangburn/Expressions) - Arithmetic and logical expressions elegantly modeled and visualized using protocol-oriented binary trees.🍁 :star:387
* [DataStructures Playground](https://github.com/oliverfoggin/DataStructuresPlayground) - Data Structures and Algorithms in Swift. ⏳ :star:14
* [Swiftography](https://github.com/sketchytech/Swiftography) - Standard cryptographic algorithms in a Swift Playground. ⏳ :star:8
* [Algorithms Playground](https://github.com/ashokgelal/AlgorithmsPlayground) - Various algorithm implementation in Swift. ⏳ :star:4
* [The Jelly Bean Problem](https://github.com/kyleweiner/Jelly-Bean-Problem) - The Jelly Bean problem from Wait But Why. ⏳ :star:2
* [Euclidean Strings](https://github.com/modulusMathews/ReEuclid) - A playground leveraging ReSwift to generate Euclidean Strings. ⏳ :star:1

### Languages
*Programming language interpreters implemented in Swift*

* [Introduction to Compilers](https://github.com/ahoppen/introduction-to-compilers) - Great introduction to the inner workings of compilers. 🌟 :star:338
* [Write your own language: Mu](https://github.com/marciok/Mu) - A playground explaining how to create a tiny programming language named Mu. 🌟 :star:1065
* [ASM Swift](https://github.com/NSExceptional/ASM-Swift) - A playground for learning Assembly language through Swift. 🌟 :star:61
* [Let's build a compiler in Swift](https://github.com/mkchoi212/LBAC-Swift) - Let's Build a Compiler by Jack Crenshaw translated to Swift Playgrounds. 🌟  :star:150
* [Pascal interpreter](https://github.com/igorkulman/SwiftPascalInterpreter) - Simple Swift interpreter for the Pascal language inspired by the Let’s Build A Simple Interpreter article series. 🍁 :star:234
* [Register VM](https://github.com/brianhill/register-vm-in-swift) - A register-based VM in a Swift playground. 🌟 ⏳ :star:5
* [Turtle Playground](https://github.com/dimsumthinking/TurtlePlayground) - A playground with Logo-like commands. 🌟 ⏳ :star:125
* [Swift Brainfuck](https://github.com/xavieryao/Swift-Brainfuck) - Brainfuck interpreter written in Swift using Playground. ⏳ :star:8

### Machine Learning

* [Emoji Intelligence](https://github.com/BilalReffas/EmojiIntelligence) - Neural Network built in Apple Playground using Swift. 🌟   :star:1242

## UIKit And Graphics
*A list of playgrounds that demostrate various aspect of UIKit and other graphical frameworks*

* [UIStackView Playground](https://github.com/dasdom/UIStackViewPlayground) - Interesting examples of use of UIStackViews.🌟 :star:301
* [Bezier Path Playgrounds](https://github.com/DigitalLeaves/BezierPathPlaygrounds) - Some playgrounds to better understand UIBezierPaths. :star:24
* [UIKit playground](https://github.com/ralfebert/uikit-playground) - Playgrounds to experiment interactively with UIKit views. :star:40
* [Checkmark Button](https://github.com/BilalReffas/CheckmarkButton) - Animated check mark button. :star:7
* [UIDynamic Playground](https://github.com/andresbrun/UIDynamicsPlayground) - Multiple Playgrounds using almost every behaviour of UIDynamic. :star:5
* [WWDC16 Typography](https://github.com/tototti/wwdc16_typography_playground) 🇯🇵 - Draw a logo or any text with the WWDC16 ASCII texture.  
* [Animated GIF Playground](https://github.com/danielrhammond/GIF-Playground) - Swift playground for generating animated GIFs. :star:1
* [RPClarity](https://github.com/RobotsAndPencils/RPClarity) - Shows a technique for blurring an image behind the characters behind one or more UILabels. ⏳ :star:39
* [Swift Clock](https://github.com/nickoneill/swiftclock) - An animated clock in a swift playground. ⏳ :star:27
* [WatchKit Asset Playground](https://github.com/cwimberger/WatchKitAssetPlayground) - A swift playground for creating awesome animations for your WatchKit Apps. ⏳ :star:5
* [Swift 2.0 Protocol Extension Example](https://github.com/jhurray/Swift2-Protocol-Extension-Example) - Showing how to use Swift2 protocol extensions to render errors in UIViews and UIViewControllers without subclassing or creating classes. ⏳ :star:40
* [Tinting](https://github.com/Jesse-calkin/tinting) - A small playground to demonstrate image tinting in UIKit. ⏳
* [Ray tracing Playground](https://github.com/mhorga/Raytracing) - A playground and a series of articles on ray tracing, see also part [2](https://github.com/mhorga/Raytracing2), [3](https://github.com/mhorga/Raytracing3), [4](https://github.com/mhorga/Raytracing4), [5](https://github.com/mhorga/Raytracing5) 🌟 ⏳ :star:15
* [WWDC16 Logo Playground](https://github.com/krutarth/WWDC16Logo) - Drawing the WWDC16 logo in a playground. ⏳ :star:3

### Core Image

* [Interpolation Playground](https://github.com/FlexMonkey/Interpolation-Playground-) - Playground demonstrating lerp, smooth step, Catcall-Rom and others! ⏳ :star:45
* [CoreImage for Swift Playgrounds](https://github.com/FlexMonkey/CoreImageForSwiftPlaygrounds) - Growing collection of CoreImage playgrounds from the upcoming book "CoreImage For Swift". 🌟 ⏳ :star:65
* [Image Processor](https://github.com/mortenbrudvik/ImageProcessor) - Implementing different image filter algorithms. ⏳ :star:4

### Metal

* [Metalbrot](https://github.com/jtbandes/metalbrot-playground) - Interactive playground that draws the Mandelbrot fractal with Metal. 🌟 :star:74
* [METAL Playground](https://github.com/haawa799/METAL_Playground) - Apple Metal framework playground. 🌟 ⏳ :star:49

### Animations

* [Core Animation Swift Playgrounds](https://github.com/rmirabelli/CoreAnimationSwiftPlaygrounds) - A set of interesting Core Animation playgounds. :star:30
* [UIViewPropertyAnimator Playground](https://github.com/mathewsanders/Scrubber) - Playground demonstrating UIViewPropertyAnimator. :star:25
* [WWDC Crowd Simulator 2017](https://github.com/neilsardesai/WWDC-Crowd-Simulator-2017) - A SpriteKit experiment to simulate the WWDC2017 logo crowd. :star:18
* [Duet-Inspired Trail Effect](https://github.com/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) - How to get a Duet style trailing effect in SpriteKit. :star:17
* [Additive Animations](https://github.com/d-ronnqvist/Additive-Animations-Playground) - Experiment with multiple additive animations in Core Animation. ⏳ :star:31
* [Core Animation Playground](https://github.com/knightsc/CoreAnimationPlayground) - Companion to Apple's Core Animation Programming Guide. ⏳ :star:5

### SpriteKit

* [SpriteKit Swift 3](https://github.com/MacMeDan/SpriteKitCollisions) - Playground for exploring Sprite Kit. :star:6
* [SpriteKit Collisions](https://github.com/jaredmpayne/SpriteKitCollisionsPlayground) - Demonstrates how to perform physics collision detection using Swift and SpriteKit. ⏳ :star:28
* [SceneKit Examples](https://github.com/UCh/swift-scene-kit-playgrounds) - Experiment with SceneKit and Swift. ⏳ :star:14
* [SceneKit ARKit Demo](https://github.com/mhanlon/ARKitDemoPlayground) - The Xcode 9 ARKit SpriteKit demo as a playground.🍁 :star:33
* [Astronomy](https://github.com/cl7/Astronomy) - A 3D earth model written in swift playground using SceneKit. :star:12


## Audio
*Sounds and music*

* [Bach Playground](https://github.com/dreamwieber/BachPlayground) - A Simple Swift Playground that plays a brief piece by Bach with AVAudioEngine and AVMIDIPlayer. :star:2
* [PlayerNode Playground](https://github.com/genedelisa/PlayerNodePlayground) - Playground using AVAudioEngine with a playernode and effects to play an audio file. 🌟 :star:2
* [Miles](https://github.com/LaloMrtnz/Miles) - A Swift Playground that creates jazz improvisations in any key using AudioToolbox and AVFoundation.  :star:16

## Mathematics
*Live math with playgrounds*

* [Lindenmayer Systems](https://github.com/henrinormak/lindenmayer) - A Swift playground exploring Lindemayer systems. :star:6
* [Swift Natural Numbers](https://github.com/jakebromberg/Swift-Natural-Numbers) - A playground for implementing the natural numbers and more concepts in number theory. :star:3
* [Polydoxical](https://github.com/kirkbyo/Polydoxical) - Interactive playground to experiment with roulettes and polygons.
* [Abstract Algebra](https://github.com/taketo1024/SwiftyMath) - Abstract algebra concepts implemented in Swift. :star:121
* [Swift Accelerate](https://github.com/haginile/SwiftAccelerate) - Using the Accelerate framework and Swift for Linear Algebra. ⏳ :star:99
* [Swifty Mathematics](https://github.com/DylanModesitt/swiftyMathematics) - A collection of swift playground about mathematics. ⏳ :star:1
* [Numerical Algorithms](https://www.raywenderlich.com/99559/numeric-algorithms-using-playgrounds) - Numerical argorithms playground from Ray Wenderlich. ⏳
* [Guilloche Pattern Playground Book](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁 :star:7

## Libraries and APIs
*Library tutorials, in a playground*

* [AudioKit Playgrounds](http://audiokit.io/playgrounds/) - 130+ Audio synthesis, processing, playback, and analysis playgrounds with AudioKit.
* [AIToolbox](https://github.com/KevinCoble/AIToolbox/tree/master/Playgrounds) - A set of playgrounds showing machine learning algorithms, all implemented with pieces of the AIToolbox framework code. :star:704
* [Cognitive Service APIs](https://github.com/codePrincess/playgrounds) - Get started with the Microsoft Cognitive Services APIs. :star:45
* [Rx Playground](https://github.com/sgr-ksmt/RxPlayground) - A playground with RxSwift examples. :star:3

## Playground Sets
*Sets of playgrounds about various topics*

* [Public Extensions](https://github.com/Jasdev/Public-Extension) - A set of useful extensions from [@PublicExtension](https://twitter.com/publicextension). 🌟 :star:6
* [Parks And Recreation](https://github.com/zwaldowski/ParksAndRecreation) - Great collection of interesting playgrounds, for fun and for profit. 🌟 :star:156
* [URaimo's Playgrounds](https://github.com/uraimo/Swift-Playgrounds) - My playgrounds, various topics. :star:128
* [ManuelCarlos's Playgrouds](https://github.com/manuelCarlos/Swift-Playgrounds) - Various playgrounds. :star:5
* [Mgrebenets's Playgrounds](https://github.com/mgrebenets/playgrounds) - Various playgrounds.c 🌟 :star:8
* [Cocoa With Love Playgrounds](https://github.com/mattgallagher/CocoaWithLovePlaygrounds) - Playground versions of select articles from Cocoa with Love.  🌟  :star:82
* [Sketchytech's Playgrounds](https://github.com/sketchytech/SwiftPlaygrounds) - Various Playgrounds. 🌟 ⏳ :star:9
* [Swift fun playgrounds](https://github.com/madbat/Swift-fun-playgrounds) - A few playgrounds to showcase Swift peculiar features. ⏳ :star:7
* [BradLarson's Playgrounds](https://github.com/BradLarson/PersonalSwiftPlaygrounds) - Various playgrounds. ⏳ :star:20
* [Dmikusa's Playgrounds](https://github.com/dmikusa/swift_playgrounds) - Playgrounds that show basic Swift, JSON parsing, sending HTTP requests and basic file IO. ⏳ :star:14
* [Cananito's Playgrounds](https://github.com/Cananito/Playgrounds) - Various playgrounds. ⏳ :star:1
* [Uberbruns's Playgrounds](https://github.com/uberbruns/SwiftPlaygrounds) - Various playgrounds. ⏳ :star:4

## Miscellaneous
*What doesn't fit anywhere else, but still awesome*

* [Icon Creator](https://github.com/tnantoka/IconCreator) - Create app icons on Swift playground. :star:21
* [2048 Playground](https://github.com/robin/2048_Playground) - The 2048 game implemented with a playground. :star:31
* [SwiftShell](https://github.com/JustinJiaDev/SwiftShell) - Bash shell in a playground. :star:16
* [LaunchPad Playground](https://github.com/Juniorlimaivd/LaunchPad-Playground) - A playground that simulates a real LaunchPad for making music. :star:5
* [Super Maze](https://github.com/W00dL3cs/Super-Maze) - A programmatic maze generator and solver. :star:6
* [Tic Tac Toe](https://github.com/aabosh/Tic-Tac-Toe) - Tic tac toe in a playground. :star:5
* [Pixel Art Maker](https://github.com/BenEmdon/PixelArtMaker) - A playground where you can make pixel art. :star:48
* [SwiftCoin](https://github.com/Thomvis/Swiftcoin) - A simplistic blockchain & cryptocurrency in a playground. :star:25
* [SentimentlySwift](https://github.com/benbahrenburg/SentimentlySwift) - Sentiment analysis in Swift.  :star:7
* [Rubik's Cube](https://github.com/codelynx/CoreRubiksCube) - Implementing basic model and behavior of Rubic's Cube in Swift. 🍁  :star:9
* [Game Boards](https://github.com/joalbright/Gameboard) - Chess, checkers, tic-tac-toe, sudoku and many others in playground. 🌟 ⏳ :star:165
* [StarWars Seals](https://github.com/jeremyconkin/StarWarsSeals) - Emblems from Star Wars in Swift playgrounds via CoreGraphics and UIViews. ⏳ :star:3
* [SwiftFiles](https://github.com/sketchytech/SwiftFiles) - Save, Load and Delete files easily from within a Swift playground. ⏳ :star:34
* [Earth photos](https://github.com/jtbandes/DSCOVR.playground) - A slideshow of Earth photos taken by DSCOVR/EPIC. 🌟 ⏳ :star:4
* [SwiftChain](https://github.com/gg2001/SwiftChain) - Simple Cryptocurrency in a Swift Playground. :star:5



