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

.. _ansible_collections.qiyutech.software.check_used_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.software.check_used module -- 检查目标目录是否安装过软件
++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.software collection <https://galaxy.ansible.com/qiyutech/software>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.software`.

    To use it in a playbook, specify: :code:`qiyutech.software.check_used`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.software

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 检查指定的目录中是否已经使用过 qiyutech.software 相关的模块安装过软件


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
        <div class="ansibleOptionAnchor" id="parameter-path"></div>

      .. _ansible_collections.qiyutech.software.check_used_module__parameter-path:

      .. rst-class:: ansible-option-title

      **path**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-path" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      需要检查的目录

      实际检查的文件为: {path}/meta/software.txt


      .. raw:: html

        </div>


.. Attributes


.. Notes

Notes
-----

.. note::
   - 这个模块支持 Windows 系统

.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 检查目录是否已使用
      qiyutech.software.check_used:
        path: path/to/directory




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

