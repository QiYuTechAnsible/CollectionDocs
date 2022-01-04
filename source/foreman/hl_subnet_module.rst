.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. role:: ansible-attribute-support-label
.. role:: ansible-attribute-support-property
.. role:: ansible-attribute-support-full
.. role:: ansible-attribute-support-partial
.. role:: ansible-attribute-support-none
.. role:: ansible-attribute-support-na
.. role:: ansible-option-type
.. role:: ansible-option-elements
.. role:: ansible-option-required
.. role:: ansible-option-versionadded
.. role:: ansible-option-aliases
.. role:: ansible-option-choices
.. role:: ansible-option-choices-entry
.. role:: ansible-option-default
.. role:: ansible-option-default-bold
.. role:: ansible-option-configuration
.. role:: ansible-option-returned-bold
.. role:: ansible-option-sample-bold

.. Anchors

.. _ansible_collections.qiyutech.foreman.hl_subnet_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.foreman.hl_subnet module -- Foreman 子网操作
+++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.foreman collection <https://galaxy.ansible.com/qiyutech/foreman>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.foreman`.

    To use it in a playbook, specify: :code:`qiyutech.foreman.hl_subnet`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.foreman

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Foreman 子网操作
- 当前不允许更新配置

.. note::
    This module has a corresponding :ref:`action plugin <action_plugins>`.

.. Aliases


.. Requirements






.. Options

Parameters
----------


