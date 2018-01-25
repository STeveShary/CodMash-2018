# CodMash-2018 Talks
Slides for the talks given at CodeMash 2018 by Stephen Shary

## Devops Zen: Injecting Automated Tests into Infrastructure

Devops zen is to make infrastructure predicable. At Kroger, we use Nginx as a reverse proxy to route traffic with a configuration that is thousands of lines long with pull requests from dozens of teams. Even with this scale, we are still able to complete on-demand deployments to multiple environments that serve dozens of domains and route to over 50 applications clusters with zero downtime. We show an open source framework, SnowGlobe, which allows us to simulate and test every possible traffic routing situation before we deploy. We use a full CI/CD pipeline with 7,000+ tests run for every commit. If boring is zen, then our meditation is automated infrastructure testing.

[Download Presentation here](https://github.com/STeveShary/CodMash-2018/raw/master/DevopsZen.pdf)

[View Snow-Globe, our Nginx testing framework here](https://github.com/Kroger-Technology/Snow-Globe)

## Prod Deployments: What should be the easiest part of your day.

Deployments to production can be a point of fear and tension. We cover strategies that used at Kroger to move new features and fixes to the customer quickly and safely. Industry techniques increased production releases from once a quarter in the middle of the night to dozens of daytime production releases every day. We cover our use trunk based development, dark environments, blue-green deployments, hot toggles, and QA in production to reduce risk. We show how advanced metrics and multi-variate testing strategies can advance you to understand the true value of production changes to customers.

[Download Presentation here](https://github.com/STeveShary/CodMash-2018/raw/master/Production%20Deployments.pdf)
