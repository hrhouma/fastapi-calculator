# Résumé des commandes:

```python
    # Cloner le dépôt
    git clone https://github.com/hrhouma/fastapi-calculator.git
    cd fastapi-calculator

    # Créer et activer un environnement virtuel
    python -m venv myenv
    # Sous Windows
    myenv\Scripts\activate
    # Sous macOS et Linux
    source myenv/bin/activate

    # Installer les dépendances
    pip install streamlit requests fastapi uvicorn

    # Démarrer le serveur FastAPI
    uvicorn backend:app --reload

    # Démarrer l'application Streamlit
    streamlit run frontend.py
```
