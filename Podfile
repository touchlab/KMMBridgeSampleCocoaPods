# Uncomment the next line to define a global platform for your project
platform :ios, '13'

target 'KMMBridgeSampleCocoaPods' do
  if ENV.include?("LOCAL_KOTLIN_PATH")
    pod 'shared', :path => ENV["LOCAL_KOTLIN_PATH"]
  else
    pod 'shared', '0.2.1'
  end
end

# Make sure to add the touchlab pod repo with 'pod repo add touchlab <ssh/https podspec repo url>`
if ENV.include?("CP_HOME_DIR")
  source ENV["CP_HOME_DIR"] + '/repos/touchlab'
else
  source ENV["HOME"] + '/.cocoapods/repos/touchlab'
end
