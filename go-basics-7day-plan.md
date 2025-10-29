# 🧭 Go 基础速通 · 7天学习计划（PHP 转 Go 就业导向版）

> 本学习计划面向有 PHP 基础的开发者，目标是在 7 天内快速掌握 Go 语言核心语法与编程思想，为进入 Web 实战（Gin + MySQL + Redis）打下基础。

---

## 🌱 前置准备
**目标：** 安装好 Go 环境 + 编辑器（VS Code 或 GoLand）

**参考资料：**
- [Go 官方安装指南](https://go.dev/doc/install)
- [Go 中文社区安装教程](https://studygolang.com/articles/34916)
- 推荐 IDE：VS Code + Go 插件 或 GoLand
- 在线环境：[Go Playground](https://go.dev/play/)

---

## 📅 Day 1：语言基础与运行机制
**目标：** 理解 Go 程序结构与变量、函数  

**学习内容：**
- Go 程序结构：`package main`、`func main()`
- 变量声明：`var` vs `:=`
- 函数与返回值
- `fmt.Println()`、输入输出

**练习：**
- 写一个程序打印 “Hello, Go!”
- 写一个函数 `add(a, b int) int`

**参考资料：**
- [A Tour of Go - Basics](https://go.dev/tour/basics/1)
- [Go by Example - Variables & Functions](https://gobyexample.com/variables)

---

## 📅 Day 2：数组、切片与 Map
**目标：** 熟悉常用数据结构  

**学习内容：**
- 数组（Array）
- 切片（Slice）
- map（类似 PHP 关联数组）
- 遍历与 range

**练习：**
- 定义一个字符串切片并循环打印
- 创建 map 存放用户信息

**参考资料：**
- [Go by Example - Arrays, Slices, Maps](https://gobyexample.com/arrays)

---

## 📅 Day 3：结构体与方法
**目标：** 理解 Go 的面向组合思想  

**学习内容：**
- `struct` 定义与初始化
- 方法绑定（`func (u User) hello()`）
- 值接收者 vs 指针接收者
- 嵌套结构体

**练习：**
- 定义 `User` 结构体（含 name、age）
- 实现方法 `SayHello()` 输出问候

**参考资料：**
- [Go by Example - Structs](https://gobyexample.com/structs)
- [Effective Go - Methods](https://go.dev/doc/effective_go#methods)

---

## 📅 Day 4：控制结构与错误处理
**目标：** 掌握流程控制与错误机制  

**学习内容：**
- `if`、`for`、`switch`
- `error` 类型与 `errors.New()`
- `defer`、`panic`、`recover`

**练习：**
- 写一个函数：除法，分母为 0 时返回错误
- 测试 `defer` 的执行顺序

**参考资料：**
- [Go by Example - Errors](https://gobyexample.com/errors)
- [Go by Example - Panic & Recover](https://gobyexample.com/panic)

---

## 📅 Day 5：包与模块（Go Modules）
**目标：** 理解项目结构与依赖管理  

**学习内容：**
- `package` 的作用与导入规则
- `go mod init` 与 `go get`
- 目录组织规范（main / internal / pkg）

**练习：**
- 创建一个新模块 `go-basics`
- 在 main 包中引用自定义包函数

**参考资料：**
- [Go Modules 官方指南](https://go.dev/doc/modules/managing-dependencies)
- [Go by Example - Packages](https://gobyexample.com/packages)

---

## 📅 Day 6：文件与 JSON 操作
**目标：** 学会处理文件与 JSON（PHP 常用能力）  

**学习内容：**
- 文件读取与写入（`os`、`io/ioutil`）
- JSON 编解码（`encoding/json`）
- 错误检查与 defer 关闭文件

**练习：**
- 从文件读取 JSON 数据并解析为结构体
- 将结构体转 JSON 并写入文件

**参考资料：**
- [Go by Example - Reading Files](https://gobyexample.com/reading-files)
- [Go by Example - JSON](https://gobyexample.com/json)

---

## 📅 Day 7：小型综合项目
**目标：** 完整实现一个 CLI 或 Web 小项目  

**项目示例：**
- 命令行版 TodoList
- 简单 HTTP 服务：返回 JSON 响应

**加分练习：**
- 用 `net/http` 写一个 `/hello` 接口
- 返回 `{ "message": "Hello, Go!" }`

**参考资料：**
- [Go by Example - HTTP Servers](https://gobyexample.com/http-servers)
- [Gin 框架文档（下阶段使用）](https://gin-gonic.com/docs/)

---

## 🏁 结课目标
✅ 能独立编写中小型 Go 程序  
✅ 熟悉语法、结构体、模块、错误处理  
✅ 为进入 Web 实战（Gin + MySQL + Redis）打好基础  

---

## 📚 附加资源
- [Go by Example](https://gobyexample.com/)
- [Go语言圣经（中文版）](https://books.studygolang.com/gopl-zh/)
- [Go 官方文档](https://go.dev/doc/)
- [Go 中文网](https://studygolang.com/)
- [Go Playground](https://go.dev/play/)

---

**作者备注：**  
本计划由 ChatGPT GPT-5 指导生成，适合有 PHP 经验的开发者在短时间内转向 Go 开发。  
学习完成后可进入《Go Web 实战（Gin + GORM）》阶段。
