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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
