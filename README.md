# Sentence-Generator-Using-Search-Methods
This assignment implements various search algorithms to generate sentences based on a given vocabulary and transition matrix. The implemented algorithms include:


- Iterative Deepening Depth-First Search (IDDFS)
- Uniform Cost Search (UCS)
- Greedy Search
- A* Search


## Requisites 

Ensure you have Python 3.x installed. 
Ensure transition and vocabulary txt files are in the same directory where you are running code.

## Usage

To run the script, use the following command:

python final_exp.py <L> <n+2> <transition_file> <vocab_file>


- `<L>`: Length of the vocabulary.
- `<n+2>`: Length of the sentence to be generated.
- `<transition_file>`: Path to the transition matrix file.
- `<vocab_file>`: Path to the vocabulary file.

Example:
python final_exp.py 4 6 transition.txt vocab.txt



## Running Experiments

If you want to check for different n values and different L values for different vocabulary and transition matrix file then add those files and uncomment the mentioned code in code file

Example:
n_values = [3, 4, 5, 6, 7, 8]
L= {3,5,10,15}
run_experiments(vocab_file, transition_file, n_values)



## License

This assignment is done under the course of Artificial Intelligence, Autumn 2024- IIT Jodhpur by Yashraj Chaturvedi
