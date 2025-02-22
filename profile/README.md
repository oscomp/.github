# 2025年全国大学生操作系统比赛（筹备阶段）

- 2025.02.23：2025年全国大学生操作系统比赛的章程和技术方案初步完成。
- 2025.02.22：发布[**与2025OS比赛内核实现赛道相关的一些OS实例/教程的参考信息**](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md)
- 2024.11.16：2024年度全国大学生操作系统比赛总结&2025年度全国大学生操作系统比赛准备会召开
 
### 内核实现赛道
- **在 https://github.com/oscomp/testsuits-for-oskernel 包含当前准备2025年决赛阶段内核实现赛道的测试用例（将进一步更新）。**
  - [2025决赛阶段内核实现赛道-RISCV测例（将进一步更新）](https://github.com/oscomp/testsuits-for-oskernel/tree/final-2025-rv)
  - [2025决赛阶段内核实现赛道-LoongArch测例（将进一步更新）](https://github.com/oscomp/testsuits-for-oskernel/tree/final-2025-la)

**注：2025内核实现赛道比赛，测试用例所在文件系统格式为Ext4， 测试用例没用到Ext4的高级功能（如系统掉电/崩溃的可靠性保障等）。[比赛提供的C和Rust的Ext4库](https://github.com/oscomp/os-competition-info/blob/main/ref-info.md#ext4%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F%E5%8F%82%E8%80%83%E5%AE%9E%E7%8E%B0)与具体OS无关，并给出了适配这些库的某些OS参考。这些库经过适配后，可集成到各种C或Rust-based的OS中。**

### 功能挑战赛道 
- **在 https://github.com/oscomp 网址下，具有 "projXXX-YYY" 名称的Public类型的仓库是OS比赛功能挑战赛道的可选题目，参加此类赛道的学生队伍可以选择。**  
- **建议学生看到想选择的OS功能挑战赛道题目（须是Public类型的仓库且能联系上该题目的出题导师）前，先及时与项目导师取得联系，找导师了解到项目情况后，再决定是否选择。**  
- **如果联系不上项目导师，请及时与比赛技术支持组的韩冰老师（微信ID: AiXi_0514 QQ ID: 3479261167）联系，寻求可能的帮助。**
- **具有Public archive类型的仓库，表示此项目(属于OS功能赛道)是往年题目，不是2025年的参赛题目，请参赛同学不要选择。**
- **如果有人感兴趣成为此项目（Public archive类型）的导师，并将进一步改进项目，请及时与会务组联系。**

## **比赛题目导师提醒：**  

- **请还没加入“2025OS功能赛道导师群”的专家，及时与比赛技术支持组的韩冰老师（微信ID: AiXi_0514 QQ ID: 3479261167）联系，她会帮助大家加入导师群。**

## 新闻：
- 2024.11.16：2024年度全国大学生操作系统比赛总结&2025年度全国大学生操作系统比赛准备会召开
- 2024.10.25：[2024年度东北区域/中西部区域/华东区域/华南区域大学生操作系统比赛启动](https://os.educg.net/#/)
- 2024.09.29：[2024秋冬季开源操作系统训练营启动](https://opencamp.cn/os2edu/camp/2024fall)

## 重要信息：

## 在研/计划的项目
- [开源实验小项目招新](https://github.com/orgs/rcore-os/discussions/categories/ideas)，可作为本科或研究生毕设课题，欢迎报名并参加！

## 相关网站
- [全国大学生OS比赛官网](https://os.educg.net/)，所有参赛作品开源，方便大家学习，欢迎参加比赛！
- [LearningOS开源社区](https://github.com/learningos)，培养操作系统专业人才
- [syswonder开源社区](https://syswonder.org/)，面向泛在技术的操作系统探索
- [rCoreOS开源社区](https://github.com/rcore-os)，面向新型安全高性能操作系统探索与实践
- [智能网联汽车创新中心训练营:开源操作系统](https://github.com/cicvedu)，面向智能驾驶领域的系统软件开发培训
- [组件化操作系统-arceos开源社区](https://github.com/arceos-org/)，用组件化思路设计的unikernel等
- [构建操作系统的内核组件开源社区](https://github.com/kern-crates)，可用于构建各种内核的组件集合

