
# Flash-Chat

## Podfile Configuration
```
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
```


## My Goal

Getting to grips with Table Views, creating custom cells, and making my own cloud-based backend database w Firebase


## What I learned

* How to integrate third party libraries in your app.
* How to store data in the cloud using Firebase.
* How to query the Firebase database.
* How to use Firebase for user authentication.
* How to work with a UITableView.
* How to use custom cells in a Table View.
* How to embed View Controllers in a Navigation Controller and understanding the navigation stack.
* How to create Segues for navigation.
* How to make custom .xib files to modify native design components.
* Using Grand Central Dispatch to queue asynchronous tasks.
