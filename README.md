## Additional patches required over AOSP

### system/fs_mgr
- [libfs_avb: Allow LKs patched with fenrir to boot on AOSP](https://github.com/realme-mt6785-devs/android_system_fs_fs_mgr/commit/116417ea413979220ceea05c060827d525e98dc9)
- [libfs_avb: Add guard to verified_boot_state check](https://github.com/realme-mt6785-devs/android_system_fs_fs_mgr/commit/81051d8fc77267dd5689617bd86ffc9e8d99a1cd)

### system/core
- [fastbootd: Always return false for GetDeviceLockStatus()](https://github.com/realme-mt6785-devs/android_system_core/commit/ab6e09adbc1b3fa7d762ffb04d106be840965103)

These patches are needed for **Kaeru LK** to boot.
