# Temperature Converter & Parameterized Tests

## Overview

This is a starter repository, containing a Java Gradle project, to be used for introducing JUnit5 parameterized tests. The included code defines methods for converting between the Fahrenheit and Celsius temperature scales. These methods are fully implemented, but there are no unit tests included; these are to be added as a practical exploration of parameterized tests, with method and CSV file sources.

This repository is intended to accompany the ["Parameterized Tests"](https://ddc-java.github.io/parameterized-tests/) introductory module.

## Test cases

The following test cases may be used in unit testing the `Converter.convertC2F` and `Converter.convertF2C` methods. Note that some of the values are actually approximations of repeating decimals; for this reason (as well as the fact that floating-point computations should not, as a rule, be regarded as exact), a tolerance should be used when testing expected vs. actual values. We recommend using tolerances of equivalent magnitude for the two scales&mdash;e.g. 0.0005&deg;C and 0.0009&deg;F.

| Celsius | Fahrenheit |
|:-------:|:----------:|
| -40 | -40 |
| 0 | 32 |
| 100 | 212 |
| -11.871 | 10.632 |
| -249.598 | -417.277 |
| 20.825 | 69.485 |
| 105.848 | 222.527 |
| -222.828 | -369.091 |

## Credits, copyright, and license information

The source code included in this project was written by Nick Bennett.

&copy; 2021 CNM Ingenuity, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

