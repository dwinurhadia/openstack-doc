..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _ceilometer-tripleo:

.. list-table:: Description of TripleO configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description
   * - **[hardware]**
     -
   * - ``meter_definitions_file`` = ``snmp.yaml``
     - (String) Configuration file for defining hardware snmp meters.
   * - ``readonly_user_name`` = ``ro_snmp_user``
     - (String) SNMPd user name of all nodes running in the cloud.
   * - ``readonly_user_password`` = ``password``
     - (String) SNMPd password of all the nodes running in the cloud.
   * - ``url_scheme`` = ``snmp://``
     - (String) URL scheme to use for hardware nodes.
