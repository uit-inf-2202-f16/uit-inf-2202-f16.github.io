---
layout: default
---

## Administrative information

Administrative course information is available [here](https://uit.no/utdanning/emner/emne?p_document_id=455473)

We use the [inf-2202-f16@list.uit.no](https://list.uit.no/sympa/info/inf-2202-f16) mailing list to send important information.

We have the following rooms and hours:

- Tuesdays 14:15-16:00, A016: lab exercises.
- Thursdays 14:15-16:00, B203 (Small auditorium): lectures.
- Thursdays 14:15-16:00, p-lab: lab exercises.
- Fridays 10:15-11:00, NYLYSTH AUD: lectures.

## Staff

- Lars Ailo Bongo <larsab@cs.uit.no>, Office: A259
- Tim Alexander Teige <tte008@post.uit.no>, Office: ODS-Lab

## GitHub

[The course GitHub repository](https://github.com/uit-inf-2202-f16).

## Lecture plan

| Lecture 	| Date		| Subject	| Lecturer |
|-----------|-----------|-----------|----------|
| L1  | Fri 19.08 | [Introduction](lectures/01-introduction.pptx) | Lars Ailo |
| L2  | Fri 26.08 | [Threads and synchronization primitives](lectures/02-threads-synchronization.pptx)| Lars Ailo |
| L3  | Thu 01.09 | Guest lecture: [Go Language](lectures/03-Go Language.pdf) | Giacomo Tartari |
| L4  | Fri 02.09 | [Parallel architectures](lectures/04-parallel-architectures.pptx) | Lars Ailo |
| L5  | Fri 09.09 | [Parallel programs](lectures/05-parallel-programs.pptx) | Lars Ailo |
| L6  | Fri 16.09 | [Programming for performance](lectures/06-programming-for-performance.pptx) | Lars Ailo |
| L7  | Fri 23.09 | [Parallel program performance evaluation](lectures/07-parallel-program-performance.pptx) | Lars Ailo |
| L8  | Fri 30.09 | [Performance evaluation](lectures/08-performance-evaluation.pptx) | Lars Ailo |
| L9  | Fri 07.10 | Cloud computing (no slides) | Lars Ailo |
| L10 | Thu 13.10 | Guest lecture: [Scala](lecutres/10-Scala.pdf) and [Spark](lectures/10-Spark.pdf) | Inge Alexander Raknes |
| -   | Fri 21.10 | Postponed | - |
| L11 | Fri 28.10 | [Data-intensive computing](lecture/11-data-intensive-computing.pptx) | Lars Ailo |
| L12 | Thu 03.10 | Spark libraries | Lars Ailo |
| L13 | Fri 04.11 | Guest lecture: The new Stallo Supercomputer | Steinar Trædal-Henden |
| L14 | Thu 10.11 | Guest lecture? | TBA  |
| L15 | Fri 11.11 | Summary lecture | Lars Ailo |
| -   | Thu 24.11 | Exam | - |

## Readings

All lecture notes are **Mandatory**.

In addition, unless otherwise noted, the following are also **mandatory** readings:

1. Introduction
* None
2. Threads and synchronization primitives (operating systems course recap):
- Modern operating systems, 3ed, Andrew S. Tanenbaum. Prentice Hall. 2007. Chapters: 2.2, 2.3, 2.5, 10.3, 11.4
- Alternative to MOS: another operating systems textbook: the chapters about threading, IPC mechanisms, and classical IPC problems.
3. Go
- Rob Pike. [SPLASH keynote talk](http://talks.golang.org/2012/splash.article)
- [A tour of Go](http://tour.golang.org/)
- [How to write Go code](http://golang.org/doc/code.html)
- [Effective Go](http://golang.org/doc/effective_go.html)
- Go concurrency patterns ([video](http://www.youtube.com/watch?v=f6kdp27TYZs), [slides](http://talks.golang.org/2012/concurrency.slide#1))
- Advanced Go concurrency patterns ([video](https://www.youtube.com/watch?v=QDDwwePbDtw), [slides](http://talks.golang.org/2013/advconc.slide#1))
4. Parallel architectures
- Computer Organization and Design: the Hardware/Software Interface, 5th. David A. Patterson, John L. Hennessy. Morgan Kaufmann. 2011. Chapter 6: “Parallel Processors from Client to Cloud”.
5. Parallel programs
- None
6. Programming for performance
- None
7. Parallel performance evaluation
- [Amdahl’s law](http://dl.acm.org/citation.cfm?id=1465560)
- [Gustafson’s law](http://dl.acm.org/citation.cfm?id=42415)
- [Debunking the 100X GPU vs. CPU myth: an evaluation of throughput computing on CPU and GPU](http://dl.acm.org/citation.cfm?id=1816021) or [Can traditional programming bridge the ninja performance gap for parallel computing applications?](http://dl.acm.org/citation.cfm?id=2766485.2742910)
8. Performance evaluation
- None

The following are suggested **additional readings**:

1. The Go Programming Language. Alan Donovan and Brian Kernighan. 2015.
2. Learning Spark. Holden Karau, Andy Konwinski, Patrick Wendell, Matei Zaharia. O’Reilly. 2015.

3. Parallel Computer Architecture: A Hardware/Software Approach. David Culler, J.P. Singh, Anoop Gupta. Morgan Kaufmann. 1998.
	* This book has a great introduction to parallel programming.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.

4. The Art of Computer Systems Performance Analysis: Techniques for Experimental Design, Measurement, Simulation, and Modeling. R. K. Jain. Wiley. 1991.
	* A very good book about performance analysis.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.    

5. Computer Architecture, Fifth Edition: A Quantitative Approach, 5ed. John L. Hennessy, David A. Patterson. Morgan Kaufmann. 2011.
	* This book has a throughout description of different parallel architectures.
	* You can purchase this book from your favourite bookstore.    

6. The Fourth Paradigm: Data-Intensive Scientific Discovery. Edited by Tony Hey, Stewart Tansley, and Kristin Tolle. 2010.
	* This collection of essays describe many of the opportunities and challenges for data-intensive computing in different scientific fields.
	* The book is freely available as an ebook.

7. Advanced Analytics with Spark. Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills. O’Reilly. 2015.

## Mandatory assignments

| Project |	Start    | Due      | Subject | Lecturer |
|---------|----------|----------|---------|----------|
| P1  	  | 23.08    | 19.09    | [Concurrent B+tree](https://github.com/uit-inf-2202-f16/assignment-1) | Tim      |
| P2  	  | 20.09    | TBD      | [Deduplication system](https://github.com/uit-inf-2202-f16/assignment-2) | Tim |
| P3      | 11.10?   | TBD      | TBA     | -        |


## Exercises

1. Introduction
	1.  None
2. Threads and synchronization primitives
	1. Compare the overhead of forking a process vs. creating a Pthread
	2. Compare the overhead of forking a process vs. creating a Python thread
	3. Implement a solution the following classical IPC problems using pthreads/Python threads and semaphores/condition variables. Note that you also need to generate a use case, test data, and useful output:
		1. Producer/ consumer
		2. Reader/ writer
		3. Sleeping barber
		4. Dining philosophers
	4. Modify the code in 3) to use message passing.
3. Go
	1. [Take a tour of Go](http://tour.golang.org/welcome/1)
	2. Implement the classical IPC problems in exercise 2.3. in Go.
4. Parallel architectures
    1. None
5. Parallel programs
	1. Implement a simpliefied BLAST search program in Go that does similarity search on two lists of random DNA sequences.
	2. Implement a heat distribution (SOR) program using Pthreads or (/and) Go.
6. Programming for performance
	1. Implement a tuple space in Python with semantics similar to Linda. Use your tuple space to implement a parallel version of Mandelbrot that uses dynamic assignment (pool of tasks).
7. Parallel program performance evaluation
	1. Go through either the [debunking](http://dl.acm.org/citation.cfm?id=1816021) or [ninja](http://dl.acm.org/citation.cfm?id=2766485.2742910) paper and study how they did each of the “Steps for a performance evaluation study”.
8. Performance evaluation
	1. None