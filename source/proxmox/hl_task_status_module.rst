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

.. _ansible_collections.qiyutech.proxmox.hl_task_status_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.proxmox.hl_task_status module -- PVE 任务状态检查
++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.proxmox collection <https://galaxy.ansible.com/qiyutech/proxmox>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.proxmox`.

    To use it in a playbook, specify: :code:`qiyutech.proxmox.hl_task_status`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.proxmox

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 等待 PVE 的任务执行到指定状态

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
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-host:

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
        <div class="ansibleOptionAnchor" id="parameter-interval"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-interval:

      .. rst-class:: ansible-option-title

      **interval**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-interval" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      检测间隔时间

      单位: 秒


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`2`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-node"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-node:

      .. rst-class:: ansible-option-title

      **node**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-node" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      PVE集群节点名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-status"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-status:

      .. rst-class:: ansible-option-title

      **status**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-status" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      任务状态


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`running`
      - :ansible-option-default-bold:`stopped` :ansible-option-default:`← (default)`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-token_id"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-token_id:

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

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-token_secret:

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
        <div class="ansibleOptionAnchor" id="parameter-upid"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_task_status_module__parameter-upid:

      .. rst-class:: ansible-option-title

      **upid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-upid" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      PVE 任务ID


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: Wait for PVE task stopped
      qiyutech.proxmox.hl_task_status:
        node: kimsufi
        upid: "xxx"
        status: "stopped"

    - name: Wait for PVE task running
      qiyutech.proxmox.hl_task_status:
        node: kimsufi
        upid: "xxx"
        status: "running"




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
    <a href="https://github.com/QiYuTechAnsible/CollectionDocs/issues" aria-role="button" target="_blank" rel="noopener external">Issue Tracker</a>
    <a href="https://github.com/QiYuTechAnsible/CollectionDocs" aria-role="button" target="_blank" rel="noopener external">Repository (Sources)</a>
  </p>

.. Parsing errors

