# Odometer

Custom animated view to animate an odometer for iOS apps.

## Overview

This Swift package allows the addition of a view to animate an odometer.

## Installing the Odometer

The odometer is distributed as binary framework in a Swift package.  To install in Xcode, select File->Swift Packages->Add Package Dependency.

## Class Reference

### Class OdometerView

**Public Member Functions**

    public init(frame: CGRect, digitNum: Int, fontsize: CGFloat)
     
**Parameters**
     
frame: View frame for the odometer

digitNum:  Number of digits that the odometer should accommodate

fontSize:  Size of the font used to render each digit
     
    updateMileage(mileage: Int, spin: Bool = false, maxSpinTime: Double = 10.0)
     
**Parameters**
     
mileage:  The mileage or value the odometer should display

spin:  Indicate if the odometer should spin its digits before displaying the final value

maxSpinTime:  The duration the odometer should spin before displaying the final value

**Public Properties**

    public var fontSize
