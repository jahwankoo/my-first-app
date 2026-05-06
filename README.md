# Hello SKKU 🎓

A simple "Hello World" web application built with [Streamlit](https://streamlit.io/) — a great starting point for learning how to build interactive Python web apps.

## Demo

When you run this app, you'll see:

- A title: **Hello, SKKU! 🎓**
- A short message: *My first web app*

## Requirements

- Python 3.8 or higher
- [Streamlit](https://streamlit.io/)

## Installation

1. **Clone this repository**

   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. **(Optional) Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate     # macOS / Linux
   venv\Scripts\activate        # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install streamlit
   ```

## Usage

Run the app with:

```bash
streamlit run app.py
```

Then open your browser at [http://localhost:8501](http://localhost:8501).

## Project Structure

```
.
├── app.py          # Main Streamlit application
└── README.md       # Project documentation
```

## Code Overview

```python
import streamlit as st

st.title("Hello, SKKU! 🎓")
st.write("My first web app")
```

| Function | Description |
|----------|-------------|
| `st.title()` | Renders a large title at the top of the page. |
| `st.write()` | A general-purpose display function for text, data, charts, and more. |

## Next Steps

Try extending the app with:

- `st.text_input()` — capture user input
- `st.button()` — add interactive buttons
- `st.slider()` — let users pick a numeric value
- `st.dataframe()` — display tables
- `st.line_chart()` — quick visualizations

See the [Streamlit documentation](https://docs.streamlit.io/) for more.

## License

This project is released under the MIT License — see the `LICENSE` file for details.

## Author

Created as part of coursework at **Sungkyunkwan University (SKKU)**.
