# verve-doc-intelligence
A gthub repo to implement Azure's document Intelligence AI service

**Prerequisites**

An Azure subscription - Create one for free.

Python 3.7 or later. Your Python installation should include pip. You can check whether you have pip installed by running pip --version on the command line. Get pip by installing the latest version of Python.

The latest version of Visual Studio Code or your preferred IDE. See Getting Started with Python in Visual Studio Code.

An Azure AI services or Document Intelligence resource. Create a single-service or multi-service. You can use the free pricing tier (F0) to try the service, and upgrade later to a paid tier for production.

The key and endpoint from the resource you create to connect your application to the Azure Document Intelligence service.

**Set your environment variables**

Set your key variable:

  setx DI_KEY <yourKey>

Set your endpoint variable

  setx DI_ENDPOINT <yourEndpoint>

**Install dependencies**

  pip install azure-ai-documentintelligence==1.0.0b4

**Run the code**

  python form_recognizer_quickstart.py
