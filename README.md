
# CHDropDownTextField

A custom text field with drop-down support.

![CHDropDownTextField](https://github.com/chaione/CHDropDownTextField/raw/master/Misc/screenshot01.png)

## Installation

### CocoaPods

CHDropDownTextField is available through [CocoaPods](http://cocoapods.org), to install it simply add the following line to your Podfile:

`pod "CHDropDownTextField"`

### Manually

To install manually, just copy everything in the `CHDropDownTextField` directory into your Xcode project.

_**Important:**_ If your project doesn't use ARC you must add the `-fobjc-arc` compiler flag to all CHCircleGaugeView implementation files in Target Settings > Build Phases > Compile Sources.

## Usage

1. Instantiate manually or through a storyboard/xib.
2. Set the number of visible rows for the drop-down to display at a time:

`self.dropDownTextField.dropDownTableVisibleRowCount = 4;`

3. Set an array of strings for the drop-down to display:

`self.dropDownTextField.dropDownTableTitlesArray = self.stringsArray;`

4. Set yourself up as the drop-down delegate through `dropDownDelegate`. Note that this delegate is separate from the regular `UITextField`'s delegate.
5. Implement `dropDownTextField:didChooseDropDownOptionAtIndex:`.

#### Optional

**Subtitles**


## Contributing

Pull request are welcomed. To add functionality or to make changes:

1. Fork this repo.
2. Open `CHDropDownTextField.xcodeproj` in the `CHDropDownTextFieldExample` directory.
3. Make changes to the necessary files in the `CHDropDownTextField` group.
4. Ensure new public methods are documented.
5. Submit a pull request.

## Authors

Created by [Osama Ashawa](http://oashawa.com/), [Matthew Morey](http://matthewmorey.com), [Rogelio Gudino](http://cananito.com/), and other [contributors](https://github.com/chaione/CHCircleGaugeView/graphs/contributors).

## License

CHDropDownTextField is available under the MIT license. See the [LICENSE](https://github.com/chaione/CHDropDownTextField/blob/master/LICENSE) file for more information. If you're using CHDropDownTextField in your project, attribution would be nice.
