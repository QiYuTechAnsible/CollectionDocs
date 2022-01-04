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

.. _ansible_collections.qiyutech.linux.docker_ipv6_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.linux.docker_ipv6 module -- Linux Docker 启用 IPv6 地址
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.linux collection <https://galaxy.ansible.com/qiyutech/linux>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.linux`.

    To use it in a playbook, specify: :code:`qiyutech.linux.docker_ipv6`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.linux

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Linux Docker 启用 IPv6 地址
- 注意: 你的服务器必须已经有分配的 IPv6 地址才能使用


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
        <div class="ansibleOptionAnchor" id="parameter-cidr"></div>

      .. _ansible_collections.qiyutech.linux.docker_ipv6_module__parameter-cidr:

      .. rst-class:: ansible-option-title

      **cidr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-cidr" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      IPv6 cidr

      例如: 2001:db8:1::/64


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.qiyutech.linux.docker_ipv6_module__parameter-state:

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


.. Attributes


.. Notes

Notes
-----

.. note::
   - 这个模块不支持 Windows 系统
   - 这个模块需要控制端 Python 3.6+

.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: Linux Docker 启用 IPv6
      qiyutech.linux.docker_ipv6:
        cidr: 2001:db8:1::/64
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

