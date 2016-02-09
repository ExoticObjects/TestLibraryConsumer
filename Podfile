
platform :ios, '9.0'
use_frameworks!

target :TestLibraryConsumer do

  # build from source - import in AppDelegate compiles fine
  # pod 'TestLibrary', :git => 'https://github.com/ExoticObjects/TestFramework.git'

  # source as local pod
  pod 'TestLibrary', :path => '../TestFramework'

  # build from framework compiled from that source - import in AppDelegate does not compile
  # pod 'TestLibrary', :git => 'https://github.com/ExoticObjects/TestFrameworkCompiled.git'

end





