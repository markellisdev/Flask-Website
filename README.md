# My foray into building an old proof of concept version of my website -- now using Flask, deploying with Lambda via Zappa

A couple of years ago, I had created a simple site using [Freelancer](https://startbootstrap.com/themes/freelancer/), a one page freelancer portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). I haven't been writing in Python since 2017, so I thought I'd pick back up by creating a Flask version of this old site.

After I successfully got this working locally, I decided to deploy remotely. I settled on using Zappa and AWS Lambda. It now works remotely and eventually plan to give it a custom more descriptive url, but for now, it should be reachable [here](https://orznqq64rf.execute-api.us-east-1.amazonaws.com/dev).

NOTE: For now, the Contact form has no way of working, so I'd like to eventually troubleshoot that issue...... but it's not really a priority since I only set out to prove concepts and improve my skills.... not build a fully funtioning website.

## References/Resources Used
For Zappa/Lambda deployment, I relied mainly on this article, [Deploy a Serverless Web App on AWS Lambda with Zappa](https://pythonforundergradengineers.com/deploy-serverless-web-app-aws-lambda-zappa.html)

For Zappa reference, [the repo](https://github.com/Miserlou/Zappa) is most helpful.

For an AWS policy of least privilege, [this one](https://github.com/Miserlou/Zappa/issues/244#issuecomment-632490490) worked for me.

## Copyright and License

Copyright ©2016-2020 Mark Ellis Development and Consulting.