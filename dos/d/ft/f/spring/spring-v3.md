

### spring load

```mermaid
flowchart TD
AbstractApplicationContext --> refresh("#refresh") --> prepareRefresh("#prepareRefresh")
--> obtainFreshBeanFactory("#obtainFreshBeanFactory")
--> prepareBeanFactory("#prepareBeanFactory")
--> postProcessBeanFactory("#postProcessBeanFactory")
--> invokeBeanFactoryPostProcessors("#invokeBeanFactoryPostProcessors")
--> registerBeanPostProcessors ("#registerBeanPostProcessors")
--> initMessageSource ("#initMessageSource")
--> initApplicationEventMulticaster ("#initApplicationEventMulticaster")
--> onRefresh ("#onRefresh")
--> registerListeners("#registerListeners")
--> finishBeanFactoryInitialization("#finishBeanFactoryInitialization")
--> finishRefresh("#finishRefresh")

```
