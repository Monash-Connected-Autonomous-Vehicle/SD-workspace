This file is responsible for installing external dependencies required for the SD-VehicleInterface repo so that each dependency doesn't have to be installed one by one.

After cloning this repo, run vcs import src < sd-vehicleinterface.repos in the workspace, then run rosdep install -i --from-path <src-name> --rosdistro humble -y and then colcon build
