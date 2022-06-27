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

.. _ansible_collections.qiyutech.message.table_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.message.table module -- 显示表格信息给用户
++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.message collection <https://galaxy.ansible.com/qiyutech/message>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.message`.

    To use it in a playbook, specify: :code:`qiyutech.message.table`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.message

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 这个模块不执行任何动作, 仅仅返回输入的参数

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
        <div class="ansibleOptionAnchor" id="parameter-caption"></div>

      .. _ansible_collections.qiyutech.message.table_module__parameter-caption:

      .. rst-class:: ansible-option-title

      **caption**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-caption" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      表格标题


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-header"></div>

      .. _ansible_collections.qiyutech.message.table_module__parameter-header:

      .. rst-class:: ansible-option-title

      **header**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-header" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      表格Header

      这个字段 和 table 必须同时有值, 这个里面值是 table header 的值


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-kv"></div>

      .. _ansible_collections.qiyutech.message.table_module__parameter-kv:

      .. rst-class:: ansible-option-title

      **kv**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-kv" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      简单KV

      简单 KV 表格, 没有 header


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-table"></div>

      .. _ansible_collections.qiyutech.message.table_module__parameter-table:

      .. rst-class:: ansible-option-title

      **table**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-table" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      表格数据

      表格的详细数据


      .. raw:: html

        </div>


.. Attributes


.. Notes

Notes
-----

.. note::
   - 这个模块支持 Windows 系统

.. Seealso

See Also
--------

.. seealso::

   \ :ref:`qiyutech.message.xterm <ansible_collections.qiyutech.message.xterm_module>`\ 
      The official documentation on the **qiyutech.message.xterm** module.

.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 显示用户信息
      qiyutech.message.table:
        caption: '用户信息'
        kv:
          username: "{{ username }}"
          password: "{{ password }}"

    - name: 显示表格信息
      qiyutech.message.table:
        caption: '数据'
        header:
        - 标题
        - 内容
        table:
        - 标题: 测试
          内容: 测试内容




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

