---------------------
TO CREATE:
---------------------

npm install -g create-react-app
create-react-app dockerdemo

---------------------
TO RUN:
---------------------
cd dockerdemo
npm run start

---------------------
To docker:
---------------------

For react router: ensure nginx.conf exists!

docker build -t dockerdemo_js .
docker run -p 5000:80 dockerdemo_js

