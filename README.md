A plugin for [Jenkins Job
Builder](http://ci.openstack.org/jenkins-job-builder/) to enable the
Jenkins [ClamAV
plugin](https://wiki.jenkins-ci.org/display/JENKINS/ClamAV+Plugin).

[![Code
Health](https://landscape.io/github/garethr/jenkins-job-builder-clamav/master/landscape.png)](https://landscape.io/github/garethr/jenkins-job-builder-clamav/master)

## Usage

Include the following in your job definitions.

```yaml
- publishers:
    - clamav:
        includes: **
```

Note that the ClamAV plugin and
[ClamAV](http://www.clamav.net/) needs to be installed.

## Installation

```bash
pip install jenkins_job_builder_clamav
```
