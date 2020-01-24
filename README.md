# parse-vue-spa-server

## 1.1 Project setup
```
yarn 
```
## 1.2 Config Setup

setup your env

```shell
#  parse-server 
echo "set DATABASE_URI"
export DATABASE_URI="mongodb://username:password@something.mlab.com:45380/parse-db-macauyellopage"
echo "set APP_ID"
export APP_ID="YOUTUB_APPLICATION_ID"
echo "set MASTER_KEY"
export MASTER_KEY="YOUTUB_MASTER_KEY"

#  s3-config for file upload
echo "set S3_ACCESS_KEY"
export S3_ACCESS_KEY="YOU_S3_ACCESS_KEY"
echo "set S3_SECRET_KEY"
export S3_SECRET_KEY="YOU_S3_SECRET_KEY"
echo "set S3_REGION"
export S3_REGION="ap-northeast-1"
echo "set S3_BUCKET"
export S3_BUCKET="bucketn-ame"

#  dashboard setup
echo "set PARSE_DASHBOARD_APP_ID"
export PARSE_DASHBOARD_APP_ID=$APP_ID
echo "set PARSE_DASHBOARD_MASTER_KEY"
export PARSE_DASHBOARD_MASTER_KEY=$MASTER_KEY
echo "set PARSE_DASHBOARD_SERVER_URL"
export PARSE_DASHBOARD_SERVER_URL="http://localhost:1337/parse"
echo "set PARSE_DASHBOARD_APP_NAME"
export PARSE_DASHBOARD_APP_NAME="MyApp"
echo "set PARSE_DASHBOARD_USER_ID"
export PARSE_DASHBOARD_USER_ID="yourDashboardUsername"
echo "set PARSE_DASHBOARD_USER_PASSWORD"
export PARSE_DASHBOARD_USER_PASSWORD="yourPASSWORD"

```



### dev
```
yarn dev
```

### Compiles and minifies for production
```
yarn server:prod
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
