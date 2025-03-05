# 图像验证码解决方案

[![Promo](https://github.com/bright-cn/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)

借助 Bright Data 高级的验证码解决技术，轻松绕过图像验证码。利用机器学习算法、[自动化 IP 轮换](https://www.bright.cn/solutions/rotating-proxies)和强大的代理基础设施，确保对目标网站的持续且稳定的访问。

Bright Data 的验证码解决方案是 [**抓取浏览器**](https://www.bright.cn/products/scraping-browser) 和 [**网络解锁器 API**](https://www.bright.cn/products/web-unlocker) 的内置功能，可处理最复杂的验证码挑战，为您提供完整的解决方案。

## 功能  
- **快速解决验证码**：以高准确率和高速自动化解决图像验证码。  
- **IP 轮换**：结合自动重试和动态 IP 调整，避免封禁。  
- **浏览器指纹**：模拟真实用户行为以[绕过高级机器人检测](https://www.bright.cn/blog/web-data/anti-scraping-techniques)。  
- **JavaScript 渲染**：可处理依赖 JavaScript 的动态网站内容。  
- **全球地域覆盖**：精准定位并解锁全球任何区域的内容。  
- **无缝集成**：可轻松与 Puppeteer、Playwright 和 Selenium 等工具配合使用。  
- **事件监控**：跟踪验证码检测、成功与失败等事件。

## 为什么选择图像验证码解决方案

### **全球 20,000+ 客户的信赖**  
Bright Data 的验证码解决方案因其卓越的可靠性和性能，深受开发者、企业和各类组织的信赖。

### **依托优质代理网络**  
拥有超过 1 亿 IP 和先进的地域定位能力，我们的代理基础设施确保平稳、不中断的验证码解决流程。

### **AI 驱动的验证码解决**  
我们的验证码解决方案使用先进的 AI 逻辑来自动检测、分析和解决验证码。它能够处理重试、指纹识别和 HTTP 头信息，以绕过最复杂的反机器人措施。

### **专为开发者打造**  
- 与 Puppeteer、Playwright、Selenium 轻松集成。  
- 保持高度自定义，满足各类验证码处理场景。  
- 自动重试与动态 IP 调整，保证持续爬取。

> **专家提示 💡**  
>> 已经有自己的验证码解决方案？融合我们的代理网络，与 [Puppeteer](https://www.bright.cn/integration/puppeteer)、[Playwright](https://www.bright.cn/integration/playwright) 和 [Selenium](https://www.bright.cn/integration/selenium) 搭配使用，最大化减少验证码阻碍。

## 工作原理

Bright Data 的验证码解决方案已集成到 **Scraping Browser** 和 **Web Unlocker** 中，实现验证码处理的自动化。

### **自动解决验证码**  
验证码解决功能会实时自动侦测并完成验证码过程。只需启用此功能，系统即可从检测到解决全程自动处理。

#### 示例流程：  
1. **检测验证码**：识别验证码类型（如 PerimeterX）。  
2. **解决验证码**：使用 AI 逻辑进行自动化识别和处理。  
3. **失败重试**：如果解决失败，系统自动更换 IP 并重试。  
4. **返回结果**：解决成功后，系统将为目标网站提供无缝访问。

## 支持的验证码类型

Bright Data 的验证码解决方案支持多种常见验证码类型，包括：

- [**DataDome**](https://www.bright.cn/products/web-unlocker/captcha-solver/datadome)
- [**reCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/recaptcha)
- [**Click Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/click-captcha)
- [**Cloudflare**](https://www.bright.cn/products/web-unlocker/captcha-solver/Cloudflare)
- [**PerimeterX**](https://www.bright.cn/products/web-unlocker/captcha-solver/perimeterx)
- [**SimpleCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/simplecaptcha)
- [**FunCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/funcaptcha)
- [**Cloudflare Turnstile**](https://www.bright.cn/products/web-unlocker/captcha-solver/cloudflare-turnstile)
- [**AWS WAF Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/aws-waf-captcha)
- [**GeeTest CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/geetest-captcha)
- [**KeyCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/keycaptcha)
- [**Puzzle CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)
- [**Yandex CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)
- [**Image CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)
- [**Text CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

## 高级自定义

[Bright Data 的验证码解决方案](https://github.com/bright-cn/Captcha-solver)允许针对特定场景进行高级自定义，以微调解决逻辑。

### **图像验证码的自定义选项示例**  
```javascript
// 为不同验证码类型定义默认配置
function getCaptchaOptions(captchaType, customOptions = {}) {
  const defaultOptions = {
    timeout: 30000, // 等待解决验证码的最长时间（毫秒）
    check_timeout: 500, // 间隔（毫秒），用于检查验证码状态
    wait_networkidle: { timeout: 1000 }, // 网络空闲后等待 1 秒
    debug: false // 调试模式（默认关闭）
  };

  // 定义不同验证码类型的选择器
  const captchaSelectors = {
    DataDome: { selector: '#datadome-captcha', success_selector: '#captcha-success' },
    reCAPTCHA: { selector: '.g-recaptcha', success_selector: '.recaptcha-success' },
    ClickCaptcha: { selector: '.click-captcha', success_selector: '.captcha-passed' },
    hCaptcha: { selector: '.h-captcha', success_selector: '.hcaptcha-success' },
    PerimeterX: { selector: '#px-captcha', success_selector: '#px-success' },
    SimpleCaptcha: { selector: '.simple-captcha', success_selector: '.captcha-done' },
    FunCaptcha: { selector: '.funcaptcha', success_selector: '.funcaptcha-success' },
    CloudflareTurnstile: { selector: '.cf-turnstile', success_selector: '.cf-success' },
    AWSWAF: { selector: '#aws-waf-captcha', success_selector: '#aws-waf-success' },
    GeeTest: { selector: '.geetest-captcha', success_selector: '.geetest-success' },
    KeyCAPTCHA: { selector: '#keycaptcha', success_selector: '#keycaptcha-success' },
    PuzzleCAPTCHA: { selector: '.puzzle-captcha', success_selector: '.puzzle-solved' },
    YandexCAPTCHA: { selector: '#yandex-captcha', success_selector: '#yandex-success' },
    ImageCAPTCHA: { selector: '.image-captcha', success_selector: '.image-captcha-success' },
    TextCAPTCHA: { selector: '.text-captcha', success_selector: '.text-captcha-success' }
  };

  // 根据传入的验证码类型获取对应的默认选择器
  const selectedOptions = captchaSelectors[captchaType] || {};

  // 将默认选项、验证码类型专属选项以及自定义选项合并
  return { ...defaultOptions, ...selectedOptions, ...customOptions };
}

// 针对不同验证码类型的示例用法
const ddOptions = getCaptchaOptions('DataDome', { timeout: 40000, debug: true });
const recaptchaOptions = getCaptchaOptions('reCAPTCHA', { debug: true });
const hcaptchaOptions = getCaptchaOptions('hCaptcha');

console.log(ddOptions);
console.log(recaptchaOptions);
console.log(hcaptchaOptions);

// 错误处理示例
try {
  if (!document.querySelector(ddOptions.selector)) {
    throw new Error(`未找到验证码元素，使用选择器：${ddOptions.selector}`);
  }

  // 在此编写你的验证码解决逻辑
  solveCaptcha(ddOptions);
} catch (error) {
  console.error('验证码解决失败：', error.message);
}
```

## **事件监控**  
监控验证码解决事件来处理高级用例：  
- `Captcha.detected`：已检测到验证码并开始解决。  
- `Captcha.solveFinished`：验证码成功解决。  
- `Captcha.solveFailed`：验证码解决失败。

## **价格方案**

| **方案**           | **每 1K 结果价格** | **月度费用** | **描述**                                 |  
|-------------------|--------------------|-------------|------------------------------------------|  
| **按量付费**       | $1.50             | 无需承诺     | 适合临时或偶发性的数据采集需求。         |  
| **成长型**         | $1.27             | $499         | 专为希望扩张的团队定制。                 |  
| **商务型**         | $1.12             | $999         | 适用于大规模的数据采集。                 |  
| **高级型**         | $1.05             | $1,999       | 提供高级功能与优先支持。                 |  
| **企业定制**       | 定制报价          | 联系我们     | 满足顶级业务需求的定制方案。             |  

🚀 **特别优惠**：首次充值最高可享受与充值金额 1:1 等额的抵扣，最高可达 **$500**！

## **开发者为何青睐图像验证码解决方案**  
- **轻松集成**：可与 Puppeteer、Playwright、Selenium 平滑结合。  
- **先进的 AI 逻辑**：自动处理重试、验证码解决、指纹识别、IP 轮换以及高级请求头。  
- **内置浏览器**：无需额外管理外部浏览器来渲染 JavaScript。  
- **实时洞察**：通过实时仪表板监控网络性能。  
- **超强支持**：全球 24/7 客户支持，且每天都在更新新功能。

## **常见问题**

### **图像验证码解决方案如何工作？**  
该方案利用先进的 AI 逻辑来自动检测并解决图像验证码。

### **能同时处理多个验证码吗？**  
可以。该方案可伸缩地同时处理多种验证码类型，保证访问的持续性。

### **如果解决验证码失败会怎样？**  
系统会自动进行重试。如果问题依旧，请随时联系我们 24/7 的支持团队以获取帮助。

---

## **告别图像验证码的困扰**  
立即开始免费试用，体验由 Bright Data 提供的流畅[图像验证码解决方案](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)！  
