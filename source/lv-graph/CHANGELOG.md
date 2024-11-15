# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2024-11-14

- expanded functionality of copy xy graph to also include the scale names (previously only included the formatting and ranges)
- removed polymorphic vi for copy xy-graph; functionality of normal vs vertical was identical

## [1.1.0] - 2021-10-03

- Updated the fg multiplier to be publically available
- Fixed bug with fg multiplier where it wouldn't store new values correctly
- Added functionality to decimate 1D or 2D array
- Added functionality to be able to decimate by values, not just a number of points
- Removed parallization in for loops for decimation
- Fixed bug in decimation where an interval of 0 would pass through and cause it to hang
- Updated decimation to pass through values if no valid interval is provided
- Added check for interval in value decimation to ensure that the interval isn't greater than the max X value
- Updated scrollbar_index and scrollbar_min_max to be a polymorphic VI that would provide functionality for page or index.

## [1.0.0] - 2021-07-22

- Initial release
