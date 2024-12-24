<p align="center"> 
<img src="images/limesurvey.png" alt="LimeSurvey">
</p>

# LimeSurvey

The package deploys the [LimeSurvey](https://www.limesurvey.org/) solution - is an open-source online statistical survey web application written in PHP. LimeSurvey provides tools to develop and publish simple, quick and anonymous online surveys. Additionally, it enable users to collect responses, review statistics, and export the resulting data to other applications.


## Environment Topology

This package creates a dedicated LimeSurvey environment that contains one application server and one database container. It automatically deploys and sets the LimeSurvey application. The automatic vertical scaling is enabled out of the box, and [horizontal scaling](https://www.virtuozzo.com/application-platform-docs/automatic-horizontal-scaling/) can be configured (if needed). The default software stacks utilized in the package are the following:

- Apache 2 PHP application server (PHP 8.2)
- MySQL 8 database
- LimeSurvey 6.6.5


## Deployment to Cloud

To get your LimeSurvey solution, click the "**Deploy to Cloud**" button below, specify your email address within the widget, choose one of the [Virtuozzo Public Cloud Providers](https://www.virtuozzo.com/application-platform-partners/), and confirm by clicking **Install**.

[![Deploy to Cloud](https://raw.githubusercontent.com/jelastic-jps/common/main/images/deploy-to-cloud.png)](https://www.virtuozzo.com/install/?manifest=https://raw.githubusercontent.com/jelastic-jps/limesurvey/refs/heads/master/manifest.jps)

> If you already have a Virtuozzo Application Platform (VAP) account, you can deploy this solution from the [Marketplace](https://www.virtuozzo.com/application-platform-docs/marketplace/) or [import](https://www.virtuozzo.com/application-platform-docs/environment-import/) a manifest file from this repository.


## Installation Process

In the opened installation window at the VAP dashboard, provide a preferred environment and display names, choose a region (if available), and confirm the installation.

![LimeSurvey deployment wizard](images/limesurvey-deployment-wizard.png)

Your LimeSurvey application will be automatically installed in a few minutes.
