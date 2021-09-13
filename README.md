# stx
starlingx4 images
```shell
"download_images_list": [
        "k8s.gcr.io/kube-apiserver:v1.18.1",
        "k8s.gcr.io/kube-controller-manager:v1.18.1",
        "k8s.gcr.io/kube-scheduler:v1.18.1",
        "k8s.gcr.io/kube-proxy:v1.18.1",
        "k8s.gcr.io/pause:3.2",
        "k8s.gcr.io/etcd:3.4.3-0",
        "k8s.gcr.io/coredns:1.6.7",
        "quay.io/calico/cni:v3.12.0",
        "quay.io/calico/node:v3.12.0",
        "quay.io/calico/kube-controllers:v3.12.0",
        "quay.io/calico/pod2daemon-flexvol:v3.12.0",
        "docker.io/nfvpe/multus:v3.4",
        "docker.io/starlingx/k8s-cni-sriov:stx.3.0-v2.2",
        "docker.io/starlingx/k8s-plugins-sriov-network-device:stx.4.0-v3.2-16-g4e0302ae",
        "gcr.io/kubernetes-helm/tiller:v2.16.1",
        "quay.io/airshipit/armada:8a1638098f88d92bf799ef4934abe569789b885e-ubuntu_bionic",
        "docker.io/starlingx/n3000-opae:stx.4.0-v1.0.0",
        "quay.io/stackanetes/kubernetes-entrypoint:v0.3.1",
        "quay.io/k8scsi/snapshot-controller:v2.0.0-rc2"
    ]
```






```shell
/usr/local/share/applications/helm
{
        quay.io/jetstack/cert-manager-controller:v0.15.0
        quay.io/jetstack/cert-manager-webhook:v0.15.0
        quay.io/jetstack/cert-manager-cainjector:v0.15.0
        quay.io/jetstack/cert-manager-acmesolver:v0.15.0
        k8s.gcr.io/defaultbackend:1.4
        quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.23.0
        docker.io/starlingx/dex:stx.4.0-v2.14.0-1
        quay.io/dexidp/dex:v2.14.0
        gcr.io/google_containers/kubernetes-dashboard-init-amd64:v1.0.0
        docker.io/starlingx/stx-oidc-client:stx.4.0-v1.0.2
        docker.io/starlingx/ceph-config-helper:v1.15.0
        quay.io/kubernetes_incubator/node-feature-discovery:v0.3.0
        quay.io/external_storage/rbd-provisioner:v2.1.1-k8s1.11
}
```


