# Daily Papers
The project automatically fetches the latest papers from arXiv based on keywords.

The subheadings in the README file represent the search keywords.

Only the most recent articles for each keyword are retained, up to a maximum of 100 papers.

You can click the 'Watch' button to receive daily email notifications.

Last update: 2025-07-21

## Default
| **Title** | **Date** | **Abstract** | **Comment** |
| --- | --- | --- | --- |
| **[Fun with flags: How Compilers Break and Fix Constant-Time Code](http://arxiv.org/abs/2507.06112v1)** | 2025-07-08 | <details><summary>Show</summary><p>Developers rely on constant-time programming to prevent timing side-channel attacks. But these efforts can be undone by compilers, whose optimizations may silently reintroduce leaks. While recent works have measured the extent of such leakage, they leave developers without actionable insights: which optimization passes are responsible, and how to disable them without modifying the compiler remains unclear. In this paper, we conduct a qualitative analysis of how compiler optimizations break constant-time code. We construct a dataset of compiler-introduced constant-time violations and analyze the internals of two widely used compilers, GCC and LLVM, to identify the specific optimization passes responsible. Our key insight is that a small set of passes are at the root of most leaks. To the best of our knowledge, we are also the first to characterize how the interactions between these passes contribute to leakage. Based on this analysis, we propose an original and practical mitigation that requires no source code modification or custom compiler: disabling selected optimization passes via compiler flags. We show that this approach significantly reduces leakage with minimal performance overhead, offering an immediately deployable defense for developers.</p></details> | 11 pages |

