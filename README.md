# Hassena-s-Learning-Hub
BrightPath Learning”
Welcome to Alpine!

You can install packages with: apk add <package>

You may change this message by editing /etc/motd.

localhost:~# apk add nodejs npm
(1/8) Installing ca-certificates (20230506-r0)
(2/8) Installing nghttp2-libs (1.43.0-r0)
(3/8) Installing brotli-libs (1.0.9-r5)
(4/8) Installing c-ares (1.17.2-r0)
(5/8) Installing libgcc (10.3.1_git20210424-r2)
(6/8) Installing libstdc++ (10.3.1_git20210424-r2)
(7/8) Installing nodejs (14.21.3-r0)
(8/8) Installing npm (7.17.0-r0)
Executing busybox-1.33.1-r6.trigger
Executing ca-certificates-20230506-r0.trigger
OK: 61 MiB in 22 packages
localhost:~# 
localhost:~# cd /path/to/project
-ash: cd: can't cd to /path/to/project: No such file or directory
localhost:~# cd /path/to/project
-ash: cd: can't cd to /path/to/project: No such file or directory
localhost:~# npm install express

npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'express@5.1.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'body-parser@2.2.0',
npm WARN EBADENGINE   required: { node: '>=18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'merge-descriptors@2.0.0',
npm WARN EBADENGINE   required: { node: '>=18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'router@2.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'send@1.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'serve-static@2.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'path-to-regexp@8.2.0',
npm WARN EBADENGINE   required: { node: '>=16' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
[         .........] \ reify:express: sill audit bulk

added 66 packages, and audited 67 packages in 1m
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'send@1.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'serve-static@2.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'serve-static@2.2.0',
npm WARN EBADENGINE   required: { node: '>= 18' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
npm WARN EBADENGINE Unsupported engine {
npm WARN EBADENGINE   package: 'path-to-regexp@8.2.0',
npm WARN EBADENGINE   required: { node: '>=16' },
npm WARN EBADENGINE   current: { node: 'v14.21.3', npm: '7.17.0' }
npm WARN EBADENGINE }
[         .........] \ reify:express: sill audit bulk

added 66 packages, and audited 67 packages in 1m

14 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
localhost:~# 
localhost:~# 
localhost:~# node server.js
internal/modules/cjs/loader.js:934
  throw err;
  ^

Error: Cannot find module '/root/server.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:931:15)
    at Function.Module._load (internal/modules/cjs/loader.js:774:27)
    at Function.executeUserEntryPoint [as runMain] (internal/modules/run_main.js:75:12)
    at internal/main/run_main_module.js:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
localhost:~# node server.js
internal/modules/cjs/loader.js:934
  throw err;
  ^
