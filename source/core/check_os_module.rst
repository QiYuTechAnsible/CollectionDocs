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

.. _ansible_collections.qiyutech.core.check_os_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.core.check_os module -- 检查是否支持远程服务器的操作系统
+++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.core collection <https://galaxy.ansible.com/qiyutech/core>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.core`.

    To use it in a playbook, specify: :code:`qiyutech.core.check_os`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.core

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 这个模块会根据 os.toml 的内容检测目标服务器是否允许继续执行

.. note::
    This module has a corresponding :ref:`action plugin <action_plugins>`.

.. Aliases


.. Requirements






.. Options


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

   \ :ref:`ansible.builtin.assert <ansible_collections.ansible.builtin.assert_module>`\ 
      The official documentation on the **ansible.builtin.assert** module.

.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 检测目标服务器是否满足系统要求
      qiyutech.core.check_os:

    - name: 检测目标服务器是否满足系统要求
      qiyutech.core.check_os:
      environment:
        QIYU_AUTOMATION_DIR: /path/to/automation/dir

    - name: 检测目标服务器是否满足系统要求
      qiyutech.core.check_os:
      when: skip_os_check != true




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

