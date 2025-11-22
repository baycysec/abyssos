# Abyssos
<p align="center">

<!-- <img src="https://github.com/user-attachments/assets/9363ea28-6c4e-4859-909e-a1f4787245f7" width="9216" height="2304" alt="artemon-banner"  /> -->
<img width="9216" height="2304" alt="abyssos-banner" src="https://github.com/user-attachments/assets/a7f1b69c-8ecb-4e46-b10f-47f24b07629f" />

</p>

> [!CAUTION]
> This repository contains a compiled binary sample of Abyssos, a research-focused ransomware prototype created strictly for security analysis, malware research training, and defensive development. Do NOT execute this binary on any production, personal, or non-isolated environment. Use only inside a controlled sandbox, isolated VM, or malware lab.

## [👤] About Abyssos

<p align="justify">Abyssos is a research-focused ransomware/wiper hybrid prototype designed to support malware analysts, DFIR practitioners, and detection engineers in studying modern ransomware behavior in a controlled environment. This sample demonstrates realistic attacker techniques—ranging from file encryption, obfuscation, and discovery to registry modification and environmental persistence—without shipping source code, minimizing the risk of misuse.</p>

## [📃] High-level Summary

<p align="justify">The binary showcases a ChaCha8-based file encryption routine, registry-level wallpaper persistence, simple masquerading techniques, and built-in self-deletion mechanisms. It is intentionally destructive, deleting original files after encryption, making it suitable for studying impact-oriented behaviors and anti-recovery patterns. Abyssos adheres to several MITRE ATT&CK techniques commonly observed in real-world ransomware campaigns, including user-execution-based initial access, encrypted impact, indicator removal, discovery, and persistent system defacement.</p>

## [📝] Developer
- [jon-brandy](https://github.com/jon-brandy)
