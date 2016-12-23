This is a list of Debian Go language source packages which build compiled Go applications, and
which cannot be compiled across architectures due to a dependency on golang-go (vs. golang-any). 
With each is a list of any build dependencies which explicitly depend on golang-go.


```
acbuild: acbuild
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-appc-spec-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-docker-distribution-dev
     golang-github-opencontainers-image-spec-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-github-juju-loggo-dev
     golang-xi2-x-xz-dev
     golang-github-stevvooe-resumable-dev
     golang-github-revel-revel-dev
     golang-github-coreos-go-tspi-dev
     golang-github-coreos-ioprogress-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-appc-docker2aci-dev
     golang-github-klauspost-cpuid-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-klauspost-compress-dev
     golang-github-garyburd-redigo-dev
     golang-github-coreos-rkt-dev
     golang-github-lsegal-gucumber-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-klauspost-pgzip-dev
     golang-github-gorilla-mux-dev
     golang-github-klauspost-crc32-dev
     golang-github-docker-libtrust-dev

aptly: aptly
     golang
     golang-doc

audit: audispd-plugins, auditd, libaudit-dev, libaudit1, libauparse-dev, libauparse0, python-audit, python3-audit

cadvisor: cadvisor
     golang-go-semver-dev
     golang-github-seandolphin-bqschema-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-abbot-go-http-auth-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-appc-spec-dev
     golang-github-bmizerany-assert-dev
     golang-github-golang-mock-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-datadog-datadog-go-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-shopify-sarama-dev
     golang-gopkg-olivere-elastic.v2-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-docker-libkv-dev
     golang-github-jwilder-encoding-dev
     golang-github-coreos-go-tspi-dev
     golang-github-xiang90-probing-dev
     golang-gopkg-eapache-go-resiliency.v1-dev
     golang-github-hashicorp-go-memdb-dev
     golang-golang-x-exp-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-hashicorp-uuid-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-dgryski-go-bits-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-influxdb-usage-client-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-hashicorp-hil-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-garyburd-redigo-dev
     golang-github-coreos-rkt-dev
     golang-gopkg-tomb.v1-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-gorilla-mux-dev
     golang-github-klauspost-crc32-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

chasquid: chasquid
     golang-github-docopt-docopt-go-dev

codesearch: codesearch

consul: consul
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-docker-libkv-dev
     golang-github-xiang90-probing-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-hashicorp-uuid-dev
     golang-github-elazarl-go-bindata-assetfs-dev
     golang-github-hashicorp-go-reap-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-gorilla-mux-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

consul-migrate: consul-migrate
     golang-github-datadog-datadog-go-dev
     golang-github-armon-gomdb-dev

containerd: containerd
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-docker-libkv-dev
     golang-github-xiang90-probing-dev
     golang-github-cloudfoundry-gosigar-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-cyberdelia-go-metrics-graphite-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-hashicorp-uuid-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-gorilla-mux-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

coyim: coyim
     golang-github-dhowett-go-plist-dev
     golang-github-hydrogen18-stalecucumber-dev
     golang-github-gotk3-gotk3-dev
     golang-github-twstrike-gotk3adapter-dev
     golang-github-twstrike-otr3-dev
     golang-github-thecreeper-go-notify-dev

dh-make-golang: dh-make-golang

direnv: direnv

docker-registry: docker-registry
     golang-github-juju-loggo-dev
     golang-github-garyburd-redigo-dev
     golang-github-stevvooe-resumable-dev
     golang-github-lsegal-gucumber-dev
     golang-github-revel-revel-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-gorilla-mux-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-armon-consul-api-dev
     golang-github-gorilla-handlers-dev
     golang-github-docker-libtrust-dev
     golang-github-agtorre-gocolorize-dev

docker-swarm: docker-swarm
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-bmizerany-assert-dev
     golang-coreos-log-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-mitchellh-cli-dev
     golang-github-mesos-mesos-go-dev
     golang-github-docker-distribution-dev
     golang-github-docker-leadership-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-juju-loggo-dev
     golang-github-stevvooe-resumable-dev
     golang-github-docker-libkv-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-revel-revel-dev
     golang-github-xiang90-probing-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-samalba-dockerclient-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-hashicorp-uuid-dev
     golang-github-docker-engine-api-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-garyburd-redigo-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-gorilla-mux-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-skarademir-naturalsort-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-docker-libtrust-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

docker.io: docker.io
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-vaughan0-go-ini-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-bmizerany-assert-dev
     golang-coreos-log-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-mitchellh-cli-dev
     golang-github-docker-distribution-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-juju-loggo-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-google-btree-dev
     golang-github-stevvooe-resumable-dev
     golang-github-revel-revel-dev
     golang-github-xiang90-probing-dev
     golang-github-docker-libkv-dev
     golang-github-imdario-mergo-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-cloudfoundry-gosigar-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-hashicorp-uuid-dev
     golang-github-docker-engine-api-dev
     golang-go-zfs-dev
     golang-github-docker-libnetwork-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-racksec-srslog-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-golang-x-time-dev
     golang-etcd-server-dev
     golang-github-garyburd-redigo-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-gorilla-mux-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-docker-libtrust-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

etcd: etcd
     golang-go-semver-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xiang90-probing-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-gorilla-mux-dev
     golang-coreos-log-dev
     golang-github-coreos-gexpect-dev
     golang-github-stathat-go-dev
     golang-github-spacejam-loghisto-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-bgentry-speakeasy-dev

etcd-fs: etcd-fs

fleet: fleet
     golang-go-semver-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xiang90-probing-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-gorilla-mux-dev
     golang-coreos-log-dev
     golang-github-rakyll-globalconf-dev
     golang-github-coreos-gexpect-dev
     golang-github-armon-consul-api-dev
     golang-github-stathat-go-dev
     golang-github-glacjay-goini-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-bgentry-speakeasy-dev

fuji: fuji
     golang-eclipse-paho-dev
     golang-gopkg-validator.v2-dev

gb: gb

gitlab-ci-multi-runner: gitlab-ci-multi-runner
     golang-go-semver-dev
     golang-github-seandolphin-bqschema-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-abbot-go-http-auth-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-appc-spec-dev
     golang-github-golang-mock-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-github-docker-distribution-dev
     golang-github-datadog-datadog-go-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-github-docker-go-units-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-emicklei-go-restful-dev
     golang-github-docker-spdystream-dev
     golang-gopkg-olivere-elastic.v2-dev
     golang-github-blang-semver-dev
     golang-github-vdemeester-shakers-dev
     golang-github-armon-go-radix-dev
     golang-github-shopify-sarama-dev
     golang-github-juju-loggo-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-google-btree-dev
     golang-github-stevvooe-resumable-dev
     golang-github-revel-revel-dev
     golang-github-xiang90-probing-dev
     golang-github-docker-libkv-dev
     golang-gopkg-eapache-go-resiliency.v1-dev
     golang-github-jwilder-encoding-dev
     golang-github-imdario-mergo-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-golang-x-exp-dev
     golang-github-coreos-go-tspi-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-hashicorp-uuid-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-dgryski-go-bits-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-influxdb-usage-client-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-hashicorp-hil-dev
     golang-github-ghodss-yaml-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-garyburd-redigo-dev
     golang-github-coreos-rkt-dev
     golang-gopkg-tomb.v1-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-gorilla-mux-dev
     golang-github-klauspost-crc32-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-coreos-go-oidc-dev
     golang-github-docker-libtrust-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-google-cadvisor-dev
     golang-github-hashicorp-go-uuid-dev

go-wire: wire
     golang-github-tendermint-log15-dev
     golang-github-tendermint-go-logger-dev

gobgp: gobgpd
     golang-github-cenk-rpc2-dev
     golang-github-socketplane-libovsdb-dev
     golang-github-cenk-hub-dev
     golang-github-dgryski-go-bits-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-jwilder-encoding-dev
     golang-github-bmizerany-assert-dev
     golang-github-influxdb-usage-client-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-armon-consul-api-dev
     golang-gopkg-eapache-channels.v1-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-armon-go-radix-dev

gocode: gocode

gocryptfs: gocryptfs
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-reqtrace-dev

goiardi: goiardi
     golang-github-hashicorp-errwrap-dev
     golang-github-lsegal-gucumber-dev
     golang-github-raintank-met-dev
     golang-github-mitchellh-cli-dev
     golang-github-pmylund-go-cache-dev
     golang-github-ctdk-go-trie-dev
     golang-gopkg-alexcesaro-statsd.v1-dev
     golang-github-datadog-datadog-go-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-hashicorp-go-version-dev
     golang-github-armon-go-radix-dev

golang-bindata: go-bindata

golang-doozer: golang-doozer-bin

golang-github-appc-docker2aci: docker2aci
     golang-go-semver-dev
     golang-github-appc-spec-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-docker-distribution-dev
     golang-github-opencontainers-image-spec-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-github-juju-loggo-dev
     golang-github-stevvooe-resumable-dev
     golang-github-revel-revel-dev
     golang-github-coreos-ioprogress-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-klauspost-cpuid-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-klauspost-compress-dev
     golang-github-garyburd-redigo-dev
     golang-github-lsegal-gucumber-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-klauspost-pgzip-dev
     golang-github-gorilla-mux-dev
     golang-github-klauspost-crc32-dev
     golang-github-docker-libtrust-dev

golang-github-appc-spec: appc-spec
     golang-speter-go-exp-math-dec-inf-dev
     golang-go-semver-dev

golang-github-benbjohnson-tmpl: tmpl

golang-github-calmh-xdr: genxdr

golang-github-cloudflare-redoctober: golang-redoctober

golang-github-docker-docker-credential-helpers: golang-docker-credential-helpers

golang-github-geertjohan-go.rice: golang-rice
     golang-github-daaku-go.zipexe-dev
     golang-github-jessevdk-go-flags-dev
     golang-github-geertjohan-go.incremental-dev
     golang-github-akavel-rsrc-dev

golang-github-golang-mock: mockgen

golang-github-hashicorp-serf: serf
     golang-github-datadog-datadog-go-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-mitchellh-cli-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-armon-go-radix-dev

golang-github-hpcloud-tail: gotail
     golang-gopkg-tomb.v1-dev

golang-github-masterzen-winrm: winrm
     golang-github-masterzen-simplexml-dev
     golang-github-masterzen-xmlpath-dev
     golang-github-nu7hatch-gouuid-dev

golang-github-odeke-em-cli-spinner: cli-spinner

golang-github-odeke-em-ripper: ripper

golang-github-opencontainers-image-spec: oci-image-tool
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-opencontainers-specs-dev
     golang-github-armon-consul-api-dev
     golang-github-xeipuuv-gojsonpointer-dev

golang-github-pointlander-peg: peg-go
     golang-github-pointlander-compress-dev
     golang-github-nfnt-resize-dev
     golang-github-pointlander-jetset-dev
     golang-github-kjk-lzma-dev

golang-github-rakyll-statik: golang-statik

golang-github-spf13-cobra: cobra
     golang-github-armon-consul-api-dev

golang-github-tinylib-msgp: msgp

golang-github-vbatts-tar-split: tar-split

golang-github-xenolf-lego: lego
     golang-github-lsegal-gucumber-dev

golang-github-xordataexchange-crypt: golang-github-xordataexchange-crypt
     golang-github-armon-consul-api-dev

golang-glide: glide

golang-gogoprotobuf: gogoprotobuf

golang-golang-x-exp: ebnflint
     golang-doc

golang-petname: golang-github-dustinkirkland-golang-petname-dev, golang-petname

golang-vhost: golang-vhost-dev

google-cloud-print-connector: google-cloud-print-connector

gosu: gosu
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-opencontainers-specs-dev
     golang-github-docker-go-units-dev

gox: gox
     golang-github-mitchellh-iochan-dev

grafana: grafana
     golang-github-gosimple-slug-dev
     golang-gopkg-redis.v2-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-vaughan0-go-ini-dev
     golang-gopkg-ini.v1-dev
     golang-github-jtolds-gls-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-go-xorm-xorm-dev
     golang-github-rainycape-unidecode-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-go-macaron-session-dev
     golang-github-go-xorm-core-dev
     golang-gopkg-bufio.v1-dev
     golang-github-go-ldap-ldap-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-klauspost-cpuid-dev
     golang-gopkg-asn1-ber.v1-dev
     golang-github-smartystreets-assertions-dev
     golang-github-streadway-amqp-dev
     golang-github-go-macaron-binding-dev
     golang-github-go-macaron-inject-dev
     golang-github-klauspost-compress-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-lsegal-gucumber-dev
     golang-github-go-macaron-gzip-dev
     golang-github-klauspost-crc32-dev
     golang-github-unknwon-com-dev

heartbleeder: heartbleeder
     golang
     golang-doc

hugo: hugo
     golang-github-armon-consul-api-dev

influxdb: influxdb, influxdb-client
     golang-github-dgryski-go-bits-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-jwilder-encoding-dev
     golang-github-bmizerany-assert-dev
     golang-github-influxdb-usage-client-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-paulbellamy-ratecounter-dev

jid: jid
     golang-github-mattn-go-runewidth-dev
     golang-github-nsf-termbox-go-dev
     golang-github-bmizerany-assert-dev

kxd: kxc, kxd

libguestfs: erlang-guestfs, gir1.2-guestfs-1.0, guestfsd, libguestfs-dev, libguestfs-gfs2, libguestfs-gobject-1.0-0, libguestfs-gobject-dev, libguestfs-hfsplus, libguestfs-java, libguestfs-jfs, libguestfs-nilfs, libguestfs-ocaml, libguestfs-ocaml-dev, libguestfs-perl, libguestfs-reiserfs, libguestfs-rescue, libguestfs-rsync, libguestfs-tools, libguestfs-xfs, libguestfs-zfs, libguestfs0, libguestfs0-dbg, lua-guestfs, php-guestfs, python-guestfs, python3-guestfs, ruby-guestfs

minica: minica
     golang-pault-go-topsort-dev
     golang-pault-go-debian-dev
     golang-pault-go-config-dev

mongo-tools: mongo-tools
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-jtolds-gls-dev
     golang-github-smartystreets-assertions-dev

nomad: nomad
     golang-go-semver-dev
     golang-github-mitchellh-hashstructure-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-mitchellh-colorstring-dev
     golang-github-inconshreveable-muxado-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-mitchellh-go-ps-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-hashicorp-go-plugin-dev
     golang-github-docker-libkv-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xiang90-probing-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-nytimes-gziphandler-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-go-version-dev
     golang-github-hashicorp-go-getter-dev
     golang-github-dustin-go-humanize-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-gorilla-mux-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

notary: notary
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-bmizerany-assert-dev
     golang-coreos-log-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-mitchellh-cli-dev
     golang-github-docker-distribution-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-juju-loggo-dev
     golang-github-google-btree-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-stevvooe-resumable-dev
     golang-github-docker-libkv-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-revel-revel-dev
     golang-github-xiang90-probing-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-robfig-config-dev
     golang-github-armon-consul-api-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-hashicorp-uuid-dev
     golang-github-tent-canonical-json-go-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-garyburd-redigo-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-gorilla-mux-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-docker-libtrust-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

obfs4proxy: obfs4proxy

packer: packer
     golang-github-hashicorp-errwrap-dev
     golang-github-mitchellh-cli-dev
     golang-github-dylanmei-iso8601-dev
     golang-github-packer-community-winrmcp-dev
     golang-github-masterzen-winrm-dev
     golang-github-rackspace-gophercloud-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-mitchellh-multistep-dev
     golang-github-armon-go-radix-dev
     golang-github-azure-go-ntlmssp-dev
     golang-github-tent-http-link-go-dev
     golang-github-dylanmei-winrmtest-dev
     golang-github-mitchellh-go-vnc-dev
     golang-gopkg-xmlpath.v2-dev
     golang-github-google-go-querystring-dev
     golang-github-hpcloud-tail-dev
     golang-github-hashicorp-go-version-dev
     golang-github-mitchellh-panicwrap-dev
     golang-github-mitchellh-iochan-dev
     golang-github-klauspost-cpuid-dev
     golang-github-pierrec-xxhash-dev
     golang-github-mitchellh-go-fs-dev
     golang-github-hashicorp-yamux-dev
     golang-github-hashicorp-atlas-go-dev
     golang-github-masterzen-simplexml-dev
     golang-github-mitchellh-prefixedio-dev
     golang-github-klauspost-compress-dev
     golang-gopkg-tomb.v1-dev
     golang-github-lsegal-gucumber-dev
     golang-github-masterzen-xmlpath-dev
     golang-github-klauspost-pgzip-dev
     golang-github-klauspost-crc32-dev
     golang-github-nu7hatch-gouuid-dev
     golang-github-digitalocean-godo-dev

paxrat: paxrat
     golang-golang-x-exp-dev

peco: peco
     golang-github-mattn-go-runewidth-dev
     golang-github-lestrrat-go-pdebug-dev
     golang-github-nsf-termbox-go-dev
     golang-github-google-btree-dev

pluginhook: pluginhook

prometheus: prometheus
     golang-github-lsegal-gucumber-dev

prometheus-blackbox-exporter: prometheus-blackbox-exporter

prometheus-mailexporter: prometheus-mailexporter

prometheus-mysqld-exporter: prometheus-mysqld-exporter
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jacobsa-oglematchers-dev
     golang-gopkg-ini.v1-dev
     golang-github-jtolds-gls-dev
     golang-github-smartystreets-assertions-dev

prometheus-varnish-exporter: prometheus-varnish-exporter

pt-websocket: pt-websocket

ratt: ratt
     golang-pault-go-topsort-dev
     golang-pault-go-debian-dev

rawdns: rawdns

rclone: rclone
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-lsegal-gucumber-dev
     golang-github-jtolds-gls-dev
     golang-github-armon-consul-api-dev
     golang-github-smartystreets-assertions-dev
     golang-github-google-go-querystring-dev

rkt: rkt
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-appc-goaci-dev
     golang-github-appc-spec-dev
     golang-github-cznic-zappy-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-coreos-go-iptables-dev
     golang-github-docker-distribution-dev
     golang-github-opencontainers-image-spec-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-cznic-ql-dev
     golang-github-juju-loggo-dev
     golang-github-google-btree-dev
     golang-github-stevvooe-resumable-dev
     golang-github-revel-revel-dev
     golang-github-coreos-go-tspi-dev
     golang-github-appc-cni-dev
     golang-github-cznic-fileutil-dev
     golang-github-coreos-ioprogress-dev
     golang-github-cznic-lldb-dev
     golang-github-robfig-config-dev
     golang-github-hydrogen18-stoppablelistener-dev
     golang-github-armon-consul-api-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-peterbourgon-diskv-dev
     golang-github-appc-docker2aci-dev
     golang-github-remyoudompheng-bigfft-dev
     golang-github-klauspost-cpuid-dev
     golang-github-d2g-dhcp4client-dev
     golang-github-dustin-go-humanize-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-cznic-strutil-dev
     golang-github-gorilla-handlers-dev
     golang-github-robfig-pathtree-dev
     golang-github-cznic-mathutil-dev
     golang-github-klauspost-compress-dev
     golang-github-garyburd-redigo-dev
     golang-github-cznic-sortutil-dev
     golang-github-lsegal-gucumber-dev
     golang-github-d2g-dhcp4-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-klauspost-pgzip-dev
     golang-github-gorilla-mux-dev
     golang-github-klauspost-crc32-dev
     golang-github-coreos-gexpect-dev
     golang-github-inconshreveable-mousetrap-dev
     golang-github-cznic-b-dev
     golang-github-docker-libtrust-dev
     golang-github-cznic-bufs-dev
     golang-github-jonboulle-clockwork-dev

robustirc-bridge: robustirc-bridge

runc: runc
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-opencontainers-specs-dev
     golang-github-docker-go-units-dev

skydns: skydns
     golang-github-stathat-go-dev

slt: slt

snapd: snapd
     golang-gopkg-macaroon.v1-dev
     golang-github-gorilla-mux-dev

syncthing: syncthing, syncthing-discosrv, syncthing-relaysrv
     golang-github-calmh-xdr-dev
     golang-github-minio-sha256-simd-dev
     golang-github-audriusbutkevicius-go-nat-pmp-dev
     golang-github-cznic-zappy-dev
     golang-github-oschwald-maxminddb-golang-dev
     golang-github-oschwald-geoip2-golang-dev
     golang-github-cznic-ql-dev
     golang-github-golang-groupcache-dev
     golang-github-cznic-fileutil-dev
     golang-github-cznic-lldb-dev
     golang-github-stathat-go-dev
     golang-github-remyoudompheng-bigfft-dev
     golang-github-thejerf-suture-dev
     golang-github-bkaradzic-go-lz4-dev
     golang-github-vitrun-qart-dev
     golang-github-cznic-strutil-dev
     golang-github-d4l3k-messagediff-dev
     genxdr
     golang-github-cznic-mathutil-dev
     golang-github-calmh-du-dev
     golang-github-calmh-luhn-dev
     golang-github-sasha-s-go-deadlock-dev
     golang-github-cznic-sortutil-dev
     golang-github-gobwas-glob-dev
     golang-github-jackpal-gateway-dev
     golang-github-cznic-b-dev
     golang-github-cznic-bufs-dev

systemd-docker: systemd-docker
     golang-go-semver-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-docker-go-connections-dev
     golang-github-inconshreveable-muxado-dev
     golang-coreos-log-dev
     golang-github-mitchellh-cli-dev
     golang-github-datadog-datadog-go-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-docker-go-units-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-armon-go-radix-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-google-btree-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-docker-libkv-dev
     golang-github-xiang90-probing-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-opencontainers-specs-dev
     golang-github-stathat-go-dev
     golang-github-hashicorp-uuid-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-hashicorp-yamux-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-consul-dev
     golang-github-mattn-go-shellwords-dev
     golang-etcd-server-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-gorilla-mux-dev
     golang-github-coreos-gexpect-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-hashicorp-go-uuid-dev

toxiproxy: toxiproxy, toxiproxy-cli
     golang-gopkg-tomb.v1-dev
     golang-github-gorilla-mux-dev

webhook: webhook
     golang-github-gorilla-mux-dev
     golang-github-urfave-negroni-dev

winrmcp: winrmcp
     golang-github-masterzen-xmlpath-dev
     golang-github-masterzen-simplexml-dev
     golang-github-masterzen-winrm-dev
     golang-github-dylanmei-iso8601-dev
     golang-github-nu7hatch-gouuid-dev
```
