# Welcome to Willaford Consulting

I help teams streamline .NET + SQL development by cutting boilerplate, improving maintainability, and delivering faster results.  
Creator of [SqlShield](https://github.com/Dominik-Willaford/SqlShield) — a lightweight Dapper + stored procedure helper.

---

## 🚀 Services

### SQL/.NET Codebase Audit
- 1–2 week engagement  
- Review your data access layer  
- Identify performance bottlenecks, risks, and boilerplate traps  
- Deliver a prioritized action plan  

*From $5,000*

---

### SqlShield Integration
- Integrate [SqlShield](https://www.nuget.org/packages/SqlShield/) into your stack  
- Convention-based mapping (snake_case / kebab-case → C# POCOs)  
- Developer enablement & knowledge transfer  
- Faster delivery with less plumbing  

*From $15,000*

---

### Data Access Modernization
- Refactor stored procedure + Dapper usage  
- Enforce naming conventions, improve testability  
- Pragmatic performance improvements  
- Option for ongoing advisory/retainer  

*From $25,000+*

---

## 🛠 Projects & Tools

### SqlShield

[![NuGet](https://img.shields.io/nuget/v/SqlShield)](https://www.nuget.org/packages/SqlShield/)
[![GitHub stars](https://img.shields.io/github/stars/Dominik-Willaford/SqlShield?style=social)](https://github.com/Dominik-Willaford/SqlShield)

A lightweight .NET helper that eliminates boilerplate when calling stored procedures with Dapper.

```csharp
await _sprocs.ExecuteNonQueryAsync(
    "usp_order_update_status",
    "DefaultConnection",
    new { order_id = 42, new_status = "complete" }
);
```
Need help implementing SqlShield in production? [Hire me](https://calendly.com/dwillaford88/30min)

## 👨‍💻 About

I’m Dominik Willaford, a full-stack .NET consultant with over 7 years of experience delivering enterprise-grade software solutions.
I specialize in .NET, SQL Server, Dapper, naming conventions, and developer productivity.

- Led incremental modernization of large monoliths (strangler pattern)

- Built reusable libraries and instrumentation for reliability and performance

- Creator of [SqlShield](https://www.nuget.org/packages/SqlShield/)

Let’s work together to modernize your data access layer and help your team ship faster with cleaner, more maintainable code.

## 📩 Contact
- [Book a call]([https://calendly.com](https://calendly.com/dwillaford88/30min))
- LinkedIn: [Connect with me](https://www.linkedin.com/in/dominik-willaford/)

## 📜 License
© 2025 Dominik Willaford. All rights reserved.
