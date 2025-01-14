### **Basic Commands**
1. **Pull a Model**  
   Download a model from the Ollama library.
   ```bash
   ollama pull <model-name>
   ```
   Example:
   ```bash
   ollama pull llama2
   ```

2. **Run a Model**  
   Start a chat session with a model.
   ```bash
   ollama run <model-name>
   ```
   Example:
   ```bash
   ollama run llama2
   ```

3. **List Downloaded Models**  
   View all models available locally.
   ```bash
   ollama list
   ```

4. **Remove a Model**  
   Delete a model from your local machine.
   ```bash
   ollama rm <model-name>
   ```
   Example:
   ```bash
   ollama rm llama2
   ```

5. **Copy a Model**  
   Duplicate an existing model with a new name.
   ```bash
   ollama cp <source-model> <new-model>
   ```
   Example:
   ```bash
   ollama cp llama2 my-llama2
   ```

### **Advanced Commands**
6. **Create a Custom Model**  
   Create a custom model using a `Modelfile`.
   ```bash
   ollama create <model-name> -f <Modelfile-path>
   ```
   Example:
   ```bash
   ollama create my-model -f ./Modelfile
   ```

7. **Show Model Information**  
   Display details about a specific model.
   ```bash
   ollama show <model-name>
   ```

8. **Push a Model**  
   Upload a custom model to the Ollama library (requires authentication).
   ```bash
   ollama push <model-name>
   ```

9. **Serve a Model**  
   Start an API server for a model.
   ```bash
   ollama serve
   ```

10. **Stop a Running Model**  
    Terminate a running model session.
    ```bash
    ollama stop <model-name>
    ```

### **Environment and Configuration**
11. **Set Verbose Mode**  
    Enable detailed logging for debugging.
    ```bash
    ollama --verbose
    ```

12. **Check Version**  
    Display the installed version of Ollama.
    ```bash
    ollama --version
    ```

13. **Help Command**  
    Get a list of available commands and options.
    ```bash
    ollama --help
    ```
