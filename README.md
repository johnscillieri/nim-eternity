nim-eternity
============

Library to convert delta times into a human or bot readable formats.

## Usage

```nimrod
import eternity as e

echo e.humanize(3600.0)		# 1h
echo e.robotize(3600.0)		# 1h 0m 0s 0ms

echo e.humanize(36.125)		# 36s 125ms
echo e.robotize(36.125)		# 0h 0m 36s 125ms

echo e.humanize(60.002)		# 1m 2ms
echo e.robotize(60.002)		# 0h 1m 0s 2ms
```


