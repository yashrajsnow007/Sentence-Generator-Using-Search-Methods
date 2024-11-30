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


## Results

The results of the experiments will be printed to the console, showing the generated sentence, score, nodes explored, and execution time for each algorithm.

Example output:
Running experiments for n=4

Results using IDDFS:
Sentence (length 6): <SoS> grass grass airport green <EoS>
Score: 0.0013628499234583315, Nodes Explored: 1049, Time: 0.0000 sec


Results using UCS:
Sentence (length 6): <SoS> grass grass airport green <EoS>
Score: 0.0013628499234583315, Nodes Explored: 128, Time: 0.0000 sec


Results using Greedy Search:
Sentence (length 6): <SoS> green airport at grass <EoS>
Score: 0.00042083261917621675, Nodes Explored: 5, Time: 0.0000 sec


Results using A* Search:
Sentence (length 6): <SoS> grass grass airport green <EoS>
Score: 0.0013628499234583315, Nodes Explored: 64, Time: 0.0000 sec


## License

This assignment is done under the course of Artificial Intelligence, Autumn 2024- IIT Jodhpur by Yashraj Chaturvedi
