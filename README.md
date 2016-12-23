This is a list of Debian Go language source packages which build compiled Go applications, and
which cannot be compiled across architectures due to a dependency on golang-go (vs. golang-any). 
With each is a list of any build dependencies which explicitly depend on golang-go.


```

acbuild: acbuild (13)
     golang-github-agtorre-gocolorize-dev
     golang-github-appc-docker2aci-dev
     golang-github-appc-spec-dev
     golang-github-armon-consul-api-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-go-tspi-dev
     golang-github-coreos-ioprogress-dev
     golang-github-coreos-rkt-dev
     golang-github-docker-distribution-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-juju-loggo-dev
     golang-github-klauspost-compress-dev
     golang-github-klauspost-cpuid-dev
     golang-github-klauspost-crc32-dev
     golang-github-klauspost-pgzip-dev
     golang-github-lsegal-gucumber-dev
     golang-github-opencontainers-image-spec-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-stevvooe-resumable-dev
     golang-go-semver-dev
     golang-speter-go-exp-math-dec-inf-dev
     golang-xi2-x-xz-dev

aptly: aptly (231)
     golang
     golang-doc

cadvisor: cadvisor (10)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-abbot-go-http-auth-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-appc-spec-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-bmizerany-assert-dev
     golang-github-coreos-gexpect-dev
     golang-github-coreos-go-tspi-dev
     golang-github-coreos-rkt-dev
     golang-github-datadog-datadog-go-dev
     golang-github-dgryski-go-bits-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-garyburd-redigo-dev
     golang-github-golang-mock-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-influxdb-usage-client-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-jwilder-encoding-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-klauspost-crc32-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-seandolphin-bqschema-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-shopify-sarama-dev
     golang-github-stathat-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev
     golang-golang-x-exp-dev
     golang-gopkg-eapache-go-resiliency.v1-dev
     golang-gopkg-olivere-elastic.v2-dev
     golang-gopkg-tomb.v1-dev
     golang-speter-go-exp-math-dec-inf-dev

chasquid: chasquid (0)
     golang-github-docopt-docopt-go-dev

codesearch: codesearch (21)

consul: consul (2424)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-elazarl-go-bindata-assetfs-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-reap-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

consul-migrate: consul-migrate (0)
     golang-github-armon-gomdb-dev
     golang-github-datadog-datadog-go-dev

containerd: containerd (926)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-cloudfoundry-gosigar-dev
     golang-github-coreos-gexpect-dev
     golang-github-cyberdelia-go-metrics-graphite-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

coyim: coyim (18)
     golang-github-dhowett-go-plist-dev
     golang-github-gotk3-gotk3-dev
     golang-github-hydrogen18-stalecucumber-dev
     golang-github-thecreeper-go-notify-dev
     golang-github-twstrike-gotk3adapter-dev
     golang-github-twstrike-otr3-dev

dh-make-golang: dh-make-golang (53)

direnv: direnv (85)

docker-registry: docker-registry (66)
     golang-github-agtorre-gocolorize-dev
     golang-github-armon-consul-api-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-juju-loggo-dev
     golang-github-lsegal-gucumber-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-stevvooe-resumable-dev

docker-swarm: docker-swarm (31)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-consul-api-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-distribution-dev
     golang-github-docker-engine-api-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-leadership-dev
     golang-github-docker-libkv-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-google-btree-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-juju-loggo-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mesos-mesos-go-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-samalba-dockerclient-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-skarademir-naturalsort-dev
     golang-github-stathat-go-dev
     golang-github-stevvooe-resumable-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

docker.io: docker.io (1752)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-consul-api-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-cloudfoundry-gosigar-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-distribution-dev
     golang-github-docker-engine-api-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-docker-libnetwork-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-google-btree-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-imdario-mergo-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-juju-loggo-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-racksec-srslog-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-stevvooe-resumable-dev
     golang-github-vaughan0-go-ini-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev
     golang-go-zfs-dev
     golang-golang-x-time-dev

etcd: etcd (37)
     golang-coreos-log-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-coreos-gexpect-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-spacejam-loghisto-dev
     golang-github-stathat-go-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

etcd-fs: etcd-fs (6)

fleet: fleet (5)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-consul-api-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-coreos-gexpect-dev
     golang-github-glacjay-goini-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-rakyll-globalconf-dev
     golang-github-stathat-go-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

fuji: fuji (1)
     golang-eclipse-paho-dev
     golang-gopkg-validator.v2-dev

gb: gb (12)

gitlab-ci-multi-runner: gitlab-ci-multi-runner (270)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-abbot-go-http-auth-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-appc-spec-dev
     golang-github-armon-consul-api-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-blang-semver-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-gexpect-dev
     golang-github-coreos-go-oidc-dev
     golang-github-coreos-go-tspi-dev
     golang-github-coreos-rkt-dev
     golang-github-datadog-datadog-go-dev
     golang-github-dgryski-go-bits-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-docker-distribution-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-docker-libtrust-dev
     golang-github-docker-spdystream-dev
     golang-github-emicklei-go-restful-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-garyburd-redigo-dev
     golang-github-ghodss-yaml-dev
     golang-github-golang-mock-dev
     golang-github-google-btree-dev
     golang-github-google-cadvisor-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-imdario-mergo-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-influxdb-usage-client-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-juju-loggo-dev
     golang-github-jwilder-encoding-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-klauspost-crc32-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-seandolphin-bqschema-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-shopify-sarama-dev
     golang-github-stathat-go-dev
     golang-github-stevvooe-resumable-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev
     golang-golang-x-exp-dev
     golang-gopkg-eapache-go-resiliency.v1-dev
     golang-gopkg-olivere-elastic.v2-dev
     golang-gopkg-tomb.v1-dev
     golang-speter-go-exp-math-dec-inf-dev

go-wire: wire (37)
     golang-github-tendermint-go-logger-dev
     golang-github-tendermint-log15-dev

gobgp: gobgpd (1)
     golang-github-armon-consul-api-dev
     golang-github-armon-go-radix-dev
     golang-github-bmizerany-assert-dev
     golang-github-cenk-hub-dev
     golang-github-cenk-rpc2-dev
     golang-github-dgryski-go-bits-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-influxdb-usage-client-dev
     golang-github-jwilder-encoding-dev
     golang-github-paulbellamy-ratecounter-dev
     golang-github-socketplane-libovsdb-dev
     golang-gopkg-eapache-channels.v1-dev

gocode: gocode (201)

gocryptfs: gocryptfs (9)
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-reqtrace-dev

goiardi: goiardi (2)
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-ctdk-go-trie-dev
     golang-github-datadog-datadog-go-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-version-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mitchellh-cli-dev
     golang-github-pmylund-go-cache-dev

golang-bindata: go-bindata (19)

golang-doozer: golang-doozer-bin (8)

golang-github-appc-docker2aci: docker2aci (15)
     golang-github-agtorre-gocolorize-dev
     golang-github-appc-spec-dev
     golang-github-armon-consul-api-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-ioprogress-dev
     golang-github-docker-distribution-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-juju-loggo-dev
     golang-github-klauspost-compress-dev
     golang-github-klauspost-cpuid-dev
     golang-github-klauspost-crc32-dev
     golang-github-klauspost-pgzip-dev
     golang-github-lsegal-gucumber-dev
     golang-github-opencontainers-image-spec-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-stevvooe-resumable-dev
     golang-go-semver-dev
     golang-speter-go-exp-math-dec-inf-dev

golang-github-appc-spec: appc-spec (8)
     golang-go-semver-dev
     golang-speter-go-exp-math-dec-inf-dev

golang-github-benbjohnson-tmpl: tmpl (4)

golang-github-calmh-xdr: genxdr (6)

golang-github-cloudflare-redoctober: golang-redoctober (1)

golang-github-docker-docker-credential-helpers: golang-docker-credential-helpers (1)

golang-github-geertjohan-go.rice: golang-rice (1)
     golang-github-akavel-rsrc-dev
     golang-github-daaku-go.zipexe-dev
     golang-github-geertjohan-go.incremental-dev
     golang-github-jessevdk-go-flags-dev

golang-github-golang-mock: mockgen (5)

golang-github-hashicorp-serf: serf (7)
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-datadog-datadog-go-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-mitchellh-cli-dev

golang-github-hpcloud-tail: gotail (5)
     golang-gopkg-tomb.v1-dev

golang-github-masterzen-winrm: winrm (18)
     golang-github-masterzen-simplexml-dev
     golang-github-masterzen-xmlpath-dev
     golang-github-nu7hatch-gouuid-dev

golang-github-odeke-em-cli-spinner: cli-spinner (5)

golang-github-odeke-em-ripper: ripper (8)

golang-github-opencontainers-image-spec: oci-image-tool (4)
     golang-github-armon-consul-api-dev
     golang-github-opencontainers-specs-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev

golang-github-pointlander-peg: peg-go (1)
     golang-github-kjk-lzma-dev
     golang-github-nfnt-resize-dev
     golang-github-pointlander-compress-dev
     golang-github-pointlander-jetset-dev

golang-github-rakyll-statik: golang-statik (4)

golang-github-spf13-cobra: cobra (5)
     golang-github-armon-consul-api-dev

golang-github-tinylib-msgp: msgp (2)

golang-github-vbatts-tar-split: tar-split (15)

golang-github-xenolf-lego: lego (7)
     golang-github-lsegal-gucumber-dev

golang-github-xordataexchange-crypt: golang-github-xordataexchange-crypt (2)
     golang-github-armon-consul-api-dev

golang-glide: glide (23)

golang-gogoprotobuf: gogoprotobuf (24)

golang-golang-x-exp: ebnflint (2)
     golang-doc

golang-petname: golang-github-dustinkirkland-golang-petname-dev (1), golang-petname (4)

golang-vhost: golang-vhost-dev (15)

google-cloud-print-connector: google-cloud-print-connector (48)

gosu: gosu (11)
     golang-github-docker-go-units-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev

gox: gox (11)
     golang-github-mitchellh-iochan-dev

grafana: grafana (348)
     golang-github-bradfitz-gomemcache-dev
     golang-github-go-ldap-ldap-dev
     golang-github-go-macaron-binding-dev
     golang-github-go-macaron-gzip-dev
     golang-github-go-macaron-inject-dev
     golang-github-go-macaron-session-dev
     golang-github-go-xorm-core-dev
     golang-github-go-xorm-xorm-dev
     golang-github-gosimple-slug-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jtolds-gls-dev
     golang-github-klauspost-compress-dev
     golang-github-klauspost-cpuid-dev
     golang-github-klauspost-crc32-dev
     golang-github-lsegal-gucumber-dev
     golang-github-rainycape-unidecode-dev
     golang-github-smartystreets-assertions-dev
     golang-github-streadway-amqp-dev
     golang-github-unknwon-com-dev
     golang-github-vaughan0-go-ini-dev
     golang-gopkg-asn1-ber.v1-dev
     golang-gopkg-bufio.v1-dev
     golang-gopkg-ini.v1-dev
     golang-gopkg-redis.v2-dev

heartbleeder: heartbleeder (50)
     golang
     golang-doc

hugo: hugo (210)
     golang-github-armon-consul-api-dev

influxdb: influxdb (241), influxdb-client (29)
     golang-github-bmizerany-assert-dev
     golang-github-dgryski-go-bits-dev
     golang-github-dgryski-go-bitstream-dev
     golang-github-influxdb-enterprise-client-dev
     golang-github-influxdb-usage-client-dev
     golang-github-jwilder-encoding-dev
     golang-github-paulbellamy-ratecounter-dev

jid: jid (20)
     golang-github-bmizerany-assert-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-nsf-termbox-go-dev

kxd: kxc (2), kxd (2)

libguestfs: erlang-guestfs (7), gir1.2-guestfs-1.0 (5), guestfsd (38), libguestfs-dev (27), libguestfs-gfs2 (48), libguestfs-gobject-1.0-0 (13), libguestfs-gobject-dev (8), libguestfs-hfsplus (895), libguestfs-java (16), libguestfs-jfs (62), libguestfs-nilfs (61), libguestfs-ocaml (7), libguestfs-ocaml-dev (5), libguestfs-perl (665), libguestfs-reiserfs (892), libguestfs-rescue (89), libguestfs-rsync (90), libguestfs-tools (660), libguestfs-xfs (905), libguestfs-zfs (61), libguestfs0 (1162), libguestfs0-dbg (3), lua-guestfs (3), php-guestfs (1), python-guestfs (286), python3-guestfs (142), ruby-guestfs (12)

minica: minica (1)
     golang-pault-go-config-dev
     golang-pault-go-debian-dev
     golang-pault-go-topsort-dev

mongo-tools: mongo-tools (52)
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jtolds-gls-dev
     golang-github-smartystreets-assertions-dev

nomad: nomad (8)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-dustin-go-humanize-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-getter-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-plugin-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-go-version-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-mitchellh-colorstring-dev
     golang-github-mitchellh-go-ps-dev
     golang-github-mitchellh-hashstructure-dev
     golang-github-nytimes-gziphandler-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

notary: notary (1)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-agtorre-gocolorize-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-consul-api-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-distribution-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-docker-libtrust-dev
     golang-github-garyburd-redigo-dev
     golang-github-google-btree-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-juju-loggo-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-lsegal-gucumber-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-stevvooe-resumable-dev
     golang-github-tent-canonical-json-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

obfs4proxy: obfs4proxy (139)

packer: packer (69)
     golang-github-armon-go-radix-dev
     golang-github-azure-go-ntlmssp-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-digitalocean-godo-dev
     golang-github-dylanmei-iso8601-dev
     golang-github-dylanmei-winrmtest-dev
     golang-github-google-go-querystring-dev
     golang-github-hashicorp-atlas-go-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-version-dev
     golang-github-hashicorp-yamux-dev
     golang-github-hpcloud-tail-dev
     golang-github-klauspost-compress-dev
     golang-github-klauspost-cpuid-dev
     golang-github-klauspost-crc32-dev
     golang-github-klauspost-pgzip-dev
     golang-github-lsegal-gucumber-dev
     golang-github-masterzen-simplexml-dev
     golang-github-masterzen-winrm-dev
     golang-github-masterzen-xmlpath-dev
     golang-github-mitchellh-cli-dev
     golang-github-mitchellh-go-fs-dev
     golang-github-mitchellh-go-vnc-dev
     golang-github-mitchellh-iochan-dev
     golang-github-mitchellh-multistep-dev
     golang-github-mitchellh-panicwrap-dev
     golang-github-mitchellh-prefixedio-dev
     golang-github-nu7hatch-gouuid-dev
     golang-github-packer-community-winrmcp-dev
     golang-github-pierrec-xxhash-dev
     golang-github-rackspace-gophercloud-dev
     golang-github-tent-http-link-go-dev
     golang-gopkg-tomb.v1-dev
     golang-gopkg-xmlpath.v2-dev

paxrat: paxrat (16)
     golang-golang-x-exp-dev

peco: peco (26)
     golang-github-google-btree-dev
     golang-github-lestrrat-go-pdebug-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-nsf-termbox-go-dev

pluginhook: pluginhook (11)

prometheus: prometheus (23)
     golang-github-lsegal-gucumber-dev

prometheus-blackbox-exporter: prometheus-blackbox-exporter (4)

prometheus-mailexporter: prometheus-mailexporter (0)

prometheus-mysqld-exporter: prometheus-mysqld-exporter (3)
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jtolds-gls-dev
     golang-github-smartystreets-assertions-dev
     golang-gopkg-ini.v1-dev

prometheus-varnish-exporter: prometheus-varnish-exporter (1)

pt-websocket: pt-websocket (3)

ratt: ratt (20)
     golang-pault-go-debian-dev
     golang-pault-go-topsort-dev

rawdns: rawdns (2)

rclone: rclone (48)
     golang-github-armon-consul-api-dev
     golang-github-google-go-querystring-dev
     golang-github-jacobsa-oglematchers-dev
     golang-github-jacobsa-oglemock-dev
     golang-github-jacobsa-ogletest-dev
     golang-github-jacobsa-reqtrace-dev
     golang-github-jtolds-gls-dev
     golang-github-lsegal-gucumber-dev
     golang-github-smartystreets-assertions-dev

restic: restic (0)
     golang-github-armon-consul-api-dev
     golang-github-inconshreveable-mousetrap-dev

rkt: rkt (59)
     golang-github-agtorre-gocolorize-dev
     golang-github-appc-cni-dev
     golang-github-appc-docker2aci-dev
     golang-github-appc-goaci-dev
     golang-github-appc-spec-dev
     golang-github-armon-consul-api-dev
     golang-github-bmizerany-assert-dev
     golang-github-bradfitz-gomemcache-dev
     golang-github-bugsnag-bugsnag-go-dev
     golang-github-bugsnag-panicwrap-dev
     golang-github-coreos-gexpect-dev
     golang-github-coreos-go-iptables-dev
     golang-github-coreos-go-tspi-dev
     golang-github-coreos-ioprogress-dev
     golang-github-cznic-b-dev
     golang-github-cznic-bufs-dev
     golang-github-cznic-fileutil-dev
     golang-github-cznic-lldb-dev
     golang-github-cznic-mathutil-dev
     golang-github-cznic-ql-dev
     golang-github-cznic-sortutil-dev
     golang-github-cznic-strutil-dev
     golang-github-cznic-zappy-dev
     golang-github-d2g-dhcp4-dev
     golang-github-d2g-dhcp4client-dev
     golang-github-docker-distribution-dev
     golang-github-docker-libtrust-dev
     golang-github-dustin-go-humanize-dev
     golang-github-garyburd-redigo-dev
     golang-github-google-btree-dev
     golang-github-gorilla-handlers-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hydrogen18-stoppablelistener-dev
     golang-github-inconshreveable-mousetrap-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-juju-loggo-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-klauspost-compress-dev
     golang-github-klauspost-cpuid-dev
     golang-github-klauspost-crc32-dev
     golang-github-klauspost-pgzip-dev
     golang-github-lsegal-gucumber-dev
     golang-github-opencontainers-image-spec-dev
     golang-github-peterbourgon-diskv-dev
     golang-github-remyoudompheng-bigfft-dev
     golang-github-revel-revel-dev
     golang-github-robfig-config-dev
     golang-github-robfig-pathtree-dev
     golang-github-stevvooe-resumable-dev
     golang-go-semver-dev
     golang-speter-go-exp-math-dec-inf-dev

robustirc-bridge: robustirc-bridge (8)

runc: runc (937)
     golang-github-docker-go-units-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev

skydns: skydns (2)
     golang-github-stathat-go-dev

slt: slt (10)

snapd: snapd (36)
     golang-github-gorilla-mux-dev
     golang-gopkg-macaroon.v1-dev

syncthing: syncthing (1230), syncthing-discosrv (14), syncthing-relaysrv (12)
     genxdr
     golang-github-audriusbutkevicius-go-nat-pmp-dev
     golang-github-bkaradzic-go-lz4-dev
     golang-github-calmh-du-dev
     golang-github-calmh-luhn-dev
     golang-github-calmh-xdr-dev
     golang-github-cznic-b-dev
     golang-github-cznic-bufs-dev
     golang-github-cznic-fileutil-dev
     golang-github-cznic-lldb-dev
     golang-github-cznic-mathutil-dev
     golang-github-cznic-ql-dev
     golang-github-cznic-sortutil-dev
     golang-github-cznic-strutil-dev
     golang-github-cznic-zappy-dev
     golang-github-d4l3k-messagediff-dev
     golang-github-gobwas-glob-dev
     golang-github-golang-groupcache-dev
     golang-github-jackpal-gateway-dev
     golang-github-minio-sha256-simd-dev
     golang-github-oschwald-geoip2-golang-dev
     golang-github-oschwald-maxminddb-golang-dev
     golang-github-remyoudompheng-bigfft-dev
     golang-github-sasha-s-go-deadlock-dev
     golang-github-stathat-go-dev
     golang-github-thejerf-suture-dev
     golang-github-vitrun-qart-dev

systemd-docker: systemd-docker (76)
     golang-coreos-log-dev
     golang-etcd-server-dev
     golang-github-akrennmair-gopcap-dev
     golang-github-armon-go-radix-dev
     golang-github-bgentry-speakeasy-dev
     golang-github-coreos-gexpect-dev
     golang-github-datadog-datadog-go-dev
     golang-github-docker-go-connections-dev
     golang-github-docker-go-units-dev
     golang-github-docker-libkv-dev
     golang-github-fsouza-go-dockerclient-dev
     golang-github-google-btree-dev
     golang-github-gorilla-mux-dev
     golang-github-hashicorp-consul-dev
     golang-github-hashicorp-errwrap-dev
     golang-github-hashicorp-go-immutable-radix-dev
     golang-github-hashicorp-go-memdb-dev
     golang-github-hashicorp-go-uuid-dev
     golang-github-hashicorp-hil-dev
     golang-github-hashicorp-uuid-dev
     golang-github-hashicorp-yamux-dev
     golang-github-inconshreveable-muxado-dev
     golang-github-jonboulle-clockwork-dev
     golang-github-kballard-go-shellquote-dev
     golang-github-mattn-go-runewidth-dev
     golang-github-mattn-go-shellwords-dev
     golang-github-mitchellh-cli-dev
     golang-github-olekukonko-tablewriter-dev
     golang-github-opencontainers-specs-dev
     golang-github-seccomp-libseccomp-golang-dev
     golang-github-stathat-go-dev
     golang-github-vdemeester-shakers-dev
     golang-github-xeipuuv-gojsonpointer-dev
     golang-github-xeipuuv-gojsonreference-dev
     golang-github-xeipuuv-gojsonschema-dev
     golang-github-xiang90-probing-dev
     golang-go-semver-dev

toxiproxy: toxiproxy (5), toxiproxy-cli (4)
     golang-github-gorilla-mux-dev
     golang-gopkg-tomb.v1-dev

webhook: webhook (9)
     golang-github-gorilla-mux-dev
     golang-github-urfave-negroni-dev

winrmcp: winrmcp (13)
     golang-github-dylanmei-iso8601-dev
     golang-github-masterzen-simplexml-dev
     golang-github-masterzen-winrm-dev
     golang-github-masterzen-xmlpath-dev
     golang-github-nu7hatch-gouuid-dev

```
