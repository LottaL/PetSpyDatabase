# PetSpyDatabase API

This is deployed in Heroku, https://rocky-wildwood-93957.herokuapp.com/

Does not work though. Runs locally just fine. Following some error logs, looking at the package.json you'll notice start script exists so wtf??

2019-10-03T21:33:23.466004+00:00 heroku[web.1]: Process exited with status 1
2019-10-03T21:33:23.504607+00:00 heroku[web.1]: State changed from starting to crashed
2019-10-03T21:33:23.393351+00:00 app[web.1]: npm ERR! missing script: start
2019-10-03T21:33:23.401223+00:00 app[web.1]:
2019-10-03T21:33:23.401476+00:00 app[web.1]: npm ERR! A complete log of this run can be found in:
2019-10-03T21:33:23.40156+00:00 app[web.1]: npm ERR!     /app/.npm/_logs/2019-10-03T21_33_23_394Z-debug.log
2019-10-03T21:33:24.454756+00:00 heroku[router]: at=error code=H10 desc="App crashed" method=GET path="/" host=rocky-wildwood-93957.herokuapp.com request_id=13452b68-c73c-4100-8c2d-d1262184aeaa fwd="213.243.171.54" dyno= connect= service= status=503 bytes= protocol=https
2019-10-03T21:33:25.343385+00:00 heroku[router]: at=error code=H10 desc="App crashed" method=GET path="/favicon.ico" host=rocky-wildwood-93957.herokuapp.com request_id=140dd812-0582-4e7c-a2c7-d79d3136f29e fwd="213.243.171.54" dyno= connect= service= status=503 bytes= protocol=https
2019-10-03T21:33:31.450083+00:00 heroku[router]: at=error code=H10 desc="App crashed" method=GET path="/users" host=rocky-wildwood-93957.herokuapp.com request_id=3def6260-c883-4f50-a1e7-b361a0898a9b fwd="213.243.171.54" dyno= connect= service= status=503 bytes= protocol=https
2019-10-03T21:36:48.815601+00:00 heroku[web.1]: State changed from crashed to starting
2019-10-03T21:36:50.938134+00:00 heroku[web.1]: Starting process with command `npm start`
2019-10-03T21:36:53.37328+00:00 heroku[web.1]: Process exited with status 1
2019-10-03T21:36:53.421787+00:00 heroku[web.1]: State changed from starting to crashed
2019-10-03T21:36:53.302208+00:00 app[web.1]: npm ERR! missing script: start
2019-10-03T21:36:53.315112+00:00 app[web.1]:
2019-10-03T21:36:53.315794+00:00 app[web.1]: npm ERR! A complete log of this run can be found in:
2019-10-03T21:36:53.316095+00:00 app[web.1]: npm ERR!     /app/.npm/_logs/2019-10-03T21_36_53_308Z-debug.log

