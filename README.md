## Basic Commands

Essential commands to get started with Ollama, including pulling, running, listing, removing, and copying models.

1. **Pull a Model**  
   - **Description**: Downloads a model from the Ollama library to your local machine.  
   - **Command**:  
     ```bash
     ollama pull <model-name>
     ```  
   - **Example**:  
     ```bash
     ollama pull llama2
     ```  
     Downloads the `llama2` model.

2. **Run a Model**  
   - **Description**: Starts an interactive chat session with the specified model.  
   - **Command**:  
     ```bash
     ollama run <model-name>
     ```  
   - **Example**:  
     ```bash
     ollama run llama2
     ```  
     Opens a chat session with the `llama2` model.

3. **List Downloaded Models**  
   - **Description**: Displays all models currently available on your local machine.  
   - **Command**:  
     ```bash
     ollama list
     ```  
   - **Example**:  
     ```bash
     ollama list
     ```  
     Shows a list like `llama2`, `codellama`, etc.

4. **Remove a Model**  
   - **Description**: Deletes a specified model from your local machine.  
   - **Command**:  
     ```bash
     ollama rm <model-name>
     ```  
   - **Example**:  
     ```bash
     ollama rm llama2
     ```  
     Removes the `llama2` model.

5. **Copy a Model**  
   - **Description**: Duplicates an existing model under a new name.  
   - **Command**:  
     ```bash
     ollama cp <source-model> <new-model>
     ```  
   - **Example**:  
     ```bash
     ollama cp llama2 my-llama2
     ```  
     Creates a copy of `llama2` named `my-llama2`.

## Advanced Commands

Commands for advanced operations, such as creating custom models, inspecting details, pushing to the library, serving via API, and stopping models.

6. **Create a Custom Model**  
   - **Description**: Builds a custom model using a `Modelfile` configuration.  
   - **Command**:  
     ```bash
     ollama create <model-name> -f <Modelfile-path>
     ```  
   - **Example**:  
     ```bash
     ollama create my-model -f ./Modelfile
     ```  
     Creates `my-model` based on the specified `Modelfile`.

7. **Show Model Information**  
   - **Description**: Displays detailed information about a specific model, such as size and parameters.  
   - **Command**:  
     ```bash
     ollama show <model-name>
     ```  
   - **Example**:  
     ```bash
     ollama show llama2
     ```  
     Outputs details like `llama2`’s architecture and configuration.

8. **Push a Model**  
   - **Description**: Uploads a custom model to the Ollama library (authentication required).  
   - **Command**:  
     ```bash
     ollama push <model-name>
     ```  
   - **Example**:  
     ```bash
     ollama push my-model
     ```  
     Uploads `my-model` to the library.

9. **Serve a Model**  
   - **Description**: Launches an API server to make a model accessible externally.  
   - **Command**:  
     ```bash
     ollama serve
     ```  
   - **Example**:  
     ```bash
     ollama serve
     ```  
     Starts the API server for model interactions.

10. **Stop a Running Model**  
    - **Description**: Terminates a currently running model session.  
    - **Command**:  
      ```bash
      ollama stop <model-name>
      ```  
    - **Example**:  
      ```bash
      ollama stop llama2
      ```  
      Stops the `llama2` model session.

## Environment and Configuration

Commands to manage Ollama’s environment, including verbosity, version checking, and help documentation.

11. **Set Verbose Mode**  
    - **Description**: Enables detailed logging for debugging purposes.  
    - **Command**:  
      ```bash
      ollama --verbose
      ```  
    - **Example**:  
      ```bash
      ollama --verbose run llama2
      ```  
      Runs `llama2` with detailed output.

12. **Check Version**  
    - **Description**: Shows the currently installed version of Ollama.  
    - **Command**:  
      ```bash
      ollama --version
      ```  
    - **Example**:  
      ```bash
      ollama --version
      ```  
      Outputs something like `ollama version 0.1.0`.

13. **Help Command**  
    - **Description**: Lists all available commands and options.  
    - **Command**:  
      ```bash
      ollama --help
      ```  
    - **Example**:  
      ```bash
      ollama --help
      ```  
      Displays the help menu.
