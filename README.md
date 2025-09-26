# SQL Injection on DVWA (Low Security)

## Steps:
1. Run DVWA using Docker.
2. Login with admin/password.
3. Set security level to Low.
4. Navigate to SQL Injection page.
5. Use payload: 1' OR '1'='1

## Result:
DVWA shows all users from the database → proving SQL Injection.
