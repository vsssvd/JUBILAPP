# JUBILAPP
cat > README.md << 'EOF'
# Jubilapp
Monorepo del proyecto:
- `jubilapp-api-py`: API en FastAPI + Firebase (Auth/Firestore)
- `jubilapp-app`: App móvil en Expo/React Native

## Levantar
Backend:
```bash
cd jubilapp-api-py
source .venv/bin/activate  # o .\.venv\Scripts\activate en Windows
uvicorn app.main:app --reload
