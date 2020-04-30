# Markov-Model
The goal of this project was to simulate the Markov Chain algorithm. Markov Chain is oven used to statistically model random processes or stochastic processes. Some common examples of stochastic processes are stock market and exchange rate fluctuations, signals such as speech; audio and video; medical data such as a patient's EKG, EEG, blood pressure or temperature. Markov chain has been and continues to be widely used in various other areas such as education, marketing, health services, finances, accounting etc.

Markov chain consists of states and probabilities and is based on the concept of “memorylessness”, that is, the next state of any process only depends on the previous state and is completely independent of the sequence of states that precede. This simple assumption allows the use of conditional probability in calculations of the various phases and steps in the Markov chain process.

Markov chain consists of a set of transitions, which are determined by probability distributions that satisfy the Markov property. This project is aimed at exploring the different concepts of the Markov chain algorithm. Ideally, the Markov chain can be implemented for n states, where n can be any number between two and infinity. However, in this project, to maintain lower complexity while ensuring a holistic view of the algorithm, the number of states used to explain the various concepts was restricted to 5 states. This can be at any time be scaled up to as many states as required.

# Spreadsheets & Worksheets
As part of the interface users need to enter the initial transition matrix. The transition matrix is a square matrix used to describe the transitions of a Markov chain. Each of its entries is a nonnegative real number representing a probability.

The entire project is implemented through macros in MS Excel. There are two main worksheets that are visible to the end user named Welcome and Model.

The Welcome sheet is designed in a way that serves as the first interaction point for the users and allows the user to enter the initial matrix.

The macro enabled file that has the implementation for the Markov Chains has two worksheets that are visible to the end user – Welcome and Model.

The Welcome sheet is displayed on load of the file and provides an option for the user to enter the Markov Chain State Transition Matrix. The captured details are displayed in the Model worksheet, which also has several command buttons that can be used to answer various questions related to the Markov Chain.

All the matrix calculations are done in worksheets that are hidden to the end users.

