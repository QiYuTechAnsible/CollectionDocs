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

.. _ansible_collections.qiyutech.core.check_role_args_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.core.check_role_args module -- 检查当前的变量是否满足 role 的需要
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.core collection <https://galaxy.ansible.com/qiyutech/core>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.core`.

    To use it in a playbook, specify: :code:`qiyutech.core.check_role_args`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.core

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 这个模块会检查当前执行 role 的 vars/main.yml 或者 vars/main.yaml 文件中所有的变量是否都存在
- 这个模块仅允许在 role 中运行 (直接从 playbook 中调用会失败)

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
        <div class="ansibleOptionAnchor" id="parameter-exclude"></div>

      .. _ansible_collections.qiyutech.core.check_role_args_module__parameter-exclude:

      .. rst-class:: ansible-option-title

      **exclude**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-exclude" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      排除字段

      不需要检查的字段有哪些


      .. raw:: html

        </div>


.. Attributes


.. Notes

Notes
-----

.. note::
   - 这个模块不支持 Windows 系统

.. Seealso

See Also
--------

.. seealso::

   \ :ref:`ansible.builtin.assert <ansible_collections.ansible.builtin.assert_module>`\ 
      The official documentation on the **ansible.builtin.assert** module.

.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 检查参数是否满足要求
      qiyutech.core.check_role_args:





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

