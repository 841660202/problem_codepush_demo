<!--
 * @version: v0.0.1
 * @Author: hailong.chen
 * @Date: 2019-08-09 23:02:20
 * @LastEditors: hailong.chen
 * @LastEditTime: 2019-08-10 00:25:57
 * @Descripttion: 
 -->
```
Successfully added the "MyApp_android" app, along with the following default deployments:
┌────────────┬──────────────────────────────────────────────────────────────────┐
│ Name       │ Deployment Key                                                   │
├────────────┼──────────────────────────────────────────────────────────────────┤
│ Production │ k0ADsBJfE7yGwIglbXAgtn9hdxkXe5678dc0-13bd-4de0-8573-dd6806745d95 │
├────────────┼──────────────────────────────────────────────────────────────────┤
│ Staging    │ ikyhTzy7BfLOGhPOR9Zx_UbWw2WVe5678dc0-13bd-4de0-8573-dd6806745d95 │
└────────────┴──────────────────────────────────────────────────────────────────┘


code-push release-react MyApp_android "android" --d "Staging" --t 1.0.0  --des " [CodePush] Reporting binary update (1.0.0)"

code-push deployment history MyApp_android Staging
```