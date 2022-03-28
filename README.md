# YYSPecPods
个人私有的pod 库

#lint
pod lib lint --no-clean --sources=https://gitlab.infra.bitmart.com/ios-componentions/Specs.git,https://github.com/CocoaPods/Specs.git --allow-warnings --verbose --use-libraries

#push
pod repo push bitmartpods $sdk_name.podspec --use-libraries --verbose --allow-warnings --sources="https://github.com/CocoaPods/Specs.git,https://gitlab.infra.bitmart.com/ios-componentions/Specs.git"
