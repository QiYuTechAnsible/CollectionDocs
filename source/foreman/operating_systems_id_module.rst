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

.. _ansible_collections.qiyutech.foreman.operating_systems_id_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.foreman.operating_systems_id module -- 获取 Foreman 的操作系统详情
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.foreman collection <https://galaxy.ansible.com/qiyutech/foreman>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.foreman`.

    To use it in a playbook, specify: :code:`qiyutech.foreman.operating_systems_id`.

.. version_added

.. versionadded:: 1.0.0 of qiyutech.foreman

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- 获取 Foreman 服务器上操作系统列表

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
        <div class="ansibleOptionAnchor" id="parameter-password"></div>

      .. _ansible_collections.qiyutech.foreman.operating_systems_id_module__parameter-password:

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

      .. _ansible_collections.qiyutech.foreman.operating_systems_id_module__parameter-server_url:

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
        <div class="ansibleOptionAnchor" id="parameter-username"></div>

      .. _ansible_collections.qiyutech.foreman.operating_systems_id_module__parameter-username:

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


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 获取 Foreman 服务器的操作系统详情
      qiyutech.foreman.operating_systems_id:
        id: 6

    - name: 获取 Foreman 服务器的操作系统详情
      qiyutech.foreman.operating_systems_id:
        id: "Ubuntu18.04"





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

