# neuraplug
# Install FastAPI & Required Dependencies
mkdir gpu_backend && cd gpu_backend
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install fastapi uvicorn pydantic requests stripe sqlalchemy databases psycopg2-binary passlib python-jose jwt
