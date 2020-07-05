## example
 ANSIBLE_INTERPRETER_PYTHON=auto_silent ansible-playbook -i inventory.ini rpi-homeassistant.yaml \
   -e 'hostname=rpi-homeassistant'
