# grunt-contrib-connect
customize for lpslib

修改了tasks/connect.js文件第142行为         
middleware.unshift(injectLiveReload({port: options.livereload, hostname: options.hostname,options:options}));
