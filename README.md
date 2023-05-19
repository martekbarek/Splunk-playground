# Splunk playground

## Building project:

1. Execute `./run.sh`
2. Splunk will be accessible on `127.0.0.1:8000` in browser
3. Log in with U: **"admin"**, P: **"splunkdev"**

***Apple Sillicon:***
1. Open Docker
2. Install rosetta emulation
3. Enable in Docker Desktop **"Use rosetta for x86/amd64 emulation on Apple Silicon"**
4. Execute `./run.sh`
5. Splunk will be accessible on `127.0.0.1:8000` in browser
6. Log in with U: `admin`, P: `splunkdev`

## Upload test data

***tutorialdata.zip***
`Setting > Add Data > Upload`
https://docs.splunk.com/Documentation/Splunk/9.0.4/SearchTutorial/GetthetutorialdataintoSplunk

## Apply configurations
1. Attach to container
2. Execute `/opt/splunk/bin/splunk restart`
