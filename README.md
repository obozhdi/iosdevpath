# Novice

 * Common
    * Use and understand basic types like Bool, Int, String, and Double
    * Declare and use variables and constants
    * Handle flow control and looping constructs
    * Create and use collections
    * Develop and use simple functions
    * Cast objects safely from one type to another

* Swift
    * Handle optionals from APIs and unwrap them safely

* ObjC
    * Use and understand Objective-C's basic data types
    * Create and use collections(NSArray, NSSet, NSDictionary, etc)
    * Understand the different between mutable and immutable and how that applies to collections.

* UI
    * Create a simple user interface with Interface Builder
    * Center views vertically and horizontally using Auto Layout
    * Create a view that fills the screen using Auto Layout
    * Connect views from Interface Builder to code
    * Connect actions from Interface Builder to code to handle taps on controls
    * Handle and respond to taps from the user
    * Customize view properties in Interface Builder
    * Change text on a label programmatically when an action is performed

* iOS
    * Display a static table of data
    * Show an alert when an action is performed
    * Understand the view controller lifecycle
    * Know how to find and read the official documentation
    * Read about delegates and understand its use before moving on to the next level(if you are building a static table of data then you have already seen delegation at work!)

* Challenges
    * Write an app that has a label with white text centered vertically and horizontally on a black background. When the user taps a button, the text in the label should change.
    * Write an app that displays a static list of items in a table view


# Beginner

* Common
    * Work effectively with properties
    * Develop and use functions with external parameter names
    * Create and use custom model objects

* Swift
    * Create closures and use them effectively
    * Handle optionals from APIs and unwrap them safely

* ObjC
    * Use and understand Objective-C's basic data types
    * Create and use collections(NSArray, NSSet, NSDictionary, etc)
    * Understand the different between mutable and immutable and how that applies to collections.

* UI
    * Set up text input fields and show and hide the keyboard as appropriate
    * Place views relative to their superview using Auto Layout
    * Create a more complex user interface with multiple views in Interface Builder
    * Create segues in Interface Builder to move between view controllers
    * Understand how to include assets for various screen densities (1x, 2x, 3x)

* iOS
    * Understand and use the delegate pattern
    * Display a dynamic table of data
    * Display editable tables of data
    * Understand the app lifecycle
    * Store and fetch user preferences on device using NSUserDefaults
    * Store and fetch data on device using NSUserDefaults
    * Read data from a plist
    * Transition between different views
    * Pass data from one view controller to the next during a transition (without using segues, that comes later!)
    * Read and understand about protocols and how to set up your own custom methods in the protocol definition. (This will be used for the next level!)

* Challenges
    * Read data from a plist and store that in your table.
    * Write a master-detail app that displays a list of items based on user input from from multiple text fields on a different view. Each item should represent a model object that you have created. The list of items grow as the user enters additional data. The user should also be able to delete items from the table as requested. As you add each item to the table, save it to the device using NSUserDefaults. When you are done adding items you should be able to close the app and then use NSUserDefaults to load in the data that you had added before. 

# intermediate

* Common
    * Create and conform to protocols to develop a blueprint of functionality
    * Understand and use pattern matching in switch statements
    * Understand the similarities and differences between enums, structs, and classes and when to use each
    * Create and format date objects
    * Create and format time objects

* Swift
    * Understand Swift initializer pattern

* ObjC
    * Understand Objictive-C initializer pattern

* UI
    * Add views and constraints to user interfaces in code
    * Create a custom UIView subclass and use it in Interface Builder
    * Lay out custom table view cells
    * Create custom segues between view controllers
    * Use segues programmatically to move between view controllers
    * Place views relative to sibling views using Auto Layout
    * Resize views based on device size using Auto Layout
    * Set a view's aspect ratio with Auto Layout
    * Understand and use inequality constraints
    * Understand and apply constraint priorities to ensure views are precisely the size they need to be
    * Understand compression resistance and content hugging
    * Size views properly using compression resistance and content hugging
    * Use Auto Layout with a scroll view to display content that doesn't fit on a single screen
    * Use appearance proxies to customize app appearance

* iOS
    * Understand ARC and manage memory properly to prevent memory leaks and retain cycles
    * Create and use a custom delegate protocol
    * Define functions that use blocks to communicate between loosely coupled objects
    * Place views a specified number of points from their superview using Auto Layout
    * Store and fetch data on device using Core Data
    * Debug apps by setting breakpoints and viewing runtime values
    * Write automated tests for the model layer
    * Access the user's photos and camera
    * Use local notifications to alert the user at a specific time
    * Display a map interface with a custom zoom level and current location
    * Pull data from a REST web service for use in an app
    * Parse JSON by serializing and deserializing it into model objects
    * Implement a basic Collection View with supplementary and Decoration Views

