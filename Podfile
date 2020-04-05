project 'photo-hut.xcodeproj'
platform :ios, '10.0'

def shared_pods
    pod 'Firebase/Analytics'
    pod 'Firebase/Auth', '6.1.0'
    pod 'Firebase/Firestore', '6.1.0'
    pod 'Firebase/Storage', '6.1.0'
    pod 'Firebase/Functions', '6.1.0'
    pod 'IQKeyboardManagerSwift', '6.0.4'
    pod 'Kingfisher', '~> 4.0'
end

target 'photo-hut' do
  use_frameworks!
  shared_pods
  pod 'Stripe', '15.0.1'
end

target 'photo-hut-admin' do
  use_frameworks!
  shared_pods
end
