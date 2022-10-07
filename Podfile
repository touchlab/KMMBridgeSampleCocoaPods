platform :ios, '13'

source 'https://github.com/touchlab/PublicPodspecs.git'

target 'KMMBridgeSampleCocoaPods' do
  if ENV.include?("LOCAL_KOTLIN_PATH")
    pod 'shared', :path => ENV["LOCAL_KOTLIN_PATH"]
  else
    pod 'shared', '~> 0.5.0'
  end
end