* Challenges
    * Write a todo app that allows the user to add and delete items from a list and stores them on device using Core Data. The user should be able to set due dates that are formatted and displayed with each item. A local notification should remind the user about the task on the specified due date.
    * Write an app that can access the user's photos and use the camera to take new photos for use within the app.
    * Write a master-detail app that displays a list of items from a web service and, when an item is tapped, shows detail about the item

# advanced

* Common
    * Develop and use functions with variadic parameters
    * Create and use generators and sequences

* Swift
    * Develop and use functions with closure parameters
    * Develop and use functions with generics
    * Detect and report problems in Swift and post them to Open Radar
    * Implement Swift's functional patterns
    * Use Swift effectively with Objective-C and vice versa
    * Use extensions to extend Swift's standard functionality

* ObjC
    * Use Objective-C effectively with Swift and vice versa
* UI
    * Space views evenly across the screen using spacer views (iOS 8) or stack views (iOS 9+)
    * Understand and use constraint priorities
    * Properly configure your user interface to handle multiple device sizes and orientations
    * Animate views by modifying layout constraints
    * Import and use custom fonts
    * Draw with UIKit
* iOS
    * Use KVO to communicate between loosely coupled objects
    * Use Notification Center to communicate between loosely coupled objects
    * Cache data from a web service for increased performance
    * Know when to use composition over inheritance
    * Swap out different interfaces (views) with animation
    * Download files in the background
    * Handle warnings from the device so apps don't get shut down
    * Handle and respond to multi-touch events
    * Link objects with dependencies in Core Data
    * Import data into Core Data
    * Build animated and user-driven transitions between view controllers
    * Improve app performance by performing work concurrently with NSOperationQueue and Grand Central Dispatch
    * Authenticate with a web service using OAuth 2
    * Make apps accessible to more users using the Accessibility APIs
    * Understand code written in Objective-C
    * Write automated tests for the controller layer using mocks and stubs as needed - (i.e., XCTest)
    * Detect and report problems in iOS frameworks and post them to Open Radar
    * Use push notifications to alert the user about events in your app
    * Understand TouchID and implement this feature in your app (iPhone5s+ devices) instead of a log in screen
    * Understand and implement Advanced Collection View Techniques (Custom Collection View Layouts, animating Collection Views using UIKit Dynamics)
* Challenges
    * Write an app that has several screens with relatively complex layouts. It should read and send data to a web service using OAuth 2 and store data in Core Data. It should also animate views based on user interaction and have a full suite of automated tests for the model and controller layers. Code should be structured well and be easy to reason about.

# expert

* Common
    * 1111

* Swift
    * Understand and use operator overloading effectively
    * Increase performance in Swift with compiler optimization techniques such as memoization
    * Understand the internals of the Swift compiler and runtime
* ObjC
    * 1111
* UI
    * Create a UI that shows and hides views dynamically based on data from a web service
* iOS
    * Apply delegate, blocks, notification, and KVO patterns properly
    * Create custom table view cells that resize dynamically using Auto Layout
    * Localize apps for international use
    * Store credentials securely using the keychain
    * Master Xcode’s performance-tuning Instruments, including CPU Profiler, Leaks and Zombies
    * Handle concurrency, caching, migrations, undo, and performance tuning with Core Data
    * Create app extensions
    * Know which pieces of the app will benefit from automated testing - and which ones won't - and write automated tests for the pieces that will benefit
    * Understand and address the challenges of collaborating on Storyboards
    * Create custom frameworks to share functionality between apps
    * Know when to use built-in frameworks, when to use third-party frameworks, and when to build your own
    * Architect large apps with multiple sources of data and interfaces
    * Use design patterns appropriately to manage a large code base
    * Build and maintain multiple apps that share a single code base
    * Know how to write and maintain code in Objective-C

* Challenges
    * Write an app with a complex UI that adjusts dynamically based on data from a web service as well as device size and orientation. The app should have a large number of screens, send and receive data from multiple web services using OAuth 2, store data in Core Data, use iOS 8 extensions, be localized for multiple regions, and perfom excellently. And it should be usable offline, queing web requests where appropriate to be sent when the connection is restored.
    * You're an expert. You can do anything you need to do in iOS, and you can do it beautifully, simply, and consistently. You can and *do* create your own challenges. :-)
