Adding roles to the documentation
=================================

.. include:: includes/all.rst

If you maintain a DebOps Contrib role, you are encouraged to add your role to
this end user documentation.

For this, check how DebOps_ does documentation but looking at `debops/docs`_
and for examples you can checkout an up-to-date role from the `DebOps Status page`_.
The links defined in `DebOps docs global.rst`_ can also be used for DebOps Contribs roles.
The file gets injected into the docs build the same way as for DebOps_ itself.
If you have additional links which fit into the file, you can add them to
`debops/docs`_ and they your changes will also be available here.
Refer to `Use global link definitions <https://github.com/debops/docs/issues/155>`__
for details.

The :file:`readme.md` file which is used for GitHub and Ansible Galaxy can be
generated using ansigenome_ and templates currently available here:
https://github.com/ypid/ypid-ansible-common/tree/master/template_READMEs

For bonus points, setup Travis CI tests for your role and import it on Ansible Galaxy.

Feel free to add your role to:
https://github.com/debops-contrib/docs
When you are member of the DebOps Contrib organization you should have write
permissions to the repository and can merge your own pull request after the
test for the PR passed.

If you push new commits to your role, this documentation should pick them up
within two hours without further intervention.
