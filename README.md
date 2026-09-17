<p align="center"><a href="#zh">🇨🇳 中文</a> &nbsp;|&nbsp; <a href="#en">🇬🇧 English</a></p>
<a id="zh"></a>

# G1 Motion Dataset

## 中文

这是 G1 动作组的独立数据项目说明仓库。按照当前发布决定，本 Public 仓库暂不上传 `bones_g1_origin` 的原始 CSV 数据；原始数据仍保留在本地备份目录，未被删除。

本仓库用于记录数据集名称、目录约定、复现命令和后续发布说明。需要使用完整动作组时，请在本地恢复 `dataset/bones_g1_origin/`，再把该路径显式传给 `robot-retargeter-smplx` 的转换脚本。CSV 转成 PKL/NPZ 后必须重新检查 FPS、坐标系、四元数顺序、joint order、关节限位、接触和输出 schema。

<a id="en"></a>

## English

This is the standalone documentation repository for the G1 motion groups. By the current publishing decision, this Public repository does not upload the original CSV files under `bones_g1_origin`; the original data remains preserved in the local backup and has not been deleted.

This repository records the dataset name, directory convention, reproduction commands, and future release notes. To use the complete motion collection locally, restore `dataset/bones_g1_origin/` and pass that path explicitly to the conversion scripts in `robot-retargeter-smplx`. After converting CSV to PKL/NPZ, recheck FPS, coordinate frame, quaternion convention, joint order, joint limits, contacts, and output schema.

```bash
git clone https://github.com/tulay-hub/g1-motion-dataset.git
cd g1-motion-dataset
```

The repository intentionally contains no G1 motion payload at this time.
