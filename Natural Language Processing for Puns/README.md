## What do you call a...
Finds new rhyming ways to say two-word phrases!
>For example:
>* play ground <img src="https://latex.codecogs.com/gif.latex?\rightarrow"/> comeback tarmac
>* wind shield <img src="https://latex.codecogs.com/gif.latex?\rightarrow"/> rain restrain
>* Bill Ray <img src="https://latex.codecogs.com/gif.latex?\rightarrow"/> legislation illumination

Google's [word2vec](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit) model is used to find related words for each input.  
Next the [pronouncing library](https://pypi.org/project/pronouncing/) is used to pair up rhyming results.  
The ouput is creative, often amusing, word combinations that resemble the input phrase
