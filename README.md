This is configured docker file of the really cool github repo: https://github.com/Atinoda/text-generation-webui-docker

You should use this in Portainer by adding a new stack and cloning the repo. OR You can cut and paste the yaml file into a new stack using the web editor (recommended if you need to alter a port or volume binding)

Volume bindings keep models persistent, which is the main change. Port number is also changed.
