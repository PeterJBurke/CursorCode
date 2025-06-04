## 🚀 Major Enhancements in v1.8

This release significantly improves the installation and deployment experience with comprehensive platform-specific setup scripts and documentation.

### 🖥️ Ubuntu 24.04 LTS Support
- **Completely rewritten `setup_desktop.sh`** for Ubuntu 24.04 LTS compatibility
- **Enhanced systemd service** with security hardening and dependency management
- **Automatic library downloads** (Bootstrap, Leaflet, Socket.IO)
- **Comprehensive error handling** and installation verification

### 🥧 Raspberry Pi Integration  
- **New `setup_raspberry_pi.sh`** with complete ground station functionality
- **MAVLink Router integration** for UART ↔ TCP communication
- **UART configuration** for GPIO pins (8/10) with Bluetooth disabling
- **WiFi hotspot failover** - automatic "RaspberryPiHotspot" creation
- **Hardware optimization** for Pi 3B+, 4B, and 5

### 📚 Enhanced Documentation
- **Platform-specific guides**: `UBUNTU_24_04_SETUP.md` and `RASPBERRY_PI_SETUP.md`
- **Updated README** with quick start sections and improved configuration
- **Comprehensive troubleshooting** and service management instructions
- **Security considerations** and performance optimization guides

### 🛠️ Technical Improvements
- **Production-ready systemd services** with proper dependency management
- **Security hardening** with restricted permissions and sandboxing
- **Improved error handling** and logging throughout setup scripts
- **Service verification** and health checking capabilities

### 📋 Compatibility
- **Ubuntu**: 24.04 LTS with Python 3.10+
- **Raspberry Pi**: Pi OS Bookworm with Python 3.11+
- **Hardware**: Optimized for Pi 3B+, 4B, and 5
- **Flight Controllers**: ArduPilot/PX4 with MAVLink support

This release provides a production-ready, one-command installation experience for both desktop and embedded deployments. 