# Ansible Security Meta Collection.
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>


The Ansible ``ansible.security`` collection is a meta collection that install all the following security supported content collections.
 ```
- ansible.netcommon
- ansible.utils
- cisco.asa
- ibm.qradar
- splunk.es
- trendmicro.deepsec
 ```


<!--start requires_ansible-->
## Ansible version compatibility

This collection has been tested against following Ansible versions: **>=2.9.10**.

Plugins and modules within a collection may be tested with only specific Ansible versions.
A collection may contain metadata that identifies these versions.
PEP440 is the schema used to describe the versions of Ansible.
<!--end requires_ansible-->

<!--start collection content-->
<!--end collection content-->

## Installing this collection

You can install the ``ansible.security`` collection with the Ansible Galaxy CLI:

    ansible-galaxy collection install ansible.security

You can also include it in a `requirements.yml` file and install it with `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
---
collections:
  - name: ansible.security
```
## Using this collection

**NOTE**: For Ansible 2.9, you may not see deprecation warnings when you run your playbooks with this collection. Use this documentation to track when a module is deprecated.

### Using ``ansible.security`` meta collection to install supported security content collections with latest available release.
```
    (python37) [root@fedora]$ ansible-galaxy collection install ansible.security
    Process install dependency map
    Starting collection install process
    Installing 'ansible.netcommon:2.1.0' to '/home/root/.ansible/collections/ansible_collections/ansible/netcommon'
    Installing 'ansible.utils:2.2.0' to '/home/root/.ansible/collections/ansible_collections/ansible/utils'
    Installing 'ansible.security:1.0.0' to '/home/root/.ansible/collections/ansible_collections/ansible/security'
    Installing 'cisco.asa:2.0.2' to '/home/root/.ansible/collections/ansible_collections/cisco/asa'
    Installing 'ibm.qradar:1.0.3' to '/home/root/.ansible/collections/ansible_collections/ibm/qradar'
    Installing 'splunk.es:1.0.2' to '/home/root/.ansible/collections/ansible_collections/splunk/es'
    Installing 'trendmicro.deepsec:1.0.0' to '/home/root/.ansible/collections/ansible_collections/trendmicro/deepsec'
```

### List of installed security content collections.**
```
    (python37) [root@fedora]$ ansible-galaxy collection list
    /home/root/.ansible/collections/ansible_collections
    Collection              Version
    ----------------------- -------
    ansible.netcommon       2.1.0
    ansible.security        1.0.0
    ansible.utils           2.2.0
    cisco.asa               2.0.2
    ibm.qradar              1.0.3
    splunk.es               1.0.2
    trendmicro.deepsec      1.0.0
```

### See Also:

* [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## Advantage of Using this collection
  The Ansible ``ansible.security`` meta collection gives a single command to install all supported
  security content collection dependencies rather than individually listing them.
## Contributing to this collection

We welcome community contributions to this collection. If you find problems, please open an issue or create a PR against the [ansible.security collection repository](https://github.com/ansible-collections/ansible.security). See [Contributing to Ansible-maintained collections](https://docs.ansible.com/ansible/devel/community/contributing_maintained_collections.html#contributing-maintained-collections) for complete details.

### Code of Conduct
This collection follows the Ansible project's
[Code of Conduct](https://docs.ansible.com/ansible/devel/community/code_of_conduct.html).
Please read and familiarize yourself with this document.


## Release notes
<!--Add a link to a changelog.md file or an external docsite to cover this information. -->

## Roadmap

<!-- Optional. Include the roadmap for this collection, and the proposed release/versioning strategy so users can anticipate the upgrade/update cycle. -->

## More information

- [Ansible Collection overview](https://github.com/ansible-collections/overview)
- [Ansible User guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)
- [Ansible Developer guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)
- [Ansible Community code of conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html)

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟


