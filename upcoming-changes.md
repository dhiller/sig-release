| Upcoming changes | PR                                                                   | Author                                          |
|------------------|----------------------------------------------------------------------|-------------------------------------------------|
| IsolateEmulatorThread: Add cluster-wide parity completion setting  | [#10872](https://github.com/kubevirt/kubevirt/pull/10872) | [RamLavi](https://github.com/RamLavi) |
| Refactor monitoring alerts  | [#10700](https://github.com/kubevirt/kubevirt/pull/10700) | [machadovilaca](https://github.com/machadovilaca) |
| Change second emulator thread assign strategy to best-effort.  | [#10839](https://github.com/kubevirt/kubevirt/pull/10839) | [RamLavi](https://github.com/RamLavi) |
| Remove year from generated code copyright  | [#10863](https://github.com/kubevirt/kubevirt/pull/10863) | [dhiller](https://github.com/dhiller) |
| Fix KubeVirt for CRIO 1.28 by using checksums to verify containerdisks when migrating VMIs  | [#10747](https://github.com/kubevirt/kubevirt/pull/10747) | [acardace](https://github.com/acardace) |
| BugFix: Double cloning with filter fails  | [#10860](https://github.com/kubevirt/kubevirt/pull/10860) | [akalenyu](https://github.com/akalenyu) |
| Attachment pod creation is now rate limited  | [#10567](https://github.com/kubevirt/kubevirt/pull/10567) | [awels](https://github.com/awels) |
| Not needed, as it affects only how tests are run.  | [#10836](https://github.com/kubevirt/kubevirt/pull/10836) | [jschintag](https://github.com/jschintag) |
| Reject VirtualMachineClone creation when target name is equal to source name  | [#10845](https://github.com/kubevirt/kubevirt/pull/10845) | [orelmisan](https://github.com/orelmisan) |
| Requests/Limits can now be configured when using CPU/Memory hotplug  | [#10840](https://github.com/kubevirt/kubevirt/pull/10840) | [acardace](https://github.com/acardace) |
| Add total VMs created metric  | [#10418](https://github.com/kubevirt/kubevirt/pull/10418) | [machadovilaca](https://github.com/machadovilaca) |
| Support macvtap as a binding plugin  | [#10800](https://github.com/kubevirt/kubevirt/pull/10800) | [AlonaKaplan](https://github.com/AlonaKaplan) |
| Fixes device permission when using USB host passthrough  | [#10753](https://github.com/kubevirt/kubevirt/pull/10753) | [victortoso](https://github.com/victortoso) |
| Windows offline activation with ACPI SLIC table  | [#10774](https://github.com/kubevirt/kubevirt/pull/10774) | [victortoso](https://github.com/victortoso) |
| Support multiple CPUs in Housekeeping cgroup  | [#10783](https://github.com/kubevirt/kubevirt/pull/10783) | [RamLavi](https://github.com/RamLavi) |
| Source virt-launcher: Log migration info by default  | [#10809](https://github.com/kubevirt/kubevirt/pull/10809) | [orelmisan](https://github.com/orelmisan) |
| Add v1alpha3 for hooks<br>Fix migration when using sidecars  | [#10046](https://github.com/kubevirt/kubevirt/pull/10046) | [victortoso](https://github.com/victortoso) |
| Refactor monitoring  recording-rules  | [#10651](https://github.com/kubevirt/kubevirt/pull/10651) | [machadovilaca](https://github.com/machadovilaca) |
| Extend kubvirt CR by adding domain attachment option to the network binding plugin API.  | [#10732](https://github.com/kubevirt/kubevirt/pull/10732) | [AlonaKaplan](https://github.com/AlonaKaplan) |
| Added “adm” subcommand under “virtctl”, and “log-verbosity" subcommand under “adm”. The log-verbosity command is:<br>- To show the log verbosity of one or more components.<br>- To set the log verbosity of one or more components.<br>- To reset the log verbosity of all components (reset to the default verbosity (2)).  | [#10244](https://github.com/kubevirt/kubevirt/pull/10244) | [hshitomi](https://github.com/hshitomi) |
| 1. Support "Clone API" to filter VirtualMachine.spec.template.annotation and VirtualMachine.spec.template.label  | [#10658](https://github.com/kubevirt/kubevirt/pull/10658) | [matthewei](https://github.com/matthewei) |
| Fixes SMT Alignment Error in virt-launcher pod by optimizing isolateEmulatorThread feature (BZ#2228103).  | [#10593](https://github.com/kubevirt/kubevirt/pull/10593) | [RamLavi](https://github.com/RamLavi) |
| Restored hotplug attachment pod request/limit to original value  | [#10720](https://github.com/kubevirt/kubevirt/pull/10720) | [awels](https://github.com/awels) |
| Exposing Filesystem Persistent Volumes (PVs)  to the VM using unprivilege virtiofsd.  | [#10657](https://github.com/kubevirt/kubevirt/pull/10657) | [germag](https://github.com/germag) |
| Functional tests for sidecar hook with ConfigMap  | [#10637](https://github.com/kubevirt/kubevirt/pull/10637) | [dharmit](https://github.com/dharmit) |
| Add PVC option to the hook sidecars for supplying additional debugging tools  | [#10598](https://github.com/kubevirt/kubevirt/pull/10598) | [alicefr](https://github.com/alicefr) |
| - documents steps to build the KubeVirt builder container  | [#10526](https://github.com/kubevirt/kubevirt/pull/10526) | [cfilleke](https://github.com/cfilleke) |
| virt-launcher: fix qemu non root log path  | [#10699](https://github.com/kubevirt/kubevirt/pull/10699) | [qinqon](https://github.com/qinqon) |
| BugFix: cgroupsv2 device allowlist is bound to virt-handler internal state/block disk device overwritten on hotplug  | [#10689](https://github.com/kubevirt/kubevirt/pull/10689) | [akalenyu](https://github.com/akalenyu) |
| Remove MigrateVmiDiskTransferRateMetric  | [#10693](https://github.com/kubevirt/kubevirt/pull/10693) | [machadovilaca](https://github.com/machadovilaca) |
| Remove leftover NonRoot feature gate  | [#10615](https://github.com/kubevirt/kubevirt/pull/10615) | [orelmisan](https://github.com/orelmisan) |
| Allow LUN disks to be hotplugged  | [#10529](https://github.com/kubevirt/kubevirt/pull/10529) | [alromeros](https://github.com/alromeros) |
| Remove leftover NonRootExperimental feature gate  | [#10582](https://github.com/kubevirt/kubevirt/pull/10582) | [orelmisan](https://github.com/orelmisan) |
| Disable HTTP/2 to mitigate CVE-2023-44487  | [#10596](https://github.com/kubevirt/kubevirt/pull/10596) | [mhenriks](https://github.com/mhenriks) |
| Fix LowKVMNodesCount not firing  | [#10570](https://github.com/kubevirt/kubevirt/pull/10570) | [machadovilaca](https://github.com/machadovilaca) |
| vmi memory footprint increase by 35M when guest serial console logging is turned on (default on).  | [#10571](https://github.com/kubevirt/kubevirt/pull/10571) | [tiraboschi](https://github.com/tiraboschi) |
| Introduce network binding plugin for Passt networking, interfacing with Kubevirt new network binding plugin API.  | [#10425](https://github.com/kubevirt/kubevirt/pull/10425) | [ormergi](https://github.com/ormergi) |
| Ability to run scripts through hook sidecar  | [#10479](https://github.com/kubevirt/kubevirt/pull/10479) | [dharmit](https://github.com/dharmit) |

