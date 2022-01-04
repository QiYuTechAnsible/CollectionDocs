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

.. _ansible_collections.qiyutech.vm.provision_os_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.vm.provision_os module -- 自动安装系统
+++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.vm collection <https://galaxy.ansible.com/qiyutech/vm>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.vm`.

    To use it in a playbook, specify: :code:`qiyutech.vm.provision_os`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.vm

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 使用 Foreman 给 Proxmox 的机器安装操作系统

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
        <div class="ansibleOptionAnchor" id="parameter-check_interval"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-check_interval:

      .. rst-class:: ansible-option-title

      **check_interval**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-check_interval" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      检查间隔

      如果需要安装操作系统，则每间隔多少秒检查一次是否已安装完成


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`15`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-foreman_host_name"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-foreman_host_name:

      .. rst-class:: ansible-option-title

      **foreman_host_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-foreman_host_name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Foreman Host 名称

      注意: 这里的名称必须是 FQN, 例如: debian.home.arpa


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-host:

      .. rst-class:: ansible-option-title

      **host**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-host" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Proxmox API server

      这个参数是必须的

      参数获取顺序:

      1 host 任务参数

      2 proxmox_host 变量 (aka: task_vars 中的 proxmox_host 变量)

      3 PROXMOX_HOST 任务环境变量

      4 PROXMOX_HOST 全局环境变量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-node"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-node:

      .. rst-class:: ansible-option-title

      **node**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-node" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      PVE Node

      PVE 节点 ID


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-password"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-password:

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

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-server_url:

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
        <div class="ansibleOptionAnchor" id="parameter-token_id"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-token_id:

      .. rst-class:: ansible-option-title

      **token_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-token_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Proxmox API Token ID

      这个参数是必须的

      参数获取顺序:

      1 token_id 任务参数

      2 proxmox_token_id 变量 (aka: task_vars 中的 proxmox_token_id 变量)

      3 PROXMOX_TOKEN_ID 任务环境变量

      4 PROXMOX_TOKEN_ID 全局环境变量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-token_secret"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-token_secret:

      .. rst-class:: ansible-option-title

      **token_secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-token_secret" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Proxmox API Token Secret

      这个参数是必须的

      参数获取顺序:

      1 token_secret 任务参数

      2 proxmox_token_secret 变量 (aka: task_vars 中的 proxmox_token_secret 变量)

      3 PROXMOX_TOKEN_SECRET 任务环境变量

      4 PROXMOX_TOKEN_SECRET 全局环境变量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-username"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-username:

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
        <div class="ansibleOptionAnchor" id="parameter-vmid"></div>

      .. _ansible_collections.qiyutech.vm.provision_os_module__parameter-vmid:

      .. rst-class:: ansible-option-title

      **vmid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-vmid" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      PVE vmid

      PVE 虚拟机 ID


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 自动安装系统
      qiyutech.vm.provision_os:




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

