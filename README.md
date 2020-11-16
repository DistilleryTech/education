![Distillery](https://distillery.com/content/uploads/2018/07/logo.svg)

# Distillery growing course

- [Distillery growing course](#distillery-growing-course)
- [Computer science](#computer-science)
  - [General topics](#general-topics)
  - [Network](#network)
- [Frontend (General)](#frontend-general)
  - [Prerequisites](#prerequisites)
  - [Semantic HTML (Basic)](#semantic-html-basic)
  - [CSS (Basic)](#css-basic)
  - [HTML / CSS tools (Basic)](#html--css-tools-basic)
  - [CSS pre- & post- processors](#css-pre---post--processors)
  - [CSS Architecture](#css-architecture)
  - [Package managers](#package-managers)
  - [CSS Frameworks](#css-frameworks)
  - [Build tools](#build-tools)
  - [JavaScript (ES2018)](#javascript-es2018)
  - [JS Networking](#js-networking)
  - [TypeScript](#typescript)
  - [RxJS](#rxjs)
  - [MobX](#mobx)
- [Frontend - Angular](#frontend---angular)
  - [Angular](#angular)
- [Frontend - React](#frontend---react)
- [Frontend - Vue](#frontend---vue)
- [Mobile - React Native](#mobile---react-native)
  - [React-Native cross-platform [Basic]](#react-native-cross-platform-basic)
  - [React-Native [Intermediate]](#react-native-intermediate)
  - [React-Native [Advanced]](#react-native-advanced)
- [Backend](#backend)
  - [Databases](#databases)
  - [PHP](#php)
    - [Phalcon](#phalcon)
- [Literature](#literature)

# Computer science

## General Topics

- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [Floating point numbers (IEEE-754)](https://www.h-schmidt.net/FloatConverter/IEEE754.html)
- [Hash tables](https://en.wikipedia.org/wiki/Hash_table)
- [Heap as data structure and heap as memory allocation](https://stackoverflow.com/q/1699057)
- [Heap vs stack allocation](https://stackoverflow.com/a/80113)
- [Algorithm complexity / O-notation](https://en.wikipedia.org/wiki/Time_complexity)
- [Quicksort](https://www.tutorialspoint.com/data_structures_algorithms/quick_sort_algorithm.htm)
- ["Event loop" pattern](https://en.wikipedia.org/wiki/Event_loop)
- [Concurrency vs Parallelism](https://stackoverflow.com/q/1050222)
- [Race conditions](https://stackoverflow.com/a/34550)
- [Mutex vs Semaphore](https://www.guru99.com/mutex-vs-semaphore.html)
- [Regular expressions](https://www.regular-expressions.info/unicode.html)

## Network

How modern networks work from developers POV

- IP
- TCP
- UDP
- HTTP
- [HTTP/2](https://http2-explained.haxx.se/en/part1)
- QUIC
- TLS, SSL
- DNS
- NTP

# Frontend (General)

## Prerequisites

Basic development principles, general for any development path

- Data structures and algorithms
- Design patterns
- SOLID, KISS, YAGNI
- Licenses
- Semantic versioning
- Character encodings

## Semantic HTML (Basic)

Basic HTML/Web

- What is "semantics" and why do we need it?
- Document structure
- Head and metadata
- Hyperlinks. A fundament of the Web.
- Block and inline elements
- Headers
- Paragraphs
- Text: emphasis and importance
- Whitespaces in HTML
- Special characters
- Lists
- Nested lists
- Tables
- Multimedia and embedding
- Images
- Video and audio content
- Vector graphics
- Responsive images
- Objects and IFrames
- Forms
  - Label
  - Input (+types)
  - Select
  - Textarea
  - Validation
  - Button

## CSS (Basic)

- Basic syntax
- Selectors
  - Element selectors
  - Class selectors
  - ID selectors
  - Universal selector \*
  - Attribute selectors
  - Combinators and selector list
  - Selector specificity
- Pseudo classes and pseudo-elements
- Layout
  - Floats
  - Positioning
  - Display
  - Box model
  - CSS Grid
  - Flexbox
- CSS values and units
- Cascade and inheritance
- Fonts
- Styling font and text layout
- Styling lists
- Styling links

## HTML / CSS tools (Basic)

- Chrome inspector
- Firefox inspector
- Safari inspector
- HTML validation
- CSS validation

## CSS pre- & post- processors

- SCSS
  - Import - fragments, nested imports, index
  - Mixins, @extend
  - SassScript
- PostCSS
  - Autoprefixer
  - CSSNext
  - PreCSS
  - Stylelint

## CSS Architecture

- Isolation
- Specificity wars
- Garbage collection
- BEM

## Package managers

- Licenses (ref to **Prerequisites**)
- Semantic versioning (ref to **Prerequisites**)
- NPM
  - Dependencies, dev-devependencies
  - Package scope, access level, visibility
  - Publishing
  - Scripts
  - Audit & Security
- Yarn

## CSS Frameworks

- Bootstrap
- Materialize CSS
- Bulma
- Semantic UI

## Build tools

- Task runners
  - NPM scripts
  - Gulp
- Bundlers
  - Webpack
  - Parcel
  - Rollup
- Linters & formaters
  - Prettier
  - ESLint
  - Stylelint
  - TSLint (will be deprecvtaed soon)

## JavaScript (ES2018)

- Grammar and types
- Control flow & error handling
- Loops & iteration
- Functions
  - Arrow functions
- Closures
- Expressions & operators
- Numbers & dates
- Text formatting
- Resular expressions
- Arrays (indexed collections)
- Map, WeakMap, Set (keyed collections)
- Objects, prototypical inheritance
- Promises
  - Async/await syntax
- Iterators & generators
- Meta-programming
  - Handlers & traps
  - Proxy
  - Revocable proxy
  - Reflection
- Strict mode
- Template literals
- Symbols
- Spread operator, rest parameters
- Shared memory, ArrayBuffer, TypedObject
- Eventloop

## JS Networking

- XHR
  - CORS
- WebSockets

## TypeScript

- Basic types
- Variable declarations
- Interfaces
- Classes
- Functions
- Generics
- Enums
- Type inference
- Type compatibility
- Advanced types
  - Intersection of types
  - Union types
  - Type guards
  - String literal types
  - Index types
  - Mapped types
  - Conditional types
    - Exclude<T, U>
    - Extract<T, U>
    - NonNullable<T>
    - ReturnType<T>
    - InstanceType<T>
- Symbols
- Iterators & generators
- Modules
  - Module resolution
- Namespaces
- Declaration merging
- JSX / TSX
- Decorators
- Mixins
- Publishing

## RxJS

- Observables
  - Hot
  - Cold
- Operators
  - Combination
  - Conditional
  - Creation
  - Error handling
  - Multicasting
  - Filtering
  - Transformation
  - Utility
- Subjects
  - AsyncSubject
  - BehaviorSubject
  - ReplaySubject
  - Subject

## MobX

- Concepts and Principles
- Decorators
- Observable
  - Objects
  - Arrays
  - Maps
  - Boxed Values
- Observers
- Reactions
  - Autorun
  - When
  - Reaction
- Actions
  - Synchronous
  - Asynchronous
- Computed Values
- Mobx React Devtools

![Angular](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/250px-Angular_full_color_logo.svg.png)

# Frontend - Angular

## Angular

- CLI - Command line interface
- Schematics
- Modules
  - JS modules vs Angular modules
  - Feature modules
    - Domain feature modules
    - Routed feature modules
    - Routing modules
    - Service feature modules
    - Widget feature modules
  - Entry components
  - Declarations
  - Providers
  - Lazy loading feature modules
  - Sharing modules
- Components
- Services and DI
  - Hierarchical dependency injectors
  - DI providers
  - Singleton services
- Templates
  - Template syntax
  - Lifecycle hooks
  - User input
  - Component interaction
  - Component styles
  - Angular components (Custom elements)
  - Dynamic components
    - Factories
    - Outlets
- Attribute directives
- Structural directives
- Pipes
- Forms
  - Reactive forms
  - Dynamic forms
  - Template-driven forms
  - Validation
- Observables in Angular
- HTTPClient
- Routing & Navigation
- Animations
- Bootstraping
- Internalization
- Angular libraries
- Server-side rendering
- Service workers & PWA
- Security
  - XSS
  - CSRF
  - XSSI
- AOT (Ahead of time) compilation
- Testing

![React](https://miro.medium.com/max/480/1*To2H39eauxaeYxYMtV1afQ.png)

# Frontend - React

- Project Scaffolding
  - create-react-app
  - nextjs
- React Developer Tools
- JSX
- Components
  - State and Props
  - Lifecycle
- Events
  - Handling Events
  - Syntetic Events
- Forms
  - Controlled and Uncontrolled Components
  - Forms Validation
- Refs
- Rendering
  - Conditional Rendering
  - Preventing from Rendering
- Higher Order Components
- Context API
- React Hooks
  - State Hook
  - Effect Hook
  - Rules of Hooks
- Portals
- Accessibility
- Animations
- Internationalization
- Optimizing Performance
- List and Keys
- Static Type Checking
- SSR - Server Side Rendering
  - nextJS
- Reconciliation
- Fiber API
- Scheduling
- Testing
- Service Workers & PWA
- Security
  - XSS
  - CSRF
  - XSS

# Frontend - Vue

# Mobile - React Native

## React-Native cross-platform [Basic]

- Project scaffolding
  - CRNA (create-react-native-app)
  - Expo SDK
  - Adding TypeScript to CRNA app
- Basic React usage (see [Frontend - React](#frontend---react))
- React Context API
- Styles & Stylesheet
- Flexbox layout
- Networking
  - XHR
  - Fetch API
  - WebSocket support
- Storages
  - AsyncStorage
- Components
  - Text
  - Text input
  - Button
  - Touchables
  - Gesture responder
  - ScrollView
  - List views
    - Flat list
    - Section list
    - Virtualized list
    - Swipeable list view
  - Image
    - Static resources
    - Network resources
    - URI Data images
    - Cache control (iOs)
    - Background image (via Nesting)
  - Picker
  - Slider
  - Switch
  - ActivityIndicator
  - Alert
  - Animated
  - CameraRoll
  - Clipboard
  - Dimensions
  - KeyboardAvoidingView
  - Linking
  - Modal
  - PixelRatio
  - RefreshControl
  - StatusBar
  - WebView
- Animations
- Accessibility
- Navigation
- Timers
- Running
  - on iOS simulator
  - on iOS device
  - on Android simulator
  - on Android device
- Debugging
- Performance profiling
- App publishing

## React-Native [Intermediate]

- iOs-specific components
  - ActionSheetIOS
  - AlertIOS
  - DatePickerIOS
  - ImagePickerIOS
  - NavigatorIOS
  - ProgressViewIOS
  - PushNotificationIOS
  - SegmentedContolIOS
  - TabBarIOS
- Android-specific components
  - BackHandler
  - DatePickerAndroid
  - DrawerLayoutAndroid
  - PermissionsAndroid
  - ProgressBarAndroid
  - TimePickerAndroid
  - ToastAndroid
  - ToolbarAndroid
  - ViewPagerAndroid
- Expo SDK (most used components)
  - AppAuth
  - AppLoading
  - Asset
  - Audio
  - AuthSession
  - AV
  - BackgroundFetch
  - Calendar
  - Camera
  - Contacts
  - DocumentPicker
  - FileSystem
  - Font
  - GestureHandler
  - ImagePicker
  - IntentLauncherAndroid
  - KeepAwake
  - LinearGradient
  - Linking
  - Location
  - MapView
  - MediaLibrary
  - Notifications
  - Payments
  - Permissions
  - SecureStore
  - Sensors
  - SMS
  - SplashScreen
  - Svg
  - TaskManager
  - Updates
  - Video
  - WebBrowser

## React-Native [Advanced]

- Integration with Existing Apps
- Creating native modules
  - iOS
  - Android
- Communication between native and React Native
- Using Jest for JS test
- Using Detox for iOs
- Using Appium
- Working with stack trace

# .Net

## .Net Roadmap next years

![Roadmap .Net](https://user-images.githubusercontent.com/50750161/99021253-e58a5d00-2525-11eb-89d3-3831403ee316.png "Roadmap for next years")


## CLR

- Assemblies
- CLR
- IL
- The Common Type System (CTS)
- The Framework Class Library (FCL)
- The Common Language Specification (CLS)

## Command Line Interface (CLI)

- dotnet command
  -   add
  -   build
  -   build-server
  -   clean
  -   help
  -   list
  -   msbuild
  -   new
  -   nuget
  -   pack
  -   publish
  -   remove
  -   restore
  -   run
  -   sln
  -   store
  -   test
  -   tool
  -   vstest

## Designing Types

- Fundamentals
  - System.Object
  - Types casting
  - Namespaces and assemblies
- Reference and ValueTypes
  - Reference Types
  - Value Types
  - Boxing and Unboxing
  - Object HashCode
  - Dynamic
- Types and Members kinds
  - Visibility
  - Accessability
  - Static
  - Partial classes
  - Polymorphism
    - Virtual Methods
    - Overriding
    - Overloading
- Constants and Fields
- Methods
  - Instance Constructors and Classes (Reference Typse)
  - Instance Constructors and Structures (Value Types)
  - Type constructors
    - Type Consstructor Performance
  - Extensions methods
  - Partial Methods
- Parameters
  - Optional and Named
  - Implicitly Typed Local Variable
  - Passging parameter by Reference
  - Passing a Variable Number of Arguments
  - Parameter and Return Type Guidelines
- Properties
  - The performance of calling Porperty Accessor Methods
- Generics
- Interfaces
- Logging during development and runtime execution
- Unit testing

## Essential Types

- Chars, Strings and Working with Text.
  - System.String
  - StringBuilder

## Core Facilities

- Exceptions
- GC

## Threading

- CLR Thread and Windows Threads
- CLR's Thread Pool
- Execution Contexts
- Tasks
- Thread Synchronization Constructs
  - Mutex
  - Interlocked
  - ManualRestEventSlim, SemaphoreSlim
  - Monitor
  - ReaderWriterLockSlim

## Working with Files, Streams, and Serialization

- Managing the filesytem
- Reading and writing with streams
- Encoding and decoding text

## Protecting Data and Applications

- Encrypting and decrypting data
- Hashing data
- Signing data
- Generating random numbers
- Implementing Authentication and authorization

## Entity Framework

- Setting up EF 
- Defining EF models
- Querying EF models
- Loading patterns with EF
- Manipulating data with EF
- Creating application Log to get executed queries

## Querying and Manipulating Data using Linq

- Writing LINQ queries
- Using LINQ with EF 
- Using multiple threads with parallel LINQ

## Practical Applications of C# and .NET

- Building Nuget packages
- Building Websites using ASP.NET Core Razor
- Building Websites using the Model-View-Controller Pattern
- Building Websites using a Content Management
- Building and Consuming Web Services
- Building Intelligent Apps using Machine Learning
- Building Windows Desktop Apps
- Building Cross-Platform Mobile Apps Using Xamarin
- Building IoT with .NET
- Deploying Websites using Docker
  - Deploying projects using TYE Project (https://github.com/dotnet/tye) 
# Backend

## Databases

- [ACID](https://en.wikipedia.org/wiki/ACID)
- [CAP theorem](https://en.wikipedia.org/wiki/CAP_theorem)
- [DATE/DATETIME/TIMESTAMP in MySQL](https://dev.mysql.com/doc/refman/8.0/en/datetime.html)
- [B-Tree vs Hash in MySQL](https://dev.mysql.com/doc/refman/8.0/en/index-btree-hash.html)
- [Index types in PostgreSQL](https://www.postgresql.org/docs/13/indexes-types.html)
- [`EXPLAIN` in MySQL](https://dev.mysql.com/doc/refman/8.0/en/explain-output.html)
- [`EXPLAIN` in PostgreSQL](https://www.postgresql.org/docs/13/using-explain.html)
- [Deadlock vs Wait timeout](https://stackoverflow.com/a/16564450) (DO NOT TRUST [THIS](https://orangematter.solarwinds.com/2018/09/12/the-difference-between-lock-wait-timeout-and-deadlock/) ARTICLE, IT'S MISLEADING)

## PHP

- [PHP 8 changelog](https://stitcher.io/blog/new-in-php-8)
- [PSR-12](https://www.php-fig.org/psr/psr-12/)
- [Types](https://www.php.net/manual/en/language.types.intro.php)
- [getopt](https://www.php.net/manual/ru/function.getopt.php)
- [Callable](https://www.php.net/manual/en/language.types.callable.php)
- [Threading](https://www.php.net/manual/en/class.thread.php)
- [Output buffering control](https://www.php.net/manual/en/book.outcontrol.php)
- [APCu](https://www.php.net/manual/en/book.apcu.php)
- [PDO](https://www.php.net/manual/ru/book.pdo)
- [`declare ticks`](https://www.php.net/manual/en/control-structures.declare.php#control-structures.declare.ticks)
- [zval](https://www.php.net/manual/ru/internals2.variables.intro.php)
- [Profiling using xhprof](https://github.com/patrickallaert/xhprof)

### Phalcon

- [Tutorial](https://docs.phalcon.io/4.0/en/tutorial-basic)

# Literature

- ["Structured Computer Organization"](https://www.amazon.com/Structured-Computer-Organization-Andrew-Tanenbaum/dp/0132916525) by Andrew Tanenbaum
- ["Refactoring"](https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599) by Martin Fowler
