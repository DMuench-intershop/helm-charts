
<a name="icm-2.15.0"></a>
## [icm-2.15.0](https://github.com/intershop/helm-charts/compare/icm-2.14.5...icm-2.15.0)

> 2025-08-13

### Features

* check if changelog excludes chore commits


<a name="icm-2.14.5"></a>
## [icm-2.14.5](https://github.com/intershop/helm-charts/compare/icm-2.14.3...icm-2.14.5)

> 2025-08-12

### Bug Fixes

* **icm:** introduce new icm-job-test chart ([#1037](https://github.com/intershop/helm-charts/issues/1037))


<a name="icm-2.14.3"></a>
## icm-2.14.3

> 2025-08-11

### Bug Fixes

* remove csi volume mount ([#709](https://github.com/intershop/helm-charts/issues/709))
* version comparision for replication fixed ([#974](https://github.com/intershop/helm-charts/issues/974))
* roll out port mapping fix ([#29](https://github.com/intershop/helm-charts/issues/29)) ([#34](https://github.com/intershop/helm-charts/issues/34)) ([#35](https://github.com/intershop/helm-charts/issues/35))
* use PageCache PVC ([#87](https://github.com/intershop/helm-charts/issues/87)) ([#88](https://github.com/intershop/helm-charts/issues/88))
* fix lint test for icm-charts ([#99](https://github.com/intershop/helm-charts/issues/99))
* relication configmap ([#106](https://github.com/intershop/helm-charts/issues/106)) ([#107](https://github.com/intershop/helm-charts/issues/107))
* **icm:** fix local repl. exec and enable CSI secret creation ([#677](https://github.com/intershop/helm-charts/issues/677))
* **icm:** ingress controller is checked ([#603](https://github.com/intershop/helm-charts/issues/603))
* **icm:** check wa instead of as ([#286](https://github.com/intershop/helm-charts/issues/286)) ([#730](https://github.com/intershop/helm-charts/issues/730))
* **icm:** use logger instead of tee ([#716](https://github.com/intershop/helm-charts/issues/716))
* **icm:** prevent CVE-2025-1974 ([#1006](https://github.com/intershop/helm-charts/issues/1006))
* **icm:** change to correct parameter ([#615](https://github.com/intershop/helm-charts/issues/615))
* **icm:** do not buffer request ([#602](https://github.com/intershop/helm-charts/issues/602))
* **icm:** use domain to check system status ([#736](https://github.com/intershop/helm-charts/issues/736))
* **icm:** use the right variables ([#584](https://github.com/intershop/helm-charts/issues/584))
* **icm:** Deprecate icm-as.newrelic.app_name and provide appName instead ([#552](https://github.com/intershop/helm-charts/issues/552))
* **icm:** test performance optimized ([#764](https://github.com/intershop/helm-charts/issues/764))
* **icm:** no command overwrite in wa and waa ([#793](https://github.com/intershop/helm-charts/issues/793))
* **icm:** rename istestrunner logfile ([#941](https://github.com/intershop/helm-charts/issues/941))
* **icm:** do not do it as root ([#961](https://github.com/intershop/helm-charts/issues/961))

### Code Refactoring

* requirements.yml not needed anymore ([#21](https://github.com/intershop/helm-charts/issues/21))
* use local dependencies ([#19](https://github.com/intershop/helm-charts/issues/19))

### Documentation

* **common:** link "Release Process"-wiki page to the contribution rules ([#867](https://github.com/intershop/helm-charts/issues/867))
* **icm:** Add explanations and examples to ConfigMapMounts documentation ([#994](https://github.com/intershop/helm-charts/issues/994))
* **icm:** Add icm configMapMounts docu ([#976](https://github.com/intershop/helm-charts/issues/976))

### Features

* add scripts for azure test execution ([#642](https://github.com/intershop/helm-charts/issues/642))
* Add umbrella chart icm ([#11](https://github.com/intershop/helm-charts/issues/11)) ([#13](https://github.com/intershop/helm-charts/issues/13))
* set release versions ([#91](https://github.com/intershop/helm-charts/issues/91))
* configuration of volumemounts for existing configmaps ([#921](https://github.com/intershop/helm-charts/issues/921))
* increate persistence sites capability for ISTE tests ([#90052](https://github.com/intershop/helm-charts/issues/90052))
* **icm:** iste with weblayer config ([#691](https://github.com/intershop/helm-charts/issues/691))
* **icm:** use weblayer configuration during end2end tests ([#454](https://github.com/intershop/helm-charts/issues/454))
* **icm:** enable ingress-nginx for domain usage during testing ([#591](https://github.com/intershop/helm-charts/issues/591))
* **icm:** enable ingress-nginx for domain usage during testing ([#591](https://github.com/intershop/helm-charts/issues/591))
* **icm:** circumvent liveness probe ([#491](https://github.com/intershop/helm-charts/issues/491))
* **icm:** enable encryption volume ([#653](https://github.com/intershop/helm-charts/issues/653)) BREAKING_CHANGE
* **icm:** redis configuration ([#335](https://github.com/intershop/helm-charts/issues/335)) ([#349](https://github.com/intershop/helm-charts/issues/349))
* **icm:** allow disabling icm-web from icm chart ([#325](https://github.com/intershop/helm-charts/issues/325))
* **icm:** prevent test abortions ([#775](https://github.com/intershop/helm-charts/issues/775))
* **icm:** New replication environment configuration ([#803](https://github.com/intershop/helm-charts/issues/803))

