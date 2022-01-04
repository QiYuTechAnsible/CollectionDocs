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

.. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.proxmox.hl_qemu_vm module -- QEMU 虚拟机 创建/删除 接口
+++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.proxmox collection <https://galaxy.ansible.com/qiyutech/proxmox>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.proxmox`.

    To use it in a playbook, specify: :code:`qiyutech.proxmox.hl_qemu_vm`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.proxmox

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 创建、获取 QEMU 虚拟机的状态

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
        <div class="ansibleOptionAnchor" id="parameter-agent"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-agent:

      .. rst-class:: ansible-option-title

      **agent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-agent" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      启用 QEMU 代理


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-bridge"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-bridge:

      .. rst-class:: ansible-option-title

      **bridge**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-bridge" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      网络桥接名称

      例如: vmbr0


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-cores"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-cores:

      .. rst-class:: ansible-option-title

      **cores**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-cores" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      CPU核心数量


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-disk_size"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-disk_size:

      .. rst-class:: ansible-option-title

      **disk_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-disk_size" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      磁盘大小

      单位: GB


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-host:

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
        <div class="ansibleOptionAnchor" id="parameter-memory"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-memory:

      .. rst-class:: ansible-option-title

      **memory**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-memory" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      内存大小

      单位: MB


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-name"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-name" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      虚拟机的名称


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-node"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-node:

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
        <div class="ansibleOptionAnchor" id="parameter-numa"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-numa:

      .. rst-class:: ansible-option-title

      **numa**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-numa" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      启用 numa


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-ostype"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-ostype:

      .. rst-class:: ansible-option-title

      **ostype**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-ostype" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      操作系统类型

      Specify guest operating system. This is used to enable special

      optimization/features for specific operating systems:

      other: unspecified OS

      win7: Microsoft Windows 7

      win8: Microsoft Windows 8/2012/2012r2

      win10: Microsoft Windows 10/2016/2019

      l24: Linux 2.4 Kernel

      l26: Linux 2.6 - 5.X Kernel

      solaris: Solaris/OpenSolaris/OpenIndiania kernel


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`l24`
      - :ansible-option-choices-entry:`l26`
      - :ansible-option-choices-entry:`win7`
      - :ansible-option-choices-entry:`win8`
      - :ansible-option-choices-entry:`win10`
      - :ansible-option-choices-entry:`other`
      - :ansible-option-choices-entry:`solaris`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-sockets"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-sockets:

      .. rst-class:: ansible-option-title

      **sockets**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-sockets" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      CPU数量


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`1`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-state:

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

      虚拟机的状态

      present 如果不存在则创建此虚拟机

      absent 如果存在则删除此虚拟机


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-default-bold:`present` :ansible-option-default:`← (default)`
      - :ansible-option-choices-entry:`absent`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-token_id"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-token_id:

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

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-token_secret:

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
        <div class="ansibleOptionAnchor" id="parameter-vga"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-vga:

      .. rst-class:: ansible-option-title

      **vga**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-vga" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      VGA设置

      格式为:

      type=xxx,memory=xxx

      内存大小单位为: MB

      Ubuntu 无法自动启动的问题 [需要设置: vga: type=vmware]:

      https://forum.proxmox.com/threads/ubuntu-desktop-vm-stuck.67269/

      vga type source code: https://github.com/proxmox/qemu-server/blob/master/PVE/QemuServer.pm#L192

      当前支持的类型: cirrus qxl qxl2 qxl3 qxl4 none serial0 serial1 serial2 serial3 std virtio vmware


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-vmid"></div>

      .. _ansible_collections.qiyutech.proxmox.hl_qemu_vm_module__parameter-vmid:

      .. rst-class:: ansible-option-title

      **vmid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-vmid" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`integer` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      虚拟机ID


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: Test with a message
      qiyutech.proxmox.hl_qemu_vm:
        host: https://proxmox.ksle.2cc.net
        token_id: 'root@pam!demo'
        token_secret: 'xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx'




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

