

.. _plugins_in_qiyutech.foreman:

Qiyutech.Foreman
================

Collection version 1.0.0

.. contents::
   :local:
   :depth: 1

Description
-----------

QiYuTech Foreman Collection

**Author:**

* dev <dev@qiyutech.tech>

.. raw:: html

  <p class="ansible-links">
    <a href="https://github.com/QiYuTechAnsible/CollectionDocs/issues" aria-role="button" target="_blank" rel="noopener external">Issue Tracker</a>
    <a href="https://github.com/QiYuTechAnsible/CollectionDocs" aria-role="button" target="_blank" rel="noopener external">Repository (Sources)</a>
  </p>



.. toctree::
    :maxdepth: 1

额外文档示例
------

.. toctree::
    :maxdepth: 1

    docsite/demo
    docsite/workflow


Plugin Index
------------

These are the plugins in the qiyutech.foreman collection:


Modules
~~~~~~~

* :ref:`ansible_api_ansible_inventories_hostgroups module <ansible_collections.qiyutech.foreman.ansible_api_ansible_inventories_hostgroups_module>` -- Show Ansible inventory for hostgroups
* :ref:`ansible_api_ansible_inventories_hostgroups_post module <ansible_collections.qiyutech.foreman.ansible_api_ansible_inventories_hostgroups_post_module>` -- Show Ansible inventory for hostgroups
* :ref:`ansible_api_ansible_inventories_hosts module <ansible_collections.qiyutech.foreman.ansible_api_ansible_inventories_hosts_module>` -- Show Ansible inventory for hosts
* :ref:`ansible_api_ansible_inventories_hosts_post module <ansible_collections.qiyutech.foreman.ansible_api_ansible_inventories_hosts_post_module>` -- Show Ansible inventory for hosts
* :ref:`ansible_api_ansible_inventories_schedule_post module <ansible_collections.qiyutech.foreman.ansible_api_ansible_inventories_schedule_post_module>` -- Schedule generating of Ansible Inventory report
* :ref:`ansible_api_ansible_override_values_id_delete module <ansible_collections.qiyutech.foreman.ansible_api_ansible_override_values_id_delete_module>` -- Destroy an override value
* :ref:`ansible_api_ansible_override_values_post module <ansible_collections.qiyutech.foreman.ansible_api_ansible_override_values_post_module>` -- Create an override value for a specific ansible variable
* :ref:`ansible_api_ansible_roles module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_module>` -- List Ansible roles
* :ref:`ansible_api_ansible_roles_fetch module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_fetch_module>` -- Fetch Ansible roles available to be synced
* :ref:`ansible_api_ansible_roles_id module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_id_module>` -- Show role
* :ref:`ansible_api_ansible_roles_id_delete module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_id_delete_module>` -- Deletes Ansible role
* :ref:`ansible_api_ansible_roles_import_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_import_put_module>` -- 
* :ref:`ansible_api_ansible_roles_obsolete_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_obsolete_put_module>` -- 
* :ref:`ansible_api_ansible_roles_sync_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_roles_sync_put_module>` -- Sync Ansible roles
* :ref:`ansible_api_ansible_variables module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_module>` -- List Ansible variables
* :ref:`ansible_api_ansible_variables_id module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_id_module>` -- Show variable
* :ref:`ansible_api_ansible_variables_id_delete module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_id_delete_module>` -- Deletes Ansible variable
* :ref:`ansible_api_ansible_variables_id_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_id_put_module>` -- Updates Ansible variable
* :ref:`ansible_api_ansible_variables_import_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_import_put_module>` -- 
* :ref:`ansible_api_ansible_variables_obsolete_put module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_obsolete_put_module>` -- 
* :ref:`ansible_api_ansible_variables_post module <ansible_collections.qiyutech.foreman.ansible_api_ansible_variables_post_module>` -- Create Ansible variable
* :ref:`api module <ansible_collections.qiyutech.foreman.api_module>` -- Show available API links
* :ref:`api_architectures module <ansible_collections.qiyutech.foreman.api_architectures_module>` -- List all architectures
* :ref:`api_architectures_architecture_id_images module <ansible_collections.qiyutech.foreman.api_architectures_architecture_id_images_module>` -- List all images for architecture
* :ref:`api_architectures_architecture_id_images_id module <ansible_collections.qiyutech.foreman.api_architectures_architecture_id_images_id_module>` -- Show an image
* :ref:`api_architectures_architecture_id_operatingsystems module <ansible_collections.qiyutech.foreman.api_architectures_architecture_id_operatingsystems_module>` -- List all operating systems for nested architecture
* :ref:`api_architectures_id module <ansible_collections.qiyutech.foreman.api_architectures_id_module>` -- Show an architecture
* :ref:`api_architectures_id_delete module <ansible_collections.qiyutech.foreman.api_architectures_id_delete_module>` -- Delete an architecture
* :ref:`api_architectures_id_put module <ansible_collections.qiyutech.foreman.api_architectures_id_put_module>` -- Update an architecture
* :ref:`api_architectures_post module <ansible_collections.qiyutech.foreman.api_architectures_post_module>` -- Create an architecture
* :ref:`api_audits module <ansible_collections.qiyutech.foreman.api_audits_module>` -- List all audits
* :ref:`api_audits_id module <ansible_collections.qiyutech.foreman.api_audits_id_module>` -- Show an audit
* :ref:`api_auth_source_externals module <ansible_collections.qiyutech.foreman.api_auth_source_externals_module>` -- List external authentication sources
* :ref:`api_auth_source_externals_auth_source_external_id_users module <ansible_collections.qiyutech.foreman.api_auth_source_externals_auth_source_external_id_users_module>` -- List all users for external authentication source
* :ref:`api_auth_source_externals_id module <ansible_collections.qiyutech.foreman.api_auth_source_externals_id_module>` -- Show an external authentication source
* :ref:`api_auth_source_externals_id_put module <ansible_collections.qiyutech.foreman.api_auth_source_externals_id_put_module>` -- Update an external authentication source
* :ref:`api_auth_source_internals module <ansible_collections.qiyutech.foreman.api_auth_source_internals_module>` -- List internal authentication sources
* :ref:`api_auth_source_internals_id module <ansible_collections.qiyutech.foreman.api_auth_source_internals_id_module>` -- Show an internal authentication source
* :ref:`api_auth_source_ldaps module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_module>` -- List all LDAP authentication sources
* :ref:`api_auth_source_ldaps_auth_source_ldap_id_external_usergroups module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_auth_source_ldap_id_external_usergroups_module>` -- List all external user groups for LDAP authentication source
* :ref:`api_auth_source_ldaps_auth_source_ldap_id_external_usergroups_id module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_auth_source_ldap_id_external_usergroups_id_module>` -- Show an external user group for LDAP authentication source
* :ref:`api_auth_source_ldaps_auth_source_ldap_id_users module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_auth_source_ldap_id_users_module>` -- List all users for LDAP authentication source
* :ref:`api_auth_source_ldaps_id module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_id_module>` -- Show an LDAP authentication source
* :ref:`api_auth_source_ldaps_id_delete module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_id_delete_module>` -- Delete an LDAP authentication source
* :ref:`api_auth_source_ldaps_id_put module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_id_put_module>` -- Update an LDAP authentication source
* :ref:`api_auth_source_ldaps_id_test_put module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_id_test_put_module>` -- Test LDAP connection
* :ref:`api_auth_source_ldaps_post module <ansible_collections.qiyutech.foreman.api_auth_source_ldaps_post_module>` -- Create an LDAP authentication source
* :ref:`api_auth_sources module <ansible_collections.qiyutech.foreman.api_auth_sources_module>` -- List all authentication sources
* :ref:`api_bookmarks module <ansible_collections.qiyutech.foreman.api_bookmarks_module>` -- List all bookmarks
* :ref:`api_bookmarks_id module <ansible_collections.qiyutech.foreman.api_bookmarks_id_module>` -- Show a bookmark
* :ref:`api_bookmarks_id_delete module <ansible_collections.qiyutech.foreman.api_bookmarks_id_delete_module>` -- Delete a bookmark
* :ref:`api_bookmarks_id_put module <ansible_collections.qiyutech.foreman.api_bookmarks_id_put_module>` -- Update a bookmark
* :ref:`api_bookmarks_post module <ansible_collections.qiyutech.foreman.api_bookmarks_post_module>` -- Create a bookmark
* :ref:`api_common_parameters module <ansible_collections.qiyutech.foreman.api_common_parameters_module>` -- List all global parameters
* :ref:`api_common_parameters_id module <ansible_collections.qiyutech.foreman.api_common_parameters_id_module>` -- Show a global parameter
* :ref:`api_common_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_common_parameters_id_delete_module>` -- Delete a global parameter
* :ref:`api_common_parameters_id_put module <ansible_collections.qiyutech.foreman.api_common_parameters_id_put_module>` -- Update a global parameter
* :ref:`api_common_parameters_post module <ansible_collections.qiyutech.foreman.api_common_parameters_post_module>` -- Create a global parameter
* :ref:`api_compute_attributes_id module <ansible_collections.qiyutech.foreman.api_compute_attributes_id_module>` -- Show a compute attributes set
* :ref:`api_compute_attributes_id_put module <ansible_collections.qiyutech.foreman.api_compute_attributes_id_put_module>` -- Update a compute attributes set
* :ref:`api_compute_attributes_post module <ansible_collections.qiyutech.foreman.api_compute_attributes_post_module>` -- Create a compute attributes set
* :ref:`api_compute_profiles module <ansible_collections.qiyutech.foreman.api_compute_profiles_module>` -- List of compute profiles
* :ref:`api_compute_profiles_compute_profile_id_compute_attributes module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_attributes_module>` -- List of compute attributes for compute profile
* :ref:`api_compute_profiles_compute_profile_id_compute_attributes_id module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_attributes_id_module>` -- Show a compute attributes set
* :ref:`api_compute_profiles_compute_profile_id_compute_attributes_id_put module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_attributes_id_put_module>` -- Update a compute attributes set
* :ref:`api_compute_profiles_compute_profile_id_compute_attributes_post module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_attributes_post_module>` -- Create a compute attributes set
* :ref:`api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_module>` -- List of compute attributes for provided compute profile and compute resource
* :ref:`api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id_module>` -- Show a compute attributes set
* :ref:`api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id_put module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id_put_module>` -- Update a compute attributes set
* :ref:`api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_post module <ansible_collections.qiyutech.foreman.api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_post_module>` -- Create a compute attributes set
* :ref:`api_compute_profiles_id module <ansible_collections.qiyutech.foreman.api_compute_profiles_id_module>` -- Show a compute profile
* :ref:`api_compute_profiles_id_delete module <ansible_collections.qiyutech.foreman.api_compute_profiles_id_delete_module>` -- Delete a compute profile
* :ref:`api_compute_profiles_id_put module <ansible_collections.qiyutech.foreman.api_compute_profiles_id_put_module>` -- Update a compute profile
* :ref:`api_compute_profiles_post module <ansible_collections.qiyutech.foreman.api_compute_profiles_post_module>` -- Create a compute profile
* :ref:`api_compute_resources module <ansible_collections.qiyutech.foreman.api_compute_resources_module>` -- List all compute resources
* :ref:`api_compute_resources_compute_resource_id_compute_attributes module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_attributes_module>` -- List of compute attributes for compute resource
* :ref:`api_compute_resources_compute_resource_id_compute_attributes_id module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_attributes_id_module>` -- Show a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_compute_attributes_id_put module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_attributes_id_put_module>` -- Update a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_compute_attributes_post module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_attributes_post_module>` -- Create a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_module>` -- List of compute attributes for provided compute profile and compute resource
* :ref:`api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id_module>` -- Show a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id_put module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id_put_module>` -- Update a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_post module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_post_module>` -- Create a compute attributes set
* :ref:`api_compute_resources_compute_resource_id_images module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_images_module>` -- List all images for a compute resource
* :ref:`api_compute_resources_compute_resource_id_images_id module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_images_id_module>` -- Show an image
* :ref:`api_compute_resources_compute_resource_id_images_id_delete module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_images_id_delete_module>` -- Delete an image
* :ref:`api_compute_resources_compute_resource_id_images_id_put module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_images_id_put_module>` -- Update an image
* :ref:`api_compute_resources_compute_resource_id_images_post module <ansible_collections.qiyutech.foreman.api_compute_resources_compute_resource_id_images_post_module>` -- Create an image
* :ref:`api_compute_resources_id module <ansible_collections.qiyutech.foreman.api_compute_resources_id_module>` -- Show a compute resource
* :ref:`api_compute_resources_id_associate_put module <ansible_collections.qiyutech.foreman.api_compute_resources_id_associate_put_module>` -- Associate VMs to Hosts
* :ref:`api_compute_resources_id_available_clusters module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_clusters_module>` -- List available clusters for a compute resource
* :ref:`api_compute_resources_id_available_clusters_cluster_id_available_networks module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_clusters_cluster_id_available_networks_module>` -- List available networks for a compute resource cluster
* :ref:`api_compute_resources_id_available_clusters_cluster_id_available_resource_pools module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_clusters_cluster_id_available_resource_pools_module>` -- List resource pools for a compute resource cluster
* :ref:`api_compute_resources_id_available_clusters_cluster_id_available_storage_domains module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_clusters_cluster_id_available_storage_domains_module>` -- List storage domains for a compute resource
* :ref:`api_compute_resources_id_available_clusters_cluster_id_available_storage_pods module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_clusters_cluster_id_available_storage_pods_module>` -- List storage pods for a compute resource
* :ref:`api_compute_resources_id_available_flavors module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_flavors_module>` -- List available flavors for a compute resource
* :ref:`api_compute_resources_id_available_folders module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_folders_module>` -- List available folders for a compute resource
* :ref:`api_compute_resources_id_available_images module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_images_module>` -- List available images for a compute resource
* :ref:`api_compute_resources_id_available_networks module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_networks_module>` -- List available networks for a compute resource
* :ref:`api_compute_resources_id_available_security_groups module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_security_groups_module>` -- List available security groups for a compute resource
* :ref:`api_compute_resources_id_available_storage_domains module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_storage_domains_module>` -- List storage domains for a compute resource
* :ref:`api_compute_resources_id_available_storage_domains_storage_domain module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_storage_domains_storage_domain_module>` -- List attributes for a given storage domain
* :ref:`api_compute_resources_id_available_storage_pods module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_storage_pods_module>` -- List storage pods for a compute resource
* :ref:`api_compute_resources_id_available_storage_pods_storage_pod module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_storage_pods_storage_pod_module>` -- List attributes for a given storage pod
* :ref:`api_compute_resources_id_available_virtual_machines module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_virtual_machines_module>` -- List available virtual machines for a compute resource
* :ref:`api_compute_resources_id_available_virtual_machines_vm_id module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_virtual_machines_vm_id_module>` -- Show a virtual machine
* :ref:`api_compute_resources_id_available_virtual_machines_vm_id_delete module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_virtual_machines_vm_id_delete_module>` -- Delete a Virtual Machine
* :ref:`api_compute_resources_id_available_virtual_machines_vm_id_power_put module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_virtual_machines_vm_id_power_put_module>` -- Power a Virtual Machine
* :ref:`api_compute_resources_id_available_vnic_profiles module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_vnic_profiles_module>` -- List available vnic profiles for a compute resource, for oVirt only
* :ref:`api_compute_resources_id_available_zones module <ansible_collections.qiyutech.foreman.api_compute_resources_id_available_zones_module>` -- List available zone for a compute resource
* :ref:`api_compute_resources_id_delete module <ansible_collections.qiyutech.foreman.api_compute_resources_id_delete_module>` -- Delete a compute resource
* :ref:`api_compute_resources_id_put module <ansible_collections.qiyutech.foreman.api_compute_resources_id_put_module>` -- Update a compute resource
* :ref:`api_compute_resources_id_refresh_cache_put module <ansible_collections.qiyutech.foreman.api_compute_resources_id_refresh_cache_put_module>` -- Refresh Compute Resource Cache
* :ref:`api_compute_resources_id_storage_domains_storage_domain_id module <ansible_collections.qiyutech.foreman.api_compute_resources_id_storage_domains_storage_domain_id_module>` -- List attributes for a given storage domain
* :ref:`api_compute_resources_id_storage_pods_storage_pod_id module <ansible_collections.qiyutech.foreman.api_compute_resources_id_storage_pods_storage_pod_id_module>` -- List attributes for a given storage pod
* :ref:`api_compute_resources_post module <ansible_collections.qiyutech.foreman.api_compute_resources_post_module>` -- Create a compute resource
* :ref:`api_config_reports module <ansible_collections.qiyutech.foreman.api_config_reports_module>` -- List all reports
* :ref:`api_config_reports_id module <ansible_collections.qiyutech.foreman.api_config_reports_id_module>` -- Show a report
* :ref:`api_config_reports_id_delete module <ansible_collections.qiyutech.foreman.api_config_reports_id_delete_module>` -- Delete a report
* :ref:`api_config_reports_post module <ansible_collections.qiyutech.foreman.api_config_reports_post_module>` -- Create a report
* :ref:`api_current_user module <ansible_collections.qiyutech.foreman.api_current_user_module>` -- Show the currently logged-in user
* :ref:`api_dashboard module <ansible_collections.qiyutech.foreman.api_dashboard_module>` -- Get dashboard details
* :ref:`api_domains module <ansible_collections.qiyutech.foreman.api_domains_module>` -- List of domains
* :ref:`api_domains_domain_id_interfaces module <ansible_collections.qiyutech.foreman.api_domains_domain_id_interfaces_module>` -- List all interfaces for domain
* :ref:`api_domains_domain_id_parameters module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_module>` -- List all parameters for a domain
* :ref:`api_domains_domain_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_delete_module>` -- Delete all nested parameters for a domain
* :ref:`api_domains_domain_id_parameters_id module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_id_module>` -- Show a nested parameter for a domain
* :ref:`api_domains_domain_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_id_delete_module>` -- Delete a nested parameter for a domain
* :ref:`api_domains_domain_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_id_put_module>` -- Update a nested parameter for a domain
* :ref:`api_domains_domain_id_parameters_post module <ansible_collections.qiyutech.foreman.api_domains_domain_id_parameters_post_module>` -- Create a nested parameter for a domain
* :ref:`api_domains_domain_id_subnets module <ansible_collections.qiyutech.foreman.api_domains_domain_id_subnets_module>` -- List of subnets for a domain
* :ref:`api_domains_id module <ansible_collections.qiyutech.foreman.api_domains_id_module>` -- Show a domain
* :ref:`api_domains_id_delete module <ansible_collections.qiyutech.foreman.api_domains_id_delete_module>` -- Delete a domain
* :ref:`api_domains_id_put module <ansible_collections.qiyutech.foreman.api_domains_id_put_module>` -- Update a domain
* :ref:`api_domains_post module <ansible_collections.qiyutech.foreman.api_domains_post_module>` -- Create a domain
* :ref:`api_environments_environment_id_hosts module <ansible_collections.qiyutech.foreman.api_environments_environment_id_hosts_module>` -- List hosts per environment
* :ref:`api_environments_environment_id_smart_proxies_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.api_environments_environment_id_smart_proxies_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy for an environment
* :ref:`api_environments_environment_id_template_combinations module <ansible_collections.qiyutech.foreman.api_environments_environment_id_template_combinations_module>` -- 
* :ref:`api_environments_environment_id_template_combinations_id module <ansible_collections.qiyutech.foreman.api_environments_environment_id_template_combinations_id_module>` -- 
* :ref:`api_environments_environment_id_template_combinations_id_put module <ansible_collections.qiyutech.foreman.api_environments_environment_id_template_combinations_id_put_module>` -- 
* :ref:`api_environments_environment_id_template_combinations_post module <ansible_collections.qiyutech.foreman.api_environments_environment_id_template_combinations_post_module>` -- 
* :ref:`api_fact_values module <ansible_collections.qiyutech.foreman.api_fact_values_module>` -- List all fact values
* :ref:`api_filters module <ansible_collections.qiyutech.foreman.api_filters_module>` -- List all filters
* :ref:`api_filters_id module <ansible_collections.qiyutech.foreman.api_filters_id_module>` -- Show a filter
* :ref:`api_filters_id_delete module <ansible_collections.qiyutech.foreman.api_filters_id_delete_module>` -- Delete a filter
* :ref:`api_filters_id_put module <ansible_collections.qiyutech.foreman.api_filters_id_put_module>` -- Update a filter
* :ref:`api_filters_post module <ansible_collections.qiyutech.foreman.api_filters_post_module>` -- Create a filter
* :ref:`api_hostgroups module <ansible_collections.qiyutech.foreman.api_hostgroups_module>` -- List all host groups
* :ref:`api_hostgroups_hostgroup_id_hosts module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_hosts_module>` -- List all hosts for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_module>` -- List all parameters for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_delete_module>` -- Delete all nested parameters for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters_id module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_id_module>` -- Show a nested parameter for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_id_delete_module>` -- Delete a nested parameter for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_id_put_module>` -- Update a nested parameter for a host group
* :ref:`api_hostgroups_hostgroup_id_parameters_post module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_parameters_post_module>` -- Create a nested parameter for a host group
* :ref:`api_hostgroups_hostgroup_id_template_combinations module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_template_combinations_module>` -- List template combination
* :ref:`api_hostgroups_hostgroup_id_template_combinations_id module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_template_combinations_id_module>` -- Show template combination
* :ref:`api_hostgroups_hostgroup_id_template_combinations_id_put module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_template_combinations_id_put_module>` -- Update template combination
* :ref:`api_hostgroups_hostgroup_id_template_combinations_post module <ansible_collections.qiyutech.foreman.api_hostgroups_hostgroup_id_template_combinations_post_module>` -- Add a template combination
* :ref:`api_hostgroups_id module <ansible_collections.qiyutech.foreman.api_hostgroups_id_module>` -- Show a host group
* :ref:`api_hostgroups_id_ansible_roles module <ansible_collections.qiyutech.foreman.api_hostgroups_id_ansible_roles_module>` -- List all Ansible roles for a hostgroup
* :ref:`api_hostgroups_id_assign_ansible_roles_post module <ansible_collections.qiyutech.foreman.api_hostgroups_id_assign_ansible_roles_post_module>` -- Assigns Ansible roles to a hostgroup
* :ref:`api_hostgroups_id_clone_post module <ansible_collections.qiyutech.foreman.api_hostgroups_id_clone_post_module>` -- Clone a host group
* :ref:`api_hostgroups_id_delete module <ansible_collections.qiyutech.foreman.api_hostgroups_id_delete_module>` -- Delete a host group
* :ref:`api_hostgroups_id_play_roles_post module <ansible_collections.qiyutech.foreman.api_hostgroups_id_play_roles_post_module>` -- Runs all Ansible roles on a hostgroup
* :ref:`api_hostgroups_id_put module <ansible_collections.qiyutech.foreman.api_hostgroups_id_put_module>` -- Update a host group
* :ref:`api_hostgroups_id_rebuild_config_put module <ansible_collections.qiyutech.foreman.api_hostgroups_id_rebuild_config_put_module>` -- Rebuild orchestration config
* :ref:`api_hostgroups_multiple_play_roles_post module <ansible_collections.qiyutech.foreman.api_hostgroups_multiple_play_roles_post_module>` -- Runs all Ansible roles on hostgroups
* :ref:`api_hostgroups_post module <ansible_collections.qiyutech.foreman.api_hostgroups_post_module>` -- Create a host group
* :ref:`api_hosts module <ansible_collections.qiyutech.foreman.api_hosts_module>` -- List all hosts
* :ref:`api_hosts_facts_post module <ansible_collections.qiyutech.foreman.api_hosts_facts_post_module>` -- Upload facts for a host, creating the host if required
* :ref:`api_hosts_host_id_audits module <ansible_collections.qiyutech.foreman.api_hosts_host_id_audits_module>` -- List all audits for a given host
* :ref:`api_hosts_host_id_config_reports_last module <ansible_collections.qiyutech.foreman.api_hosts_host_id_config_reports_last_module>` -- Show the last report for a host
* :ref:`api_hosts_host_id_facts module <ansible_collections.qiyutech.foreman.api_hosts_host_id_facts_module>` -- List all fact values of a given host
* :ref:`api_hosts_host_id_interfaces module <ansible_collections.qiyutech.foreman.api_hosts_host_id_interfaces_module>` -- List all interfaces for host
* :ref:`api_hosts_host_id_interfaces_id module <ansible_collections.qiyutech.foreman.api_hosts_host_id_interfaces_id_module>` -- Show an interface for host
* :ref:`api_hosts_host_id_interfaces_id_delete module <ansible_collections.qiyutech.foreman.api_hosts_host_id_interfaces_id_delete_module>` -- Delete a host's interface
* :ref:`api_hosts_host_id_interfaces_id_put module <ansible_collections.qiyutech.foreman.api_hosts_host_id_interfaces_id_put_module>` -- Update a host's interface
* :ref:`api_hosts_host_id_interfaces_post module <ansible_collections.qiyutech.foreman.api_hosts_host_id_interfaces_post_module>` -- Create an interface on a host
* :ref:`api_hosts_host_id_parameters module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_module>` -- List all parameters for a host
* :ref:`api_hosts_host_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_delete_module>` -- Delete all nested parameters for a host
* :ref:`api_hosts_host_id_parameters_id module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_id_module>` -- Show a nested parameter for a host
* :ref:`api_hosts_host_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_id_delete_module>` -- Delete a nested parameter for a host
* :ref:`api_hosts_host_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_id_put_module>` -- Update a nested parameter for a host
* :ref:`api_hosts_host_id_parameters_post module <ansible_collections.qiyutech.foreman.api_hosts_host_id_parameters_post_module>` -- Create a nested parameter for a host
* :ref:`api_hosts_id module <ansible_collections.qiyutech.foreman.api_hosts_id_module>` -- Show a host
* :ref:`api_hosts_id_ansible_roles module <ansible_collections.qiyutech.foreman.api_hosts_id_ansible_roles_module>` -- List all Ansible roles for a host
* :ref:`api_hosts_id_assign_ansible_roles_post module <ansible_collections.qiyutech.foreman.api_hosts_id_assign_ansible_roles_post_module>` -- Assigns Ansible roles to a host
* :ref:`api_hosts_id_boot_put module <ansible_collections.qiyutech.foreman.api_hosts_id_boot_put_module>` -- Boot host from specified device
* :ref:`api_hosts_id_delete module <ansible_collections.qiyutech.foreman.api_hosts_id_delete_module>` -- Delete a host
* :ref:`api_hosts_id_disassociate_put module <ansible_collections.qiyutech.foreman.api_hosts_id_disassociate_put_module>` -- Disassociate the host from a VM
* :ref:`api_hosts_id_enc module <ansible_collections.qiyutech.foreman.api_hosts_id_enc_module>` -- Get ENC values of host
* :ref:`api_hosts_id_play_roles_post module <ansible_collections.qiyutech.foreman.api_hosts_id_play_roles_post_module>` -- Runs all Ansible roles on a host
* :ref:`api_hosts_id_power module <ansible_collections.qiyutech.foreman.api_hosts_id_power_module>` -- Fetch the status of whether the host is powered on or not. Supported hosts are VMs and physical hosts with BMCs.
* :ref:`api_hosts_id_power_put module <ansible_collections.qiyutech.foreman.api_hosts_id_power_put_module>` -- Run a power operation on host
* :ref:`api_hosts_id_puppetrun_put module <ansible_collections.qiyutech.foreman.api_hosts_id_puppetrun_put_module>` -- Force a Puppet agent run on the host
* :ref:`api_hosts_id_put module <ansible_collections.qiyutech.foreman.api_hosts_id_put_module>` -- Update a host
* :ref:`api_hosts_id_rebuild_config_put module <ansible_collections.qiyutech.foreman.api_hosts_id_rebuild_config_put_module>` -- Rebuild orchestration config
* :ref:`api_hosts_id_status_type module <ansible_collections.qiyutech.foreman.api_hosts_id_status_type_module>` -- Get status of host
* :ref:`api_hosts_id_status_type_delete module <ansible_collections.qiyutech.foreman.api_hosts_id_status_type_delete_module>` -- Clear sub-status of host
* :ref:`api_hosts_id_template_kind module <ansible_collections.qiyutech.foreman.api_hosts_id_template_kind_module>` -- Preview rendered provisioning template content
* :ref:`api_hosts_id_vm_compute_attributes module <ansible_collections.qiyutech.foreman.api_hosts_id_vm_compute_attributes_module>` -- Get vm attributes of host
* :ref:`api_hosts_multiple_play_roles_post module <ansible_collections.qiyutech.foreman.api_hosts_multiple_play_roles_post_module>` -- Runs all Ansible roles on hosts
* :ref:`api_hosts_post module <ansible_collections.qiyutech.foreman.api_hosts_post_module>` -- Create a host
* :ref:`api_http_proxies module <ansible_collections.qiyutech.foreman.api_http_proxies_module>` -- List of HTTP Proxies
* :ref:`api_http_proxies_id module <ansible_collections.qiyutech.foreman.api_http_proxies_id_module>` -- Show an HTTP Proxy
* :ref:`api_http_proxies_id_delete module <ansible_collections.qiyutech.foreman.api_http_proxies_id_delete_module>` -- Delete an HTTP Proxy
* :ref:`api_http_proxies_id_put module <ansible_collections.qiyutech.foreman.api_http_proxies_id_put_module>` -- Update an HTTP Proxy
* :ref:`api_http_proxies_post module <ansible_collections.qiyutech.foreman.api_http_proxies_post_module>` -- Create an HTTP Proxy
* :ref:`api_job_invocations module <ansible_collections.qiyutech.foreman.api_job_invocations_module>` -- List job invocations
* :ref:`api_job_invocations_id module <ansible_collections.qiyutech.foreman.api_job_invocations_id_module>` -- Show job invocation
* :ref:`api_job_invocations_id_cancel_post module <ansible_collections.qiyutech.foreman.api_job_invocations_id_cancel_post_module>` -- Cancel job invocation
* :ref:`api_job_invocations_id_hosts_host_id module <ansible_collections.qiyutech.foreman.api_job_invocations_id_hosts_host_id_module>` -- Get output for a host
* :ref:`api_job_invocations_id_hosts_host_id_raw module <ansible_collections.qiyutech.foreman.api_job_invocations_id_hosts_host_id_raw_module>` -- Get raw output for a host
* :ref:`api_job_invocations_id_outputs module <ansible_collections.qiyutech.foreman.api_job_invocations_id_outputs_module>` -- Get outputs of hosts in a job
* :ref:`api_job_invocations_id_rerun_post module <ansible_collections.qiyutech.foreman.api_job_invocations_id_rerun_post_module>` -- Rerun job on failed hosts
* :ref:`api_job_invocations_job_invocation_id_template_invocations module <ansible_collections.qiyutech.foreman.api_job_invocations_job_invocation_id_template_invocations_module>` -- List template invocations belonging to job invocation
* :ref:`api_job_invocations_post module <ansible_collections.qiyutech.foreman.api_job_invocations_post_module>` -- Create a job invocation
* :ref:`api_job_templates module <ansible_collections.qiyutech.foreman.api_job_templates_module>` -- List job templates
* :ref:`api_job_templates_id module <ansible_collections.qiyutech.foreman.api_job_templates_id_module>` -- Show job template details
* :ref:`api_job_templates_id_clone_post module <ansible_collections.qiyutech.foreman.api_job_templates_id_clone_post_module>` -- Clone a provision template
* :ref:`api_job_templates_id_delete module <ansible_collections.qiyutech.foreman.api_job_templates_id_delete_module>` -- Delete a job template
* :ref:`api_job_templates_id_export module <ansible_collections.qiyutech.foreman.api_job_templates_id_export_module>` -- Export a job template to ERB
* :ref:`api_job_templates_id_put module <ansible_collections.qiyutech.foreman.api_job_templates_id_put_module>` -- Update a job template
* :ref:`api_job_templates_import_post module <ansible_collections.qiyutech.foreman.api_job_templates_import_post_module>` -- Import a job template from ERB
* :ref:`api_job_templates_post module <ansible_collections.qiyutech.foreman.api_job_templates_post_module>` -- Create a job template
* :ref:`api_job_templates_revision module <ansible_collections.qiyutech.foreman.api_job_templates_revision_module>` -- None
* :ref:`api_locations module <ansible_collections.qiyutech.foreman.api_locations_module>` -- List all locations
* :ref:`api_locations_id module <ansible_collections.qiyutech.foreman.api_locations_id_module>` -- Show a location
* :ref:`api_locations_id_delete module <ansible_collections.qiyutech.foreman.api_locations_id_delete_module>` -- Delete a location
* :ref:`api_locations_id_put module <ansible_collections.qiyutech.foreman.api_locations_id_put_module>` -- Update a location
* :ref:`api_locations_location_id_auth_source_externals module <ansible_collections.qiyutech.foreman.api_locations_location_id_auth_source_externals_module>` -- List external authentication sources per location
* :ref:`api_locations_location_id_auth_source_ldaps module <ansible_collections.qiyutech.foreman.api_locations_location_id_auth_source_ldaps_module>` -- List LDAP authentication sources per location
* :ref:`api_locations_location_id_auth_sources module <ansible_collections.qiyutech.foreman.api_locations_location_id_auth_sources_module>` -- List all authentication sources per location
* :ref:`api_locations_location_id_domains module <ansible_collections.qiyutech.foreman.api_locations_location_id_domains_module>` -- List of domains per location
* :ref:`api_locations_location_id_hostgroups module <ansible_collections.qiyutech.foreman.api_locations_location_id_hostgroups_module>` -- List all host groups per location
* :ref:`api_locations_location_id_hosts module <ansible_collections.qiyutech.foreman.api_locations_location_id_hosts_module>` -- List hosts per location
* :ref:`api_locations_location_id_job_templates module <ansible_collections.qiyutech.foreman.api_locations_location_id_job_templates_module>` -- List job templates per location
* :ref:`api_locations_location_id_media module <ansible_collections.qiyutech.foreman.api_locations_location_id_media_module>` -- List all media per location
* :ref:`api_locations_location_id_parameters module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_module>` -- List all parameters for a location
* :ref:`api_locations_location_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_delete_module>` -- Delete all nested parameter for a location
* :ref:`api_locations_location_id_parameters_id module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_id_module>` -- Show a nested parameter for a location
* :ref:`api_locations_location_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_id_delete_module>` -- Delete a nested parameter for a location
* :ref:`api_locations_location_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_id_put_module>` -- Update a nested parameter for a location
* :ref:`api_locations_location_id_parameters_post module <ansible_collections.qiyutech.foreman.api_locations_location_id_parameters_post_module>` -- Create a nested parameter for a location
* :ref:`api_locations_location_id_provisioning_templates module <ansible_collections.qiyutech.foreman.api_locations_location_id_provisioning_templates_module>` -- List provisioning templates per location
* :ref:`api_locations_location_id_ptables module <ansible_collections.qiyutech.foreman.api_locations_location_id_ptables_module>` -- List all partition tables per location
* :ref:`api_locations_location_id_report_templates module <ansible_collections.qiyutech.foreman.api_locations_location_id_report_templates_module>` -- List all report templates per location
* :ref:`api_locations_location_id_subnets module <ansible_collections.qiyutech.foreman.api_locations_location_id_subnets_module>` -- List of subnets per location
* :ref:`api_locations_location_id_users module <ansible_collections.qiyutech.foreman.api_locations_location_id_users_module>` -- List all users for location
* :ref:`api_locations_post module <ansible_collections.qiyutech.foreman.api_locations_post_module>` -- Create a location
* :ref:`api_mail_notifications module <ansible_collections.qiyutech.foreman.api_mail_notifications_module>` -- List of email notifications
* :ref:`api_mail_notifications_id module <ansible_collections.qiyutech.foreman.api_mail_notifications_id_module>` -- Show an email notification
* :ref:`api_media module <ansible_collections.qiyutech.foreman.api_media_module>` -- List all installation media
* :ref:`api_media_id module <ansible_collections.qiyutech.foreman.api_media_id_module>` -- Show a medium
* :ref:`api_media_id_delete module <ansible_collections.qiyutech.foreman.api_media_id_delete_module>` -- Delete a medium
* :ref:`api_media_id_put module <ansible_collections.qiyutech.foreman.api_media_id_put_module>` -- Update a medium
* :ref:`api_media_medium_id_operatingsystems module <ansible_collections.qiyutech.foreman.api_media_medium_id_operatingsystems_module>` -- List all operating systems for nested medium
* :ref:`api_media_post module <ansible_collections.qiyutech.foreman.api_media_post_module>` -- Create a medium
* :ref:`api_models module <ansible_collections.qiyutech.foreman.api_models_module>` -- List all hardware models
* :ref:`api_models_id module <ansible_collections.qiyutech.foreman.api_models_id_module>` -- Show a hardware model
* :ref:`api_models_id_delete module <ansible_collections.qiyutech.foreman.api_models_id_delete_module>` -- Delete a hardware model
* :ref:`api_models_id_put module <ansible_collections.qiyutech.foreman.api_models_id_put_module>` -- Update a hardware model
* :ref:`api_models_post module <ansible_collections.qiyutech.foreman.api_models_post_module>` -- Create a hardware model
* :ref:`api_operatingsystems module <ansible_collections.qiyutech.foreman.api_operatingsystems_module>` -- List all operating systems
* :ref:`api_operatingsystems_id module <ansible_collections.qiyutech.foreman.api_operatingsystems_id_module>` -- Show an operating system
* :ref:`api_operatingsystems_id_bootfiles module <ansible_collections.qiyutech.foreman.api_operatingsystems_id_bootfiles_module>` -- List boot files for an operating system
* :ref:`api_operatingsystems_id_delete module <ansible_collections.qiyutech.foreman.api_operatingsystems_id_delete_module>` -- Delete an operating system
* :ref:`api_operatingsystems_id_put module <ansible_collections.qiyutech.foreman.api_operatingsystems_id_put_module>` -- Update an operating system
* :ref:`api_operatingsystems_operatingsystem_id_architectures module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_architectures_module>` -- List all architectures for operating system
* :ref:`api_operatingsystems_operatingsystem_id_images module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_images_module>` -- List all images for operating system
* :ref:`api_operatingsystems_operatingsystem_id_images_id module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_images_id_module>` -- Show an image
* :ref:`api_operatingsystems_operatingsystem_id_media module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_media_module>` -- List all media for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_os_default_templates module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_os_default_templates_module>` -- List default templates combinations for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_os_default_templates_id module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_os_default_templates_id_module>` -- Show a default template combination for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_os_default_templates_id_delete module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_os_default_templates_id_delete_module>` -- Delete a default template combination for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_os_default_templates_id_put module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_os_default_templates_id_put_module>` -- Update a default template combination for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_os_default_templates_post module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_os_default_templates_post_module>` -- Create a default template combination for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_module>` -- List all parameters for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_delete_module>` -- Delete all nested parameters for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters_id module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_id_module>` -- Show a nested parameter for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_id_delete_module>` -- Delete a nested parameter for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_id_put_module>` -- Update a nested parameter for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_parameters_post module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_parameters_post_module>` -- Create a nested parameter for an operating system
* :ref:`api_operatingsystems_operatingsystem_id_provisioning_templates module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_provisioning_templates_module>` -- List provisioning templates per operating system
* :ref:`api_operatingsystems_operatingsystem_id_ptables module <ansible_collections.qiyutech.foreman.api_operatingsystems_operatingsystem_id_ptables_module>` -- List all partition tables for an operating system
* :ref:`api_operatingsystems_post module <ansible_collections.qiyutech.foreman.api_operatingsystems_post_module>` -- Create an operating system
* :ref:`api_orchestration_id_tasks module <ansible_collections.qiyutech.foreman.api_orchestration_id_tasks_module>` -- List all tasks for a given orchestration event
* :ref:`api_organizations module <ansible_collections.qiyutech.foreman.api_organizations_module>` -- List all organizations
* :ref:`api_organizations_id module <ansible_collections.qiyutech.foreman.api_organizations_id_module>` -- Show an organization
* :ref:`api_organizations_id_delete module <ansible_collections.qiyutech.foreman.api_organizations_id_delete_module>` -- Delete an organization
* :ref:`api_organizations_id_put module <ansible_collections.qiyutech.foreman.api_organizations_id_put_module>` -- Update an organization
* :ref:`api_organizations_organization_id_auth_source_externals module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_auth_source_externals_module>` -- List external authentication sources per organization
* :ref:`api_organizations_organization_id_auth_source_ldaps module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_auth_source_ldaps_module>` -- List LDAP authentication sources per organization
* :ref:`api_organizations_organization_id_auth_sources module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_auth_sources_module>` -- List all authentication sources per organization
* :ref:`api_organizations_organization_id_domains module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_domains_module>` -- List of domains per organization
* :ref:`api_organizations_organization_id_hostgroups module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_hostgroups_module>` -- List all host groups per organization
* :ref:`api_organizations_organization_id_hosts module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_hosts_module>` -- List hosts per organization
* :ref:`api_organizations_organization_id_job_templates module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_job_templates_module>` -- List job templates per organization
* :ref:`api_organizations_organization_id_media module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_media_module>` -- List all media per organization
* :ref:`api_organizations_organization_id_parameters module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_module>` -- List all parameters for an organization
* :ref:`api_organizations_organization_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_delete_module>` -- Delete all nested parameter for an organization
* :ref:`api_organizations_organization_id_parameters_id module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_id_module>` -- Show a nested parameter for an organization
* :ref:`api_organizations_organization_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_id_delete_module>` -- Delete a nested parameter for an organization
* :ref:`api_organizations_organization_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_id_put_module>` -- Update a nested parameter for an organization
* :ref:`api_organizations_organization_id_parameters_post module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_parameters_post_module>` -- Create a nested parameter for an organization
* :ref:`api_organizations_organization_id_provisioning_templates module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_provisioning_templates_module>` -- List provisioning templates per organization
* :ref:`api_organizations_organization_id_ptables module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_ptables_module>` -- List all partition tables per organization
* :ref:`api_organizations_organization_id_report_templates module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_report_templates_module>` -- List all report templates per organization
* :ref:`api_organizations_organization_id_subnets module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_subnets_module>` -- List of subnets per organization
* :ref:`api_organizations_organization_id_users module <ansible_collections.qiyutech.foreman.api_organizations_organization_id_users_module>` -- List all users for organization
* :ref:`api_organizations_post module <ansible_collections.qiyutech.foreman.api_organizations_post_module>` -- Create an organization
* :ref:`api_permissions module <ansible_collections.qiyutech.foreman.api_permissions_module>` -- List all permissions
* :ref:`api_permissions_id module <ansible_collections.qiyutech.foreman.api_permissions_id_module>` -- Show a permission
* :ref:`api_permissions_resource_types module <ansible_collections.qiyutech.foreman.api_permissions_resource_types_module>` -- List available resource types
* :ref:`api_ping module <ansible_collections.qiyutech.foreman.api_ping_module>` -- Shows status of Foreman system and it's subcomponents
* :ref:`api_plugins module <ansible_collections.qiyutech.foreman.api_plugins_module>` -- List installed plugins
* :ref:`api_provisioning_templates module <ansible_collections.qiyutech.foreman.api_provisioning_templates_module>` -- List provisioning templates
* :ref:`api_provisioning_templates_build_pxe_default_post module <ansible_collections.qiyutech.foreman.api_provisioning_templates_build_pxe_default_post_module>` -- Update the default PXE menu on all configured TFTP servers
* :ref:`api_provisioning_templates_id module <ansible_collections.qiyutech.foreman.api_provisioning_templates_id_module>` -- Show provisioning template details
* :ref:`api_provisioning_templates_id_clone_post module <ansible_collections.qiyutech.foreman.api_provisioning_templates_id_clone_post_module>` -- Clone a provision template
* :ref:`api_provisioning_templates_id_delete module <ansible_collections.qiyutech.foreman.api_provisioning_templates_id_delete_module>` -- Delete a provisioning template
* :ref:`api_provisioning_templates_id_export module <ansible_collections.qiyutech.foreman.api_provisioning_templates_id_export_module>` -- Export a provisioning template to ERB
* :ref:`api_provisioning_templates_id_put module <ansible_collections.qiyutech.foreman.api_provisioning_templates_id_put_module>` -- Update a provisioning template
* :ref:`api_provisioning_templates_import_post module <ansible_collections.qiyutech.foreman.api_provisioning_templates_import_post_module>` -- Import a provisioning template
* :ref:`api_provisioning_templates_post module <ansible_collections.qiyutech.foreman.api_provisioning_templates_post_module>` -- Create a provisioning template
* :ref:`api_provisioning_templates_provisioning_template_id_operatingsystems module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_operatingsystems_module>` -- List all operating systems for nested provisioning template
* :ref:`api_provisioning_templates_provisioning_template_id_os_default_templates module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_os_default_templates_module>` -- List operating systems where this template is set as a default
* :ref:`api_provisioning_templates_provisioning_template_id_template_combinations module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_template_combinations_module>` -- List template combination
* :ref:`api_provisioning_templates_provisioning_template_id_template_combinations_id module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_template_combinations_id_module>` -- Show template combination
* :ref:`api_provisioning_templates_provisioning_template_id_template_combinations_id_put module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_template_combinations_id_put_module>` -- Update template combination
* :ref:`api_provisioning_templates_provisioning_template_id_template_combinations_post module <ansible_collections.qiyutech.foreman.api_provisioning_templates_provisioning_template_id_template_combinations_post_module>` -- Add a template combination
* :ref:`api_provisioning_templates_revision module <ansible_collections.qiyutech.foreman.api_provisioning_templates_revision_module>` -- None
* :ref:`api_ptables module <ansible_collections.qiyutech.foreman.api_ptables_module>` -- List all partition tables
* :ref:`api_ptables_id module <ansible_collections.qiyutech.foreman.api_ptables_id_module>` -- Show a partition table
* :ref:`api_ptables_id_clone_post module <ansible_collections.qiyutech.foreman.api_ptables_id_clone_post_module>` -- Clone a template
* :ref:`api_ptables_id_delete module <ansible_collections.qiyutech.foreman.api_ptables_id_delete_module>` -- Delete a partition table
* :ref:`api_ptables_id_export module <ansible_collections.qiyutech.foreman.api_ptables_id_export_module>` -- Export a partition template to ERB
* :ref:`api_ptables_id_put module <ansible_collections.qiyutech.foreman.api_ptables_id_put_module>` -- Update a partition table
* :ref:`api_ptables_import_post module <ansible_collections.qiyutech.foreman.api_ptables_import_post_module>` -- Import a provisioning template
* :ref:`api_ptables_post module <ansible_collections.qiyutech.foreman.api_ptables_post_module>` -- Create a partition table
* :ref:`api_ptables_ptable_id_operatingsystems module <ansible_collections.qiyutech.foreman.api_ptables_ptable_id_operatingsystems_module>` -- List all operating systems for nested partition table
* :ref:`api_ptables_revision module <ansible_collections.qiyutech.foreman.api_ptables_revision_module>` -- None
* :ref:`api_puppetclasses_puppetclass_id_hostgroups module <ansible_collections.qiyutech.foreman.api_puppetclasses_puppetclass_id_hostgroups_module>` -- List all host groups for a Puppet class
* :ref:`api_realms module <ansible_collections.qiyutech.foreman.api_realms_module>` -- List of realms
* :ref:`api_realms_id module <ansible_collections.qiyutech.foreman.api_realms_id_module>` -- Show a realm
* :ref:`api_realms_id_delete module <ansible_collections.qiyutech.foreman.api_realms_id_delete_module>` -- Delete a realm
* :ref:`api_realms_id_put module <ansible_collections.qiyutech.foreman.api_realms_id_put_module>` -- Update a realm
* :ref:`api_realms_post module <ansible_collections.qiyutech.foreman.api_realms_post_module>` -- Create a realm
* :ref:`api_register module <ansible_collections.qiyutech.foreman.api_register_module>` -- Render Global registration template
* :ref:`api_register_post module <ansible_collections.qiyutech.foreman.api_register_post_module>` -- Find or create a host and render the 'Host initial configuration' template
* :ref:`api_registration_commands_post module <ansible_collections.qiyutech.foreman.api_registration_commands_post_module>` -- Generate global registration command
* :ref:`api_remote_execution_features module <ansible_collections.qiyutech.foreman.api_remote_execution_features_module>` -- List remote execution features
* :ref:`api_remote_execution_features_id module <ansible_collections.qiyutech.foreman.api_remote_execution_features_id_module>` -- Show remote execution feature
* :ref:`api_remote_execution_features_id_put module <ansible_collections.qiyutech.foreman.api_remote_execution_features_id_put_module>` -- Update a job template
* :ref:`api_report_templates module <ansible_collections.qiyutech.foreman.api_report_templates_module>` -- List all report templates
* :ref:`api_report_templates_id module <ansible_collections.qiyutech.foreman.api_report_templates_id_module>` -- Show a report template
* :ref:`api_report_templates_id_clone_post module <ansible_collections.qiyutech.foreman.api_report_templates_id_clone_post_module>` -- Clone a template
* :ref:`api_report_templates_id_delete module <ansible_collections.qiyutech.foreman.api_report_templates_id_delete_module>` -- Delete a report template
* :ref:`api_report_templates_id_export module <ansible_collections.qiyutech.foreman.api_report_templates_id_export_module>` -- Export a report template to ERB
* :ref:`api_report_templates_id_generate_post module <ansible_collections.qiyutech.foreman.api_report_templates_id_generate_post_module>` -- Generate report from a template
* :ref:`api_report_templates_id_put module <ansible_collections.qiyutech.foreman.api_report_templates_id_put_module>` -- Update a report template
* :ref:`api_report_templates_id_report_data_job_id module <ansible_collections.qiyutech.foreman.api_report_templates_id_report_data_job_id_module>` -- Downloads a generated report
* :ref:`api_report_templates_id_schedule_report_post module <ansible_collections.qiyutech.foreman.api_report_templates_id_schedule_report_post_module>` -- Schedule generating of a report
* :ref:`api_report_templates_import_post module <ansible_collections.qiyutech.foreman.api_report_templates_import_post_module>` -- Import a report template
* :ref:`api_report_templates_post module <ansible_collections.qiyutech.foreman.api_report_templates_post_module>` -- Create a report template
* :ref:`api_report_templates_revision module <ansible_collections.qiyutech.foreman.api_report_templates_revision_module>` -- None
* :ref:`api_roles module <ansible_collections.qiyutech.foreman.api_roles_module>` -- List all roles
* :ref:`api_roles_id module <ansible_collections.qiyutech.foreman.api_roles_id_module>` -- Show a role
* :ref:`api_roles_id_clone_post module <ansible_collections.qiyutech.foreman.api_roles_id_clone_post_module>` -- Clone a role
* :ref:`api_roles_id_delete module <ansible_collections.qiyutech.foreman.api_roles_id_delete_module>` -- Delete a role
* :ref:`api_roles_id_put module <ansible_collections.qiyutech.foreman.api_roles_id_put_module>` -- Update a role
* :ref:`api_roles_post module <ansible_collections.qiyutech.foreman.api_roles_post_module>` -- Create a role
* :ref:`api_roles_role_id_users module <ansible_collections.qiyutech.foreman.api_roles_role_id_users_module>` -- List all users for role
* :ref:`api_settings module <ansible_collections.qiyutech.foreman.api_settings_module>` -- List all settings
* :ref:`api_settings_id module <ansible_collections.qiyutech.foreman.api_settings_id_module>` -- Show a setting
* :ref:`api_settings_id_put module <ansible_collections.qiyutech.foreman.api_settings_id_put_module>` -- Update a setting
* :ref:`api_smart_proxies module <ansible_collections.qiyutech.foreman.api_smart_proxies_module>` -- List all smart proxies
* :ref:`api_smart_proxies_id module <ansible_collections.qiyutech.foreman.api_smart_proxies_id_module>` -- Show a smart proxy
* :ref:`api_smart_proxies_id_delete module <ansible_collections.qiyutech.foreman.api_smart_proxies_id_delete_module>` -- Delete a smart proxy
* :ref:`api_smart_proxies_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.api_smart_proxies_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy
* :ref:`api_smart_proxies_id_put module <ansible_collections.qiyutech.foreman.api_smart_proxies_id_put_module>` -- Update a smart proxy
* :ref:`api_smart_proxies_id_refresh_put module <ansible_collections.qiyutech.foreman.api_smart_proxies_id_refresh_put_module>` -- Refresh smart proxy features
* :ref:`api_smart_proxies_post module <ansible_collections.qiyutech.foreman.api_smart_proxies_post_module>` -- Create a smart proxy
* :ref:`api_smart_proxies_smart_proxy_id_autosign module <ansible_collections.qiyutech.foreman.api_smart_proxies_smart_proxy_id_autosign_module>` -- List all autosign entries
* :ref:`api_smart_proxies_smart_proxy_id_autosign_id_delete module <ansible_collections.qiyutech.foreman.api_smart_proxies_smart_proxy_id_autosign_id_delete_module>` -- Delete autosign entry
* :ref:`api_smart_proxies_smart_proxy_id_autosign_post module <ansible_collections.qiyutech.foreman.api_smart_proxies_smart_proxy_id_autosign_post_module>` -- Create autosign entry
* :ref:`api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy for an environment
* :ref:`api_statistics module <ansible_collections.qiyutech.foreman.api_statistics_module>` -- Get statistics
* :ref:`api_status module <ansible_collections.qiyutech.foreman.api_status_module>` -- Show status
* :ref:`api_statuses module <ansible_collections.qiyutech.foreman.api_statuses_module>` -- Shows status and version information of Foreman system and it's subcomponents
* :ref:`api_subnets module <ansible_collections.qiyutech.foreman.api_subnets_module>` -- List of subnets
* :ref:`api_subnets_id module <ansible_collections.qiyutech.foreman.api_subnets_id_module>` -- Show a subnet
* :ref:`api_subnets_id_delete module <ansible_collections.qiyutech.foreman.api_subnets_id_delete_module>` -- Delete a subnet
* :ref:`api_subnets_id_freeip module <ansible_collections.qiyutech.foreman.api_subnets_id_freeip_module>` -- Provides an unused IP address in this subnet
* :ref:`api_subnets_id_put module <ansible_collections.qiyutech.foreman.api_subnets_id_put_module>` -- Update a subnet
* :ref:`api_subnets_post module <ansible_collections.qiyutech.foreman.api_subnets_post_module>` -- Create a subnet
* :ref:`api_subnets_subnet_id_domains module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_domains_module>` -- List of domains per subnet
* :ref:`api_subnets_subnet_id_interfaces module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_interfaces_module>` -- List all interfaces for subnet
* :ref:`api_subnets_subnet_id_parameters module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_module>` -- List all parameters for a subnet
* :ref:`api_subnets_subnet_id_parameters_delete module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_delete_module>` -- Delete all nested parameters for a subnet
* :ref:`api_subnets_subnet_id_parameters_id module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_id_module>` -- Show a nested parameter for a subnet
* :ref:`api_subnets_subnet_id_parameters_id_delete module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_id_delete_module>` -- Delete a nested parameter for a subnet
* :ref:`api_subnets_subnet_id_parameters_id_put module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_id_put_module>` -- Update a nested parameter for a subnet
* :ref:`api_subnets_subnet_id_parameters_post module <ansible_collections.qiyutech.foreman.api_subnets_subnet_id_parameters_post_module>` -- Create a nested parameter for a subnet
* :ref:`api_template_combinations_id module <ansible_collections.qiyutech.foreman.api_template_combinations_id_module>` -- Show template combination
* :ref:`api_template_combinations_id_delete module <ansible_collections.qiyutech.foreman.api_template_combinations_id_delete_module>` -- Delete a template combination
* :ref:`api_template_kinds module <ansible_collections.qiyutech.foreman.api_template_kinds_module>` -- List all template kinds
* :ref:`api_templates_export_post module <ansible_collections.qiyutech.foreman.api_templates_export_post_module>` -- Initiate Export
* :ref:`api_templates_import_post module <ansible_collections.qiyutech.foreman.api_templates_import_post_module>` -- Initiate Import
* :ref:`api_templates_template_id_foreign_input_sets module <ansible_collections.qiyutech.foreman.api_templates_template_id_foreign_input_sets_module>` -- List foreign input sets
* :ref:`api_templates_template_id_foreign_input_sets_id module <ansible_collections.qiyutech.foreman.api_templates_template_id_foreign_input_sets_id_module>` -- Show foreign input set details
* :ref:`api_templates_template_id_foreign_input_sets_id_delete module <ansible_collections.qiyutech.foreman.api_templates_template_id_foreign_input_sets_id_delete_module>` -- Delete a foreign input set
* :ref:`api_templates_template_id_foreign_input_sets_id_put module <ansible_collections.qiyutech.foreman.api_templates_template_id_foreign_input_sets_id_put_module>` -- Update a foreign input set
* :ref:`api_templates_template_id_foreign_input_sets_post module <ansible_collections.qiyutech.foreman.api_templates_template_id_foreign_input_sets_post_module>` -- Create a foreign input set
* :ref:`api_templates_template_id_template_inputs module <ansible_collections.qiyutech.foreman.api_templates_template_id_template_inputs_module>` -- List template inputs
* :ref:`api_templates_template_id_template_inputs_id module <ansible_collections.qiyutech.foreman.api_templates_template_id_template_inputs_id_module>` -- Show template input details
* :ref:`api_templates_template_id_template_inputs_id_delete module <ansible_collections.qiyutech.foreman.api_templates_template_id_template_inputs_id_delete_module>` -- Delete a template input
* :ref:`api_templates_template_id_template_inputs_id_put module <ansible_collections.qiyutech.foreman.api_templates_template_id_template_inputs_id_put_module>` -- Update a template input
* :ref:`api_templates_template_id_template_inputs_post module <ansible_collections.qiyutech.foreman.api_templates_template_id_template_inputs_post_module>` -- Create a template input
* :ref:`api_trends module <ansible_collections.qiyutech.foreman.api_trends_module>` -- List of trends counters
* :ref:`api_trends_id module <ansible_collections.qiyutech.foreman.api_trends_id_module>` -- Show a trend
* :ref:`api_trends_id_delete module <ansible_collections.qiyutech.foreman.api_trends_id_delete_module>` -- Delete a trend counter
* :ref:`api_trends_post module <ansible_collections.qiyutech.foreman.api_trends_post_module>` -- Create a trend counter
* :ref:`api_usergroups module <ansible_collections.qiyutech.foreman.api_usergroups_module>` -- List all user groups
* :ref:`api_usergroups_id module <ansible_collections.qiyutech.foreman.api_usergroups_id_module>` -- Show a user group
* :ref:`api_usergroups_id_delete module <ansible_collections.qiyutech.foreman.api_usergroups_id_delete_module>` -- Delete a user group
* :ref:`api_usergroups_id_put module <ansible_collections.qiyutech.foreman.api_usergroups_id_put_module>` -- Update a user group
* :ref:`api_usergroups_post module <ansible_collections.qiyutech.foreman.api_usergroups_post_module>` -- Create a user group
* :ref:`api_usergroups_usergroup_id_external_usergroups module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_module>` -- List all external user groups for user group
* :ref:`api_usergroups_usergroup_id_external_usergroups_id module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_id_module>` -- Show an external user group for user group
* :ref:`api_usergroups_usergroup_id_external_usergroups_id_delete module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_id_delete_module>` -- Delete an external user group
* :ref:`api_usergroups_usergroup_id_external_usergroups_id_put module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_id_put_module>` -- Update external user group
* :ref:`api_usergroups_usergroup_id_external_usergroups_id_refresh_put module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_id_refresh_put_module>` -- Refresh external user group
* :ref:`api_usergroups_usergroup_id_external_usergroups_post module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_external_usergroups_post_module>` -- Create an external user group linked to a user group
* :ref:`api_usergroups_usergroup_id_users module <ansible_collections.qiyutech.foreman.api_usergroups_usergroup_id_users_module>` -- List all users for user group
* :ref:`api_users module <ansible_collections.qiyutech.foreman.api_users_module>` -- List all users
* :ref:`api_users_id module <ansible_collections.qiyutech.foreman.api_users_id_module>` -- Show a user
* :ref:`api_users_id_delete module <ansible_collections.qiyutech.foreman.api_users_id_delete_module>` -- Delete a user
* :ref:`api_users_id_put module <ansible_collections.qiyutech.foreman.api_users_id_put_module>` -- Update a user
* :ref:`api_users_post module <ansible_collections.qiyutech.foreman.api_users_post_module>` -- Create a user
* :ref:`api_users_user_id_mail_notifications module <ansible_collections.qiyutech.foreman.api_users_user_id_mail_notifications_module>` -- List all email notifications for a user
* :ref:`api_users_user_id_mail_notifications_mail_notification_id_delete module <ansible_collections.qiyutech.foreman.api_users_user_id_mail_notifications_mail_notification_id_delete_module>` -- Remove an email notification for a user
* :ref:`api_users_user_id_mail_notifications_mail_notification_id_put module <ansible_collections.qiyutech.foreman.api_users_user_id_mail_notifications_mail_notification_id_put_module>` -- Update an email notification for a user
* :ref:`api_users_user_id_mail_notifications_post module <ansible_collections.qiyutech.foreman.api_users_user_id_mail_notifications_post_module>` -- Add an email notification for a user
* :ref:`api_users_user_id_personal_access_tokens module <ansible_collections.qiyutech.foreman.api_users_user_id_personal_access_tokens_module>` -- List all Personal Access Tokens for a user
* :ref:`api_users_user_id_personal_access_tokens_id module <ansible_collections.qiyutech.foreman.api_users_user_id_personal_access_tokens_id_module>` -- Show a Personal Access Token for a user
* :ref:`api_users_user_id_personal_access_tokens_id_delete module <ansible_collections.qiyutech.foreman.api_users_user_id_personal_access_tokens_id_delete_module>` -- Revoke a Personal Access Token for a user
* :ref:`api_users_user_id_personal_access_tokens_post module <ansible_collections.qiyutech.foreman.api_users_user_id_personal_access_tokens_post_module>` -- Create a Personal Access Token for a user
* :ref:`api_users_user_id_ssh_keys module <ansible_collections.qiyutech.foreman.api_users_user_id_ssh_keys_module>` -- List all SSH keys for a user
* :ref:`api_users_user_id_ssh_keys_id module <ansible_collections.qiyutech.foreman.api_users_user_id_ssh_keys_id_module>` -- Show an SSH key from a user
* :ref:`api_users_user_id_ssh_keys_id_delete module <ansible_collections.qiyutech.foreman.api_users_user_id_ssh_keys_id_delete_module>` -- Delete an SSH key for a user
* :ref:`api_users_user_id_ssh_keys_post module <ansible_collections.qiyutech.foreman.api_users_user_id_ssh_keys_post_module>` -- Add an SSH key for a user
* :ref:`api_users_user_id_table_preferences module <ansible_collections.qiyutech.foreman.api_users_user_id_table_preferences_module>` -- List of table preferences for a user
* :ref:`api_users_user_id_table_preferences_name module <ansible_collections.qiyutech.foreman.api_users_user_id_table_preferences_name_module>` -- Table preference details of a given table
* :ref:`api_users_user_id_table_preferences_name_delete module <ansible_collections.qiyutech.foreman.api_users_user_id_table_preferences_name_delete_module>` -- Delete a table preference for a given table
* :ref:`api_users_user_id_table_preferences_name_put module <ansible_collections.qiyutech.foreman.api_users_user_id_table_preferences_name_put_module>` -- Updates a table preference for a given table
* :ref:`api_users_user_id_table_preferences_post module <ansible_collections.qiyutech.foreman.api_users_user_id_table_preferences_post_module>` -- Creates a table preference for a given table
* :ref:`api_webhook_templates module <ansible_collections.qiyutech.foreman.api_webhook_templates_module>` -- List webhook templates
* :ref:`api_webhook_templates_id module <ansible_collections.qiyutech.foreman.api_webhook_templates_id_module>` -- Show webhook template details
* :ref:`api_webhook_templates_id_clone_post module <ansible_collections.qiyutech.foreman.api_webhook_templates_id_clone_post_module>` -- Clone a template
* :ref:`api_webhook_templates_id_delete module <ansible_collections.qiyutech.foreman.api_webhook_templates_id_delete_module>` -- Delete a webhook template
* :ref:`api_webhook_templates_id_export module <ansible_collections.qiyutech.foreman.api_webhook_templates_id_export_module>` -- Export a webhook template to ERB
* :ref:`api_webhook_templates_id_put module <ansible_collections.qiyutech.foreman.api_webhook_templates_id_put_module>` -- Update a webhook template
* :ref:`api_webhook_templates_import_post module <ansible_collections.qiyutech.foreman.api_webhook_templates_import_post_module>` -- Import a webhook template
* :ref:`api_webhook_templates_post module <ansible_collections.qiyutech.foreman.api_webhook_templates_post_module>` -- Create a webhook template
* :ref:`api_webhooks module <ansible_collections.qiyutech.foreman.api_webhooks_module>` -- List Webhooks
* :ref:`api_webhooks_events module <ansible_collections.qiyutech.foreman.api_webhooks_events_module>` -- List available events for subscription
* :ref:`api_webhooks_id module <ansible_collections.qiyutech.foreman.api_webhooks_id_module>` -- Show Webhook details
* :ref:`api_webhooks_id_delete module <ansible_collections.qiyutech.foreman.api_webhooks_id_delete_module>` -- Delete a Webhook
* :ref:`api_webhooks_id_put module <ansible_collections.qiyutech.foreman.api_webhooks_id_put_module>` -- Update a Webhook
* :ref:`api_webhooks_post module <ansible_collections.qiyutech.foreman.api_webhooks_post_module>` -- Create a Webhook
* :ref:`bootdisk_api module <ansible_collections.qiyutech.foreman.bootdisk_api_module>` -- Subnet boot disks
* :ref:`bootdisk_api_generic module <ansible_collections.qiyutech.foreman.bootdisk_api_generic_module>` -- Download generic image
* :ref:`bootdisk_api_hosts_host_id module <ansible_collections.qiyutech.foreman.bootdisk_api_hosts_host_id_module>` -- Download host image
* :ref:`bootdisk_api_subnets_subnet_id module <ansible_collections.qiyutech.foreman.bootdisk_api_subnets_subnet_id_module>` -- Download subnet generic image
* :ref:`foreman_puppet_api_config_groups module <ansible_collections.qiyutech.foreman.foreman_puppet_api_config_groups_module>` -- List of config groups
* :ref:`foreman_puppet_api_config_groups_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_config_groups_id_module>` -- Show a config group
* :ref:`foreman_puppet_api_config_groups_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_config_groups_id_delete_module>` -- Delete a config group
* :ref:`foreman_puppet_api_config_groups_id_put module <ansible_collections.qiyutech.foreman.foreman_puppet_api_config_groups_id_put_module>` -- Update a config group
* :ref:`foreman_puppet_api_config_groups_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_config_groups_post_module>` -- Create a config group
* :ref:`foreman_puppet_api_environments module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_module>` -- List all environments
* :ref:`foreman_puppet_api_environments_environment_id_puppetclasses module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_environment_id_puppetclasses_module>` -- List all Puppet classes for an environment
* :ref:`foreman_puppet_api_environments_environment_id_puppetclasses_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_environment_id_puppetclasses_id_module>` -- Show a Puppet class for an environment
* :ref:`foreman_puppet_api_environments_environment_id_puppetclasses_puppetclass_id_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_environment_id_puppetclasses_puppetclass_id_smart_class_parameters_module>` -- List of smart class parameters for a specific environment/Puppet class combination
* :ref:`foreman_puppet_api_environments_environment_id_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_environment_id_smart_class_parameters_module>` -- List of smart class parameters for a specific environment
* :ref:`foreman_puppet_api_environments_environment_id_smart_proxies_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_environment_id_smart_proxies_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy for an environment
* :ref:`foreman_puppet_api_environments_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_id_module>` -- Show an environment
* :ref:`foreman_puppet_api_environments_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_id_delete_module>` -- Delete an environment
* :ref:`foreman_puppet_api_environments_id_put module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_id_put_module>` -- Update an environment
* :ref:`foreman_puppet_api_environments_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_environments_post_module>` -- Create an environment
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_module>` -- List all Puppet class IDs for host group
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_id_delete_module>` -- Remove a Puppet class from host group
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_post_module>` -- Add a Puppet class to host group
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses_module>` -- List all Puppet classes for a host group
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses_id_module>` -- Show a Puppet class for a host group
* :ref:`foreman_puppet_api_hostgroups_hostgroup_id_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hostgroups_hostgroup_id_smart_class_parameters_module>` -- List of smart class parameters for a specific host group
* :ref:`foreman_puppet_api_hosts_host_id_puppetclass_ids module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_puppetclass_ids_module>` -- List all Puppet class IDs for host
* :ref:`foreman_puppet_api_hosts_host_id_puppetclass_ids_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_puppetclass_ids_id_delete_module>` -- Remove a Puppet class from host
* :ref:`foreman_puppet_api_hosts_host_id_puppetclass_ids_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_puppetclass_ids_post_module>` -- Add a Puppet class to host
* :ref:`foreman_puppet_api_hosts_host_id_puppetclasses module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_puppetclasses_module>` -- List all Puppet classes for a host
* :ref:`foreman_puppet_api_hosts_host_id_puppetclasses_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_puppetclasses_id_module>` -- Show a Puppet class for host
* :ref:`foreman_puppet_api_hosts_host_id_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_hosts_host_id_smart_class_parameters_module>` -- List of smart class parameters for a specific host
* :ref:`foreman_puppet_api_locations_location_id_environments module <ansible_collections.qiyutech.foreman.foreman_puppet_api_locations_location_id_environments_module>` -- List environments per location
* :ref:`foreman_puppet_api_organizations_organization_id_environments module <ansible_collections.qiyutech.foreman.foreman_puppet_api_organizations_organization_id_environments_module>` -- List environments per organization
* :ref:`foreman_puppet_api_puppetclasses module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_module>` -- List all Puppet classes
* :ref:`foreman_puppet_api_puppetclasses_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_id_module>` -- Show a Puppet class
* :ref:`foreman_puppet_api_puppetclasses_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_id_delete_module>` -- Delete a Puppet class
* :ref:`foreman_puppet_api_puppetclasses_id_put module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_id_put_module>` -- Update a Puppet class
* :ref:`foreman_puppet_api_puppetclasses_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_post_module>` -- Create a Puppet class
* :ref:`foreman_puppet_api_puppetclasses_puppetclass_id_environments module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_puppetclass_id_environments_module>` -- List environments of Puppet class
* :ref:`foreman_puppet_api_puppetclasses_puppetclass_id_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_puppetclasses_puppetclass_id_smart_class_parameters_module>` -- List of smart class parameters for a specific Puppet class
* :ref:`foreman_puppet_api_smart_class_parameters module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_module>` -- List all smart class parameters
* :ref:`foreman_puppet_api_smart_class_parameters_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_id_module>` -- Show a smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_id_put module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_id_put_module>` -- Update a smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_module>` -- List of override values for a specific smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_module>` -- Show an override value for a specific smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_delete module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_delete_module>` -- Delete an override value for a specific smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_put module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_put_module>` -- Update an override value for a specific smart class parameter
* :ref:`foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_post_module>` -- Create an override value for a specific smart class parameter
* :ref:`foreman_puppet_api_smart_proxies_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_proxies_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy
* :ref:`foreman_puppet_api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post module <ansible_collections.qiyutech.foreman.foreman_puppet_api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post_module>` -- Import puppet classes from puppet proxy for an environment
* :ref:`foreman_tasks_api_recurring_logics module <ansible_collections.qiyutech.foreman.foreman_tasks_api_recurring_logics_module>` -- List recurring logics
* :ref:`foreman_tasks_api_recurring_logics_bulk_destroy_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_recurring_logics_bulk_destroy_post_module>` -- Delete recurring logics by search query
* :ref:`foreman_tasks_api_recurring_logics_id module <ansible_collections.qiyutech.foreman.foreman_tasks_api_recurring_logics_id_module>` -- Show recurring logic details
* :ref:`foreman_tasks_api_recurring_logics_id_cancel_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_recurring_logics_id_cancel_post_module>` -- Cancel recurring logic
* :ref:`foreman_tasks_api_recurring_logics_id_put module <ansible_collections.qiyutech.foreman.foreman_tasks_api_recurring_logics_id_put_module>` -- Update recurring logic
* :ref:`foreman_tasks_api_tasks module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_module>` -- List tasks
* :ref:`foreman_tasks_api_tasks_bulk_cancel_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_bulk_cancel_post_module>` -- Cancel selected cancellable tasks
* :ref:`foreman_tasks_api_tasks_bulk_resume_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_bulk_resume_post_module>` -- Resume all paused error tasks
* :ref:`foreman_tasks_api_tasks_bulk_search_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_bulk_search_post_module>` -- List dynflow tasks for uuids
* :ref:`foreman_tasks_api_tasks_bulk_stop_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_bulk_stop_post_module>` -- Stop selected stoppable tasks
* :ref:`foreman_tasks_api_tasks_callback_post module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_callback_post_module>` -- Send data to the task from external executor (such as smart_proxy_dynflow)
* :ref:`foreman_tasks_api_tasks_id module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_id_module>` -- Show task details
* :ref:`foreman_tasks_api_tasks_id_details module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_id_details_module>` -- Show task extended details
* :ref:`foreman_tasks_api_tasks_parent_task_id_sub_tasks module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_parent_task_id_sub_tasks_module>` -- Show sub_tasks details
* :ref:`foreman_tasks_api_tasks_summary module <ansible_collections.qiyutech.foreman.foreman_tasks_api_tasks_summary_module>` -- Show task summary
* :ref:`hl_domain module <ansible_collections.qiyutech.foreman.hl_domain_module>` -- Foreman 域配置
* :ref:`hl_host module <ansible_collections.qiyutech.foreman.hl_host_module>` -- 
* :ref:`hl_os module <ansible_collections.qiyutech.foreman.hl_os_module>` -- 
* :ref:`hl_provision_template module <ansible_collections.qiyutech.foreman.hl_provision_template_module>` -- Foreman Provision 模版
* :ref:`hl_ptable module <ansible_collections.qiyutech.foreman.hl_ptable_module>` -- 
* :ref:`hl_setting module <ansible_collections.qiyutech.foreman.hl_setting_module>` -- Foreman 配置操作
* :ref:`hl_subnet module <ansible_collections.qiyutech.foreman.hl_subnet_module>` -- Foreman 子网操作
* :ref:`operating_systems module <ansible_collections.qiyutech.foreman.operating_systems_module>` -- 获取 Foreman 的操作系统列表
* :ref:`operating_systems_id module <ansible_collections.qiyutech.foreman.operating_systems_id_module>` -- 获取 Foreman 的操作系统详情
* :ref:`smart_proxies module <ansible_collections.qiyutech.foreman.smart_proxies_module>` -- 获取 Foreman 的 智能代理 列表
* :ref:`smart_proxies_id module <ansible_collections.qiyutech.foreman.smart_proxies_id_module>` -- 获取 智能代理(by id) 的详细信息



