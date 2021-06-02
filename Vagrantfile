Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.synced_folder ".", "/app"

  config.vm.define "machine" do |machine1|
    machine1.vm.hostname = "machine"
  end
end
