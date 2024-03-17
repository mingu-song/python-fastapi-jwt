ref : https://fastapi.tiangolo.com/tutorial/security/oauth2-jwt/

```shell
pip install "python-jose[cryptography]"
pip install "passlib[bcrypt]"
pip install python-multipart

# to generate a secure random secret key
openssl rand -hex 32
```
openapi : http://127.0.0.1:8000/docs