.. seealso::

    List of :ref:`collections <list_of_collections>` with docs hosted here.

.. toctree::
    :maxdepth: 1
    :hidden:

    ansible_api_ansible_inventories_hostgroups_module
    ansible_api_ansible_inventories_hostgroups_post_module
    ansible_api_ansible_inventories_hosts_module
    ansible_api_ansible_inventories_hosts_post_module
    ansible_api_ansible_inventories_schedule_post_module
    ansible_api_ansible_override_values_id_delete_module
    ansible_api_ansible_override_values_post_module
    ansible_api_ansible_roles_module
    ansible_api_ansible_roles_fetch_module
    ansible_api_ansible_roles_id_module
    ansible_api_ansible_roles_id_delete_module
    ansible_api_ansible_roles_import_put_module
    ansible_api_ansible_roles_obsolete_put_module
    ansible_api_ansible_roles_sync_put_module
    ansible_api_ansible_variables_module
    ansible_api_ansible_variables_id_module
    ansible_api_ansible_variables_id_delete_module
    ansible_api_ansible_variables_id_put_module
    ansible_api_ansible_variables_import_put_module
    ansible_api_ansible_variables_obsolete_put_module
    ansible_api_ansible_variables_post_module
    api_module
    api_architectures_module
    api_architectures_architecture_id_images_module
    api_architectures_architecture_id_images_id_module
    api_architectures_architecture_id_operatingsystems_module
    api_architectures_id_module
    api_architectures_id_delete_module
    api_architectures_id_put_module
    api_architectures_post_module
    api_audits_module
    api_audits_id_module
    api_auth_source_externals_module
    api_auth_source_externals_auth_source_external_id_users_module
    api_auth_source_externals_id_module
    api_auth_source_externals_id_put_module
    api_auth_source_internals_module
    api_auth_source_internals_id_module
    api_auth_source_ldaps_module
    api_auth_source_ldaps_auth_source_ldap_id_external_usergroups_module
    api_auth_source_ldaps_auth_source_ldap_id_external_usergroups_id_module
    api_auth_source_ldaps_auth_source_ldap_id_users_module
    api_auth_source_ldaps_id_module
    api_auth_source_ldaps_id_delete_module
    api_auth_source_ldaps_id_put_module
    api_auth_source_ldaps_id_test_put_module
    api_auth_source_ldaps_post_module
    api_auth_sources_module
    api_bookmarks_module
    api_bookmarks_id_module
    api_bookmarks_id_delete_module
    api_bookmarks_id_put_module
    api_bookmarks_post_module
    api_common_parameters_module
    api_common_parameters_id_module
    api_common_parameters_id_delete_module
    api_common_parameters_id_put_module
    api_common_parameters_post_module
    api_compute_attributes_id_module
    api_compute_attributes_id_put_module
    api_compute_attributes_post_module
    api_compute_profiles_module
    api_compute_profiles_compute_profile_id_compute_attributes_module
    api_compute_profiles_compute_profile_id_compute_attributes_id_module
    api_compute_profiles_compute_profile_id_compute_attributes_id_put_module
    api_compute_profiles_compute_profile_id_compute_attributes_post_module
    api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_module
    api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id_module
    api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_id_put_module
    api_compute_profiles_compute_profile_id_compute_resources_compute_resource_id_compute_attributes_post_module
    api_compute_profiles_id_module
    api_compute_profiles_id_delete_module
    api_compute_profiles_id_put_module
    api_compute_profiles_post_module
    api_compute_resources_module
    api_compute_resources_compute_resource_id_compute_attributes_module
    api_compute_resources_compute_resource_id_compute_attributes_id_module
    api_compute_resources_compute_resource_id_compute_attributes_id_put_module
    api_compute_resources_compute_resource_id_compute_attributes_post_module
    api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_module
    api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id_module
    api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_id_put_module
    api_compute_resources_compute_resource_id_compute_profiles_compute_profile_id_compute_attributes_post_module
    api_compute_resources_compute_resource_id_images_module
    api_compute_resources_compute_resource_id_images_id_module
    api_compute_resources_compute_resource_id_images_id_delete_module
    api_compute_resources_compute_resource_id_images_id_put_module
    api_compute_resources_compute_resource_id_images_post_module
    api_compute_resources_id_module
    api_compute_resources_id_associate_put_module
    api_compute_resources_id_available_clusters_module
    api_compute_resources_id_available_clusters_cluster_id_available_networks_module
    api_compute_resources_id_available_clusters_cluster_id_available_resource_pools_module
    api_compute_resources_id_available_clusters_cluster_id_available_storage_domains_module
    api_compute_resources_id_available_clusters_cluster_id_available_storage_pods_module
    api_compute_resources_id_available_flavors_module
    api_compute_resources_id_available_folders_module
    api_compute_resources_id_available_images_module
    api_compute_resources_id_available_networks_module
    api_compute_resources_id_available_security_groups_module
    api_compute_resources_id_available_storage_domains_module
    api_compute_resources_id_available_storage_domains_storage_domain_module
    api_compute_resources_id_available_storage_pods_module
    api_compute_resources_id_available_storage_pods_storage_pod_module
    api_compute_resources_id_available_virtual_machines_module
    api_compute_resources_id_available_virtual_machines_vm_id_module
    api_compute_resources_id_available_virtual_machines_vm_id_delete_module
    api_compute_resources_id_available_virtual_machines_vm_id_power_put_module
    api_compute_resources_id_available_vnic_profiles_module
    api_compute_resources_id_available_zones_module
    api_compute_resources_id_delete_module
    api_compute_resources_id_put_module
    api_compute_resources_id_refresh_cache_put_module
    api_compute_resources_id_storage_domains_storage_domain_id_module
    api_compute_resources_id_storage_pods_storage_pod_id_module
    api_compute_resources_post_module
    api_config_reports_module
    api_config_reports_id_module
    api_config_reports_id_delete_module
    api_config_reports_post_module
    api_current_user_module
    api_dashboard_module
    api_domains_module
    api_domains_domain_id_interfaces_module
    api_domains_domain_id_parameters_module
    api_domains_domain_id_parameters_delete_module
    api_domains_domain_id_parameters_id_module
    api_domains_domain_id_parameters_id_delete_module
    api_domains_domain_id_parameters_id_put_module
    api_domains_domain_id_parameters_post_module
    api_domains_domain_id_subnets_module
    api_domains_id_module
    api_domains_id_delete_module
    api_domains_id_put_module
    api_domains_post_module
    api_environments_environment_id_hosts_module
    api_environments_environment_id_smart_proxies_id_import_puppetclasses_post_module
    api_environments_environment_id_template_combinations_module
    api_environments_environment_id_template_combinations_id_module
    api_environments_environment_id_template_combinations_id_put_module
    api_environments_environment_id_template_combinations_post_module
    api_fact_values_module
    api_filters_module
    api_filters_id_module
    api_filters_id_delete_module
    api_filters_id_put_module
    api_filters_post_module
    api_hostgroups_module
    api_hostgroups_hostgroup_id_hosts_module
    api_hostgroups_hostgroup_id_parameters_module
    api_hostgroups_hostgroup_id_parameters_delete_module
    api_hostgroups_hostgroup_id_parameters_id_module
    api_hostgroups_hostgroup_id_parameters_id_delete_module
    api_hostgroups_hostgroup_id_parameters_id_put_module
    api_hostgroups_hostgroup_id_parameters_post_module
    api_hostgroups_hostgroup_id_template_combinations_module
    api_hostgroups_hostgroup_id_template_combinations_id_module
    api_hostgroups_hostgroup_id_template_combinations_id_put_module
    api_hostgroups_hostgroup_id_template_combinations_post_module
    api_hostgroups_id_module
    api_hostgroups_id_ansible_roles_module
    api_hostgroups_id_assign_ansible_roles_post_module
    api_hostgroups_id_clone_post_module
    api_hostgroups_id_delete_module
    api_hostgroups_id_play_roles_post_module
    api_hostgroups_id_put_module
    api_hostgroups_id_rebuild_config_put_module
    api_hostgroups_multiple_play_roles_post_module
    api_hostgroups_post_module
    api_hosts_module
    api_hosts_facts_post_module
    api_hosts_host_id_audits_module
    api_hosts_host_id_config_reports_last_module
    api_hosts_host_id_facts_module
    api_hosts_host_id_interfaces_module
    api_hosts_host_id_interfaces_id_module
    api_hosts_host_id_interfaces_id_delete_module
    api_hosts_host_id_interfaces_id_put_module
    api_hosts_host_id_interfaces_post_module
    api_hosts_host_id_parameters_module
    api_hosts_host_id_parameters_delete_module
    api_hosts_host_id_parameters_id_module
    api_hosts_host_id_parameters_id_delete_module
    api_hosts_host_id_parameters_id_put_module
    api_hosts_host_id_parameters_post_module
    api_hosts_id_module
    api_hosts_id_ansible_roles_module
    api_hosts_id_assign_ansible_roles_post_module
    api_hosts_id_boot_put_module
    api_hosts_id_delete_module
    api_hosts_id_disassociate_put_module
    api_hosts_id_enc_module
    api_hosts_id_play_roles_post_module
    api_hosts_id_power_module
    api_hosts_id_power_put_module
    api_hosts_id_puppetrun_put_module
    api_hosts_id_put_module
    api_hosts_id_rebuild_config_put_module
    api_hosts_id_status_type_module
    api_hosts_id_status_type_delete_module
    api_hosts_id_template_kind_module
    api_hosts_id_vm_compute_attributes_module
    api_hosts_multiple_play_roles_post_module
    api_hosts_post_module
    api_http_proxies_module
    api_http_proxies_id_module
    api_http_proxies_id_delete_module
    api_http_proxies_id_put_module
    api_http_proxies_post_module
    api_job_invocations_module
    api_job_invocations_id_module
    api_job_invocations_id_cancel_post_module
    api_job_invocations_id_hosts_host_id_module
    api_job_invocations_id_hosts_host_id_raw_module
    api_job_invocations_id_outputs_module
    api_job_invocations_id_rerun_post_module
    api_job_invocations_job_invocation_id_template_invocations_module
    api_job_invocations_post_module
    api_job_templates_module
    api_job_templates_id_module
    api_job_templates_id_clone_post_module
    api_job_templates_id_delete_module
    api_job_templates_id_export_module
    api_job_templates_id_put_module
    api_job_templates_import_post_module
    api_job_templates_post_module
    api_job_templates_revision_module
    api_locations_module
    api_locations_id_module
    api_locations_id_delete_module
    api_locations_id_put_module
    api_locations_location_id_auth_source_externals_module
    api_locations_location_id_auth_source_ldaps_module
    api_locations_location_id_auth_sources_module
    api_locations_location_id_domains_module
    api_locations_location_id_hostgroups_module
    api_locations_location_id_hosts_module
    api_locations_location_id_job_templates_module
    api_locations_location_id_media_module
    api_locations_location_id_parameters_module
    api_locations_location_id_parameters_delete_module
    api_locations_location_id_parameters_id_module
    api_locations_location_id_parameters_id_delete_module
    api_locations_location_id_parameters_id_put_module
    api_locations_location_id_parameters_post_module
    api_locations_location_id_provisioning_templates_module
    api_locations_location_id_ptables_module
    api_locations_location_id_report_templates_module
    api_locations_location_id_subnets_module
    api_locations_location_id_users_module
    api_locations_post_module
    api_mail_notifications_module
    api_mail_notifications_id_module
    api_media_module
    api_media_id_module
    api_media_id_delete_module
    api_media_id_put_module
    api_media_medium_id_operatingsystems_module
    api_media_post_module
    api_models_module
    api_models_id_module
    api_models_id_delete_module
    api_models_id_put_module
    api_models_post_module
    api_operatingsystems_module
    api_operatingsystems_id_module
    api_operatingsystems_id_bootfiles_module
    api_operatingsystems_id_delete_module
    api_operatingsystems_id_put_module
    api_operatingsystems_operatingsystem_id_architectures_module
    api_operatingsystems_operatingsystem_id_images_module
    api_operatingsystems_operatingsystem_id_images_id_module
    api_operatingsystems_operatingsystem_id_media_module
    api_operatingsystems_operatingsystem_id_os_default_templates_module
    api_operatingsystems_operatingsystem_id_os_default_templates_id_module
    api_operatingsystems_operatingsystem_id_os_default_templates_id_delete_module
    api_operatingsystems_operatingsystem_id_os_default_templates_id_put_module
    api_operatingsystems_operatingsystem_id_os_default_templates_post_module
    api_operatingsystems_operatingsystem_id_parameters_module
    api_operatingsystems_operatingsystem_id_parameters_delete_module
    api_operatingsystems_operatingsystem_id_parameters_id_module
    api_operatingsystems_operatingsystem_id_parameters_id_delete_module
    api_operatingsystems_operatingsystem_id_parameters_id_put_module
    api_operatingsystems_operatingsystem_id_parameters_post_module
    api_operatingsystems_operatingsystem_id_provisioning_templates_module
    api_operatingsystems_operatingsystem_id_ptables_module
    api_operatingsystems_post_module
    api_orchestration_id_tasks_module
    api_organizations_module
    api_organizations_id_module
    api_organizations_id_delete_module
    api_organizations_id_put_module
    api_organizations_organization_id_auth_source_externals_module
    api_organizations_organization_id_auth_source_ldaps_module
    api_organizations_organization_id_auth_sources_module
    api_organizations_organization_id_domains_module
    api_organizations_organization_id_hostgroups_module
    api_organizations_organization_id_hosts_module
    api_organizations_organization_id_job_templates_module
    api_organizations_organization_id_media_module
    api_organizations_organization_id_parameters_module
    api_organizations_organization_id_parameters_delete_module
    api_organizations_organization_id_parameters_id_module
    api_organizations_organization_id_parameters_id_delete_module
    api_organizations_organization_id_parameters_id_put_module
    api_organizations_organization_id_parameters_post_module
    api_organizations_organization_id_provisioning_templates_module
    api_organizations_organization_id_ptables_module
    api_organizations_organization_id_report_templates_module
    api_organizations_organization_id_subnets_module
    api_organizations_organization_id_users_module
    api_organizations_post_module
    api_permissions_module
    api_permissions_id_module
    api_permissions_resource_types_module
    api_ping_module
    api_plugins_module
    api_provisioning_templates_module
    api_provisioning_templates_build_pxe_default_post_module
    api_provisioning_templates_id_module
    api_provisioning_templates_id_clone_post_module
    api_provisioning_templates_id_delete_module
    api_provisioning_templates_id_export_module
    api_provisioning_templates_id_put_module
    api_provisioning_templates_import_post_module
    api_provisioning_templates_post_module
    api_provisioning_templates_provisioning_template_id_operatingsystems_module
    api_provisioning_templates_provisioning_template_id_os_default_templates_module
    api_provisioning_templates_provisioning_template_id_template_combinations_module
    api_provisioning_templates_provisioning_template_id_template_combinations_id_module
    api_provisioning_templates_provisioning_template_id_template_combinations_id_put_module
    api_provisioning_templates_provisioning_template_id_template_combinations_post_module
    api_provisioning_templates_revision_module
    api_ptables_module
    api_ptables_id_module
    api_ptables_id_clone_post_module
    api_ptables_id_delete_module
    api_ptables_id_export_module
    api_ptables_id_put_module
    api_ptables_import_post_module
    api_ptables_post_module
    api_ptables_ptable_id_operatingsystems_module
    api_ptables_revision_module
    api_puppetclasses_puppetclass_id_hostgroups_module
    api_realms_module
    api_realms_id_module
    api_realms_id_delete_module
    api_realms_id_put_module
    api_realms_post_module
    api_register_module
    api_register_post_module
    api_registration_commands_post_module
    api_remote_execution_features_module
    api_remote_execution_features_id_module
    api_remote_execution_features_id_put_module
    api_report_templates_module
    api_report_templates_id_module
    api_report_templates_id_clone_post_module
    api_report_templates_id_delete_module
    api_report_templates_id_export_module
    api_report_templates_id_generate_post_module
    api_report_templates_id_put_module
    api_report_templates_id_report_data_job_id_module
    api_report_templates_id_schedule_report_post_module
    api_report_templates_import_post_module
    api_report_templates_post_module
    api_report_templates_revision_module
    api_roles_module
    api_roles_id_module
    api_roles_id_clone_post_module
    api_roles_id_delete_module
    api_roles_id_put_module
    api_roles_post_module
    api_roles_role_id_users_module
    api_settings_module
    api_settings_id_module
    api_settings_id_put_module
    api_smart_proxies_module
    api_smart_proxies_id_module
    api_smart_proxies_id_delete_module
    api_smart_proxies_id_import_puppetclasses_post_module
    api_smart_proxies_id_put_module
    api_smart_proxies_id_refresh_put_module
    api_smart_proxies_post_module
    api_smart_proxies_smart_proxy_id_autosign_module
    api_smart_proxies_smart_proxy_id_autosign_id_delete_module
    api_smart_proxies_smart_proxy_id_autosign_post_module
    api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post_module
    api_statistics_module
    api_status_module
    api_statuses_module
    api_subnets_module
    api_subnets_id_module
    api_subnets_id_delete_module
    api_subnets_id_freeip_module
    api_subnets_id_put_module
    api_subnets_post_module
    api_subnets_subnet_id_domains_module
    api_subnets_subnet_id_interfaces_module
    api_subnets_subnet_id_parameters_module
    api_subnets_subnet_id_parameters_delete_module
    api_subnets_subnet_id_parameters_id_module
    api_subnets_subnet_id_parameters_id_delete_module
    api_subnets_subnet_id_parameters_id_put_module
    api_subnets_subnet_id_parameters_post_module
    api_template_combinations_id_module
    api_template_combinations_id_delete_module
    api_template_kinds_module
    api_templates_export_post_module
    api_templates_import_post_module
    api_templates_template_id_foreign_input_sets_module
    api_templates_template_id_foreign_input_sets_id_module
    api_templates_template_id_foreign_input_sets_id_delete_module
    api_templates_template_id_foreign_input_sets_id_put_module
    api_templates_template_id_foreign_input_sets_post_module
    api_templates_template_id_template_inputs_module
    api_templates_template_id_template_inputs_id_module
    api_templates_template_id_template_inputs_id_delete_module
    api_templates_template_id_template_inputs_id_put_module
    api_templates_template_id_template_inputs_post_module
    api_trends_module
    api_trends_id_module
    api_trends_id_delete_module
    api_trends_post_module
    api_usergroups_module
    api_usergroups_id_module
    api_usergroups_id_delete_module
    api_usergroups_id_put_module
    api_usergroups_post_module
    api_usergroups_usergroup_id_external_usergroups_module
    api_usergroups_usergroup_id_external_usergroups_id_module
    api_usergroups_usergroup_id_external_usergroups_id_delete_module
    api_usergroups_usergroup_id_external_usergroups_id_put_module
    api_usergroups_usergroup_id_external_usergroups_id_refresh_put_module
    api_usergroups_usergroup_id_external_usergroups_post_module
    api_usergroups_usergroup_id_users_module
    api_users_module
    api_users_id_module
    api_users_id_delete_module
    api_users_id_put_module
    api_users_post_module
    api_users_user_id_mail_notifications_module
    api_users_user_id_mail_notifications_mail_notification_id_delete_module
    api_users_user_id_mail_notifications_mail_notification_id_put_module
    api_users_user_id_mail_notifications_post_module
    api_users_user_id_personal_access_tokens_module
    api_users_user_id_personal_access_tokens_id_module
    api_users_user_id_personal_access_tokens_id_delete_module
    api_users_user_id_personal_access_tokens_post_module
    api_users_user_id_ssh_keys_module
    api_users_user_id_ssh_keys_id_module
    api_users_user_id_ssh_keys_id_delete_module
    api_users_user_id_ssh_keys_post_module
    api_users_user_id_table_preferences_module
    api_users_user_id_table_preferences_name_module
    api_users_user_id_table_preferences_name_delete_module
    api_users_user_id_table_preferences_name_put_module
    api_users_user_id_table_preferences_post_module
    api_webhook_templates_module
    api_webhook_templates_id_module
    api_webhook_templates_id_clone_post_module
    api_webhook_templates_id_delete_module
    api_webhook_templates_id_export_module
    api_webhook_templates_id_put_module
    api_webhook_templates_import_post_module
    api_webhook_templates_post_module
    api_webhooks_module
    api_webhooks_events_module
    api_webhooks_id_module
    api_webhooks_id_delete_module
    api_webhooks_id_put_module
    api_webhooks_post_module
    bootdisk_api_module
    bootdisk_api_generic_module
    bootdisk_api_hosts_host_id_module
    bootdisk_api_subnets_subnet_id_module
    foreman_puppet_api_config_groups_module
    foreman_puppet_api_config_groups_id_module
    foreman_puppet_api_config_groups_id_delete_module
    foreman_puppet_api_config_groups_id_put_module
    foreman_puppet_api_config_groups_post_module
    foreman_puppet_api_environments_module
    foreman_puppet_api_environments_environment_id_puppetclasses_module
    foreman_puppet_api_environments_environment_id_puppetclasses_id_module
    foreman_puppet_api_environments_environment_id_puppetclasses_puppetclass_id_smart_class_parameters_module
    foreman_puppet_api_environments_environment_id_smart_class_parameters_module
    foreman_puppet_api_environments_environment_id_smart_proxies_id_import_puppetclasses_post_module
    foreman_puppet_api_environments_id_module
    foreman_puppet_api_environments_id_delete_module
    foreman_puppet_api_environments_id_put_module
    foreman_puppet_api_environments_post_module
    foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_module
    foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_id_delete_module
    foreman_puppet_api_hostgroups_hostgroup_id_puppetclass_ids_post_module
    foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses_module
    foreman_puppet_api_hostgroups_hostgroup_id_puppetclasses_id_module
    foreman_puppet_api_hostgroups_hostgroup_id_smart_class_parameters_module
    foreman_puppet_api_hosts_host_id_puppetclass_ids_module
    foreman_puppet_api_hosts_host_id_puppetclass_ids_id_delete_module
    foreman_puppet_api_hosts_host_id_puppetclass_ids_post_module
    foreman_puppet_api_hosts_host_id_puppetclasses_module
    foreman_puppet_api_hosts_host_id_puppetclasses_id_module
    foreman_puppet_api_hosts_host_id_smart_class_parameters_module
    foreman_puppet_api_locations_location_id_environments_module
    foreman_puppet_api_organizations_organization_id_environments_module
    foreman_puppet_api_puppetclasses_module
    foreman_puppet_api_puppetclasses_id_module
    foreman_puppet_api_puppetclasses_id_delete_module
    foreman_puppet_api_puppetclasses_id_put_module
    foreman_puppet_api_puppetclasses_post_module
    foreman_puppet_api_puppetclasses_puppetclass_id_environments_module
    foreman_puppet_api_puppetclasses_puppetclass_id_smart_class_parameters_module
    foreman_puppet_api_smart_class_parameters_module
    foreman_puppet_api_smart_class_parameters_id_module
    foreman_puppet_api_smart_class_parameters_id_put_module
    foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_module
    foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_module
    foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_delete_module
    foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_id_put_module
    foreman_puppet_api_smart_class_parameters_smart_class_parameter_id_override_values_post_module
    foreman_puppet_api_smart_proxies_id_import_puppetclasses_post_module
    foreman_puppet_api_smart_proxies_smart_proxy_id_environments_id_import_puppetclasses_post_module
    foreman_tasks_api_recurring_logics_module
    foreman_tasks_api_recurring_logics_bulk_destroy_post_module
    foreman_tasks_api_recurring_logics_id_module
    foreman_tasks_api_recurring_logics_id_cancel_post_module
    foreman_tasks_api_recurring_logics_id_put_module
    foreman_tasks_api_tasks_module
    foreman_tasks_api_tasks_bulk_cancel_post_module
    foreman_tasks_api_tasks_bulk_resume_post_module
    foreman_tasks_api_tasks_bulk_search_post_module
    foreman_tasks_api_tasks_bulk_stop_post_module
    foreman_tasks_api_tasks_callback_post_module
    foreman_tasks_api_tasks_id_module
    foreman_tasks_api_tasks_id_details_module
    foreman_tasks_api_tasks_parent_task_id_sub_tasks_module
    foreman_tasks_api_tasks_summary_module
    hl_domain_module
    hl_host_module
    hl_os_module
    hl_provision_template_module
    hl_ptable_module
    hl_setting_module
    hl_subnet_module
    operating_systems_module
    operating_systems_id_module
    smart_proxies_module
    smart_proxies_id_module
