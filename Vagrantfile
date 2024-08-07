Vagrant.configure("2") do |config|
  # Configuración de la caja
  config.vm.box = "ubuntu/bionic64"

  # Configuración de red privada
  config.vm.network "private_network", ip: "192.168.33.10"
  
  # Configuración del hostname
  config.vm.hostname = "devops-server"
  
  # Configuración del proveedor (VirtualBox)
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end

  # Configuración del directorio compartido
  config.vm.synced_folder ".", "/vagrant"
end

  