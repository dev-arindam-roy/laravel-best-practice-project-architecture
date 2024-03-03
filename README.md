# Laravel Best Practice Project Architecture
Best practice of project architecture for laravel professional developer


![2024-03-03_150840](https://github.com/dev-arindam-roy/laravel-best-practice-project-architecture/assets/24665327/b14cd214-7e7f-402e-adef-45214fbc5d9f)

## Notes:
```
1) Route call controllers methods
2) Method call validation request from [Request] folder
3) For custom validation rules, make [Rules] folder
4) If validation pass then method call [Repositories] (Interface)
5) Repositiry call [Services]
6) Services use [Traits] / [Helpers] / [Facades] .. as per requirements
```
