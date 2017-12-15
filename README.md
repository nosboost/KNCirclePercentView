# KNCirclePrecentView

A custom animated circle percent view

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Usage
1. Add KNCirclePercentView using storyboard/nib/code
2. Call Methods:
```Objective-C
/**
 * Draw Circle with specified radius
 *
 * @param radius radius of circle view
 * @param percent percent of circle to display
 * @param lineWidth circle thickness
 * @param clockwise determine clockwise
 * @param fillColor color inside circle
 * @param strokeColor color of circle line
 * @param animatedColors colors array to animated. if this param is nil, Stroke color will be used to draw circle
 */

- (void)drawCircleWithRadius:(CGFloat)radius
                     percent:(CGFloat)percent
                    duration:(CGFloat)duration
                   lineWidth:(CGFloat)lineWidth
                   clockwise:(BOOL)clockwise
                   fillColor:(UIColor *)fillColor
                 strokeColor:(UIColor *)strokeColor
              animatedColors:(NSArray *)colors;

- (void)startAnimation;
```

## Screenshot
### iPhone

![](CirclePercent.gif)

## Installation

KNCirclePrecentView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'KNCirclePrecentView'
```

## License

KNCirclePrecentView is available under the MIT license. See the LICENSE file for more info.
