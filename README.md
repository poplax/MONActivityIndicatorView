# MONActivityIndicatorView

MONActivityIndicatorView is an awesome custom activity indicator view for iOS.

## Installation

### Manual Install
* Copy and add the files `MONActivityIndicatorView.h` and `MONActivityIndicatorView.m` to your project.
* Add the **QuartzCore** framework to your project.
* Then do, `import MONActivityIndicatorView.h`

### From CocoaPods
* Add `pod 'MONActivityIndicatorView'` to your Podfile.
* Then `pod install` in the terminal.

## Usage

### Initialization
``` objective-c
- (void)viewDidLoad {
  MONActivityIndicatorView *indicatorView = [[MONActivityIndicatorView alloc] init];
  [self.view addSubview:indicatorView];
}
```

### Starting and Stopping the Indicator
``` objective-c
[indicatorView startAnimating];
[indicatorView stopAnimating];
```


## Customization



