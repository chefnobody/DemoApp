source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '13.0'

use_frameworks!

target 'DemoApp' do
end

target 'First' do
  target 'FirstTests' do
    inherit! :search_paths
  end  
end

target 'Second' do
  pod 'SwiftDate', '6.3.1'

  target 'SecondTests' do
    inherit! :search_paths
  end  
end