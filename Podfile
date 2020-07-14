# Uncomment the next line to define a global platform for your project
plugin "cocoapods-mPaaS", :show_all_specs => true
mPaaS_baseline '10.1.68'  # 请将 x.x.x 替换成真实基线版本
mPaaS_version_code 11   # This line is maintained by MPaaS plugin automatically. Please don't modify.
platform :ios, '9.0'
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/wittech/libqimkit-ios-cook.git'
source "https://code.aliyun.com/mpaas-public/podspecs.git"

target 'QIMGeneralModule' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  pod 'QIMCommon'
  pod 'QIMKitVendor'
  pod 'QIMDataBase'
  pod 'QIMCommonCategories'

#  pod 'SocketRocket'
#  pod 'SCLAlertView-Objective-C'
#  pod 'GoogleWebRTC'
#  pod 'Masonry'

  #SocketRocket版本过低，最新的已经采用SocketCraft替代
  pod 'SocketCraft'
  pod 'SCLAlertView-Objective-C'
  pod 'GoogleWebRTC'
  pod 'Masonry'

  #通用UI
  mPaaS_pod "mPaaS_CommonUI"
  pod 'APOpenSSL'

end
