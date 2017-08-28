# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'React' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Pods for React

  target 'ReactTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'ReactUITests' do
    inherit! :search_paths
    # Pods for testing
  end

pod 'React', :path => './ReactComponents/node_modules/react-native', :subspecs => [
    'Core',
    'RCTText',
    'RCTNetwork',
    'RCTWebSocket', # needed for debugging
    # Add any other subspecs you want to use in your project
  ]
  # Explicitly include Yoga if you are using RN >= 0.42.0

end
