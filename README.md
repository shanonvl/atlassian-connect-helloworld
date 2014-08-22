# atlassian-connect-helloworld

Functional "Getting Started" example from the [Atlassian website](https://developer.atlassian.com/static/connect/docs/guides/getting-started.html)

## Dependencies

* nodejs / npm 0.10+
* [Atlassian SDK](https://developer.atlassian.com/display/DOCS/Downloads)
  
  Homebrew: `brew tap atlassian/tap && brew install atlassian/tap/atlassian-connect-sdk`

## Install

1.  Clone this repository

    `git clone https://shanonvl/atlassian-connect-helloworld`

2.  Pull dependencies

    `npm install`

## Usage

1.  Start a local _cloud instance_ of JIRA

    `atlas-run-standalone --product jira --version 6.3-OD-08-005-WN --bundled-plugins com.atlassian.plugins:atlassian-connect-plugin:1.1.0-rc.3,com.atlassian.jwt:jwt-plugin:1.1.0,com.atlassian.bundles:json-schema-validator-atlassian-bundle:1.0.4,com.atlassian.upm:atlassian-universal-plugin-manager-plugin:2.17.2,com.atlassian.webhooks:atlassian-webhooks-plugin:1.0.6 --jvmargs -Datlassian.upm.on.demand=true`

2.  Start the local web server:

    `./http-server.sh [-p PORT]`

3.  Browse to your local JIRA:  `http://localhost:2990/jira/`

4.  Login with `admin/admin`
  
5.  


