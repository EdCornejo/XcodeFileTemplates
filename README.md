# XcodeFileTemplates
A few custom Top-Comment  Xcode file templates 

## Example

### Before
```objective-c

//
//  ___FILENAME___
//  ___PROJECTNAME___
//
//  Created by ___FULLUSERNAME___ on ___DATE___.
//___COPYRIGHT___
//

```

### Now
```objective-c

/**
 *  ___FILENAME___ 
 *  ___PROJECTNAME___
 *
 *  Created by ___FULLUSERNAME___ on ___DATE___.
 *
 *  每位工程师都有保持代码优雅的义务.
 *  Each engineer has a duty to keep the code elegant.
 */

```


## Installation

Copy all of the xctemplate folders into the install directory.
~/Library/Developer/Xcode/Templates/File\ Templates/"$folderName"

```objective-c
./setup.sh folderName
```
