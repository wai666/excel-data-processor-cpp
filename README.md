# Excel Data Processor (C++)

> 🚀 一个用C++编写的Excel数据自动化处理工具，专注于工业数据分析与报表生成

## 项目简介

这是一个命令行工具，用于自动化处理Excel数据文件。最初为钢厂生产数据分析设计，可扩展用于任何需要批量处理Excel数据的场景。

**核心功能**：
- 读取Excel文件（.xlsx/.csv）
- 数据清洗与验证
- 加权计算与统计分析
- 自动生成报表

## 技术栈

- **语言**：C++17
- **库**：
  - [xlnt](https://github.com/tfussell/xlnt) - Excel文件读写
  - STL - 数据结构与算法

## 项目背景

在钢厂工作中，每天需要处理大量炉座数据（炉数、材料消耗、产量等），手动用Excel公式计算效率低且容易出错。这个工具将重复性工作自动化，提升数据处理效率。

## 功能规划

### Phase 1: 基础功能（2026-03）
- [x] 项目初始化
- [ ] 读取CSV文件
- [ ] 基础数据结构设计（炉座、材料、产量）
- [ ] 简单的加权计算

### Phase 2: Excel支持（2026-04）
- [ ] 集成xlnt库
- [ ] 读取.xlsx文件
- [ ] 写入计算结果到新Excel

### Phase 3: 高级功能（2026-05）
- [ ] 多文件批处理
- [ ] 配置文件支持（JSON）
- [ ] 错误处理与日志

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/wai666/excel-data-processor-cpp.git
cd excel-data-processor-cpp

# 编译（需要C++17支持）
mkdir build && cd build
cmake ..
make

# 运行示例
./excel_processor ../examples/sample_data.csv
```

## 项目结构

```
excel-data-processor-cpp/
├── src/              # 源代码
│   ├── main.cpp
│   ├── data_reader.cpp
│   └── calculator.cpp
├── include/          # 头文件
├── examples/         # 示例数据
├── docs/             # 学习笔记
│   └── cpp_notes.md  # C++学习笔记（对应自考考点）
├── tests/            # 单元测试
├── CMakeLists.txt
└── README.md
```

## 学习目标

这个项目同时服务于：
1. **工作实用**：提升数据处理效率
2. **技能提升**：深入学习C++（文件IO、STL、面向对象）
3. **考试准备**：覆盖自考C++科目核心考点

相关考点笔记：[docs/cpp_notes.md](docs/cpp_notes.md)

## 开发日志

### 2026-03-13
- 项目启动
- 完成README规划
- 下一步：设计数据结构

## 许可证

MIT License

## 联系方式

- GitHub: [@wai666](https://github.com/wai666)
- 项目用途：学习交流 + 工作实用

---

**注**：这是一个持续迭代的项目，欢迎提Issue和PR。
