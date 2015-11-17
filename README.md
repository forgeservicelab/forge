
Copyright (c) 2015 DIGILE Ltd.
These contributions has been created by FORGE Service Lab funding granted by Finnish Ministry of Transport and Communications.

The contributions contain the copy of the FORGE Service Lab assets. External wiki was created to help FORGE Affiliates to use FORGE in digital service creation. Internal wiki was created to document internal processes and practices in building and operating FORGE Service Lab. Other assets contains code and Ansible playbooks which have been used to build and operate FORGE Service Lab SaaS environment. Assets also contain examples which can be used to build digital services.

The contributions contain valuable information in terms of digital service creation e.g. learning, setting up and using various technologies. The contributions have references and links to various services which may be discontinued and nonexistent e.g. git.forgeservicelab.fi, cloud.forgeservicelab.fi, support.forgeservicelab.fi and the links are provided as a reference.

The contributions may contain logos and trademarks referring to products, services and software owned by third parties. DIGILE has attempted to ensure that these logos and trademarks are used fairly only for the identification purposes according to the terms set by the owners of the logos and trademarks.

The contributions are licensed with open source licenses like Creative Commons Attribution-ShareAlike 3.0 Unported License, MIT, GPLv2 and GPLv3. The license is indicated in components. The contributions are listed in [Contributions section](#contributions).

FORGE Service Lab has also used some upstream components in building it's services. Links to used upstream components are provided in [Upstream section](#upstream).

The wiki documents below are the best place to start learning the content.

- [forge-external-wiki](https://github.com/forgeservicelab/forge/forge-external-wiki) contains external wiki documentation
- [forge-internal-wiki](https://github.com/forgeservicelab/forge/forge-internal-wiki) contains internal wiki documentation


Contributions
========================================

	ansible/SP_adder
	ansible/account-cleanup
	ansible/admin_config
	ansible/ansible_plaza
	ansible/backup-server
	ansible/ci
	ansible/django_saml_demo
	ansible/docker_playbook
	ansible/forge-birt
	ansible/forge-birt-reports-ansible
	ansible/gitlab
	ansible/gitlab-setadmin
	ansible/grid
	ansible/identity-backend
	ansible/idp
	ansible/inventory
	ansible/kapa-secureserver 
	ansible/kapa-testapp
	ansible/log-senders
	ansible/nagios4
	ansible/postgresql
	ansible/redmine
	ansible/testautomation
	ansible/training-setup
	ansible/vagrantizer
	ansible-modules/cinder-volumes
	ansible-modules/get-used-locales
	ansible-modules/nova-get-name
	ansible-modules/nova-state
	ansible-modules/patched-core-modules 
	ansible-modules/security-group-id 
	ansible-modules/server-groups
	ansible-roles/avro-sender
	ansible-roles/backup-source
	ansible-roles/backup-target
	ansible-roles/birt-reports
	ansible-roles/birt-viewer
	ansible-roles/casino
	ansible-roles/common
	ansible-roles/django_saml_app
	ansible-roles/drupal
	ansible-roles/firewallder
	ansible-roles/forge-error-pages
	ansible-roles/forge_hostname
	ansible-roles/forge_jenkins_mods
	ansible-roles/forge_ssl
	ansible-roles/forge_users
	ansible-roles/gitlab
	ansible-roles/grid
	ansible-roles/ha-disk
	ansible-roles/ha-loadbalancer
	ansible-roles/heartbeat
	ansible-roles/ipython
	ansible-roles/jmeter
	ansible-roles/kapa-secureserver
	ansible-roles/load-balancer
	ansible-roles/ltb_password_app
	ansible-roles/mysql
	ansible-roles/mysql-replication-master
	ansible-roles/mysql-replication-slave
	ansible-roles/nagios4
	ansible-roles/nfs
	ansible-roles/openfire
	ansible-roles/phpldapadmin
	ansible-roles/piwik-ssl
	ansible-roles/postgresql-replication-master
	ansible-roles/postgresql-replication-standby
	ansible-roles/redis
	ansible-roles/redmine
	ansible-roles/resource-usage-reporting-ansible
	ansible-roles/robot_framework
	ansible-roles/simplesamlphp
	ansible-roles/synchronizer
	ansible-roles/zato
	druid/web
	forge/benchmark
	forge/combined-log-parser
	forge/forge-birt-reportdesigns
	forge/forge-piwik
	forge/forge-processes
	forge/forge-support-wiki
	forge/internal-wiki
	forge/GeoAccess
	forge/insightly-fetch
	forge/insightly-sync
	forge/internal-navigation-menu
	forge/Mailing-List
	forge/redmine_bulk_issue_closer
	forge/resource-usage-reporting
	forge-redmine-plugins/redmine_pdf_macro
	forge-redmine-plugins/redmine_statistics
	heartbeat-openstack/floatingip
	provisioning-tools/apache-libcloud
	redmine-plugins-ansible-modules/generic_install
	redmine-plugins-ansible-modules/redmine_backlogs
	redmine-plugins-ansible-modules/redmine_my_page_queries
	testautomation/common
	testautomation/example
	testautomation/forge-birt-reportdesign-tests
	testautomation/gitlab
	testautomation/hadoop_performance_analysis
	testautomation/helpers
	testautomation/idp
	testautomation/imagecreation
	testautomation/openstack
	testautomation/password
	testautomation/performance
	testautomation/performance_example
	testautomation/plaza
	testautomation/redmine
	testautomation/sso
	testautomation/xmpp

Upstream
========================================

	ansible-roles.timezone origin:https://github.com.knopki.ansible-timezone.git
	ansible.cdh5-hadoop origin:http://www.cloudera.com/content/cloudera/en/documentation/cdh5/latest/CDH5-Release-Notes/cdh5rn_new_in_513.html
	ansible-modules.openstack-ansible-modules origin:http://github.com/lorin/openstack-ansible
	ansible-roles.ansible-piwik origin:https://github.com/ICTO/ansible-piwik.git
	ansible-roles.jenkins origin:https://github.com/Stouts/Stouts.jenkins.git
	ansible-roles.openldap_server origin:https://github.com/bennojoy/openldap_server.git
	forge.casinoapp origin:https://github.com/rbCAS/CASinoApp.git
	forge.forge-password-change origin:http://ltb-project.org/wiki/download
	forge.gitlab-ce origin:https://gitlab.com/gitlab-org/gitlab-ce/
	forge.redmine origin:http://www.redmine.org
	forge-redmine-plugins.redmine_anonymous_watchers origin:git@github.com:pheelay/redmine_anonymous_watchers.git
	forge-redmine-plugins.redmine_backlogs origin:https://github.com/backlogs/redmine_backlogs.git
	forge-redmine-plugins.redmine_canned_responses origin:https://github.com/commandprompt/redmine_canned_responses.git
	forge-redmine-plugins.redmine_cas origin:https://github.com/ninech/redmine_cas.git
	forge-redmine-plugins.redmine_email_notification_content_filter origin:https://github.com/keeps/redmine_email_notification_content_filter.git
	forge-redmine-plugins.redmine_extended_watchers origin:https://github.com/maxrossello/redmine_extended_watchers.git
	forge-redmine-plugins.redmine_impasse origin:https://github.com/kawasima/redmine_impasse.git
	forge-redmine-plugins.redmine_improved_searchbox origin:https://github.com/ries-tech/redmine_improved_searchbox.git
	forge-redmine-plugins.redmine_ldap_sync origin:https://github.com/thorin/redmine_ldap_sync.git
	forge-redmine-plugins.redmine_my_page_queries origin:git://github.com/Undev/redmine_my_page_queries.git
	forge-redmine-plugins.redmine_watcher_groups origin:https://github.com/kamenf/redmine_watcher_groups.git
	forge-redmine-plugins.redmine_wiki_extensions origin:https://bitbucket.org/haru_iida/redmine_wiki_extensions
