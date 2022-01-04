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

.. _ansible_collections.qiyutech.core.logger_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.core.logger module -- 写入日志到 journald 或 文件中
+++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.core collection <https://galaxy.ansible.com/qiyutech/core>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.core`.

    To use it in a playbook, specify: :code:`qiyutech.core.logger`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.core

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 写入日志到 journald 或者 临时文件中

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
        <div class="ansibleOptionAnchor" id="parameter-auto_delete"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-auto_delete:

      .. rst-class:: ansible-option-title

      **auto_delete**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-auto_delete" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`boolean`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      自动删除临时文件

      自动删除写入 journald 的时候创建的临时文件


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`no`
      - :ansible-option-default-bold:`yes` :ansible-option-default:`← (default)`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-ctx"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-ctx:

      .. rst-class:: ansible-option-title

      **ctx**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-ctx" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      上下文


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-level"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-level:

      .. rst-class:: ansible-option-title

      **level**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-level" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      日志等级


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`debug`
      - :ansible-option-default-bold:`info` :ansible-option-default:`← (default)`
      - :ansible-option-choices-entry:`notice`
      - :ansible-option-choices-entry:`warning`
      - :ansible-option-choices-entry:`err`
      - :ansible-option-choices-entry:`crit`
      - :ansible-option-choices-entry:`alert`
      - :ansible-option-choices-entry:`emerg`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-message_id"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-message_id:

      .. rst-class:: ansible-option-title

      **message_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-message_id" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      消息标识

      消息标志, journald 中的 MESSAGE_ID, 用户所有的上下文

      通过获取:

      * qiyu_log_message_id 变量* QIYU_LOG_MESSAGE_ID 环境变量

      如果都没则会自动创建 一个新的 MESSAGE_ID 并 使用 set_facts 复制给 qiyu_log_message_id


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-msg"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-msg:

      .. rst-class:: ansible-option-title

      **msg**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-msg" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      日志消息


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-storage"></div>

      .. _ansible_collections.qiyutech.core.logger_module__parameter-storage:

      .. rst-class:: ansible-option-title

      **storage**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-storage" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      日志存储位置

      * remote 数据存储到远程控制的机器

      * local  数据存储到(controller)本地文件


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-default-bold:`remote` :ansible-option-default:`← (default)`
      - :ansible-option-choices-entry:`local`

      .. raw:: html

        </div>


.. Attributes


.. Notes

Notes
-----

.. note::
   - 这个模块不支持 Windows 系统

.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 写入日志
      qiyutech.core.logger:
        msg: hello
        ctx:
          key: value




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