```shell
"openstack1.0-49": [
        docker.io/starlingx/stx-heat:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-nova-api-proxy:rc-4.0-centos-stable-latest
        docker.io/rabbitmq:3.7.24
        docker.io/rabbitmq:3.7.24-management
        docker.io/starlingx/stx-ceilometer:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-mariadb:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-fm-rest-api:rc-4.0-centos-stable-latest
        docker.io/starlingx/ceph-config-helper:v1.15.0
        docker.io/starlingx/stx-libvirt:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-placement:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-barbican:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-keystone:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-nova:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-panko:rc-4.0-centos-stable-latest
        docker.io/openstackhelm/mariadb:ubuntu_xenial-20200303
        docker.io/openstackhelm/mariadb:10.2.18
        docker.io/starlingx/stx-aodh:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-glance:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-cinder:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-gnocchi:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-neutron:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-ironic:rc-4.0-centos-stable-latest
        docker.io/nginx:1.13.3
        docker.io/starlingx/stx-keystone-api-proxy:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-horizon:rc-4.0-centos-stable-latest
        docker.io/starlingx/stx-ovs:rc-4.0-centos-stable-latest
        docker.io/openstackhelm/heat:ocata-ubuntu_xenial
        docker.io/rabbitmq:3.7-management
        docker.io/kolla/ubuntu-source-aodh-api:ocata
        docker.io/kolla/ubuntu-source-aodh-evaluator:ocata
        docker.io/kolla/ubuntu-source-aodh-listener:ocata
        docker.io/kolla/ubuntu-source-aodh-notifier:ocata
        docker.io/kolla/ubuntu-source-aodh-base:ocata
        docker.io/docker:17.07.0
        quay.io/airshipit/kubernetes-entrypoint:v1.0.0
        docker.io/openstackhelm/ceph-daemon:ubuntu_bionic-20200217
        docker.io/openstackhelm/ceph-config-helper:ubuntu_bionic-20200217
        docker.io/openstackhelm/heat:newton-ubuntu_xenial
        docker.io/starlingx/stx-fm-rest-api:master-centos-stable-latest
        docker.io/starlingx/stx-heat:master-centos-stable-latest
        quay.io/stackanetes/kubernetes-entrypoint:v0.3.1
        docker.io/openstackhelm/ceph-config-helper:ubuntu_bionic-20191216
        docker.io/postgres:9.5
        quay.io/attcomdev/ubuntu-source-gnocchi-api:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-statsd:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-metricd:3.0.3
        quay.io/attcomdev/ubuntu-source-gnocchi-base:3.0.3
        docker.io/openstackhelm/heat:stein-ubuntu_bionic
        docker.io/openstackhelm/horizon:stein-ubuntu_bionic
        docker.io/openstackhelm/osh-selenium:latest-ubuntu_bionic
        docker.io/xrally/xrally-openstack:1.3.0
        docker.io/openstackhelm/keystone:stein-ubuntu_bionic
        docker.io/openstackhelm/magnum:ocata-ubuntu_xenial
        docker.io/openstackhelm/ospurge:latest
        docker.io/openstackhelm/neutron:stein-ubuntu_bionic
        docker.io/openstackhelm/neutron:stein-18.04-sriov
        docker.io/starlingx/stx-nova-api-proxy:master-centos-stable-latest
        docker.io/openstackhelm/heat:pike
        docker.io/openstackhelm/placement:master-ubuntu_bionic
        docker.io/openstackhelm/barbican:stein-ubuntu_bionic
        docker.io/openstackhelm/cinder:stein-ubuntu_bionic
        docker.io/starlingx/stx-mariadb:master-centos-stable-latest
        docker.io/openstackhelm/neutron:ocata-ubuntu_xenial
        docker.io/osixia/keepalived:1.4.5
        quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.23.0
        docker.io/starlingx/stx-keystone-api-proxy:master-centos-stable-latest
        docker.io/mariadb:10.2.31
        docker.io/prom/mysqld-exporter:v0.10.0
        docker.io/openstackhelm/mariadb:ubuntu_xenial-20191031
        quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.9.0
        docker.io/openstackhelm/openvswitch:ubuntu_bionic-20191031
        docker.io/mongo:3.4.9-jessie
        docker.io/kolla/ubuntu-source-ceilometer-api:ocata
        docker.io/kolla/ubuntu-source-ceilometer-central:ocata
        docker.io/kolla/ubuntu-source-ceilometer-collector:ocata
        docker.io/kolla/ubuntu-source-ceilometer-compute:ocata
        docker.io/kolla/ubuntu-source-ceilometer-base:ocata
        docker.io/kolla/ubuntu-source-ceilometer-notification:ocata
        docker.io/starlingx/stx-keystone:master-centos-stable-latest
        docker.io/openstackhelm/ceph-config-helper:latest-ubuntu_xenial
        docker.io/openstackhelm/glance:stein-ubuntu_bionic
        docker.io/openstackhelm/ironic:ocata-ubuntu_xenial
        docker.io/openstackhelm/libvirt:latest-ubuntu_bionic
        docker.io/memcached:1.5.5
        docker.io/prom/memcached-exporter:v0.4.1
        docker.io/openstackhelm/nova:stein-ubuntu_bionic
        docker.io/kolla/ubuntu-source-nova-compute-ironic:ocata
        docker.io/kolla/ubuntu-source-nova-novncproxy:ocata
        docker.io/port/ceph-config-helper:v1.10.3
        docker.io/kolla/ubuntu-source-panko-api:ocata
        docker.io/kolla/ubuntu-source-panko-base:ocata
        docker.io/kbudde/rabbitmq-exporter:v0.21.0
]
```

```shell
"questions": [
        docker.io/openstackhelm/neutron:stein-18.04-sriov not found
]
