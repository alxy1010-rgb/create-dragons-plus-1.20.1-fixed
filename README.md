# Create: Dragons Plus - Custom Fix Edition (1.20.1 Forge)

**This is a third-party custom fix version** based on **Forge-Create: Dragons Plus v1.0.1 (Unofficial Forge 1.20.1 Port)**.  
Modifications made by **Hinakiel**.

## 📝 [1.0.1-mc1.20.1-fix2] - 2026-04-14

### Fixed

  - **ClassCastException in Fan Sanding**: Fixed a critical crash where `SandingFanProcessingType` passed a generic `RecipeWrapper` to Create's `SandPaperPolishingRecipe`. Now correctly wraps the stack in `SandPaperInv`.
  - **NPE in Fan Ending**: Fixed a `NullPointerException` during the initialization of fan Ending recipes within `PotionMixingRecipesMixin`.

### Added

  - **Localization**: Supplemented missing translation keys for fluids (including buckets) and fan processing recipe types to resolve raw translation key display issues.

-----

# 机械动力：龙+ - 第三方个人修复版 (1.20.1 Forge)

**本修改版**是基于 **Forge-Create: Dragons Plus v1.0.1 (非官方 Forge 1.20.1 移植版)** 的第三方个人修复版本。  
修改人：**Hinakiel**

## 📝 [1.0.1-mc1.20.1-fix2] - 2026-04-14

### 修复

  - **批量喷砂崩溃**: 修复了 `SandingFanProcessingType` 尝试将 `RecipeWrapper` 强转为 `SandPaperInv` 导致的 `ClassCastException` 炸档问题。
  - **批量终结崩溃**: 修复了 `PotionMixingRecipesMixin` 在初始化批量终结配方时可能触发的空指针（NPE）崩溃。

### 新增

  - **本地化**: 针对所有流体（及对应流体桶）与鼓风机批量处理配方类型，补全了原版缺失的翻译键，解决了游戏内显示原始代码键名的问题。

-----

## 🏗️ Credits / 致谢

  * **Original Project**: Forge-Create: Dragons Plus
  * **Fixed by**: [Hinakiel](https://www.google.com/search?q=https://github.com/alxy1010-rgb)

## 📄 License / 协议

Distributed under the **LGPL-3.0-or-later** License.
