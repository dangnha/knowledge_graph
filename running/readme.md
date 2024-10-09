1. Clone reposetory:  
```
git clone https://github.com/dangnha/knowledge_graph.git
cd knowledge_graph
```
2. Install Language Model:  
Open other termianl:  
Install Ollama 
```
curl -fsSL https://ollama.com/install.sh | sh
```
Run ```ollama run zephyr```  
3. Set up virtual environments:  
Back to original terminal, run:
```
python -m venv myenv
```   
Activate: 
```
source myenv/bin/activate
```
4. Set up necessary library:  
```
pip install -r requirements.txt
```
5. Runing:
papermill extract_graph.ipynb output_notebook.ipynb

