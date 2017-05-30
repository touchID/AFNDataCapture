# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'AFNDataCapture' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Pods for AFNDataCapture
#platform :ios, '8.2'

#Swift
use_frameworks!
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.1'
        end
    end
end

inhibit_all_warnings! 

pod 'Masonry'
pod 'AFNetworking'
pod 'YYModel'
pod 'SDWebImage'
pod 'FMDB'
pod 'ReactiveCocoa'
pod 'Addition', '~>0.1.5'

pod 'JGProgressHUD'  #HUD(透明指示层)
pod 'skpsmtpmessage' #发送邮件
#pod 'AMap3DMap','~> 4.1.0' #可模拟器调试
pod 'MJRefresh' #下拉刷新
pod 'SDCycleScrollView' #图片轮播器 
end
