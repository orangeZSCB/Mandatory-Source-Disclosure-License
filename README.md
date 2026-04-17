# Mandatory Source Disclosure License (MSDL)

> Use it and open source it. Don't open source it, don't use it. Take it or leave it, go fuck yourself.

[en] [zh](https://github.com/orangeZSCB/Mandatory-Source-Disclosure-License/blob/master/Docs/zh/README_zh.md) [ja](https://github.com/orangeZSCB/Mandatory-Source-Disclosure-License/blob/master/Docs/zh/README_ja.md)

---

## What is this?

MSDL (Mandatory Source Disclosure License) is a Copyleft license more radical than AGPL.

Its core claim is a single rule: **modify means disclose, regardless of whether you distribute.**

Most open source licenses (including GPL and AGPL) tie disclosure obligations to "distribution" — as long as you don't hand the software to someone else, you can modify it internally with no obligation to open source anything. MSDL removes that premise: modify means disclose, full stop.

---

## Comparison with mainstream licenses

| Action | MIT | GPL v3 | AGPL v3 | **MSDL** |
|--------|-----|--------|---------|----------|
| Use as-is (no modifications) | ✅ No restrictions | ✅ Retain notices | ✅ Retain notices | ✅ Retain notices |
| Modify for internal use, no distribution | ✅ No restrictions | ✅ No obligation | ✅ No obligation | ⚠️ **Must disclose** |
| Modify and serve as SaaS | ✅ No restrictions | ✅ No obligation | ⚠️ Must disclose | ⚠️ **Must disclose** |
| Modify and distribute | ✅ No restrictions | ⚠️ Must disclose | ⚠️ Must disclose | ⚠️ **Must disclose** |
| Config files / secrets | ✅ No restrictions | ✅ No obligation | ✅ No obligation | ✅ **Exempt** |

---

## What you CAN do

- ✅ Use the Software as-is, without modification
- ✅ Distribute the Software (with license and copyright notices intact)
- ✅ Edit config files, fill in API keys, and other deployment operations
- ✅ Reference the Software as an unmodified dependency
- ✅ Study and research based on the Software

## What you CANNOT do

- ❌ Modify the source code and refuse to disclose it, for any reason
- ❌ Apply restrictions to Derivative Works stricter than this License
- ❌ Remove or obscure original copyright notices or the License text
- ❌ Distribute or deploy a modified version of the Software in closed-source form

---

## FAQ

**Q: I just changed a database password in `.env`. Do I need to open source that?**

No. Config files, environment variables, and runtime-generated data files are all exempt (Section 2). As long as you haven't touched the source code logic, no disclosure obligation is triggered.

**Q: I deployed this internally at my company for my own use. Do I still need to open source it?**

Yes. MSDL's disclosure obligation does not depend on "distribution" — internal use is equally covered. This is the most fundamental difference between MSDL and GPL/AGPL.

**Q: I made a tiny change. What are the disclosure requirements?**

Satisfy at least one of the following: publish on a publicly accessible code hosting platform (GitHub/GitLab/Gitea/etc.), accompany every copy with complete source code, or provide a written offer to supply complete source code on request, valid for three years.

**Q: I violated the license. Is there any way to remedy this?**

Yes. For a first violation, if you fully cure it within 30 days of receiving notice, your rights are automatically reinstated. Second and subsequent violations are not eligible for automatic reinstatement — written consent from the Copyright Holder is required (Section 7).

**Q: Does this count as "open source"?**

Depends on your definition. It does not meet the OSI definition of open source (which requires no restriction on use cases), but the source code is fully public, and it sits squarely in the strong Copyleft camp in spirit. If OSI certification matters to you, AGPL v3 is the closest mainstream alternative.

---

## How to use this License

Place the `LICENSE` file in the root of your project and replace the placeholders at the top:

```
Copyright (c) 2025 Your Name or Organization
```

Note it in your project README:

```
This project is released under the MSDL v1.0 License. See the LICENSE file for details.
```

---

## Design philosophy

Code is an extension of the commons. You are free to build upon it — but what you build should belong to everyone too.

MSDL is not designed to stop people from using software. It exists to ensure that improvements flow back into the public domain — wherever those improvements happen to occur.

---

## File reference

| File | Description |
|------|-------------|
| `LICENSE` | License text (Chinese) |
| `LICENSE-en` | License text (English) |
| `README.md` | README (Chinese) |
| `README-en.md` | This file |

> This is a custom license. It is not OSI-certified and has not been tested in court.
> For high-stakes commercial scenarios, consulting a legal professional is recommended.

## A Pragmatic Note on Enforcement (Informal — not part of the binding License text)

The authors of this License are fully aware that private violations are technically difficult to detect or pursue. Our position is as follows:

If you have modified and used this Software without fulfilling your obligations under this License, and this fact has never entered anyone's field of awareness, the universe will greet it with its customary silence.

However, should this fact come to the attention of the Copyright Holder by any means — whether through public channels, a tip-off, technical forensics, or sheer accident — Section 7 will apply without hesitation.

In short: what we cannot see, we cannot act on.      
Just don't let us see it.

[![Star History Chart](https://api.star-history.com/chart?repos=orangeZSCB/Mandatory-Source-Disclosure-License&type=date&legend=top-left)](https://www.star-history.com/?repos=orangeZSCB%2FMandatory-Source-Disclosure-License&type=date&legend=top-left)
