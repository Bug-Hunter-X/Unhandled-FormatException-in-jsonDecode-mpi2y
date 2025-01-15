# Unhandled FormatException in Dart's jsonDecode

This example demonstrates a common error in Dart when working with JSON data: an unhandled `FormatException` thrown by `jsonDecode`.

The `bug.dart` file contains code that fetches data from an API and attempts to decode it using `jsonDecode`. If the API response is not valid JSON, a `FormatException` is thrown, and the application crashes without proper error handling.

The `bugSolution.dart` file demonstrates the solution by adding robust error handling to catch this exception and prevent crashes.  Proper error handling ensures a better user experience and prevents unexpected app termination.
