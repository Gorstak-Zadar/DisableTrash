# 🗑️ DisableTrash

> Registry tweak to **disable the Recycle Bin** and enable confirm-on-delete for permanent file deletion.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚫 **No Recycle Bin** | Bypasses Recycle Bin — files are deleted permanently |
| ✅ **Confirm Delete** | Adds confirmation dialog before delete |
| 📋 **Registry Merge** | Double-click `.reg` to apply |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **Scope** | Current user (HKCU) |

---

## 🚀 Usage

1. **Create a restore point** (recommended)
2. Double-click `DisableTrash.reg` or right-click → **Merge**

---

## 🔧 Registry Keys

| Key | Value |
|-----|-------|
| `NoRecycleFiles` | 1 (disable Recycle Bin) |
| `ConfirmFileDelete` | 1 (confirm deletion) |
| `NonEnum\{645FF040-5081-101B-9F08-00AA002F954E}` | 1 (hide Recycle Bin icon) |

---

<p align="center">
  <sub>🔧 Gorstak Registry Tweak</sub>
</p>
