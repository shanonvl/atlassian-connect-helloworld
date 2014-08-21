# atlassian-connect-helloworld

Hello World example for Atlassian Connect

## Install

1.  Install the [Atlassian SDK](https://developer.atlassian.com/display/DOCS/Downloads).
2.  Clone this repository

    `git clone https://shanonvl/atlassian-connect-helloworld && cd atlassian-connect-helloworld`

3.  Start the SDK's cloud service ( here on port `8081` )
    
    `atlas-run-standalone --http-port 8081 --product jira --version 6.3-OD-08-005-WN --bundled-plugins com.atlassian.plugins:atlassian-connect-plugin:1.1.0-rc.3,com.atlassian.jwt:jwt-plugin:1.1.0,com.atlassian.bundles:json-schema-validator-atlassian-bundle:1.0.4,com.atlassian.upm:atlassian-universal-plugin-manager-plugin:2.17.2,com.atlassian.webhooks:atlassian-webhooks-plugin:1.0.6 --jvmargs -Datlassian.upm.on.demand=true`


## Usage



