# CocoaPods Nomenclature
A list of terms used in the [CocoaPods](https://github.com/CocoaPods/CocoaPods) context.

## Glossary

### Aggregate Target
The target generated to aide the integration of the Pod targets with the user targets, prefixed with `Pods-`. Example: `Pods-MyApp.framework`

### App Spec
A Subspec which describes the details for creating an Application target, rather than a library or test target.

### Build
A package generated after the code in your project has been compiled.

### Bundle
A bundle is a directory with a standardized hierarchical structure that holds executable code and the resources used by that code.

### CocoaPods
CocoaPods is a dependency manager for Swift and Objective-C Cocoa projects.

### Dependency
A file that is required by the project to execute a task.

### Dynamically Linked
When you Dynamically Link a file, a pointer to the file being linked in (the file name of the file, for example) is included in the executable and the contents of said file are not included at link time. It's only when you later run the executable that these dynamically linked files are brought in and they're only brought into the in-memory copy of the executable, not the one on disk.

### Existing Xcode Project
A subproject used directly to build a spec.

### Framework
A framework is a bundle that contains shared libraries as well as sub directories of headers and other resources.

### Library
Library is a packaged collection of executable object files that a program can link against.

### Header
The Header is a file that holds function declarations and macro definitions to be shared between several source files.

### Native Target
The `PBXNativeTarget` Xcode / Xcodeproj build artifact, which could be an application, a framework, or a static library, or any other target type supported by Xcode.

### Pod
An organized directory that manages the files to be used in a project along with its dependencies.

### Podfile
The Podfile is a specification that describes the dependencies of the targets of one or more Xcode projects.

### Repo
A virtual space where your code is stored.

### Shared Library
A Shared Library is a Library that is not copied into the project, instead, it is referenced by the project.

### Static Framework
A `.framework` bundle which wraps a statically linked library. Similar to a Static Library, but wrapped within the structure of a `.framework`

### Static Library
A Static Library is a Library that statically linked into the build.

### Statically Linked
When you statically link a file into an executable, the contents of the file are physically inserted into the executable that you will run.

### Spec
A specification describes a version of Pod library. It includes details about where the source should be fetched from, what files to use, the build settings to apply, and other general metadata such as its name, version, and description.

### Subproject
A Subproject is an Xcode Project embedded into another Xcode project's tree.

### Subspec
Represents specification for a module within the library.

### Target
A target specifies a product to build and contains the instructions for building the product from a set of files in a project or workspace.

### Test Spec
A Subspec which defines a test bundle meant for testing the library in which it is defined.

### Trunk
The CocoaPods Trunk is an authentication and CocoaPods API service used for the distribution of public pods.

### User target
The target being integrated (part of the user's project outside of CocoaPods).

### Workspace
A workspace is an Xcode document that groups projects and other documents so you can work on them together.

### Xcode
Xcode is an integrated development environment for macOS containing a suite of software development tools developed by Apple for developing software for macOS, iOS, watchOS and tvOS.

### Xcodeproj File
The Xcodeproj File is a file generated by Xcode that contains contains project configuration, data, and links to files referenced by the project.
