# Telugu Morphological analyzer 


## Requirement
lttoolbox(apertium)
To install lttoolbox:
````
sudo apt install lttoolbox-dev
````

Input data should be in WX format

### Download TeluguMorph

````
git clone https://github.com/parameshkrishnaa/Telugu-Morph-lttoolbox.git
````

### How to run:
````
cd Telugu-Morph-lttoolbox
lt-proc -c telugu_morph_analyzer_v2.0.bin 
````

#### To run using a file 
````
lt-proc -c telugu_morph_analyzer_v2.0.bin < input.txt
````
