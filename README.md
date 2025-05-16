# ansible_manager
This is a simple web-based frontend for Ansible using Flask, `ansible-runner`, and SQLite. It allows you to:

- Run Ansible playbooks
- Pass extra variables in YAML format
- Schedule playbooks to run later
- View a history of executed jobs

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Ansible installed on the control node

### Install Dependencies

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
