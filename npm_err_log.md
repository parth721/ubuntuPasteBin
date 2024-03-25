0 verbose cli /home/parth/.nvm/versions/node/v18.19.1/bin/node /home/parth/.nvm/versions/node/v18.19.1/lib/node_modules/npm/bin/npm-cli.js
1 info using npm@10.3.0
2 info using node@v18.19.1
3 timing npm:load:whichnode Completed in 2ms
4 timing config:load:defaults Completed in 3ms
5 timing config:load:file:/home/parth/.nvm/versions/node/v18.19.1/lib/node_modules/npm/npmrc Completed in 1ms
6 timing config:load:builtin Completed in 2ms
7 timing config:load:cli Completed in 3ms
8 timing config:load:env Completed in 1ms
9 timing config:load:project Completed in 6ms
10 timing config:load:file:/home/parth/.npmrc Completed in 0ms
11 timing config:load:user Completed in 1ms
12 timing config:load:file:/home/parth/.nvm/versions/node/v18.19.1/etc/npmrc Completed in 0ms
13 timing config:load:global Completed in 0ms
14 timing config:load:setEnvs Completed in 2ms
15 timing config:load Completed in 18ms
16 timing npm:load:configload Completed in 18ms
17 timing config:load:flatten Completed in 4ms
18 timing npm:load:mkdirpcache Completed in 1ms
19 timing npm:load:mkdirplogs Completed in 1ms
20 verbose title npm exec @backstage/create-app
21 verbose argv "exec" "--" "@backstage/create-app"
22 timing npm:load:setTitle Completed in 1ms
23 timing npm:load:display Completed in 1ms
24 verbose logfile logs-max:10 dir:/home/parth/.npm/_logs/2024-03-25T11_07_21_899Z-
25 verbose logfile /home/parth/.npm/_logs/2024-03-25T11_07_21_899Z-debug-0.log
26 timing npm:load:logFile Completed in 14ms
27 timing npm:load:timers Completed in 0ms
28 timing npm:load:configScope Completed in 0ms
29 timing npm:load Completed in 62ms
30 silly logfile start cleaning logs, removing 1 files
31 silly logfile done cleaning log files
32 timing arborist:ctor Completed in 1ms
33 http fetch GET 200 https://registry.npmjs.org/@backstage%2fcreate-app 2562ms (cache revalidated)
34 timing arborist:ctor Completed in 0ms
35 timing arborist:ctor Completed in 0ms
36 timing command:exec Completed in 6083ms
37 verbose stack Error: canceled
37 verbose stack     at exec (/home/parth/.nvm/versions/node/v18.19.1/lib/node_modules/npm/node_modules/libnpmexec/lib/index.js:270:19)
37 verbose stack     at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
37 verbose stack     at async module.exports (/home/parth/.nvm/versions/node/v18.19.1/lib/node_modules/npm/lib/cli-entry.js:61:5)
38 verbose cwd /home/parth/forster-try
39 verbose Linux 6.5.0-26-generic
40 verbose node v18.19.1
41 verbose npm  v10.3.0
42 error canceled
43 verbose exit 1
44 timing npm Completed in 6502ms
45 verbose code 1
46 error A complete log of this run can be found in: /home/parth/.npm/_logs/2024-03-25T11_07_21_899Z-debug-0.log
