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
- Tim Alexander Teige <tte008@post.uit.no>, Office: ?
- Morten Grønnesby?

## Lecture plan

| Lecture 	| Date		| Subject	| Lecturer |
|-----------|-----------|-----------|----------|
| L1  | Fri 19.08 | [Introduction](lectures/01-introduction.pptx) | Lars Ailo |
| L2  | Fri 26.08 | Threads and synchronization primitives| Lars Ailo |
| L3  | Thu 01.09 | Guest lecture: Go | Giacomo Tartari? |
| L4  | Fri 02.09 | Parallel architectures | Lars Ailo |
| L5  | Fri 09.09 | Parallel programs | Lars Ailo |
| L6  | Fri 16.09 | Programming for performance | Lars Ailo |
| L7  | Fri 23.09 | Performance evaluation | Lars Ailo |
| L8  | Fri 30.09 | Parallel program performance evaluation | Lars Ailo |
| L9  | Fri 07.10 | Guest lecture: Cloud computing | Aleksandr Agafonov? |
| L10 | Thu 13.10 | Guest lecture: Scala and Spark | Inge Alexander Raknes? |
| L11 | Fri 24.10 | Data-intensive computing | Lars Ailo |
| L12 | Fri 28.10 | Spark libraries | Lars Ailo |
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

The following are suggested **additional readings**:
- The Go Programming Language. Alan Donovan and Brian Kernighan. 2015.
- Learning Spark. Holden Karau, Andy Konwinski, Patrick Wendell, Matei Zaharia. O’Reilly. 2015.
- Parallel Computer Architecture: A Hardware/Software Approach. David Culler, J.P. Singh, Anoop Gupta. Morgan Kaufmann. 1998.
	* This book has a great introduction to parallel programming.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.
- The Art of Computer Systems Performance Analysis: Techniques for Experimental Design, Measurement, Simulation, and Modeling. R. K. Jain. Wiley. 1991.
	* A very good book about performance analysis.
	* There is one copy in the library. Please be nice to your fellow students and do not lend that copy for an extended period.    
- Computer Architecture, Fifth Edition: A Quantitative Approach, 5ed. John L. Hennessy, David A. Patterson. Morgan Kaufmann. 2011.
	* This book has a throughout description of different parallel architectures.
	* You can purchase this book from your favourite bookstore.    
- The Fourth Paradigm: Data-Intensive Scientific Discovery. Edited by Tony Hey, Stewart Tansley, and Kristin Tolle. 2010.
	* This collection of essays describe many of the opportunities and challenges for data-intensive computing in different scientific fields.
	* The book is freely available as an ebook.
- Advanced Analytics with Spark. Sandy Ryza, Uri Laserson, Sean Owen, Josh Wills. O’Reilly. 2015.

## Mandatory assignments

| Project |	Start    | Due      | Subject | Lecturer |
|---------|----------|----------|---------|----------|
| P1  	  | 23.08    | 12.09    | Concurrent B+tree| Tim      |
| P2  	  | 13.09    | TBD      | TBA     | Tim      |
| P3      | 11.10?   | TBD      | TBA     | -        |

Note! The mandatory assignment text and pre-code are available in private repositories accessible only for the members of the uit-inf-2202-f16 github organization. 

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
