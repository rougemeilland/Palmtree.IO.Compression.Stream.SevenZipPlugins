# Palmtree.IO.Compression.Stream.Plugin.SevenZip.Bzip2

## 1. Overview

<!--
���̃p�b�P�[�W�́A�p�b�P�[�W `Palmtree.IO.Compression.Archive.Zip`�� BZIP2 ���k�������T�|�[�g���邽�߂̃v���O�C�����C�u�����̃p�b�P�[�W�ł��B
-->
This package is a plugin library package to support the BZIP2 compression method in the package `Palmtree.IO.Compression.Archive.Zip`.

## 2. Required environment


| Item | Condition |
| --- | --- |
| CPU | x64 / x86 |
| OS | Windows / Linux |
| .NET rumtime | 7.0 / 8.0 |
| 7-zip | Confirmed to work with 7-zip 23.01 |

<!--
�ʓr�A 7-zip �̃C���X�g�[�����K�v�ł��B
�ڍׂɂ��Ă� �p�b�P�[�W "SevenZip.Compression.Wrapper.NET" �̃h�L�������g���Q�Ƃ��Ă��������B
-->
7-zip must be installed separately.
See [documentation for package `SevenZip.Compression.Wrapper.NET`](https://github.com/rougemeilland/SevenZip.Compression.Wrapper.NET/blob/main/docs/HowToInstall7z_en.md) for more information.

## 3. Usage

<!--
BZIP2 ���k������L���ɂ��邽�߂ɂ́A�A�v���P�[�V�����v���O�����ōŏ��Ɉȉ��̃X�e�[�g�����g�����s���Ă��������B
-->
To enable the BZIP2 compression method, first execute the following statement in your application program.

```csharp
 Palmtree.IO.Compression.Stream.Plugin.SevenZip.Bzip2CoderPlugin.EnablePlugin();
```

## 4. License
The source code of this software is covered by the MIT License.

## 5. Disclaimer
The developer of this software is not responsible for any defects or troubles that may occur when using this software. Please understand that.
