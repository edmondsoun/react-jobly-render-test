to deploy::

 REACT_APP_BASE_URL=https://express-jobly.onrender.com npm run build
 cd build
 echo "/*    /index.html   200" > _redirects
 netlify deploy -p -d .
