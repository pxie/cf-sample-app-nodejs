# Node.js / Express app adapted to Predix

## Deploy
```sh
git clone https://github.com/pxie/cf-sample-app-nodejs.git
cd cf-sample-app-nodejs
cf push
```

command line output of `cf push` is,
```

requested state: started
instances: 1/1
usage: 512M x 1 instances
urls: hello-node-interferential-impoverishment.run.aws-jp01-pr.ice.predix.io      <--- application URL
last uploaded: Thu May 18 04:49:19 UTC 2017
stack: cflinuxfs2
buildpack: https://github.com/cloudfoundry/nodejs-buildpack.git

     state     since                    cpu     memory          disk          details
#0   running   2017-05-18 12:49:50 PM   81.0%   75.4M of 512M   53.3M of 1G
```

## Usage

Type above URL in browser, `https://hello-node-interferential-impoverishment.run.aws-jp01-pr.ice.predix.io`

## Tips

https://docs.cloudfoundry.org/buildpacks/node/node-tips.html
