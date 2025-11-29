# Backend – Sistema de Ingressos de Cinema

API desenvolvida para gerenciar filmes, sessões,  ingressos e entre outros, seguindo os requisitos de Avaliação na disciplina de Sistemas Distribuídos e Mobile.

## Tecnologias
- Python
- Django
- Django Rest Framework
- Oracle Database (OCI)
- Miniconda

## Como rodar
1. Criar e ativar ambiente Miniconda:
   ```
   conda create -n cinema-backend
   conda activate cinema-backend
   ```
2. Configurar variáveis no `.env`
   ```
   SECRET_KEY=... 
   DEBUG= ...
   DB_NAME= ...
   DB_USER= ...
   DB_PASSWORD= ...
   ```
3. Instalar dependências:
   ```
   pip install -r requirements.txt
   ```
4. Aplicar migrações:
   ```
   python manage.py migrate
   ```
5. Rodar:
   ```
   python manage.py runserver
   ```

## Estrutura básica
Cada app contém:
- Models 
- Views
- Serializers
- URLs