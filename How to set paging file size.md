# 📘 Guide: Switch Virtual Memory from Dynamic to Static (Windows 10 & 11)

Why fix it?
Fixing the page file size ensures predictable performance—especially useful if you're running demanding games like Starfield or using huge mod packs for Skyrim.
🔧 Steps (Windows 10 & 11)

Open Settings → System → About
→ Click Advanced system settings on the right.

In System Properties, go to Advanced → Performance → Settings…

Open the Advanced tab in Performance Options → click Change… under Virtual memory.

Uncheck Automatically manage paging file size for all drives → Select Custom size.
Initial size = ~1.5 × RAM
Maximum size = ~3 × RAM
Example: For 16 GB RAM → 24 GB / 48 GB

Click Set → OK on all windows → Restart your PC.
📏 Microsoft Recommended Values
(Initial = 1.5× RAM, Maximum = 3× RAM)

16 GB RAM → 24 GB / 48 GB
32 GB RAM → 48 GB / 96 GB
64 GB RAM → 96 GB / 192 GB
128 GB RAM → 192 GB / 384 GB

ℹ️ Source: Microsoft Learn

## 🚀 Starfield Tip
For Starfield, many players recommend setting a fixed paging file between 60 GB and 80 GB, regardless of your installed RAM, for best stability. Considering that 32GB RAM is recommended for the collection, the value should be at least 48 GB. The instructions were written by AI, so that's why it's like that.
In my case I have 32 GB RAM and 40 GB swap and it works. I will put a screenshot below. If you're wondering why we don't leave it on automatic, it's because the engine BGS uses is buggy.
---

## ✅ With this setup, you’ll have consistent performance across heavy games like Starfield or heavily-modded Skyrim.
