#!/usr/bin/env groovy

buildPlugin(failFast: false,
            // Opt-in to the Artifact Caching Proxy, to be removed when it will be in opt-out.
            // See https://github.com/jenkins-infra/helpdesk/issues/2752 for more details and updates.
            artifactCachingProxyEnabled: true,
            configurations: [
                [platform: 'linux',   jdk: '11', jenkins: '2.376'],
                [platform: 'linux',   jdk: '11', jenkins: '2.361.3'],
                [platform: 'windows', jdk: '8'],
            ])
