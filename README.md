[README.md](https://github.com/user-attachments/files/25710971/README.md)
# CrossFit Open 26.1 Thailand Dashboard Project

This project turns the provided Thailand CrossFit Open 26.1 CSV into:

- a cleaned analytical dataset
- chart outputs
- a static website (GitHub Pages friendly)
- a basic Streamlit dashboard

## Files
- `cleaned_crossfit_open_26_1_thailand.csv` - cleaned long-format data
- `analysis_report.md` - written analytical summary
- `analysis_script.py` - Python workflow for cleaning, analysis, and chart export
- `streamlit_app.py` - beginner-friendly Streamlit dashboard
- `index.html` and `style.css` - static site for GitHub Pages
- `charts/` - exported PNG charts

## Local setup
```bash
pip install -r requirements.txt
python analysis_script.py
```

## Static site preview
Open `index.html` in your browser.

## Streamlit run
```bash
streamlit run streamlit_app.py
```

## GitHub Pages
1. Push the repository to GitHub.
2. In GitHub, open **Settings -> Pages**.
3. Set the source to deploy from the main branch root.
4. Save and wait for the site URL.

## Streamlit hosting
If you want the interactive version online:
- keep the code in GitHub
- connect the repo to Streamlit Community Cloud
- set `streamlit_app.py` as the entry point
