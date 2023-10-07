# CSC2516: 	Neural Networks and Deep Learning

Instructor: [Colin Raffel](mailto:craffel@gmail.com)

TAs: [Micaela Consens](mailto:micaela.consens@mail.utoronto.ca), [Amanjit Singh Kainth](mailto:amanjitsk@cs.toronto.edu), [Matin Moezzi](mailto:matin.moezzi@mail.utoronto.ca), [Mustafa Ammous](mailto:mustafa.ammous@mail.utoronto.ca), and [Rupert Wu](mailto:rupert.wu@mail.utoronto.ca)

Quercus: https://q.utoronto.ca/courses/327324

Piazza: Link in Quercus

Term: Fall 2023

Lectures: Wednesdays, 9-11am in AH400 (Muzzo Family Alumni Hall)

Tutorials: Thursdays, 12-1pm in AH400

Deep learning is the branch of machine learning focused on training neural networks.
Neural networks have proven to be powerful across a wide range of domains and tasks, including computer vision, natural language processing, speech recognition, and beyond.
The success of these models is partially thanks to the fact that their performance tends to improve as more and more data is used to train them.
Further, there have been many advances over the past few decades that have made it easier to attain good performance when using neural networks.
In this course, we will provide a thorough introduction to the field of deep learning.
We will cover the basics of building and optimizing neural networks in addition to specifics of different model architectures and training schemes.
The course will cover portions of the "[Dive into Deep Learning](https://d2l.ai/)" textbook and will have a standard lecture/homework/exam format.

## Prerequisites

Students should have taken courses on machine learning, linear algebra, and multivariate calculus.
Further, it is recommended that students have some basic familiarity with statistical concepts.
Finally, students must be proficient in reading and writing Python code.
For a list of courses that serve as prerequisites for the undergraduate version of this course, see [here](https://artsci.calendar.utoronto.ca/course/csc413h1).

## Lecture and tutorial schedule

The following schedule is tentative; the content of each lecture may change depending on pacing.
All readings refer to corresponding sections in [Dive into Deep Learning](http://d2l.ai).
Because the book is occasionally updated, the sections listed may become out of date.
If a reading seems incongruous with the topic of the lecture, please let me know and I will check if the sections changed.
Tutorials will more directly cover the background and tools needed for each homework assignment or, when preceding an exam, will consist of an exam review.

| Date  | Subject                                                                        | Reading                     | Homework             |
| ----- | ------------------------------------------------------------------------------ | --------------------------- | -------------------- |
| 9/13  | Class introduction, linear regression                                          | 2.1-2.7 (optional), 3.1-3.5 | H1 assigned          |
| 9/20  | Logistic regression, gradient descent, adaptive gradient methods               | 4.1-4.5, 12.1-12.6, 12.10   | H1 due, H2 assigned  |
| 9/27  | Under/overfitting, regularization, multilayer perceptrons                      | 3.6-3.7, 5.1-5.2, 5.6       | H2 due, H3 assigned  |
| 10/4  | Backpropagation, numerical stability, automatic differentiation                | 5.3-5.4                     | H3 due, H4 assigned  |
| 10/11 | Convolutional neural networks, batch/layer normalization, residual connections | 7.1-7.5, 8.5-8.6            | H4 due, H5 assigned  |
| 10/18 | Sequences, recurrent neural networks, and sequence-to-sequence learning        | 9.1-9.7, 10.1-10.8          | H5 due, H6 assigned  |
| 10/25 | Midterm                                                                        |                             |                      |
| 11/1  | Attention                                                                      | 11.1-11.6                   | H6 due, H7 assigned  |
| 11/8  | No class - fall reading week                                                   | —                           |                      |
| 11/15 | Transformers part 1                                                            | 11.7, 15.8-15.10            | H7 due, H8 assigned  |
| 11/22 | Transformers part 2, large language models                                     | 11.8-11.9                   | H8 due, H9 assigned  |
| 11/29 | Semi-/self-supervised and a little more deep generative modeling               | —                           | H9 due, H10 assigned |
| 12/6  | Deep learning engineering; fairness, accountability, and transparency          | 13.5-13.6, 4.7              | H10 due              |

## Grading

  1. **Homework**, 50 points: There will be 10 homework assignments. Each homework assignment will be assigned on Wednesday and due the following Wednesday. Homework will consist of some combination of math and coding. Each homework is worth 5 points.
  1. **Midterm**, 20 points: The midterm will take place on 10/18 and will cover all topics discussed before the midterm.
  1. **Final Exam**, 30 points: The final exam will take place during our scheduled final exam slot and will cover all topics discussed in the class.

## Late work, collaboration rules, and the honor code

You can replace your worst homework grade with a perfect grade (5/5), which effectively excuses you from a single homework.
I can grant you an extension on a homework due to a life emergency, but you must request an extension at least 24 hours before the homework is due.

You are welcome to work together with other students on the homework.
You are also welcome to use any resources you find (online tutorials, textbooks, papers, chatbots, etc.) to help you complete the homework.
However, **you must list any collaboration or resources you used to complete each homework on each assignment**.
If you hand in homework that involved collaboration and/or makes use of content that you did not create and you do not disclose this, you will get a 0 for that homework.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

## Resources

Please be aware of the following resources at U of T which can help ensure your academic success and personal well-being:

- [Writing at U of T](http://www.writing.utoronto.ca/)
- [University of Toronto Academic Integrity](http://academicintegrity.utoronto.ca/)
- [U of T Student Life](http://www.studentlife.utoronto.ca/)
- [Accessibility Services](http://www.accessibility.utoronto.ca/)
- [Health Services](https://studentlife.utoronto.ca/department/health-wellness/)
    
## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.
