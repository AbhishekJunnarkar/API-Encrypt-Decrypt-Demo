# API-Encrypt-Decrypt-Demo
1. Secure storage for parameters and secrets
2. Seamless encryption
3. Version tracking (git)
4. Configuration management
5. Log trail

## API model
- get-parameters --names <name1> <name2> 
- get-parameters-by-path
- get-parameters-by-path --recursive
- get-parameters-by-path --with-decryption


## Parameters example
- /my-app/dev/dburl
- /my-app/prod/dburl
- /my-app/dev/sslpw
- /my-app/prod/sslpw

## Response
- name: <> e.g. /my-app/prod/dbpassword
- type: <> e.g. secureString
- value: <> e.g. prod/database/oracle/prodpass123
- version: <> e.g. 1
- lastModifiedDate: <> e.g. 14892388.234
- lastModifiedBy: <> e.g. junnarkar.abhishek@gmail.com

