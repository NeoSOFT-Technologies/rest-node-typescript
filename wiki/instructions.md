### 1. Why is my git pre-commit hook not executable by default?

- Because files are not executable by default; they must be set to be executable.

```
chmod ug+x .husky/*
chmod ug+x .git/hooks/*
```

### 2. [Production Best Practices: Security](https://expressjs.com/en/advanced/best-practice-security.html)

- Don’t use deprecated or vulnerable versions of Express
- Use TLS
- Use Helmet
- Use cookies securely
- Prevent brute-force attacks against authorization
- Ensure your dependencies are secure
- Avoid other known vulnerabilities
- Additional considerations

### 3. How can I resolve the TypeScript Compiler error “Namespace 'NodeJS' has no exported member 'Global'”?

- We can fix this issue by adding `"skipLibCheck": true` to my `tsconfig`.
- [Skip Default Lib Check - `skipDefaultLibCheck`](https://www.typescriptlang.org/tsconfig#skipLibCheck)