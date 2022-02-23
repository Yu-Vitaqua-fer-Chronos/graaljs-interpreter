# GraalJS Interpreter
This is just GraalVM's JS interpreter packaged into a simple file that can be ran!
Note that it has *complete* access to your environment and does not include any
other modules, and is incompatible with many NodeJS modules and does not allow
use of them either.

Another note, this also runs on stock JDKs! Probably doesn't work on Graal JDKs
though, due to it including the jar files into the project, so they'll clash.
