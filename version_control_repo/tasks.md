# Create git server as service in your company with CI/CD capabilities.

*   setup clean centos/debian server with these dependencies:
    *   Ssh
    *   Postfix

*   add gilab-ce install script with this command:
```bash
  curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.rpm.sh | sudo bash]

*   configure its url.
*   generate letsencrypt certificates.
*   enable https access.
*   perform gitlab confiuration.
*   setup ssh key access
*   test connection and git repo configuration.

<!-- https://www.howtoforge.com/tutorial/how-to-install-and-configure-gitlab-ce-on-centos-7/ -->
