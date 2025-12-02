# 🌍 Duck Market - Localization Guide

Welcome to contribute translations for Duck Market MOD! This guide will help you understand how to contribute.

## 📁 File Structure

```
DuckMarket.Core/Localization/
├── zh-CN.txt    # Simplified Chinese (Default)
├── zh-TW.txt    # Traditional Chinese
├── en-US.txt    # English
├── ja-JP.txt    # Japanese
├── ko-KR.txt    # Korean
├── fr-FR.txt    # French
├── vi-VN.txt    # Vietnamese
├── ru-RU.txt    # Russian
└── README.md    # Documentation
```

## 📝 Translation File Format

Each translation file uses simple `key=value` format:

```properties
# Comments start with #
market.title=Duck Market
buy.button=Purchase
```

### Format Rules

1. **Key**: Do NOT modify, keep consistent with `zh-CN.txt`
2. **Value**: Translate to target language
3. **Placeholders**: `{0}`, `{1}`, `{2}` must be preserved, order can be adjusted
4. **Comments**: Lines starting with `#` are comments, can be translated or kept

### Placeholder Example

```properties
# Chinese
delist.success=下架成功！{0} x{1} 已存入自提柜

# English
delist.success=Delisted successfully! {0} x{1} sent to locker

# Japanese (placeholder order can be adjusted)
delist.success={0} x{1} の出品を取り消しました！ロッカーに送信されました
```

## 🚀 How to Contribute

### Method 1: Submit Pull Request (Recommended)

1. **Fork this repository**
2. **Clone to local**
   ```bash
   git clone https://github.com/DuckMarket-Dev/DuckMarket-i18n.git
   ```
3. **Edit translation files**
   - Modify existing language files (e.g., `en-US.txt`)
   - Or create new language files (e.g., `fr-FR.txt`)
4. **Commit changes**
   ```bash
   git add .
   git commit -m "Update [language code] translation"
   git push origin main
   ```
5. **Create Pull Request**
   - Go to GitHub repository page
   - Click "New Pull Request"
   - Fill in translation description

### Method 2: Submit Issue

If you're not familiar with Git:
1. Go to [Issues page](https://github.com/DuckMarket-Dev/DuckMarket-i18n/issues)
2. Create new Issue, title format: `[Translation] Language Name`
3. Paste your translation content in the Issue

## 🌐 Supported Language Codes

| Code | Language | Status | Lines | Last Updated |
|------|----------|--------|-------|--------------|
| `zh-CN` | Simplified Chinese | ✅ Complete | 186 | 2025-11-21 |
| `zh-TW` | Traditional Chinese | ✅ Complete | 186 | 2025-11-21 |
| `en-US` | English | ✅ Complete | 181 | 2025-11-21 |
| `ja-JP` | Japanese | ✅ Complete | 189 | 2025-11-21 |
| `ko-KR` | Korean | ✅ Complete | 189 | 2025-11-21 |
| `fr-FR` | French | ✅ Complete | 125 | 2025-11-21 |
| `vi-VN` | Vietnamese | ✅ Complete | 120 | 2025-11-21 |
| `ru-RU` | Russian | ❌ Pending | - | - |
| `de-DE` | German | ❌ Pending | - | - |

## ✅ Translation Checklist

Before submitting, please ensure:

- [ ] All keys match `zh-CN.txt`
- [ ] Placeholders `{0}`, `{1}` are correctly preserved
- [ ] Translation follows target language conventions
- [ ] No missing entries
- [ ] File encoding is UTF-8
- [ ] Line endings use LF (Unix style)

## 📖 Translation Reference

### Common Terms

| Chinese | English | Japanese | Korean | French | Vietnamese |
|---------|---------|----------|--------|--------|-----------|
| 鸭鸭市场 | Duck Market | ダックマーケット | 덕 마켓 | Duck Market | Duck Market |
| 上架 | List Item | 出品 | 등록 | Mettre en vente | Đăng bán |
| 下架 | Delist | 出品取消 | 등록 취소 | Retirer | Gỡ bỏ |
| 购买 | Purchase | 購入 | 구매 | Acheter | Mua |
| 卖家 | Seller | 出品者 | 판매자 | Vendeur | Người bán |
| 库存 | Stock | 在庫 | 재고 | Stock | Kho |
| 自提柜 | Locker | ロッカー | 보관함 | Casier | Tủ khóa |
| 网页登录 | Web Login | ウェブログイン | 웹 로그인 | Connexion web | Đăng nhập web |

## 🤝 Contributors

Thanks to all translation contributors!

### 🌟 Translation Team

| Language | Contributor | GitHub | Status |
|----------|-------------|--------|--------|
| 🇨🇳 Simplified Chinese | DuckMarket Team | [@DuckMarket-Dev](https://github.com/DuckMarket-Dev) | Maintainer |
| 🇹🇼 Traditional Chinese | DuckMarket Team | [@DuckMarket-Dev](https://github.com/DuckMarket-Dev) | Maintainer |
| 🇺🇸 English | DuckMarket Team | [@DuckMarket-Dev](https://github.com/DuckMarket-Dev) | Maintainer |
| 🇯🇵 Japanese | DuckMarket Team | [@DuckMarket-Dev](https://github.com/DuckMarket-Dev) | Maintainer |
| 🇰🇷 Korean | DuckMarket Team | [@DuckMarket-Dev](https://github.com/DuckMarket-Dev) | Maintainer |
| 🇫🇷 French | Takeshi06 | [@Takeshi06](https://github.com/Takeshi06) | Contributor |
| 🇻🇳 Vietnamese | Lehuyknight | [@Lehuyknight](https://github.com/Lehuyknight) | Contributor |

### 🎯 Recent Updates (Nov 2025)

- **2025-11-21**: ✨ Added **Web Login Dialog** translations for all 7 languages
- **2025-11-21**: 🔧 Integrated as Git Submodule in main project
- **2025-11-13**: 🇫🇷 French translation by [@Takeshi06](https://github.com/Takeshi06)
- **2025-11-11**: 🇻🇳 Vietnamese translation by [@Lehuyknight](https://github.com/Lehuyknight)

### 🏆 Want to Contribute?

We welcome contributions for:
- 🇷🇺 Russian (ru-RU)
- 🇩🇪 German (de-DE)  
- 🇪🇸 Spanish (es-ES)
- 🇮🇹 Italian (it-IT)
- And more languages!

## 📧 Contact

For any questions:
- Submit [GitHub Issue](https://github.com/DuckMarket-Dev/DuckMarket-i18n/issues)

## 📄 License

Translation files follow the same license as the main project.

---

**Thank you for contributing to Duck Market MOD internationalization!** 🦆✨

