
platform :ios, '9.0'
use_frameworks!

target :TestLibraryConsumer do

  # build from source - import in AppDelegate compiles fine
  # pod 'TestLibrary', :git => 'https://github.com/ExoticObjects/TestFramework.git'

  # source as local pod
  # pod 'TestLibrary', :path => '../TestFramework'

  # build from framework compiled from that source - import in AppDelegate compiles now!
  # The (known) issue is that the podspec generated by the packager doesn't include frameworks
  # used in dependencies. See here: https://github.com/CocoaPods/cocoapods-packager/issues/67
  pod 'TestLibrary', :git => 'https://github.com/ExoticObjects/TestFrameworkCompiled.git'

end





