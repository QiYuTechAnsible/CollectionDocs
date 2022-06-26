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

.. _ansible_collections.qiyutech.message.error_module:

.. Anchors: short name for ansible.builtin

.. Anchors: aliases



.. Title

qiyutech.message.error module -- 显示错误消息给用户
++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `qiyutech.message collection <https://galaxy.ansible.com/qiyutech/message>`_ (version 1.0.0).

    You might already have this collection installed if you are using the ``ansible`` package.
    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install qiyutech.message`.

    To use it in a playbook, specify: :code:`qiyutech.message.error`.

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
        <div class="ansibleOptionAnchor" id="parameter-content"></div>

      .. _ansible_collections.qiyutech.message.error_module__parameter-content:

      .. rst-class:: ansible-option-title

      **content**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-content" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      内容

      提示的详细内容


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-title"></div>

      .. _ansible_collections.qiyutech.message.error_module__parameter-title:

      .. rst-class:: ansible-option-title

      **title**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-title" title="Permalink to this option"></a>

      .. rst-class:: ansible-option-type-line

      :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      标题

      提示标题


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

   \ :ref:`qiyutech.message.error <ansible_collections.qiyutech.message.error_module>`\ 
      The official documentation on the **qiyutech.message.error** module.
   \ :ref:`qiyutech.message.info <ansible_collections.qiyutech.message.info_module>`\ 
      The official documentation on the **qiyutech.message.info** module.
   \ :ref:`qiyutech.message.success <ansible_collections.qiyutech.message.success_module>`\ 
      The official documentation on the **qiyutech.message.success** module.
   \ :ref:`qiyutech.message.warn <ansible_collections.qiyutech.message.warn_module>`\ 
      The official documentation on the **qiyutech.message.warn** module.
   \ :ref:`qiyutech.message.xterm <ansible_collections.qiyutech.message.xterm_module>`\ 
      The official documentation on the **qiyutech.message.xterm** module.

.. Examples

Examples
--------

.. code-block:: yaml+jinja

    
    - name: 安装 httpd 失败
      qiyutech.message.info:
        title: '提示'
        content: '安装 httpd 失败'




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

