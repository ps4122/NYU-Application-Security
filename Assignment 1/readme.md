In this project, we were tasked with auditing a problematic codebase from Shoddycorp's Cut-Rate Contracting. The program in question reads gift card files in a legacy binary format and outputs them in either text or JSON format.
Our goal was to identify and rectify bugs within this poorly documented and error-prone code.

We began by setting up our development environment with Git for version control and GitHub Actions for automated testing. Initial exploration of the code involved running the program with sample files and using debugging tools to
understand its behavior.

The next phase involved creating specific test cases to expose flaws. We developed two crash-inducing gift card files and one that caused an infinite loop, 
documenting each bug's root cause. After fixing these issues, we ensured the robustness of the program by integrating these tests into our continuous integration setup.

Lastly, we used coverage analysis and fuzzing techniques to further test the program. By generating additional test cases and addressing new crashes and hangs, we improved the overall 
code coverage and reliability. This thorough process not only enhanced the stability of the gift card reader but also provided valuable insights into effective code auditing and testing practices.






