# IBM PC/AT 與 80286 Protected Mode

## 從 Real Mode 到 Protected Mode

Intel 80286 的核心創新是「保護模式」（Protected Mode），它提供了硬體層級的記憶體保護與多工作業支援。在保護模式下，處理器可以存取多達 16MB 的記憶體（相對於 Real Mode 的 1MB 限制），並可以防止一個程式存取另一個程式的記憶體空間。

PC/AT 在 1984 年推出時，理論上具備執行多工 UNIX 或 OS/2 的能力——但現實遠比理論複雜。

## 相容性的兩難

80286 的問題在於：保護模式與過去的 Real Mode 不相容。開機時處理器只能從 Real Mode 啟動——這是為了相容 DOS 和 8086 軟體——然後需要一個「模式切換」來進入保護模式。關鍵的問題是：Intel 的硬體設計沒有提供從保護模式回到 Real Mode 的標準方法（唯一的辦法是重置處理器）。

這意味著在 80286 上，無法在同一個會話中同時執行 DOS 應用和保護模式應用。結果是 80286 的保護模式幾乎從未被一般使用者利用。DOS 繼續統治，OS/2 遲遲不能成熟。

## 教訓

80286 的保護模式困境是一個經典的工程案例：硬體功能再強大，如果實際使用條件不可行，就等於不存在。這個教訓直接影響了 80386 的設計——後者引入了虛擬 8086 模式，可以在保護模式下同時執行多個 DOS 工作階段。

## 延伸閱讀

- [Intel 80286 - Wikipedia](https://en.wikipedia.org/wiki/Intel_80286)
- [Protected Mode - OSDev Wiki](https://wiki.osdev.org/Protected_Mode)
