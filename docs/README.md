- filters

  1. SecurityContextPersistenceFilter

     > Security上下文过滤器优先从Session中加载用户信息

  2. WebAsyncManagerIntegrationFilter

     > web 异步管理过滤器

  3. HeaderWriterFilter

     > 

  4. CsrfFilter

     > CSRF 跨站请求伪造，防止CSRF攻击

  5. LogoutFilter

     > 登出过滤器

  6. UsernamePasswordAuthenticationFilter

     > 

  7. DefaultLoginPageGeneratingFilter

     > 将登录界面静态html返回前台

  8. DefaultLogoutPageGeneratingFilter

  9. BasicAuthenticationFilter

  10. RequestCacheAwareFilter

  11. SecurityContextHolderAwareRequestFilter

  12. AnonymousAuthenticationFilter

  13. SessionManagementFilter

  14. ExceptionTranslationFilter

  15. FilterSecurityInterceptor

- 