.. rst-class:: ansible-option-table

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1

  * - Parameter
    - Comments

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-location_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-location_id:

      .. rst-class:: ansible-option-title

      **location_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-location_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the current location context for the request


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-location_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-location_name:

      .. rst-class:: ansible-option-title

      **location_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-location_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      如果 location_id 没有设置, 则使用此值 获取 location_id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-organization_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-organization_id:

      .. rst-class:: ansible-option-title

      **organization_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-organization_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the current organization context for the request


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-organization_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-organization_name:

      .. rst-class:: ansible-option-title

      **organization_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-organization_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      如果 organization_id 没有设置，则使用此值 获取 organization_id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-password"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-password:

      .. rst-class:: ansible-option-title

      **password**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-password" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Foreman password

      此参数是必须的

      获取参数顺序:

      1 password 任务参数

      2 foreman_password 变量 (aka: task_vars 中的 foreman_password 变量)

      3 FOREMAN_PASSWORD 任务环境变量

      4 FOREMAN_PASSWORD 全局环境变量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-server_url"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-server_url:

      .. rst-class:: ansible-option-title

      **server_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-server_url" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Foreman Server URL

      此参数是必须的

      获取参数顺序:

      1 server_url 任务参数

      2 foreman_server_url 变量 (aka: task_vars 中的 foreman_server_url 变量)

      3 FOREMAN_SERVER_URL 任务环境变量

      4 FOREMAN_SERVER_URL 全局环境变量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-state:

      .. rst-class:: ansible-option-title

      **state**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-state" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      状态


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-default-bold:`present` :ansible-option-default:`← (default)`
      - :ansible-option-choices-entry:`absent`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet:

      .. rst-class:: ansible-option-title

      **subnet**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      subnet


      .. raw:: html

        </div>
    
  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/bmc_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/bmc_id:

      .. rst-class:: ansible-option-title

      **bmc_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/bmc_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      BMC Proxy ID to use within this subnet

      实际上支持此功能的 smart proxy id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/bmc_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/bmc_name:

      .. rst-class:: ansible-option-title

      **bmc_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/bmc_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      BMC Proxy Name to use within this subnet

      实际上支持此功能的 smart proxy 名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/boot_mode"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/boot_mode:

      .. rst-class:: ansible-option-title

      **boot_mode**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/boot_mode" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Default boot mode for interfaces assigned to this subnet.


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`Static`
      - :ansible-option-choices-entry:`DHCP`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/cidr"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/cidr:

      .. rst-class:: ansible-option-title

      **cidr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/cidr" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Network prefix in CIDR notation


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/description"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/description:

      .. rst-class:: ansible-option-title

      **description**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/description" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Subnet description


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dhcp_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dhcp_id:

      .. rst-class:: ansible-option-title

      **dhcp_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dhcp_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DHCP Proxy ID to use within this subnet

      实际上支持此功能的 smart proxy id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dhcp_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dhcp_name:

      .. rst-class:: ansible-option-title

      **dhcp_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dhcp_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DHCP Proxy name to use within this subnet

      use this value auto fill dhcp_id if None

      实际上支持此功能的 smart proxy 名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dns_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dns_id:

      .. rst-class:: ansible-option-title

      **dns_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dns_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNS Proxy ID to use within this subnet

      实际上支持此功能的 smart proxy id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dns_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dns_name:

      .. rst-class:: ansible-option-title

      **dns_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dns_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNS Proxy Name to use within this subnet

      实际上支持此功能的 smart proxy 名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dns_primary"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dns_primary:

      .. rst-class:: ansible-option-title

      **dns_primary**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dns_primary" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Primary DNS for this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/dns_secondary"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/dns_secondary:

      .. rst-class:: ansible-option-title

      **dns_secondary**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/dns_secondary" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Secondary DNS for this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/domain_ids"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/domain_ids:

      .. rst-class:: ansible-option-title

      **domain_ids**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/domain_ids" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Domains in which this subnet is part


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/domain_names"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/domain_names:

      .. rst-class:: ansible-option-title

      **domain_names**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/domain_names" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Domains in which this subnet is part

      auto fill domain_ids use this value if domain_ids is empty


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/externalipam_group"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/externalipam_group:

      .. rst-class:: ansible-option-title

      **externalipam_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/externalipam_group" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      External IPAM group - only relevant when IPAM is set to external


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/externalipam_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/externalipam_id:

      .. rst-class:: ansible-option-title

      **externalipam_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/externalipam_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      External IPAM Proxy ID to use within this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/externalipam_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/externalipam_name:

      .. rst-class:: ansible-option-title

      **externalipam_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/externalipam_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      External IPAM Proxy Name to use within this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/from_"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/from_:

      .. rst-class:: ansible-option-title

      **from_**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/from_" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Starting IP Address for IP auto suggestion


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/gateway"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/gateway:

      .. rst-class:: ansible-option-title

      **gateway**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/gateway" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Subnet gateway


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/httpboot_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/httpboot_id:

      .. rst-class:: ansible-option-title

      **httpboot_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/httpboot_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      HTTPBoot Proxy ID to use within this subnet

      实际上支持此功能的 smart proxy id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/httpboot_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/httpboot_name:

      .. rst-class:: ansible-option-title

      **httpboot_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/httpboot_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      HTTPBoot Proxy Name to use within this subnet

      实际上支持此功能的 smart proxy 名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/ipam"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/ipam:

      .. rst-class:: ansible-option-title

      **ipam**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/ipam" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      IP Address auto suggestion mode for this subnet.

      for IPv4 you can use DHCP, for IPv6 use EUI-64


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`DHCP`
      - :ansible-option-choices-entry:`Internal DB`
      - :ansible-option-choices-entry:`Random DB`
      - :ansible-option-choices-entry:`EUI-64`
      - :ansible-option-choices-entry:`External IPAM`
      - :ansible-option-choices-entry:`None`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/location_ids"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/location_ids:

      .. rst-class:: ansible-option-title

      **location_ids**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/location_ids" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      REPLACE locations with given ids


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/location_names"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/location_names:

      .. rst-class:: ansible-option-title

      **location_names**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/location_names" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      REPLACE locations with given names


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/mask"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/mask:

      .. rst-class:: ansible-option-title

      **mask**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/mask" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Netmask for this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/mtu"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/mtu:

      .. rst-class:: ansible-option-title

      **mtu**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/mtu" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      MTU for this subnet


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`1500`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Subnet name


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/network"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/network:

      .. rst-class:: ansible-option-title

      **network**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/network" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Subnet network


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/network_type"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/network_type:

      .. rst-class:: ansible-option-title

      **network_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/network_type" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type or protocol, IPv4 or IPv6, defaults to IPv4


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-default-bold:`IPv4` :ansible-option-default:`← (default)`
      - :ansible-option-choices-entry:`IPv6`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/organization_ids"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/organization_ids:

      .. rst-class:: ansible-option-title

      **organization_ids**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/organization_ids" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      REPLACE organizations with given ids.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/organization_names"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/organization_names:

      .. rst-class:: ansible-option-title

      **organization_names**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/organization_names" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      REPLACE organizations with given names.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/subnet_parameters_attributes"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/subnet_parameters_attributes:

      .. rst-class:: ansible-option-title

      **subnet_parameters_attributes**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/subnet_parameters_attributes" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Array of parameters (name, value)


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/template_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/template_id:

      .. rst-class:: ansible-option-title

      **template_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/template_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Template HTTP(S) Proxy ID to use within this subnet


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/template_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/template_name:

      .. rst-class:: ansible-option-title

      **template_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/template_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Template HTTP(S) Proxy Name to use within this subnet

      当前不支持


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/tftp_id"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/tftp_id:

      .. rst-class:: ansible-option-title

      **tftp_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/tftp_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TFTP Proxy ID to use within this subnet

      实际上支持此功能的 smart proxy id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/tftp_name"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/tftp_name:

      .. rst-class:: ansible-option-title

      **tftp_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/tftp_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TFTP Proxy Name to use within this subnet

      use this value auto fill tftp_id if None

      实际上支持此功能的 smart proxy 名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/to_"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/to_:

      .. rst-class:: ansible-option-title

      **to_**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/to_" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Ending IP Address for IP auto suggestion


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet/vlanid"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet/vlanid:

      .. rst-class:: ansible-option-title

      **vlanid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet/vlanid" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      VLAN ID for this subnet


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-subnet_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-subnet_file:

      .. rst-class:: ansible-option-title

      **subnet_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-subnet_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      subnet 配置文件

      如果 subnet 值不存在，则尝试从此文件中读取 subnet 的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-username"></div>

      .. _ansible_collections.qiyutech.foreman.hl_subnet_module__parameter-username:

      .. rst-class:: ansible-option-title

      **username**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-username" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Foreman username

      此参数是必须的

      获取参数顺序:

      1 username 任务参数

      2 foreman_username 变量 (aka: task_vars 中的 foreman_username 变量)

      3 FOREMAN_USERNAME 任务环境变量

      4 FOREMAN_USERNAME 全局环境变量


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: Foreman Setting
      qiyutech.foreman.hl_subnet:
        subnet_file: subnet_config_file.toml
        state: present




.. Facts


.. Return values


..  Status (Presently only deprecated)


.. Authors

Authors
~~~~~~~

- dev 



.. Extra links

Collection links
~~~~~~~~~~~~~~~~

.. raw:: html

  <p class="ansible-links">
    <a href="https://dev.azure.com/QiYuTech/ansible/_workitems" aria-role="button" target="_blank" rel="noopener external">Issue Tracker</a>
    <a href="https://dev.azure.com/QiYuTech/ansible/_git/collections" aria-role="button" target="_blank" rel="noopener external">Repository (Sources)</a>
  </p>

.. Parsing errors

