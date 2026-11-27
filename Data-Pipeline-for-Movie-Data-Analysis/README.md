# Data-Pipeline-for-Movie-Data-Analysis
Data Pipeline for Movie Data Analysis

## TMDb API key

The notebook reads the TMDb API key from the `TMDB_API_KEY` environment variable. Do not paste the key into the notebook.

Locally:

```bash
export TMDB_API_KEY="your_key"
```

In Google Colab, open the Secrets panel (key icon), add a secret named `TMDB_API_KEY`, and allow this notebook to access it. When the notebook runs in Colab, it loads that secret into `TMDB_API_KEY`.
