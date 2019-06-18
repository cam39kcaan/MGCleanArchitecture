platform :ios, '10.0'

def pods
    # Clean Architecture
    pod 'MGArchitecture', '~> 0.5'
    pod 'MGAPIService', '~> 0.7'
    pod 'MGLoadMore', '~> 0.4'
    
    # Rx
    pod 'NSObject+Rx', '~> 5.0'
    pod 'RxDataSources', '~> 4.0'
    
    # Core
    pod 'ObjectMapper', '~> 3.5'
    pod 'Reusable', '~> 4.1'
    pod 'Then', '~> 2.4'
    pod 'MJRefresh', '~> 3.2'
    pod 'Validator', '~> 3.1.1'
    
    # Core Data
    pod 'MagicalRecord', '~> 2.3'
    
    #
    pod 'MBProgressHUD', '~> 1.1'
    pod 'SDWebImage', '5.0'
    pod 'ActionSheetPicker-3.0', '2.3'
    pod 'Nuke', '~> 7.6'
end

def test_pods
    pod 'RxBlocking', '~> 5.0'
    pod 'Mockingjay', :git => 'https://github.com/anhnc55/Mockingjay.git', :branch => 'swift_5'
end

target 'CleanArchitecture' do
  use_frameworks!
  inhibit_all_warnings!
  pods

  target 'CleanArchitectureTests' do
    inherit! :search_paths
    test_pods	
  end

end
