# -*- ruby -*-

require "rake"
require "yaml"
require "erb"

desc "Apply the Ansible configurations"
task :deploy do
  sh("ansible-playbook",
     "--inventory-file", "hosts",
     "ansible/playbook.yml")
end
