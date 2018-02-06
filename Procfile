local: NODE_ENV=staging-local node ./app.js
web: http-server ./dist/
server: NODE_ENV=production node ./app.js
#pm2: NODE_ENV=staging-local pm2 start app.js -n dashboardserver -i 0 --merge-logs