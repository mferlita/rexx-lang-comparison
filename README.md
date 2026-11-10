# rexx-lang-comparison
A syntax comparison of the different Rexx implementations (ooRexx, NetRexx, 
CREXX) and other common programming languages.

*This is still a work in progress. See [guidelines.md](guidelines.md) for rules on contributing.*

## Why
Between Rosetta Code and benchmarks like the Benchmark Game, it is difficult to 
find a proper, standardized comparison of syntax between different languages. 
While Rosetta Code is good for minor comparisons, its lack of consistent 
styling and completeness makes side-by-side comparisons difficult. And while 
the Benchmark Game is interesting for comparing performance, those programs are 
not usually coded idiomatically or in a way that is easy to understand. Neither 
of these are helpful for newcomers, learners, or someone wanting to know if 
Rexx would suit their needs.

## Methodology
Found here is a suite of programs which exhibit some of the most common 
language dimensions. The languages are translated as closely as possible 
while emphasizing each language's idiomatic style. This is to ensure that each 
example is as similar as possible for a fair comparison. Languages pass a
linter if one is available. If a direct translation is difficult or awkward, 
the idiomatic version is preferred. If the idioms diverge significantly, the 
difference is noted in a comment. 

## The Suite
| Program               | Dimensions covered               |
|-----------------------|----------------------------------|
| FizzBuzz              | Syntax, Boilerplate              |
| SumCsvColumn          | I/O, error handling              |
| ShapesAndArea         | Type system, data modeling       |
| FindTasks             | Async, stdlib, dependencies      |
| PngParser             | Pattern matching, expressiveness |
| MandelbrotSet         | Performance, concurrency         |

### Descriptions
* *FizzBuzz:* From Rosetta Code. A simple program which counts incrementally 
from 1 to 100 and replaces numbers divisible by three with "Fizz," numbers 
divisible by five with "Buzz," and numbers divisible by both with "FizzBuzz."
* *SumCsvColumn:* Takes the numerical values in a single column from a [CSV file](https://github.com/datablist/sample-csv-files/blob/f97f6cfdf0aede55f2730225a5de17ddac11a443/README.md) 
and finds the sum.
* *ShapesAndArea:* From [w3resource](https://www.w3resource.com/cpp-exercises/oop/cpp-oop-exercise-10.php). Defines and calculates the area of a rectangle, a triangle, 
and a circle.
* *FindTasks:* From Rosetta Code. Finds all tasks on Rosetta Code which are not 
implemented in Rexx. 
* *PngParser:* Reads a byte stream from a PNG file and produces a list of pairs 
consisting of the chunk type and its data.
* *MandelbrotSet:* Calculates the fractal and reports the program's speed and 
correctness.

### Rexx In Context
| Rexx Implmentation | Compared To                                    |
|--------------------|------------------------------------------------|
| ooRexx             | Ruby, Python, JavaScript (Node.js), Lua        |
| NetRexx            | Java, Kotlin, C#                               |
| CREXX              | Go, C, Rust                                    |

## Further Reading
[ooRexx Documentation](https://sourceforge.net/projects/oorexx/files/oorexx-docs/5.2.0/)  
[NetRexx Documentation](https://www.netrexx.org/documentation.nsp)  
[CREXX Documentation](https://crexx.org/#docs)  
[Rexx History](https://www.rexxla.org/rexxlang/history/index.srsp)  
