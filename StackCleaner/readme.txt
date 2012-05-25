==== About StackCleaner ====
Among the many handy features introduced in REALbasic 2006, RuntimeException.Stack() stands out as a particularly useful one. This enables more rapid and precise debugging in the event of an exception (e.g., a NilObjectException) being triggered by your code, allowing you to pinpoint the exact location and cause of the error.
Unfortunately, as of 2006r1, the RuntimeException.Stack() function outputs function names as the compiler sees them, not as they're presented to the developer in the IDE. StackCleaner aims to remedy this by translating the compiler names back into their familiar forms - simply call RuntimeException.CleanStack() and you'll be presented with the same data in a more friendly format.
StackCleaner will be supported until REAL Software includes this functionality with REALbasic (it's expected in a near release).

==== Author ====
SirG3 <TheSirG3@gmail.com>

==== License ====
StackCleaner is open source.

==== Version History ====
January 21, 2006 - Bugfixes.
January 11, 2006 - Initial release.