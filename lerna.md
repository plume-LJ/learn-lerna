{
  "$schema": "node_modules/lerna/schemas/lerna-schema.json",
  "version": "0.0.0",
   // 定义各个项目存放的位置，这里我们新增一个examples/
	"packages": ["packages/*", "examples/*"],
  // 当前的版本号
  /* 以下为新增 */
  // 执行命令的client，默认为npm，这里我们需要配置为yarn
	"npmClient": "npm",
  // 是否使用workspace工作模式
	"useWorkspaces": true
}