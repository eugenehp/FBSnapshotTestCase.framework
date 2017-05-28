# FBSnapshotTestCase.framework

Binaries that allow to prevent `x86_64` mismatch:

```
2017-05-28 09:13:53.318 XCTRunner[74941:8039620] Running tests...
2017-05-28 09:13:53.346 XCTRunner[74941:8039620] The bundle “StagingUITests” couldn’t be loaded because it is damaged or missing necessary resources. Try reinstalling the bundle.
2017-05-28 09:13:53.346 XCTRunner[74941:8039620] (dlopen_preflight(/Users/user/Library/Developer/Xcode/DerivedData/APP-cqopmrtpghfcazaoxnnscwqnmgzg/Build/Products/Debug-iphonesimulator/StagingUITests-Runner.app/PlugIns/StagingUITests.xctest/StagingUITests): Library not loaded: @rpath/libswiftCore.dylib
  Referenced from: /Users/user/Library/Developer/Xcode/DerivedData/APP-cqopmrtpghfcazaoxnnscwqnmgzg/Build/Products/Debug-iphonesimulator/StagingUITests-Runner.app/PlugIns/StagingUITests.xctest/Frameworks/FBSnapshotTestCase.framework/FBSnapshotTestCase
  Reason: no suitable image found.  Did find:
	/Users/user/Library/Developer/Xcode/DerivedData/APP-cqopmrtpghfcazaoxnnscwqnmgzg/Build/Products/Debug-iphonesimulator/StagingUITests-Runner.app/PlugIns/StagingUITests.xctest/Frameworks/FBSnapshotTestCase.framework/Frameworks/libswiftCore.dylib: no matching architecture in universal wrapper)

```
