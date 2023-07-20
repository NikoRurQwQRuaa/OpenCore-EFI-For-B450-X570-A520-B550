# OpenCore-EFI-For-B450-X570-A520-B550
基于OpenCore的AMD Ryzen台式机平台黑苹果引导

---

#如何使用

**1.选择你的平台+核心数**

**2.使用三码工具写入三码（OCAT or GenSMBIOS）**

**3.使用可编辑plist的工具编辑你的config.plist 推荐OCAT**

**4.boot-args加入-v跑码 还需要RX5000/6000系列GPU加入agdpmod=pikera**

---

# Tips:

**1.A520 B550需要加入ACPI文件：SSDT-CPUR.aml**

**2.该EFI并不适用于所有平台 请自行测试**

**3.如需使用USB驱动 请将三码平台改为MacPro 7,1**

--

# 致谢

## 致谢

**Acidanthera的OpenCore**

**Apple的macOS**

**AMD Vanilla开发的AMD Ryzen CPU Patch**
