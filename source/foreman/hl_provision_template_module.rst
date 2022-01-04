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

.. _ansible_collections.qiyutech.foreman.hl_provision_template_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.foreman.hl_provision_template module -- Foreman Provision 模版
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.foreman collection <https://galaxy.ansible.com/qiyutech/foreman>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.foreman`.

    To use it in a playbook, specify: :code:`qiyutech.foreman.hl_provision_template`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.foreman

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Foreman Provision Template 模版

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
        <div class="ansibleOptionAnchor" id="parameter-Bootdisk_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-bootdisk_template_file:

      .. rst-class:: ansible-option-title

      **Bootdisk_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-Bootdisk_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman Bootdisk 模版内容

      模版内容文件 [erb] 模版文件


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-Bootdisk_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-bootdisk_template_meta:

      .. rst-class:: ansible-option-title

      **Bootdisk_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-Bootdisk_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman Bootdisk 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-cloud_init_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-cloud_init_template_file:

      .. rst-class:: ansible-option-title

      **cloud_init_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-cloud_init_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman cloud-init 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-cloud_init_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-cloud_init_template_meta:

      .. rst-class:: ansible-option-title

      **cloud_init_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-cloud_init_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman cloud-init 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-finish_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-finish_template_file:

      .. rst-class:: ansible-option-title

      **finish_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-finish_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman finish 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-finish_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-finish_template_meta:

      .. rst-class:: ansible-option-title

      **finish_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-finish_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman finish 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host_init_config_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-host_init_config_template_file:

      .. rst-class:: ansible-option-title

      **host_init_config_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-host_init_config_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman host_init_config 模版内容

      模版内容文件 [erb] 模版文件


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host_init_config_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-host_init_config_template_meta:

      .. rst-class:: ansible-option-title

      **host_init_config_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-host_init_config_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman host_init_config 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-iPXE_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-ipxe_template_file:

      .. rst-class:: ansible-option-title

      **iPXE_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-iPXE_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman iPXE 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-iPXE_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-ipxe_template_meta:

      .. rst-class:: ansible-option-title

      **iPXE_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-iPXE_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman iPXE 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-password"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-password:

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
        <div class="ansibleOptionAnchor" id="parameter-POAP_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-poap_template_file:

      .. rst-class:: ansible-option-title

      **POAP_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-POAP_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman POAP 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-POAP_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-poap_template_meta:

      .. rst-class:: ansible-option-title

      **POAP_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-POAP_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman POAP 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-provision_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-provision_template_file:

      .. rst-class:: ansible-option-title

      **provision_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-provision_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman provision 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-provision_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-provision_template_meta:

      .. rst-class:: ansible-option-title

      **provision_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-provision_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman provision 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXEGrub2_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxegrub2_template_file:

      .. rst-class:: ansible-option-title

      **PXEGrub2_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXEGrub2_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXEGrub2 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXEGrub2_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxegrub2_template_meta:

      .. rst-class:: ansible-option-title

      **PXEGrub2_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXEGrub2_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXEGrub2 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXEGrub_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxegrub_template_file:

      .. rst-class:: ansible-option-title

      **PXEGrub_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXEGrub_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXEGrub 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXEGrub_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxegrub_template_meta:

      .. rst-class:: ansible-option-title

      **PXEGrub_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXEGrub_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXEGrub 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXELinux_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxelinux_template_file:

      .. rst-class:: ansible-option-title

      **PXELinux_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXELinux_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXELinux 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-PXELinux_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-pxelinux_template_meta:

      .. rst-class:: ansible-option-title

      **PXELinux_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-PXELinux_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman PXELinux 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-registration_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-registration_template_file:

      .. rst-class:: ansible-option-title

      **registration_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-registration_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman registration 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-registration_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-registration_template_meta:

      .. rst-class:: ansible-option-title

      **registration_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-registration_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman registration 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-script_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-script_template_file:

      .. rst-class:: ansible-option-title

      **script_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-script_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman script 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-script_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-script_template_meta:

      .. rst-class:: ansible-option-title

      **script_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-script_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman script 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-server_url"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-server_url:

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
        <div class="ansibleOptionAnchor" id="parameter-user_data_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-user_data_template_file:

      .. rst-class:: ansible-option-title

      **user_data_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-user_data_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman user_data 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-user_data_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-user_data_template_meta:

      .. rst-class:: ansible-option-title

      **user_data_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-user_data_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman user_data 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-username"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-username:

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

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-ZTP_template_file"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-ztp_template_file:

      .. rst-class:: ansible-option-title

      **ZTP_template_file**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-ZTP_template_file" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman ZTP 模版内容

      除了模版内容之外的配置


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-ZTP_template_meta"></div>

      .. _ansible_collections.qiyutech.foreman.hl_provision_template_module__parameter-ztp_template_meta:

      .. rst-class:: ansible-option-title

      **ZTP_template_meta**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-ZTP_template_meta" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      foreman ZTP 模版配置

      除了模版内容之外的配置


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: Foreman Provision 模版 详情
      qiyutech.foreman.hl_provision_template
        Bootdisk_template_meta: path/to/meta/file
        Bootdisk_template_file: path/to/meta/file




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

