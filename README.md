# Objective-C Memory Management Bug: Retain/Release Imbalance

This repository demonstrates a common bug in Objective-C related to memory management using `retain` and `release`.  Improper handling of these methods can lead to memory leaks or crashes.  The example showcases a scenario where a retained object is not properly released, resulting in a memory leak.  The solution provides a corrected version that demonstrates proper memory management.

## Bug Description:

The bug is in the `MyClass` implementation.  `myObject` is retained but never released, leading to a memory leak.  The solution shows a correct pattern using proper `release` to prevent this issue.  This is more relevant in non-ARC code but good practice remains relevant even in ARC environments to understand the system's behavior.