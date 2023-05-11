```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/JafarAbdi/franka-humble-packages-v2/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/JafarAbdi_franka-humble-packages-v2.list
echo "yaml https://raw.githubusercontent.com/JafarAbdi/franka-humble-packages-v2/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-JafarAbdi_franka-humble-packages-v2.list
```
