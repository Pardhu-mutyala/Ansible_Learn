# Ansible Learn

A small repository to practice and demonstrate Ansible playbooks, roles, and related automation techniques.

## Contents

- playbooks/ - Example Ansible playbooks
- roles/ - Example Ansible roles
- inventory/ - Sample inventory files
- docs/ - Additional documentation and notes

## Prerequisites

- Ansible 2.9+ (recommended: latest stable)
- Python 3.8+
- Access to target machines (SSH keys or password-based auth)

## Getting started

1. Clone the repository:

   git clone https://github.com/Pardhu-mutyala/Ansible_Learn.git
   cd Ansible_Learn

2. Install dependencies (if any), e.g. via requirements.yml:

   ansible-galaxy install -r requirements.yml

3. Run a playbook:

   ansible-playbook -i inventory/hosts playbooks/site.yml

## Directory structure

- playbooks/: top-level playbooks that orchestrate tasks
- roles/: reusable roles with tasks, handlers, templates, and defaults
- inventory/: host groups and variables
- docs/: notes and runbooks

## Examples

See playbooks/ and roles/ for concrete examples. Start with playbooks/site.yml (if present) or run an individual playbook:

ansible-playbook -i inventory/hosts playbooks/setup.yml

## Contributing

Contributions welcome. Open an issue or submit a pull request with proposed changes. Follow standard Ansible practices and include tests where appropriate.

## License

Specify a license for your repository (e.g., MIT). Add a LICENSE file with the project's license.

## Contact

Maintainer: Pardhu-mutyala

If you'd like adjustments to the README (more examples, diagrams, CI instructions), tell me what to include and I will update it.