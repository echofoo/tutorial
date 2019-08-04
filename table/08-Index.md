# Index

## A
Access Control List (ACL), [Using ACLs](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#using-acls)
	examples, [Examples](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#examples)
	how they work, [How ACLs Work](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#how-acls-work)
	using, [Using ACLs with the Lustre Software](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#using-acls-with-the-lustre-software)
audit
	change logs, [Audit with Changelogs](03.01-Monitoring%20a%20Lustre%20File%20System.md#audit-with-changelogs)

## B
backup, [Backing up a File System](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-a-file-system)
	aborting recovery, [Aborting Recovery](03.03-Lustre%20Maintenance.md#aborting-recovery)
	index objects, [Backing Up an OST or MDT (Backend File System Level)](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-an-ost-or-mdt-backend-file-system-level)
	MDT file system, [Backing Up an OST or MDT (Backend File System Level)](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-an-ost-or-mdt-backend-file-system-level)
	MDT/OST device level, [Backing Up and Restoring an MDT or OST (ldiskfs Device Level)](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-and-restoring-an-mdt-or-ost-ldiskfs-device-level)
	new/changed files, [Backing up New/Changed Files to the Backup File System](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-newchanged-files-to-the-backup-file-system)
	OST and MDT, [Backing Up an OST or MDT](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-an-ost-or-mdt)
	OST config, [Backing Up OST Configuration Files](03.03-Lustre%20Maintenance.md#backing-up-ost-configuration-files)
	OST file system, [Backing Up an OST or MDT (Backend File System Level)](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#backing-up-an-ost-or-mdt-backend-file-system-level)
	restoring file system backup, [Restoring a File-Level Backup](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#restoring-a-file-level-backup)
	restoring OST config, [Restoring OST Configuration Files](03.03-Lustre%20Maintenance.md#restoring-ost-configuration-files)
	rsync, [Lustre_rsync](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#lustre_rsync)

​		examples, [lustre_rsync Examples](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#lustre_rsync-examples)
		using, [Using Lustre_rsync](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#using-lustre_rsync)

​	using LVM, [Using LVM Snapshots with the Lustre File System](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#using-lvm-snapshots-with-the-lustre-file-system)

​		creating, [Creating an LVM-based Backup File System](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#creating-an-lvm-based-backup-file-system)
		creating snapshots, [Creating Snapshot Volumes](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#creating-snapshot-volumes)
		deleting, [Deleting Old Snapshots](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#deleting-old-snapshots)
		resizing, [Changing Snapshot Volume Size](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#changing-snapshot-volume-size)
		restoring, [Restoring the File System From a Snapshot](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#restoring-the-file-system-from-a-snapshot)

​	ZFS to ldiskfs, [Migrate from a ZFS to an ldiskfs based filesystem](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#migrate-from-a-zfs-to-an-ldiskfs-based-filesystem), [Migrate from an ldiskfs to a ZFS based 		filesystem](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#migrate-from-an-ldiskfs-to-a-zfs-based-filesystem)
	ZFS ZPL, [Migration Between ZFS and ldiskfs Target Filesystems](03.07-BackingUp%20and%20Restoring%20a%20File%20System.md#migration-between-zfs-and-ldiskfs-target-filesystems)

barrier, [Global Write Barriers](03.19-Lustre%20ZFS%20Snapshots.md#global-write-barriers)

​	impose, [Impose Barrier](03.19-Lustre%20ZFS%20Snapshots.md#impose-barrier)
	query, [Query Barrier](03.19-Lustre%20ZFS%20Snapshots.md#query-barrier)
	remove, [Remove Barrier](03.19-Lustre%20ZFS%20Snapshots.md#remove-barrier)
	rescan, [Rescan Barrier](03.19-Lustre%20ZFS%20Snapshots.md#rescan-barrier)

###### benchmarking

​	application profiling, [Collecting Application Profiling Information (stats-collect)](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#collecting-application-profiling-information-stats-collect)
	local disk, [Testing Local Disk Performance](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-local-disk-performance)
	MDS performance, [Testing MDS Performance (mds-survey)](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-mds-performance-mds-survey)
	network, [Testing Network Performance](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-network-performance)
	OST I/O, [Testing OST I/O Performance (ost-survey)](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-ost-io-performance-ost-survey)
	OST performance, [Testing OST Performance (obdfilter-survey)](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-ost-performance-obdfilter-survey)
	raw hardware with sgpdd-survey, [Testing I/O Performance of Raw Hardware (sgpdd-survey)](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-io-performance-of-raw-hardware-sgpdd-survey)
	remote disk, [Testing Remote Disk Performance](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#testing-remote-disk-performance)
	tuning storage, [Tuning Linux Storage Devices](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#tuning-linux-storage-devices)
	with Lustre I/O Kit, [Using Lustre I/O Kit Tools](04.02-Benchmarking%20Lustre%20File%20System%20Performance%20(Lustre%20IO%20Kit).md#using-lustre-io-kit-tools)

## C
change logs (see [monitoring](monitoring))
commit on share, [Commit on Share](06.01-Lustre%20File%20System%20Recovery.md#commit-on-share)	

​	tuning, [Tuning Commit On Share](06.01-Lustre%20File%20System%20Recovery.md#tuning-commit-on-share)
	working with, [Working with Commit on Share](06.01-Lustre%20File%20System%20Recovery.md#working-with-commit-on-share)

configlogs, [Lustre Configuration Logs](03.19-Lustre%20ZFS%20Snapshots.md#lustre-configuration-logs)

###### configuring,

 [Introduction](06.06-Configuration%20Files%20and%20Module%20Parameters.md#introduction)

​	adaptive timeouts, [Configuring Adaptive Timeouts](06.02-Lustre%20Parameters.md#configuring-adaptive-timeouts)
	LNet options, [LNet Options](06.06-Configuration%20Files%20and%20Module%20Parameters.md#lnet-options)
	module options, [Module Options](06.06-Configuration%20Files%20and%20Module%20Parameters.md#module-options)
	multihome, [Multihome Server Example](02.06-Configuring%20Lustre%20Networking%20(LNet).md#multihome-server-example)
	network

​		forwarding, [forwarding ("")](06.06-Configuration%20Files%20and%20Module%20Parameters.md#forwarding-)
		rnet_htable_size, [rnet_htable_size](06.06-Configuration%20Files%20and%20Module%20Parameters.md#rnet_htable_size)
		routes, [routes ("")](06.06-Configuration%20Files%20and%20Module%20Parameters.md#routes-)
		SOCKLND, [SOCKLND Kernel TCP/IP LND](06.06-Configuration%20Files%20and%20Module%20Parameters.md#socklnd-kernel-tcpip-lnd)	
		tcp, [networks ("tcp")](06.06-Configuration%20Files%20and%20Module%20Parameters.md#networks-tcp)

​	network topology, [Network Topology](06.06-Configuration%20Files%20and%20Module%20Parameters.md#network-topology)

## D
debug

​	utilities, [Testing / Debugging Utilities](06.07-System%20Configuration%20Utilities.md#testing--debugging-utilities)

debugging, [Diagnostic and Debugging Tools](05.03-Debugging%20a%20Lustre%20File%20System.md#diagnostic-and-debugging-tools)

​	admin tools, [Tools for Administrators and Developers](05.03-Debugging%20a%20Lustre%20File%20System.md#tools-for-administrators-and-developers)
	developer tools, [Tools for Developers](05.03-Debugging%20a%20Lustre%20File%20System.md#tools-for-developers)
	developers tools, [Lustre Debugging for Developers](05.03-Debugging%20a%20Lustre%20File%20System.md#lustre-debugging-for-developers)
	disk contents, [Looking at Disk Content](05.03-Debugging%20a%20Lustre%20File%20System.md#looking-at-disk-content)
	external tools, [External Debugging Tools](05.03-Debugging%20a%20Lustre%20File%20System.md#external-debugging-tools)
	kernel debug log, [Controlling Information Written to the Kernel Debug Log](05.03-Debugging%20a%20Lustre%20File%20System.md#controlling-information-written-to-the-kernel-debug-log)
	lctl example, [Sample lctl Run](05.03-Debugging%20a%20Lustre%20File%20System.md#sample-lctl-run)
	memory leaks, [Finding Memory Leaks Using leak_finder.pl](05.03-Debugging%20a%20Lustre%20File%20System.md#finding-memory-leaks-using-leak_finderpl)
	message format, [Understanding the Lustre Debug Messaging Format](05.03-Debugging%20a%20Lustre%20File%20System.md#understanding-the-lustre-debug-messaging-format)
	procedure, [Lustre Debugging Procedures](05.03-Debugging%20a%20Lustre%20File%20System.md#lustre-debugging-procedures)
	tools, [Lustre Debugging Tools](05.03-Debugging%20a%20Lustre%20File%20System.md#lustre-debugging-tools)
	using lctl, [Using the lctl Tool to View Debug Messages](05.03-Debugging%20a%20Lustre%20File%20System.md#using-the-lctl-tool-to-view-debug-messages)
	using strace, [Troubleshooting with strace](05.03-Debugging%20a%20Lustre%20File%20System.md#troubleshooting-with-strace)

design (see setup)
DLC

​	Code Example, [Adding a route code example](06.08-LNet%20Configuration%20C-API.md#adding-a-route-code-example)

dom, [Introduction to Data on MDT (DoM)](03.09-Data%20on%20MDT%20(DoM).md#introduction-to-data-on-mdt-dom), [User Commands](03.09-Data%20on%20MDT%20(DoM).md#user-commands), [DoM Stripe Size Restrictions](03.09-Data%20on%20MDT%20(DoM).md#dom-stripe-size-restrictions), [lfs getstripe for DoM files](03.09-Data%20on%20MDT%20(DoM).md#lfs-getstripe-for-dom-files), [lfs find for DoM files](03.09-Data%20on%20MDT%20(DoM).md#lfs-find-for-dom-files), [The dom_stripesize parameter](03.09-Data%20on%20MDT%20(DoM).md#the-dom_stripesize-parameter), [Disable DoM](03.09-Data%20on%20MDT%20(DoM).md#disable-dom)

​	disabledom, [Disable DoM](03.09-Data%20on%20MDT%20(DoM).md#disable-dom)
	domstripesize, [DoM Stripe Size Restrictions](03.09-Data%20on%20MDT%20(DoM).md#dom-stripe-size-restrictions)
	dom_stripesize, [The dom_stripesize parameter](03.09-Data%20on%20MDT%20(DoM).md#the-dom_stripesize-parameter)
	intro, [Introduction to Data on MDT (DoM)](03.09-Data%20on%20MDT%20(DoM).md#introduction-to-data-on-mdt-dom)
	lfsfind, [lfs find for DoM files](03.09-Data%20on%20MDT%20(DoM).md#lfs-find-for-dom-files)
	lfsgetstripe, [lfs getstripe for DoM files](03.09-Data%20on%20MDT%20(DoM).md#lfs-getstripe-for-dom-files)
	lfssetstripe, [lfs setstripe for DoM files](03.09-Data%20on%20MDT%20(DoM).md#lfs-setstripe-for-dom-files)
	usercommands, [User Commands](03.09-Data%20on%20MDT%20(DoM).md#user-commands)

## E
e2scan, [e2scan](06.07-System%20Configuration%20Utilities.md#e2scan)
errors (see [troubleshooting](#t))
## F
failover, [What is Failover?](02-Introducing%20the%20Lustre%20File%20System.md#what-is-failover), [Setting Up a Failover Environment](02.08-Configuring%20Failover%20in%20a%20Lustre%20File%20System.md#setting-up-a-failover-environment)

​	and Lustre, [Failover Functionality in a Lustre File System](02-Introducing%20the%20Lustre%20File%20System.md#failover-functionality-in-a-lustre-file-system)
	capabilities, [Failover Capabilities](02-Introducing%20the%20Lustre%20File%20System.md#failover-capabilities)
	configuration, [Types of Failover Configurations](02-Introducing%20the%20Lustre%20File%20System.md#types-of-failover-configurations)
	high-availability (HA) software, [Selecting High-Availability (HA) Software](02.08-Configuring%20Failover%20in%20a%20Lustre%20File%20System.md#selecting-high-availability-ha-software)
	MDT, [MDT Failover Configuration (Active/Passive)](02-Introducing%20the%20Lustre%20File%20System.md#mdt-failover-configuration-activepassive), [MDT Failover Configuration (Active/Active)](02-Introducing%20the%20Lustre%20File%20System.md#mdt-failover-configuration-activeactive)
	OST, [OST Failover Configuration (Active/Active)](02-Introducing%20the%20Lustre%20File%20System.md#ost-failover-configuration-activeactive)
	power control device, [Selecting Power Equipment](02.08-Configuring%20Failover%20in%20a%20Lustre%20File%20System.md#selecting-power-equipment)
	power management software, [Selecting Power Management Software](02.08-Configuring%20Failover%20in%20a%20Lustre%20File%20System.md#selecting-power-management-software)
	setup, [Preparing a Lustre File System for Failover](02.08-Configuring%20Failover%20in%20a%20Lustre%20File%20System.md#preparing-a-lustre-file-system-for-failover)

feature overview

​	configuration, [Configuration](03.19-Lustre%20ZFS%20Snapshots.md#configuration)

file layout

​	See striping, [Lustre File Layout (Striping) Considerations](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#lustre-file-layout-striping-considerations)

filefrag, [filefrag](06.03-User%20Utilities.md#filefrag)
fileset, [Fileset Feature](06.07-System%20Configuration%20Utilities.md#fileset-feature)
fragmentation, [Description](06.03-User%20Utilities.md#description-1)

## H
Hierarchical Storage Management (HSM)

​	introduction, [Introduction](03.15-Hierarchical%20Storage%20Management%20(HSM).md#introduction)
High availability (see [failover](#f))
HSM

​	agents, [Agents](03.15-Hierarchical%20Storage%20Management%20(HSM).md#agents)
	agents and copytools, [Agents and copytool](03.15-Hierarchical%20Storage%20Management%20(HSM).md#agents-and-copytool)
	archiveID backends, [Archive ID, multiple backends](03.15-Hierarchical%20Storage%20Management%20(HSM).md#archive-id-multiple-backends)
	automatic restore, [Automatic restore](03.15-Hierarchical%20Storage%20Management%20(HSM).md#automatic-restore)
	changelogs, [change logs](03.15-Hierarchical%20Storage%20Management%20(HSM).md#change-logs)
	commands, [Commands](03.15-Hierarchical%20Storage%20Management%20(HSM).md#commands)
	coordinator, [Coordinator](03.15-Hierarchical%20Storage%20Management%20(HSM).md#coordinator)
	file states, [File states](03.15-Hierarchical%20Storage%20Management%20(HSM).md#file-states)
	grace_delay, [grace_delay](03.15-Hierarchical%20Storage%20Management%20(HSM).md#grace_delay)
	hsm_control, [hsm_controlpolicy](03.15-Hierarchical%20Storage%20Management%20(HSM).md#hsm_controlpolicy)
	max_requests, [max_requests](03.15-Hierarchical%20Storage%20Management%20(HSM).md#max_requests)
	policy, [policy](03.15-Hierarchical%20Storage%20Management%20(HSM).md#policy)
	policy engine, [Policy engine](03.15-Hierarchical%20Storage%20Management%20(HSM).md#policy-engine)
	registered agents, [Registered agents](03.15-Hierarchical%20Storage%20Management%20(HSM).md#registered-agents)
	request monitoring, [Request monitoring](03.15-Hierarchical%20Storage%20Management%20(HSM).md#request-monitoring)
	requests, [Requests](03.15-Hierarchical%20Storage%20Management%20(HSM).md#requests)
	requirements, [Requirements](03.15-Hierarchical%20Storage%20Management%20(HSM).md#requirements)
	robinhood, [Robinhood](03.15-Hierarchical%20Storage%20Management%20(HSM).md#robinhood)
	setup, [Setup](03.15-Hierarchical%20Storage%20Management%20(HSM).md#setup)
	timeout, [Timeout](03.15-Hierarchical%20Storage%20Management%20(HSM).md#timeout)
	tuning, [Tuning](03.15-Hierarchical%20Storage%20Management%20(HSM).md#tuning)

## I
I/O, [Handling Full OSTs](03.12-Managing%20the%20File%20System%20and%20IO.md#handling-full-osts)

​	adding an OST, [Adding an OST to a Lustre File System](03.12-Managing%20the%20File%20System%20and%20IO.md#adding-an-ost-to-a-lustre-file-system)
	bringing OST online, [Returning an Inactive OST Back Online](03.12-Managing%20the%20File%20System%20and%20IO.md#returning-an-inactive-ost-back-online)
	direct, [Performing Direct I/O](03.12-Managing%20the%20File%20System%20and%20IO.md#performing-direct-io)
	disabling OST creates, [Disabling creates on a Full OST](03.12-Managing%20the%20File%20System%20and%20IO.md#disabling-creates-on-a-full-ost)
	full OSTs, [Handling Full OSTs](03.12-Managing%20the%20File%20System%20and%20IO.md#handling-full-osts)
	migrating data, [Migrating Data within a File System](03.12-Managing%20the%20File%20System%20and%20IO.md#migrating-data-within-a-file-system)
	OST space usage, [Checking OST Space Usage](03.12-Managing%20the%20File%20System%20and%20IO.md#checking-ost-space-usage)
	pools, [Creating and Managing OST Pools](03.12-Managing%20the%20File%20System%20and%20IO.md#creating-and-managing-ost-pools)

imperative recovery, [Imperative Recovery](06.01-Lustre%20File%20System%20Recovery.md#imperative-recovery)

​	Configuration Suggestions, [Configuration Suggestions for Imperative Recovery](06.01-Lustre%20File%20System%20Recovery.md#configuration-suggestions-for-imperative-recovery)
	MGS role, [MGS role](06.01-Lustre%20File%20System%20Recovery.md#mgs-role)
	Tuning, [Tuning Imperative Recovery](06.01-Lustre%20File%20System%20Recovery.md#tuning-imperative-recovery)

inodes

​	MDS, [Setting Formatting Options for an ldiskfs MDT](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#setting-formatting-options-for-an-ldiskfs-mdt)
	OST, [Setting Formatting Options for an ldiskfs OST](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#setting-formatting-options-for-an-ldiskfs-ost)

installing, [Steps to Installing the Lustre Software](02.01-Installation%20Overview.md#steps-to-installing-the-lustre-software)

​	preparation, [Preparing to Install the Lustre Software](02.05-Installing%20the%20Lustre%20Software.md#preparing-to-install-the-lustre-software)

Introduction, [Introduction](03.19-Lustre%20ZFS%20Snapshots.md#introduction)

​	Requirements, [Requirements](03.19-Lustre%20ZFS%20Snapshots.md#requirements)

ior-survey, [ior-survey](06.07-System%20Configuration%20Utilities.md#ior-survey)
Isolation, [Isolating Clients to a Sub-directory Tree](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#isolating-clients-to-a-sub-directory-tree)

​	client identification, [Identifying Clients](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#identifying-clients)
	configuring, [Configuring Isolation](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#configuring-isolation)
	making permanent, [Making Isolation Permanent](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#making-isolation-permanent)

## J
jobstats (see [monitoring](monitoring))
## L
large_xattr

​	ea_inode, [File and File System Limits](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#file-and-file-system-limits), [Upgrading to Lustre Software Release 2.x (Major Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2x-major-release)

lctl, [lctl](06.07-System%20Configuration%20Utilities.md#lctl)
ldiskfs

​	formatting options, [Setting ldiskfs File System Formatting Options](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#setting-ldiskfs-file-system-formatting-options)

lfs, [lfs](06.03-User%20Utilities.md#lfs)
lfs_migrate, [lfs_migrate](06.03-User%20Utilities.md#lfs_migrate)
llodbstat, [llobdstat](06.07-System%20Configuration%20Utilities.md#llobdstat)
llog_reader, [llog_reader](06.07-System%20Configuration%20Utilities.md#llog_reader)
llstat, [llstat](06.07-System%20Configuration%20Utilities.md#llstat)
llverdev, [llverdev](06.07-System%20Configuration%20Utilities.md#llverdev)
ll_decode_filter_fid, [ll_decode_filter_fid](06.07-System%20Configuration%20Utilities.md#ll_decode_filter_fid)
ll_recover_lost_found_objs, [ll_recover_lost_found_objs](06.07-System%20Configuration%20Utilities.md#ll_recover_lost_found_objs)
LNet, [Introducing LNet](02-Introducing%20the%20Lustre%20File%20System.md#introducing-lnet), [Overview of LNet Module Parameters](02.06-Configuring%20Lustre%20Networking%20(LNet).md#overview-of-lnet-module-parameters), [Dynamically Configuring LNet Routes](03.04-ManagingLustreNetworking(LNet).md#dynamically-configuring-lnet-routes), [lustre_routes_config](03.04-ManagingLustreNetworking(LNet).md#lustre_routes_config), [lustre_routes_conversion](03.04-ManagingLustreNetworking(LNet).md#lustre_routes_conversion), [Route Configuration Examples](03.04-ManagingLustreNetworking(LNet).md#route-configuration-examples) (see [configuring](configuring))

​	best practice, [Best Practices for LNet Options](02.06-Configuring%20Lustre%20Networking%20(LNet).md#best-practices-for-lnet-options)
	buffer yaml syntax, [Enable Routing and Adjust Router Buffer Configuration](02.06-Configuring%20Lustre%20Networking%20(LNet).md#enable-routing-and-adjust-router-buffer-configuration)
	capi general information, [General API Information](06.08-LNet%20Configuration%20C-API.md#general-api-information)
	capi input params, [API Common Input Parameters](06.08-LNet%20Configuration%20C-API.md#api-common-input-parameters)
	capi output params, [API Common Output Parameters](06.08-LNet%20Configuration%20C-API.md#api-common-output-parameters)
	capi return code, [API Return Code](06.08-LNet%20Configuration%20C-API.md#api-return-code)
	cli, [Configuring LNet](02.06-Configuring%20Lustre%20Networking%20(LNet).md#configuring-lnet), [Displaying Global Settings](02.06-Configuring%20Lustre%20Networking%20(LNet).md#displaying-global-settings), [Adding, Deleting and Showing Networks](02.06-Configuring%20Lustre%20Networking%20(LNet).md#adding-deleting-and-showing-networks), [Manual Adding, Deleting and Showing Peers](02.06-Configuring%20Lustre%20Networking%20(LNet).md#manual-adding-deleting-and-showing-peers), [Adding, Deleting and Showing routes](02.06-Configuring%20Lustre%20Networking%20(LNet).md#adding-deleting-and-showing-routes), [Enabling and Disabling Routing](02.06-Configuring%20Lustre%20Networking%20(LNet).md#enabling-and-disabling-routing), [Showing routing information](02.06-Configuring%20Lustre%20Networking%20(LNet).md#showing-routing-information), [Configuring Routing Buffers](02.06-Configuring%20Lustre%20Networking%20(LNet).md#configuring-routing-buffers), [Importing YAML Configuration File](02.06-Configuring%20Lustre%20Networking%20(LNet).md#importing-yaml-configuration-file), [Exporting Configuration in YAML format](02.06-Configuring%20Lustre%20Networking%20(LNet).md#exporting-configuration-in-yaml-format), [Showing LNet Traffic Statistics](02.06-Configuring%20Lustre%20Networking%20(LNet).md#showing-lnet-traffic-statistics)

​		asymmetrical route, [Asymmetrical Routes](02.06-Configuring%20Lustre%20Networking%20(LNet).md#asymmetrical-routes)
		dynamic discovery, [Dynamic Peer Discovery](02.06-Configuring%20Lustre%20Networking%20(LNet).md#dynamic-peer-discovery)

​	comments, [Including comments](02.06-Configuring%20Lustre%20Networking%20(LNet).md#including-comments)
	Configuring LNet, [Configuring LNet via lnetctl](02.06-Configuring%20Lustre%20Networking%20(LNet).md#configuring-lnet-via-lnetctl)
	cyaml, [Internal YAML Representation (cYAML)](06.08-LNet%20Configuration%20C-API.md#internal-yaml-representation-cyaml)
	error block, [Error Block](06.08-LNet%20Configuration%20C-API.md#error-block)
	escaping commas with quotes, [Escaping commas with quotes](02.06-Configuring%20Lustre%20Networking%20(LNet).md#escaping-commas-with-quotes)
	features, [Key Features of LNet](02-Introducing%20the%20Lustre%20File%20System.md#key-features-of-lnet)
	hardware multi-rail configuration, [Hardware Based Multi-Rail Configurations with LNet](03.04-ManagingLustreNetworking(LNet).md#hardware-based-multi-rail-configurations-with-lnet)
	InfiniBand load balancing, [Load Balancing with an InfiniBand* Network](03.04-ManagingLustreNetworking(LNet).md#load-balancing-with-an-infiniband-network)
	ip2nets, [Setting the LNet Module ip2nets Parameter](02.06-Configuring%20Lustre%20Networking%20(LNet).md#setting-the-lnet-module-ip2nets-parameter)
	lustre.conf, [Setting Up lustre.conf for Load Balancing](03.04-ManagingLustreNetworking(LNet).md#setting-up-lustreconf-for-load-balancing)
	lustre_lnet_config_buf, [Adjusting Router Buffer Pools](06.08-LNet%20Configuration%20C-API.md#adjusting-router-buffer-pools)
	lustre_lnet_config_net, [Adding a Network Interface](06.08-LNet%20Configuration%20C-API.md#adding-a-network-interface)
	lustre_lnet_config_ni_system, [Configuring LNet](06.08-LNet%20Configuration%20C-API.md#configuring-lnet)
	lustre_lnet_config_route, [Adding Routes](06.08-LNet%20Configuration%20C-API.md#adding-routes)
	lustre_lnet_del_net, [Deleting a Network Interface](06.08-LNet%20Configuration%20C-API.md#deleting-a-network-interface)
	lustre_lnet_del_route, [Deleting Routes](06.08-LNet%20Configuration%20C-API.md#deleting-routes)
	lustre_lnet_enable_routing, [Enabling and Disabling Routing](06.08-LNet%20Configuration%20C-API.md#enabling-and-disabling-routing)
	lustre_lnet_show stats, [Showing LNet Traffic Statistics](06.08-LNet%20Configuration%20C-API.md#showing-lnet-traffic-statistics)
	lustre_lnet_show_buf, [Showing Routing information](06.08-LNet%20Configuration%20C-API.md#showing-routing-information)
	lustre_lnet_show_net, [Showing Network Interfaces](06.08-LNet%20Configuration%20C-API.md#showing-network-interfaces)
	lustre_lnet_show_route, [Showing Routes](06.08-LNet%20Configuration%20C-API.md#showing-routes)
	lustre_yaml, [Adding/Deleting/Showing Parameters through a YAML Block](06.08-LNet%20Configuration%20C-API.md#addingdeletingshowing-parameters-through-a-yaml-block)
	management, [Updating the Health Status of a Peer or Router](03.04-ManagingLustreNetworking(LNet).md#updating-the-health-status-of-a-peer-or-router)
	module parameters, [Setting the LNet Module networks Parameter](02.06-Configuring%20Lustre%20Networking%20(LNet).md#setting-the-lnet-module-networks-parameter)
	network yaml syntax, [Network Configuration](02.06-Configuring%20Lustre%20Networking%20(LNet).md#network-configuration)
	proc, [Monitoring LNet](06.02-Lustre%20Parameters.md#monitoring-lnet)
	route checker, [Configuring the Router Checker](02.06-Configuring%20Lustre%20Networking%20(LNet).md#configuring-the-router-checker)
	router yaml syntax, [Route Configuration](02.06-Configuring%20Lustre%20Networking%20(LNet).md#route-configuration)
	routes, [Setting the LNet Module routes Parameter](02.06-Configuring%20Lustre%20Networking%20(LNet).md#setting-the-lnet-module-routes-parameter)
	routing example, [Routing Example](02.06-Configuring%20Lustre%20Networking%20(LNet).md#routing-example)
	self-test, [LNet Self-Test Overview](04.01-Testing%20Lustre%20Network%20Performance%20(LNet%20Self-Test).md#lnet-self-test-overview)
	show block, Show Block, [The LNet Configuration C-API](06.08-LNet%20Configuration%20C-API.md#the-lnet-configuration-c-api)
	starting/stopping, [Starting and Stopping LNet](03.04-ManagingLustreNetworking(LNet).md#starting-and-stopping-lnet)
	statistics yaml syntax, [Show Statistics](02.06-Configuring%20Lustre%20Networking%20(LNet).md#show-statistics)
	supported networks, [Supported Network Types](02-Introducing%20the%20Lustre%20File%20System.md#supported-network-types)
	testing, [Testing the LNet Configuration](02.06-Configuring%20Lustre%20Networking%20(LNet).md#testing-the-lnet-configuration)
	tuning, [Tuning LNet Parameters](04.03-Tuning%20a%20Lustre%20File%20System.md#tuning-lnet-parameters)
	understanding, [Introducing LNet](02-Introducing%20the%20Lustre%20File%20System.md#introducing-lnet)
	using NID, [Using a Lustre Network Identifier (NID) to Identify a Node](02.06-Configuring%20Lustre%20Networking%20(LNet).md#using-a-lustre-network-identifier-nid-to-identify-a-node)
	yaml syntax, [YAML Syntax](02.06-Configuring%20Lustre%20Networking%20(LNet).md#yaml-syntax)

logs, [Snapshot Logs](03.19-Lustre%20ZFS%20Snapshots.md#snapshot-logs)
lr_reader, [lr_reader](06.07-System%20Configuration%20Utilities.md#lr_reader)
lshowmount, [lshowmount](06.07-System%20Configuration%20Utilities.md#lshowmount)
lsom

​	enablelsom, [Enable LSoM](03.10-Lazy%20Size%20on%20MDT%20(LSoM).md#enable-lsom)
	intro, [Introduction to Lazy Size on MDT (LSoM)](03.10-Lazy%20Size%20on%20MDT%20(LSoM).md#introduction-to-lazy-size-on-mdt-lsom)
	lfsgetsom, [lfs getsom for LSoM data](03.10-Lazy%20Size%20on%20MDT%20(LSoM).md#lfs-getsom-for-lsom-data)
	usercommands, [User Commands](03.10-Lazy%20Size%20on%20MDT%20(LSoM).md#user-commands)

lst, [lst](06.07-System%20Configuration%20Utilities.md#lst)
Lustre, [What a Lustre File System Is (and What It Isn't)](02-Introducing%20the%20Lustre%20File%20System.md#what-a-lustre-file-system-is-and-what-it-isnt)

​	at scale, [Lustre Cluster](02-Introducing%20the%20Lustre%20File%20System.md#lustre-cluster)
	cluster, [Lustre Cluster](02-Introducing%20the%20Lustre%20File%20System.md#lustre-cluster)
	components, [Lustre Components](02-Introducing%20the%20Lustre%20File%20System.md#lustre-components)
	configuring, [Configuring a Simple Lustre File System](02.07-Configuring%20a%20Lustre%20File%20System.md#configuring-a-simple-lustre-file-system)

​		additional options, [Additional Configuration Options](02.07-Configuring%20a%20Lustre%20File%20System.md#additional-configuration-options)
		for scale, [Scaling the Lustre File System](02.07-Configuring%20a%20Lustre%20File%20System.md#scaling-the-lustre-file-system)
		simple example, [Simple Lustre Configuration Example](02.07-Configuring%20a%20Lustre%20File%20System.md#simple-lustre-configuration-example)
		striping, [Changing Striping Defaults](02.07-Configuring%20a%20Lustre%20File%20System.md#changing-striping-defaults)
		utilities, [Using the Lustre Configuration Utilities](02.07-Configuring%20a%20Lustre%20File%20System.md#using-the-lustre-configuration-utilities)

​	features, [Lustre Features](02-Introducing%20the%20Lustre%20File%20System.md#lustre-features)
	fileset, [Fileset Feature](06.07-System%20Configuration%20Utilities.md#fileset-feature)
	I/O, [Lustre File System Storage and I/O](02-Introducing%20the%20Lustre%20File%20System.md#lustre-file-system-storage-and-io)
	LNet, [Lustre Networking (LNet)](02-Introducing%20the%20Lustre%20File%20System.md#lustre-networking-lnet)	
	MGS, [Management Server (MGS)](02-Introducing%20the%20Lustre%20File%20System.md#management-server-mgs)
	Networks, [Lustre Networks](02-Introducing%20the%20Lustre%20File%20System.md#lustre-networks)

​	requirements, [Lustre File System Components](02-Introducing%20the%20Lustre%20File%20System.md#lustre-file-system-components)
	storage, [Lustre File System Storage and I/O](02-Introducing%20the%20Lustre%20File%20System.md#lustre-file-system-storage-and-io)
	striping, [Lustre File System and Striping](02-Introducing%20the%20Lustre%20File%20System.md#lustre-file-system-and-striping)
	upgrading (see [upgrading](#u))

lustre

​	errors (see [troubleshooting](#t))

​	recovery (see [recovery](#r))
	troubleshooting (see [troubleshooting](#t))

lustre_rmmod.sh, [lustre_rmmod.sh](06.07-System%20Configuration%20Utilities.md#lustre_rmmodsh)
lustre_rsync, [lustre_rsync](06.07-System%20Configuration%20Utilities.md#lustre_rsync)
LVM (see [backup](#b))
l_getidentity, [l_getidentity](06.07-System%20Configuration%20Utilities.md#l_getidentity)

## M
maintenance, [Working with Inactive OSTs](03.03-Lustre%20Maintenance.md#working-with-inactive-osts), [Working with Inactive MDTs](03.03-Lustre%20Maintenance.md#working-with-inactive-mdts)

​	aborting recovery, [Aborting Recovery](03.03-Lustre%20Maintenance.md#aborting-recovery)
	adding a OST, [Adding a New OST to a Lustre File System](03.03-Lustre%20Maintenance.md#adding-a-new-ost-to-a-lustre-file-system)
	adding an MDT, [Adding a New MDT to a Lustre File System](03.03-Lustre%20Maintenance.md#adding-a-new-mdt-to-a-lustre-file-system)
	backing up OST config, [Backing Up OST Configuration Files](03.03-Lustre%20Maintenance.md#backing-up-ost-configuration-files)
	bringing OST online, [Returning an Inactive OST Back Online](03.12-Managing%20the%20File%20System%20and%20IO.md#returning-an-inactive-ost-back-online)
	changing a NID, [Changing a Server NID](03.03-Lustre%20Maintenance.md#changing-a-server-nid)
	changing failover node address, [Changing the Address of a Failover Node](03.03-Lustre%20Maintenance.md#changing-the-address-of-a-failover-node)
	Clearing a config, [Clearing configuration](03.03-Lustre%20Maintenance.md#clearing-configuration)
	finding nodes, [Finding Nodes in the Lustre File System](03.03-Lustre%20Maintenance.md#finding-nodes-in-the-lustre-file-system)
	full OSTs, [Migrating Data within a File System](03.12-Managing%20the%20File%20System%20and%20IO.md#migrating-data-within-a-file-system)
	identifying OST host, [Determining Which Machine is Serving an OST](03.03-Lustre%20Maintenance.md#determining-which-machine-is-serving-an-ost)
	inactive MDTs, [Working with Inactive MDTs](03.03-Lustre%20Maintenance.md#working-with-inactive-mdts)L 2.4
	inactive OSTs, [Working with Inactive OSTs](03.03-Lustre%20Maintenance.md#working-with-inactive-osts)
	mounting a server, [Mounting a Server Without Lustre Service](03.03-Lustre%20Maintenance.md#mounting-a-server-without-lustre-service)
	pools, [Creating and Managing OST Pools](03.12-Managing%20the%20File%20System%20and%20IO.md#creating-and-managing-ost-pools)
	regenerating config logs, [Regenerating Lustre Configuration Logs](03.03-Lustre%20Maintenance.md#regenerating-lustre-configuration-logs)
	reintroducing an OSTs, [Returning a Deactivated OST to Service](03.03-Lustre%20Maintenance.md#returning-a-deactivated-ost-to-service)
	removing an MDT, [Removing an MDT from the File System](03.03-Lustre%20Maintenance.md#removing-an-mdt-from-the-file-system)
	removing an OST, [Removing and Restoring MDTs and OSTs](03.03-Lustre%20Maintenance.md#removing-and-restoring-mdts-and-osts), [Removing an OST from the File System](03.03-Lustre%20Maintenance.md#removing-an-ost-from-the-file-system)
	restoring an OST, [Removing and Restoring MDTs and OSTs](03.03-Lustre%20Maintenance.md#removing-and-restoring-mdts-and-osts)
	restoring OST config, [Restoring OST Configuration Files](03.03-Lustre%20Maintenance.md#restoring-ost-configuration-files)
	separate a combined MGS/MDT, [Separate a combined MGS/MDT](03.03-Lustre%20Maintenance.md#separate-a-combined-mgsmdt)

MDT

​	multiple MDSs, [Upgrading to Lustre Software Release 2.x (Major Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2x-major-release)

migrating metadata, [Migrating Metadata within a Filesystem](03.12-Managing%20the%20File%20System%20and%20IO.md#migrating-metadata-within-a-filesystem), [Whole Directory Migration](03.12-Managing%20the%20File%20System%20and%20IO.md#whole-directory-migration), [Striped Directory Migration](03.12-Managing%20the%20File%20System%20and%20IO.md#striped-directory-migration)
mkfs.lustre, [mkfs.lustre](06.07-System%20Configuration%20Utilities.md#mkfslustre)

###### monitoring, 

[Lustre Changelogs](03.01-Monitoring%20a%20Lustre%20File%20System.md#lustre-changelogs), [Lustre Jobstats](03.01-Monitoring%20a%20Lustre%20File%20System.md#lustre-jobstats)

​	additional tools, [Other Monitoring Options](03.01-Monitoring%20a%20Lustre%20File%20System.md#other-monitoring-options)
	change logs, [Lustre Changelogs](03.01-Monitoring%20a%20Lustre%20File%20System.md#lustre-changelogs), [Working with Changelogs](03.01-Monitoring%20a%20Lustre%20File%20System.md#working-with-changelogs)
	jobstats, [Lustre Jobstats](03.01-Monitoring%20a%20Lustre%20File%20System.md#lustre-jobstats), [How Jobstats Works](03.01-Monitoring%20a%20Lustre%20File%20System.md#how-jobstats-works), [Enable/Disable Jobstats](03.01-Monitoring%20a%20Lustre%20File%20System.md#enabledisable-jobstats), [Check Job Stats](03.01-Monitoring%20a%20Lustre%20File%20System.md#check-job-stats), [Clear Job Stats](03.01-Monitoring%20a%20Lustre%20File%20System.md#clear-job-stats), [Configure Auto-cleanup Interval](03.01-Monitoring%20a%20Lustre%20File%20System.md#configure-auto-cleanup-interval)
	Lustre Monitoring Tool, [Lustre Monitoring Tool (LMT)](03.01-Monitoring%20a%20Lustre%20File%20System.md#lustre-monitoring-tool-lmt)

mount, [mount](06.03-User%20Utilities.md#mount)
mount.lustre, [mount.lustre](06.07-System%20Configuration%20Utilities.md#mountlustre)
MR

​	addremotepeers, [Adding Remote Peers that are Multi-Rail Capable](03.05-LNet%20Software%20Multi-Rail%202.10.md#adding-remote-peers-that-are-multi-rail-capable)
	configuring, [Configuring Multi-Rail](03.05-LNet%20Software%20Multi-Rail%202.10.md#configuring-multi-rail)
	deleteinterfaces, [Deleting Network Interfaces](03.05-LNet%20Software%20Multi-Rail%202.10.md#deleting-network-interfaces)
	deleteremotepeers, [Deleting Remote Peers](03.05-LNet%20Software%20Multi-Rail%202.10.md#deleting-remote-peers)
	health, [LNet Health](03.05-LNet%20Software%20Multi-Rail%202.10.md#lnet-health)
	mrhealth

​		display, [Displaying Information](03.05-LNet%20Software%20Multi-Rail%202.10.md#displaying-information)
		failuretypes, [Failure Types and Behavior](03.05-LNet%20Software%20Multi-Rail%202.10.md#failure-types-and-behavior)
		initialsetup, [Initial Settings Recommendations](03.05-LNet%20Software%20Multi-Rail%202.10.md#initial-settings-recommendations)
		interface, [User Interface](03.05-LNet%20Software%20Multi-Rail%202.10.md#user-interface)
		value, [Health Value](03.05-LNet%20Software%20Multi-Rail%202.10.md#health-value)

​	mrrouting, [Notes on routing with Multi-Rail](03.05-LNet%20Software%20Multi-Rail%202.10.md#notes-on-routing-with-multi-rail)

​		routingex, [Multi-Rail Cluster Example](03.05-LNet%20Software%20Multi-Rail%202.10.md#multi-rail-cluster-example)
		routingmixed, [Mixed Multi-Rail/Non-Multi-Rail Cluster](03.05-LNet%20Software%20Multi-Rail%202.10.md#mixed-multi-railnon-multi-rail-cluster)
		routingresiliency, [Utilizing Router Resiliency](03.05-LNet%20Software%20Multi-Rail%202.10.md#utilizing-router-resiliency)

​	multipleinterfaces, [Configure Multiple Interfaces on the Local Node](03.05-LNet%20Software%20Multi-Rail%202.10.md#configure-multiple-interfaces-on-the-local-node)
	overview, [Multi-Rail Overview](03.05-LNet%20Software%20Multi-Rail%202.10.md#multi-rail-overview)

multiple-mount protection, [Overview of Multiple-Mount Protection](03.13-Lustre%20File%20System%20Failover%20and%20Multiple-Mount%20Protection.md#overview-of-multiple-mount-protection)

## O
obdfilter-survey, [obdfilter-survey](06.07-System%20Configuration%20Utilities.md#obdfilter-survey)
operations, [Mounting by Label](03.02-Lustre%20Operations.md#mounting-by-label), [Snapshot Operations](03.19-Lustre%20ZFS%20Snapshots.md#snapshot-operations)

​	create, [Creating a Snapshot](03.19-Lustre%20ZFS%20Snapshots.md#creating-a-snapshot)
	degraded OST RAID, [Handling Degraded OST RAID Arrays](03.02-Lustre%20Operations.md#handling-degraded-ost-raid-arrays)
	delete, [Delete a Snapshot](03.19-Lustre%20ZFS%20Snapshots.md#delete-a-snapshot)
	erasing a file system, [Erasing a File System](03.02-Lustre%20Operations.md#erasing-a-file-system)
	failover, [Specifying Failout/Failover Mode for OSTs](03.02-Lustre%20Operations.md#specifying-failoutfailover-mode-for-osts), [Specifying NIDs and Failover](03.02-Lustre%20Operations.md#specifying-nids-and-failover)
	identifying OSTs, [Identifying To Which Lustre File an OST Object Belongs](03.02-Lustre%20Operations.md#identifying-to-which-lustre-file-an-ost-object-belongs)
	list, [List Snapshots](03.19-Lustre%20ZFS%20Snapshots.md#list-snapshots)
	mkdir, [Creating a directory striped across multiple MDTs](03.02-Lustre%20Operations.md#creating-a-directory-striped-across-multiple-mdts)
	modify, [Modify Snapshot Attributes](03.19-Lustre%20ZFS%20Snapshots.md#modify-snapshot-attributes)
	mount, [Mounting a Snapshot](03.19-Lustre%20ZFS%20Snapshots.md#mounting-a-snapshot)
	mounting, [Mounting a Server](03.02-Lustre%20Operations.md#mounting-a-server)
	mounting by label, [Mounting by Label](03.02-Lustre%20Operations.md#mounting-by-label)
	multiple file systems, [Running Multiple Lustre File Systems](03.02-Lustre%20Operations.md#running-multiple-lustre-file-systems)
	parameters, [Setting and Retrieving Lustre Parameters](03.02-Lustre%20Operations.md#setting-and-retrieving-lustre-parameters)
	reclaiming space, [Reclaiming Reserved Disk Space](03.02-Lustre%20Operations.md#reclaiming-reserved-disk-space)
	remote directory, [Creating a sub-directory on a given MDT](03.02-Lustre%20Operations.md#creating-a-sub-directory-on-a-given-mdt)
	replacing an OST or MDS, [Replacing an Existing OST or MDT](03.02-Lustre%20Operations.md#replacing-an-existing-ost-or-mdt)
	setdirstripe, [Creating a directory striped across multiple MDTs](03.02-Lustre%20Operations.md#creating-a-directory-striped-across-multiple-mdts)	
	shutdownLustre, [Stopping the Filesystem](03.02-Lustre%20Operations.md#stopping-the-filesystem)
	starting, [Starting Lustre](03.02-Lustre%20Operations.md#starting-lustre)
	striped directory, [Creating a directory striped across multiple MDTs](03.02-Lustre%20Operations.md#creating-a-directory-striped-across-multiple-mdts)
	unmount, [Unmounting a Snapshot](03.19-Lustre%20ZFS%20Snapshots.md#unmounting-a-snapshot)
	unmounting, [Unmounting a Specific Target on a Server](03.02-Lustre%20Operations.md#unmounting-a-specific-target-on-a-server)

ost-survey, [ost-survey](06.07-System%20Configuration%20Utilities.md#ost-survey)

## P
performance (see [benchmarking](#benchmarking))
pings

​	evict_client, [Client Death Notification](06.01-Lustre%20File%20System%20Recovery.md#client-death-notification)
	suppress_pings, ["suppress_pings" Kernel Module Parameter](06.01-Lustre%20File%20System%20Recovery.md#suppress_pings-kernel-module-parameter)

plot-llstat, [plot-llstat](06.07-System%20Configuration%20Utilities.md#plot-llstat)
pools, [Creating and Managing OST Pools](03.12-Managing%20the%20File%20System%20and%20IO.md#creating-and-managing-ost-pools)

​	usage tips, [Tips for Using OST Pools](03.12-Managing%20the%20File%20System%20and%20IO.md#tips-for-using-ost-pools)

proc

​	adaptive timeouts, [Configuring Adaptive Timeouts](06.02-Lustre%20Parameters.md#configuring-adaptive-timeouts)
	block I/O, [Monitoring the OST Block I/O Stream](06.02-Lustre%20Parameters.md#monitoring-the-ost-block-io-stream)
	client metadata performance, [Tuning the Client Metadata RPC Stream](06.02-Lustre%20Parameters.md#tuning-the-client-metadata-rpc-stream)
	client stats, [Monitoring Client Activity](06.02-Lustre%20Parameters.md#monitoring-client-activity)
	configuring adaptive timeouts, [Configuring Adaptive Timeouts](06.02-Lustre%20Parameters.md#configuring-adaptive-timeouts)
	debug, [Enabling and Interpreting Debugging Logs](06.02-Lustre%20Parameters.md#enabling-and-interpreting-debugging-logs)
	free space, [Allocating Free Space on OSTs](06.02-Lustre%20Parameters.md#allocating-free-space-on-osts)
	LNet, [Monitoring LNet](06.02-Lustre%20Parameters.md#monitoring-lnet)
	locking, [Configuring Locking](06.02-Lustre%20Parameters.md#configuring-locking)
	OSS journal, [Enabling OSS Asynchronous Journal Commit](06.02-Lustre%20Parameters.md#enabling-oss-asynchronous-journal-commit)
	read cache, [Tuning OSS Read Cache](06.02-Lustre%20Parameters.md#tuning-oss-read-cache)
	read/write survey, [Monitoring Client Read-Write Offset Statistics](06.02-Lustre%20Parameters.md#monitoring-client-read-write-offset-statistics), [Monitoring Client Read-Write Extent 	Statistics](06.02-Lustre%20Parameters.md#monitoring-client-read-write-extent-statistics)
	readahead, [Tuning File Readahead and Directory Statahead](06.02-Lustre%20Parameters.md#tuning-file-readahead-and-directory-statahead)
	RPC tunables, [Tuning the Client I/O RPC Stream](06.02-Lustre%20Parameters.md#tuning-the-client-io-rpc-stream)
	static timeouts, [Setting Static Timeouts](06.02-Lustre%20Parameters.md#setting-static-timeouts)
	thread counts, [Setting MDS and OSS Thread Counts](06.02-Lustre%20Parameters.md#setting-mds-and-oss-thread-counts)
	watching RPC, [Monitoring the Client RPC Stream](06.02-Lustre%20Parameters.md#monitoring-the-client-rpc-stream)

profiling (see [benchmarking](#benchmarking))
programming

​	upcall, [User/Group Upcall](06.04-Programming%20Interfaces.md#usergroup-upcall)

## Q
Quotas

​	allocating, [Quota Allocation](03.14-Configuring%20and%20Managing%20Quotas.md#quota-allocation)
	configuring, [Working with Quotas](03.14-Configuring%20and%20Managing%20Quotas.md#working-with-quotas)
	creating, [Quota Administration](03.14-Configuring%20and%20Managing%20Quotas.md#quota-administration)
	enabling disk, [Enabling Disk Quotas](03.14-Configuring%20and%20Managing%20Quotas.md#enabling-disk-quotas)
	Interoperability, [Quotas and Version Interoperability](03.14-Configuring%20and%20Managing%20Quotas.md#quotas-and-version-interoperability)
	known issues, [Granted Cache and Quota Limits](03.14-Configuring%20and%20Managing%20Quotas.md#granted-cache-and-quota-limits)
	statistics, [Lustre Quota Statistics](03.14-Configuring%20and%20Managing%20Quotas.md#lustre-quota-statistics)
	verifying, [Quota Verification](03.14-Configuring%20and%20Managing%20Quotas.md#quota-verification)

## R
recovery, [Recovery Overview](06.01-Lustre%20File%20System%20Recovery.md#recovery-overview)

​	client eviction, [Client Eviction](06.01-Lustre%20File%20System%20Recovery.md#client-eviction)
	client failure, [Client Failure](06.01-Lustre%20File%20System%20Recovery.md#client-failure)
	commit on share (see [commit on share](06.01-Lustre%20File%20System%20Recovery.md#commit-on-share))
	corruption of backing ldiskfs file system, [Recovering from Errors or Corruption on a Backing ldiskfs File 	System](05.02-Troubleshooting%20Recovery.md#recovering-from-errors-or-corruption-on-a-backing-ldiskfs-file-system)
	corruption of Lustre file system, [Recovering from Corruption in the Lustre File System](05.02-Troubleshooting%20Recovery.md#recovering-from-corruption-in-the-lustre-file-system)
	failed recovery, [Failed Recovery](06.01-Lustre%20File%20System%20Recovery.md#failed-recovery)
	LFSCK, [Checking the file system with LFSCK](05.02-Troubleshooting%20Recovery.md#checking-the-file-system-with-lfsck)
	locks, [Lock Recovery](06.01-Lustre%20File%20System%20Recovery.md#lock-recovery)
	MDS failure, [MDS Failure (Failover)](06.01-Lustre%20File%20System%20Recovery.md#mds-failure-failover)
	metadata replay, [Metadata Replay](06.01-Lustre%20File%20System%20Recovery.md#metadata-replay)
	network, [Network Partition](06.01-Lustre%20File%20System%20Recovery.md#network-partition)
	oiscrub, [Checking the file system with LFSCK](05.02-Troubleshooting%20Recovery.md#checking-the-file-system-with-lfsck)
	orphaned objects, [Working with Orphaned Objects](05.02-Troubleshooting%20Recovery.md#working-with-orphaned-objects)
	OST failure, [OST Failure (Failover)](06.01-Lustre%20File%20System%20Recovery.md#ost-failure-failover)
	unavailable OST, [Recovering from an Unavailable OST](05.02-Troubleshooting%20Recovery.md#recovering-from-an-unavailable-ost)
	VBR (see [version-based recovery](06.01-Lustre%20File%20System%20Recovery.md#version-based-recovery))

reporting bugs (see [troubleshooting](#t))
restoring (see [backup](#b))
root squash, [Using Root Squash](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#using-root-squash)

​	configuring, [Configuring Root Squash](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#configuring-root-squash)
	enabling, [Enabling and Tuning Root Squash](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#enabling-and-tuning-root-squash)
	tips, [Tips on Using Root Squash](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#tips-on-using-root-squash)

round-robin algorithm, [Managing Free Space](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#managing-free-space)
routerstat, [routerstat](06.07-System%20Configuration%20Utilities.md#routerstat)
rsync (see [backup](#b))

## S
selinux policy check, [Checking SELinux Policy Enforced by Lustre Clients](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#checking-selinux-policy-enforced-by-lustre-clients)

​	determining, [Determining SELinux Policy Info](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#determining-selinux-policy-info)
	enforcing, [Enforcing SELinux Policy Check](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#enforcing-selinux-policy-check)
	making permanent, [Making SELinux Policy Check Permanent](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#making-selinux-policy-check-permanent)
	sending client, [Sending SELinux Status Info from Clients](03.18-Managing%20Security%20in%20a%20Lustre%20File%20System.md#sending-selinux-status-info-from-clients)

setup, [Hardware Considerations](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#hardware-considerations)

​	hardware, [Hardware Considerations](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#hardware-considerations)
	inodes, [Setting Formatting Options for an ldiskfs MDT](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#setting-formatting-options-for-an-ldiskfs-mdt)
	ldiskfs, [Setting ldiskfs File System Formatting Options](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#setting-ldiskfs-file-system-formatting-options)
	limits, [File and File System Limits](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#file-and-file-system-limits)
	MDT, [MGT and MDT Storage Hardware Considerations](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#mgt-and-mdt-storage-hardware-considerations), [Determining MDT Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-mdt-space-requirements)
	memory, [Determining Memory Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-memory-requirements)

​		client, [Client Memory Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#client-memory-requirements)
		MDS, MDS Memory Requirements, [Calculating MDS Memory Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#calculating-mds-memory-requirements)
		OSS, OSS Memory Requirements, [Calculating OSS Memory Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#calculating-oss-memory-requirements)

​	MGT, [Determining MGT Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-mgt-space-requirements)
	network, [Implementing Networks To Be Used by the Lustre File System](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#implementing-networks-to-be-used-by-the-lustre-file-system)
	OST, [OST Storage Hardware Considerations](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#ost-storage-hardware-considerations), [Determining OST Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-ost-space-requirements)
	space, [Determining Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-space-requirements)

sgpdd-survey, [sgpdd-survey](06.07-System%20Configuration%20Utilities.md#sgpdd-survey)

###### space,

 [How Lustre File System Striping Works](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#how-lustre-file-system-striping-works)

​	considerations, [Lustre File Layout (Striping) Considerations](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#lustre-file-layout-striping-considerations)
	determining MDT requirements, [Determining MDT Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-mdt-space-requirements)
	determining MGT requirements, [Determining MGT Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-mgt-space-requirements)
	determining OST requirements, [Determining OST Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-ost-space-requirements)
	determining requirements, [Determining Space Requirements](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#determining-space-requirements)
	free space, [Managing Free Space](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#managing-free-space)
	location weighting, [Adjusting the Weighting Between Free Space and Location](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#adjusting-the-weighting-between-free-space-and-location)
	striping, [How Lustre File System Striping Works](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#how-lustre-file-system-striping-works)

stats-collect, [stats-collect](06.07-System%20Configuration%20Utilities.md#stats-collect)
storage

​	configuring, [Selecting Storage for the MDT and OSTs](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#selecting-storage-for-the-mdt-and-osts)

​		external journal, [Choosing Parameters for an External Journal](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#choosing-parameters-for-an-external-journal)
		for best practice, [Reliability Best Practices](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#reliability-best-practices)
		for mkfs, [Computing file system parameters for mkfs](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#computing-file-system-parameters-for-mkfs)
		MDT, [Metadata Target (MDT)](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#metadata-target-mdt)
		OST, [Object Storage Server (OST)](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#object-storage-server-ost)
		RAID options, [Formatting Options for ldiskfs RAID Devices](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#formatting-options-for-ldiskfs-raid-devices)
		SAN, [Connecting a SAN to a Lustre File System](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#connecting-a-san-to-a-lustre-file-system)

​	performance tradeoffs, [Performance Tradeoffs](02.03-Configuring%20Storage%20on%20a%20Lustre%20File%20System.md#performance-tradeoffs)

striping (see [space](#space))

​	allocations, [Stripe Allocation Methods](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#stripe-allocation-methods)
	configuration, [Setting the File Layout/Striping Configuration (lfs setstripe)](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#setting-the-file-layoutstriping-configuration-lfs-setstripe)
	considerations, [Lustre File Layout (Striping) Considerations](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#lustre-file-layout-striping-considerations)
	count, [Setting the Stripe Count](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#setting-the-stripe-count)
	getting information, [Retrieving File Layout/Striping Information (getstripe)](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#retrieving-file-layoutstriping-information-getstripe)
	how it works, [How Lustre File System Striping Works](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#how-lustre-file-system-striping-works)
	metadata, [Creating a directory striped across multiple MDTs](03.02-Lustre%20Operations.md#creating-a-directory-striped-across-multiple-mdts)
	on specific OST, [Creating a File on a Specific OST](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#creating-a-file-on-a-specific-ost)
	overview, [Lustre File System and Striping](02-Introducing%20the%20Lustre%20File%20System.md#lustre-file-system-and-striping)
	per directory, [Setting the Striping Layout for a Directory](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#setting-the-striping-layout-for-a-directory)
	per file system, [Setting the Striping Layout for a File System](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#setting-the-striping-layout-for-a-file-system)
	PFL, [Progressive File Layout(PFL)](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#progressive-file-layoutpfl)
	remote directories, [Locating the MDT for a remote directory](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#locating-the-mdt-for-a-remote-directory)
	round-robin algorithm, [Managing Free Space](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#managing-free-space)
	size, [Choosing a Stripe Size](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#choosing-a-stripe-size)
	weighted algorithm, [Managing Free Space](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#managing-free-space)
	wide striping, [Lustre Striping Internals](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#lustre-striping-internals)

suppressing pings, [Suppressing Pings](06.01-Lustre%20File%20System%20Recovery.md#suppressing-pings)

## T
troubleshooting, [Lustre Error Messages](05.01-Lustre%20File%20System%20Troubleshooting.md#lustre-error-messages)

​	'Address already in use', [Handling/Debugging "Bind: Address already in use" Error](05.01-Lustre%20File%20System%20Troubleshooting.md#handlingdebugging-bind-address-already-in-use-error)
	'Error -28', [Handling/Debugging Error "- 28"](05.01-Lustre%20File%20System%20Troubleshooting.md#handlingdebugging-error---28)
	common problems, [Common Lustre File System Problems](05.01-Lustre%20File%20System%20Troubleshooting.md#common-lustre-file-system-problems)
	error messages, [Viewing Error Messages](05.01-Lustre%20File%20System%20Troubleshooting.md#viewing-error-messages)
	error numbers, [Error Numbers](05.01-Lustre%20File%20System%20Troubleshooting.md#error-numbers)
	OST out of memory, [Log Message 'Out of Memory' on OST](05.01-Lustre%20File%20System%20Troubleshooting.md#log-message-out-of-memory-on-ost)
	reporting bugs, [Reporting a Lustre File System Bug](05.01-Lustre%20File%20System%20Troubleshooting.md#reporting-a-lustre-file-system-bug)
	slowdown during startup, [Slowdown Occurs During Lustre File System Startup](05.01-Lustre%20File%20System%20Troubleshooting.md#slowdown-occurs-during-lustre-file-system-startup)
	timeouts on setup, [Handling Timeouts on Initial Lustre File System Setup](05.01-Lustre%20File%20System%20Troubleshooting.md#handling-timeouts-on-initial-lustre-file-system-setup)

tunefs.lustre, [tunefs.lustre](06.07-System%20Configuration%20Utilities.md#tunefslustre)
tuning, [Optimizing the Number of Service Threads](04.03-Tuning%20a%20Lustre%20File%20System.md#optimizing-the-number-of-service-threads) (see [benchmarking](#b))

​	for small files, [Improving Lustre I/O Performance for Small Files](04.03-Tuning%20a%20Lustre%20File%20System.md#improving-lustre-io-performance-for-small-files)
	Large Bulk IO, [Large Bulk IO (16MB RPC)](04.03-Tuning%20a%20Lustre%20File%20System.md#large-bulk-io-16mb-rpc)
	libcfs, [libcfs Tuning](04.03-Tuning%20a%20Lustre%20File%20System.md#libcfs-tuning)
	LND tuning, [LND Tuning](04.03-Tuning%20a%20Lustre%20File%20System.md#lnd-tuning)
	LNet, [Tuning LNet Parameters](04.03-Tuning%20a%20Lustre%20File%20System.md#tuning-lnet-parameters)
	lockless I/O, [Lockless I/O Tunables](04.03-Tuning%20a%20Lustre%20File%20System.md#lockless-io-tunables)
	MDS binding, [Binding MDS Service Thread to CPU Partitions](04.03-Tuning%20a%20Lustre%20File%20System.md#binding-mds-service-thread-to-cpu-partitions)
	MDS threads, [Specifying the MDS Service Thread Count](04.03-Tuning%20a%20Lustre%20File%20System.md#specifying-the-mds-service-thread-count)
	Network interface binding, [Binding Network Interface Against CPU Partitions](04.03-Tuning%20a%20Lustre%20File%20System.md#binding-network-interface-against-cpu-partitions)
	Network interface credits, [Network Interface Credits](04.03-Tuning%20a%20Lustre%20File%20System.md#network-interface-credits)
	Network Request Scheduler (NRS) Tuning, [Network Request Scheduler (NRS) Tuning](04.03-Tuning%20a%20Lustre%20File%20System.md#network-request-scheduler-nrs-tuning)

​		client round-robin over NIDs (CRR-N) policy, [Client Round-Robin over NIDs (CRR-N) policy](04.03-Tuning%20a%20Lustre%20File%20System.md#client-round-robin-over-nids-crr-n-policy)
		Delay policy, [Delay policy](04.03-Tuning%20a%20Lustre%20File%20System.md#delay-policy)
		first in, first out (FIFO) policy, [First In, First Out (FIFO) policy](04.03-Tuning%20a%20Lustre%20File%20System.md#first-in-first-out-fifo-policy)
		object-based round-robin (ORR) policy, [Object-based Round-Robin (ORR) policy](04.03-Tuning%20a%20Lustre%20File%20System.md#object-based-round-robin-orr-policy)
		Target-based round-robin (TRR) policy, [Target-based Round-Robin (TRR) policy](04.03-Tuning%20a%20Lustre%20File%20System.md#target-based-round-robin-trr-policy)
		Token Bucket Filter (TBF) policy, [Token Bucket Filter (TBF) policy](04.03-Tuning%20a%20Lustre%20File%20System.md#token-bucket-filter-tbf-policy)

​	OSS threads, [Specifying the OSS Service Thread Count](04.03-Tuning%20a%20Lustre%20File%20System.md#specifying-the-oss-service-thread-count)
	portal round-robin, [Portal Round-Robin](04.03-Tuning%20a%20Lustre%20File%20System.md#portal-round-robin)
	router buffers, [Router Buffers](04.03-Tuning%20a%20Lustre%20File%20System.md#router-buffers)
	service threads, [Optimizing the Number of Service Threads](04.03-Tuning%20a%20Lustre%20File%20System.md#optimizing-the-number-of-service-threads)
	with lfs ladvise, [Server-Side Advice and Hinting](04.03-Tuning%20a%20Lustre%20File%20System.md#server-side-advice-and-hinting)
	write performance, [Understanding Why Write Performance is Better Than Read Performance](04.03-Tuning%20a%20Lustre%20File%20System.md#understanding-why-write-performance-is-better-than-read-performance)

## U
upgrading, [Release Interoperability and Upgrade Requirements](03.06-Upgrading%20a%20Lustre%20File%20System.md#release-interoperability-and-upgrade-requirements)

​	2.X.y to 2.X.y (minor release), [Upgrading to Lustre Software Release 2.x.y (Minor Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2xy-minor-release)
	major release (2.x to 2.x), [Upgrading to Lustre Software Release 2.x (Major Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2x-major-release)

utilities

​	application profiling, [Application Profiling Utilities](06.07-System%20Configuration%20Utilities.md#application-profiling-utilities)
	debugging, [Testing / Debugging Utilities](06.07-System%20Configuration%20Utilities.md#testing--debugging-utilities)
	system config, [Additional System Configuration Utilities](06.07-System%20Configuration%20Utilities.md#additional-system-configuration-utilities)

## V
version

​	which version of Lustre am I running?, [Revisions](01-Preface.md#revisions)

Version-based recovery (VBR), [Version-based Recovery](06.01-Lustre%20File%20System%20Recovery.md#version-based-recovery)

​	messages, [VBR Messages](06.01-Lustre%20File%20System%20Recovery.md#vbr-messages)
	tips, [Tips for Using VBR](06.01-Lustre%20File%20System%20Recovery.md#tips-for-using-vbr)

## W
weighted algorithm, [Managing Free Space](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#managing-free-space)
wide striping, [File and File System Limits](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#file-and-file-system-limits), [Upgrading to Lustre Software Release 2.x (Major Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2x-major-release), [Lustre Striping Internals](03.08-Managing%20File%20Layout%20(Striping)%20and%20Free%20Space.md#lustre-striping-internals)

​	large_xattr

​		ea_inode, [File and File System Limits](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#file-and-file-system-limits), [Upgrading to Lustre Software Release 2.x (Major Release)](03.06-Upgrading%20a%20Lustre%20File%20System.md#upgrading-to-lustre-software-release-2x-major-release)

## X
xattr

​	See wide striping, [File and File System Limits](02.02-Determining%20Hardware%20Configuration%20Requirements%20and%20Formatting%20Options.md#file-and-file-system-limits)
