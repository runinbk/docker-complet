```bash
docker container run `
--name nest-app `
-w /app `
-p 80:3000 `
-v ${pwd}:/app `
node:18-alpine3.17 `
sh -c "yarn install && yarn start:dev"
```
