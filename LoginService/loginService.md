1. 登录系统（认证与授权）
   核心目标：验证用户身份，颁发访问凭证，控制资源访问权限
   关键功能：
   用户登录认证（用户名 / 密码、手机号 / 验证码、第三方登录）
   Token 生成与校验（JWT、Session Token）
   会话管理（登录状态保持、自动登录、登出）
   权限控制（基于角色的访问控制 RBAC）
   安全增强（密码加密、验证码、限流、异常登录检测）
   数据关注点：临时会话数据、权限关系、登录日志