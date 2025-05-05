# Role Name

A brief description of the role goes here.

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

NOTAS

                    {% set total_checks = 49 %}
                    {% set initial_compliant = 0 %}
                    {% set final_compliant = 0 %}

                    {% if instance_data.cis_1 is defined %}
                        {% if instance_data.cis_1.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_1.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_2 is defined %}
                        {% if instance_data.cis_2.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_2.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_3 is defined %}
                        {% if instance_data.cis_3.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_3.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_4 is defined %}
                        {% if instance_data.cis_4.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_4.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_5 is defined %}
                        {% if instance_data.cis_5.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_5.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_6 is defined %}
                        {% if instance_data.cis_6.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_6.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_sn is defined %}
                        {% if instance_data.cis_sn.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_sn.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_7 is defined %}
                        {% if instance_data.cis_7.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_7.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_8 is defined %}
                        {% if instance_data.cis_8.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_8.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_9 is defined %}
                        {% if instance_data.cis_9.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_9.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_10 is defined %}
                        {% if instance_data.cis_10.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_10.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_11 is defined %}
                        {% if instance_data.cis_11.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_11.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_12 is defined %}
                        {% if instance_data.cis_12.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_12.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_13 is defined %}
                        {% if instance_data.cis_13.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_13.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_14 is defined %}
                        {% if instance_data.cis_14.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_14.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_15 is defined %}
                        {% if instance_data.cis_15.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_15.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_16 is defined %}
                        {% if instance_data.cis_16.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_16.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_17 is defined %}
                        {% if instance_data.cis_17.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_17.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_18 is defined %}
                        {% if instance_data.cis_18.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_18.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_19 is defined %}
                        {% if instance_data.cis_19.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_19.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_20 is defined %}
                        {% if instance_data.cis_20.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_20.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_21 is defined %}
                        {% if instance_data.cis_21.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_21.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_22 is defined %}
                        {% if instance_data.cis_22.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_22.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_23 is defined %}
                        {% if instance_data.cis_23.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_23.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_24 is defined %}
                        {% if instance_data.cis_24.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_24.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_25 is defined %}
                        {% if instance_data.cis_25.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_25.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_26 is defined %}
                        {% if instance_data.cis_26.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_26.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_27 is defined %}
                        {% if instance_data.cis_27.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_27.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_28 is defined %}
                        {% if instance_data.cis_28.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_28.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_29 is defined %}
                        {% if instance_data.cis_29.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_29.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_30 is defined %}
                        {% if instance_data.cis_30.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_30.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_31 is defined %}
                        {% if instance_data.cis_31.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_31.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_32 is defined %}
                        {% if instance_data.cis_32.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_32.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_33 is defined %}
                        {% if instance_data.cis_33.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_33.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_34 is defined %}
                        {% if instance_data.cis_34.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_34.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_35 is defined %}
                        {% if instance_data.cis_35.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_35.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_36 is defined %}
                        {% if instance_data.cis_36.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_36.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

{#
{% if instance_data.cis_37 is defined %}
{% if instance_data.cis_37.compliant_initial | default(false) %}
{% set initial_compliant = initial_compliant + 1 %}
{% endif %}
{% if instance_data.cis_37.compliant_final | default(false) %}
{% set final_compliant = final_compliant + 1 %}
{% endif %}
{% endif %}
#}
{% if instance_data.cis_38 is defined %}
{% if instance_data.cis_38.compliant_initial | default(false) %}
{% set initial_compliant = initial_compliant + 1 %}
{% endif %}
{% if instance_data.cis_38.compliant_final | default(false) %}
{% set final_compliant = final_compliant + 1 %}
{% endif %}
{% endif %}

                    {% if instance_data.cis_39 is defined %}
                        {% if instance_data.cis_39.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_39.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_40 is defined %}
                        {% if instance_data.cis_40.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_40.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_41 is defined %}
                        {% if instance_data.cis_41.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_41.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_42 is defined %}
                        {% if instance_data.cis_42.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_42.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_43 is defined %}
                        {% if instance_data.cis_43.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_43.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_44 is defined %}
                        {% if instance_data.cis_44.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_44.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_45 is defined %}
                        {% if instance_data.cis_45.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_45.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_49 is defined %}
                        {% if instance_data.cis_49.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_49.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_51 is defined %}
                        {% if instance_data.cis_51.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_51.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_52 is defined %}
                        {% if instance_data.cis_52.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_52.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% if instance_data.cis_53 is defined %}
                        {% if instance_data.cis_53.compliant_initial | default(false) %}
                            {% set initial_compliant = initial_compliant + 1 %}
                        {% endif %}
                        {% if instance_data.cis_53.compliant_final | default(false) %}
                            {% set final_compliant = final_compliant + 1 %}
                        {% endif %}
                    {% endif %}

                    {% set initial_percent = (initial_compliant / total_checks * 100) | round | int %}
                    {% set final_percent = (final_compliant / total_checks * 100) | round | int %}
