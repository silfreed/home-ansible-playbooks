## examples
  ansible-playbook -i production homeassistant.yml -e 'hostname=rpi-homeassistant'
  ansible-playbook -i production btmon.yml -e 'hostname=rpi-btmon'
  ansible-playbook -i production thor.yml --ask-become-pass --check --diff
  ansible-playbook -i production thor.yml --ask-become-pass