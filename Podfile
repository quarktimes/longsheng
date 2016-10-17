# Uncomment this line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, ‘8.0’
use_frameworks!
    target 'Longsheng' do
        
pod 'Kingfisher'
pod 'AFNetworking', '~> 3.1.0'
pod 'R.swift'
pod 'RongCloudIMKit'
pod 'IQKeyboardManagerSwift'
pod 'SwiftyJSON'
pod 'PKHUD', :git => 'https://github.com/toyship/PKHUD.git'
#
#pod 'Alamofire',
#:git => 'https://github.com/Homely/Alamofire.git',
#:branch => 'ios8'

pod 'SnapKit', :git => 'https://github.com/SnapKit/SnapKit', :branch => 'feature/0.40.0'

	end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end
