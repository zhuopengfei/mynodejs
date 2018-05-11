# mynodejs
mynodejs


## 创建项目须知

- 代码检查 eslint
```
npm i eslint -g

eslint --init

eslint 会创建一个 .eslintrc.json 的配置文件，同时自动安装并添加相关的模块到 devDependencies。
这里我们使用 Standard 规范，其主要特点是不加分号。
```

- 创建 .gitignore 文件,忽略提交的文件或目录
```

$ touch .gitignore


.gitignore 中常用内容：
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
 
# Runtime data
pids
*.pid
*.seed
*.pid.lock
 
# Directory for instrumented libs generated by jscoverage/JSCover
lib-cov
 
# Coverage directory used by tools like istanbul
coverage
 
# nyc test coverage
.nyc_output
 
# Grunt intermediate storage (http://gruntjs.com/creating-plugins#storing-task-files)
.grunt
 
# Bower dependency directory (https://bower.io/)
bower_components
 
# node-waf configuration
.lock-wscript
 
# Compiled binary addons (https://nodejs.org/api/addons.html)
build/Release
 
# Dependency directories
node_modules/
jspm_packages/
 
# Typescript v1 declaration files
typings/
 
# Optional npm cache directory
.npm
 
# Optional eslint cache
.eslintcache
 
# Optional REPL history
.node_repl_history
 
# Output of 'npm pack'
*.tgz
 
# Yarn Integrity file
.yarn-integrity
 
# dotenv environment variables file
.env

```

================================================


- 创建 .editorconfig ,统一代码风格

```
$ touch .editorconfig

.editorconfig常用内容设置：

# editorconfig.org
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
tab_width = 2

[*.md]
trim_trailing_whitespace = false

[Makefile]
indent_style = tab

```
