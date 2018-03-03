
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, ‘9.0’
use_frameworks!
target “Jipicar” do
    pod 'Socket.IO-Client-Swift', '~> 11.1.3’
    pod 'GoogleMaps'
    pod 'Canvas'
    pod 'AFNetworking'
    pod 'SwiftyJSON'
    
    post_install do |installer|
        installer.pods_project.targets.each do |target|
            target.build_configurations.each do |config|
                config.build_settings['SWIFT_VERSION'] = '3.0'
            end
        end
    end
    
end