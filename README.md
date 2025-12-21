# Genetic Programming-based Strategy Generation for Trading in Financial Markets

This repository contains the code that implements the proposals in the paper above.
The code is written in Clojure and has the Dockerfile and start script available to run in apptainer.
main.clj file contains the entry points into the code, examples can be found below.

Code for benchmarks can be found under the deeplearning folder.

## Usage

Run command for main function as entrypoint: clj -M -m clojure-scraps.main r/t/b PARAMS

*start.sh* file can be used for apptainer runs, and the Dockerfile can be used to prepare an image which can then be used by apptainer.

## License

Copyright © 2025 FIXME

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
