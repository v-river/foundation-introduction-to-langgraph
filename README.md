# Foundation: Introduction to LangGraph

Projects based on training course

### Useful Commands

```sh
pip list --not-required
```

```sh
python3 -m venv .venv
source .venv/bin/activate
```

```sh
pip install -U pip
```

### Set up LangSmith Studio

LangSmith Studio is a custom IDE for viewing and testing agents.
Studio can be run locally and opened in your browser.
Graphs for LangSmith Studio are in the `module/studio/` folders.
To start the local development server, run the following command in your terminal in the `/studio` directory each module:

```sh
langgraph dev
```

You should see the following output:

- 🚀 API: http://127.0.0.1:2024
- 🎨 Studio UI: https://smith.langchain.com/studio/?baseUrl=http://127.0.0.1:2024
- 📚 API Docs: http://127.0.0.1:2024/docs

Open your browser and navigate to the Studio UI: https://smith.langchain.com/studio/?baseUrl=http://127.0.0.1:2024
